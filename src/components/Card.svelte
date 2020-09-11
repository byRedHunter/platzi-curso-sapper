<script>
  import Comments from './Comments.svelte'
</script>

<div class="Card">
  <div class="Card-container">
    <div class="Card-header">
      <div class="Card-user">
        <img src="https://s3-alpha.figma.com/profile/555a5a8c-f79d-4083-938c-04df1e163dd8" alt="">
        <h2>Elmo.pug <span>Lima, Perú</span></h2>
      </div>

      <div class="Card-settings">
        <i class="fas fa-ellipsis-h"></i>
      </div>
    </div>

    <div class="Card-photo">
      <figure>
        <img src="https://cdn.pixabay.com/photo/2015/06/08/15/02/pug-801826__340.jpg" alt="">
      </figure>
    </div>

    <div class="Card-icons">
      <div class="Card-icons-first">
        <i class="fas fa-heart"></i>
        <i class="fas fa-paper-plane"></i>
      </div>

      <div class="Card-icons-second">
        <i class="fas fa-bookmark"></i>
      </div>
    </div>

    <div class="Card-description">
      <h3>Elmo.pug</h3>
      <span>Hola</span>
    </div>

    <Comments />
  </div>
</div>