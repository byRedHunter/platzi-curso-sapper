<script>
  export let nickname
  export let name
</script>

<style>
  .Profile-content {
    display: flex;
    align-items: center;
  }
  .Profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .Profile-info {
    margin: 0 0 0 0.5em;
  }
  .Profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .Profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="Profile">
  <div class="Profile-content">
    <div class="Profile-avatar">
      <img src="https://instagram.flim16-2.fna.fbcdn.net/v/t51.2885-19/s150x150/82094575_589383831885959_7689306982552961024_n.jpg?_nc_ht=instagram.flim16-2.fna.fbcdn.net&_nc_ohc=BTboyBzAHi8AX-Al_yq&oh=b506bb07f594ef4d883ba9e887b0a557&oe=5F86961B" alt="">
    </div>

    <div class="Profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>