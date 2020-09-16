<script context="module">
  export async function preload() {
    let data = {}
    const response = await this.fetch(
      `https://us-central1-pugstagram-co.cloudfunctions.net/data`
    )

    data = await response.json()

    return {data}
  }
</script>

<script>
  import Header from '../components/Header.svelte'
  import Main from '../components/Main.svelte'
  import TimeLine from '../components/TimeLine.svelte'
  import Sidebar from '../components/Sidebar.svelte'
  import Card from '../components/Card.svelte'

  export let data

  const user = {
    nickname: 'ByRedHunter',
    name: 'Jhonny Quispe'
  }
</script>

<svelte:head>
  <title>Pugstagram</title>
</svelte:head>

<Main>
  <TimeLine posts={data.posts} />
  <Sidebar {...user} />
</Main>