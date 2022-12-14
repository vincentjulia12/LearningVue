<template>
   <div class="container">
    <div class="grid">
      <div class="row">
        <div class="col">
          <p id="p1" class="h3 mt-5 mb-2">About Web</p>
          <p id="p2" class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis qui deserunt error. Culpa cum odio beatae libero accusamus, itaque facere minima consectetur voluptatibus optio molestias nemo porro asperiores magnam natus. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Distinctio et ex, nesciunt quam, eum commodi fugit aut velit cum aperiam molestias iste architecto explicabo. Maxime dolorem doloremque velit totam voluptas! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere voluptatem voluptatum ab amet assumenda dolorum. Consequuntur nostrum obcaecati recusandae mollitia nihil voluptatem nemo, architecto minus asperiores aut in molestias cumque!</p>
        </div>
        <div class="row">
          <p id="p1" class="h3 mt-5 mb-2">About Users</p>
          <p id="p2" class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis qui deserunt error. Culpa cum odio beatae libero accusamus, itaque facere minima consectetur voluptatibus optio molestias nemo porro asperiores magnam natus. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Distinctio et ex, nesciunt quam, eum commodi fugit aut velit cum aperiam molestias iste architecto explicabo. Maxime dolorem doloremque velit totam voluptas! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere voluptatem voluptatum ab amet assumenda dolorum. Consequuntur nostrum obcaecati recusandae mollitia nihil voluptatem nemo, architecto minus asperiores aut in molestias cumque!</p>
        </div>
        <div class="row">
          <p id="p1" class="h3 mt-5 mb-2">Gago</p>
          <p id="p2" class="">Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis qui deserunt error. Culpa cum odio beatae libero accusamus, itaque facere minima consectetur voluptatibus optio molestias nemo porro asperiores magnam natus. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Distinctio et ex, nesciunt quam, eum commodi fugit aut velit cum aperiam molestias iste architecto explicabo. Maxime dolorem doloremque velit totam voluptas! Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facere voluptatem voluptatum ab amet assumenda dolorum. Consequuntur nostrum obcaecati recusandae mollitia nihil voluptatem nemo, architecto minus asperiores aut in molestias cumque! Lorem ipsum dolor sit amet consectetur adipisicing elit. Et nihil, non qui iure sapiente autem. Expedita repellat et aut reiciendis harum officia illum laudantium consequuntur? Voluptatum sapiente qui quam praesentium. Lorem ipsum dolor sit, amet consectetur adipisicing elit. Error tenetur, maiores sequi a optio ducimus debitis reprehenderit expedita, tempore nemo corrupti praesentium cum sunt fugit atque ullam aliquid corporis porro! Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur inventore minus rem! Ducimus, similique pariatur numquam perferendis quo, possimus, fuga cum beatae voluptas eius velit. Ex adipisci placeat tenetur minima. Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa iste asperiores ut maiores laboriosam qui, a quisquam earum mollitia inventore in magnam nesciunt quis nam eum natus ullam aliquid assumenda. Lorem ipsum dolor sit amet consectetur adipisicing elit. Consectetur dolore sint distinctio reiciendis accusantium blanditiis quaerat, veritatis exercitationem quia nihil non earum aspernatur. Voluptatum recusandae culpa voluptatibus, doloribus et dolores. Lorem, ipsum dolor sit amet consectetur adipisicing elit. Omnis autem at nam voluptatibus eaque architecto minima nihil distinctio doloribus quod maiores sunt, hic consequatur consectetur suscipit nisi aut neque soluta. Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi quisquam atque amet vel provident laborum? Corporis, earum debitis iusto ab mollitia magni consequuntur dolor cupiditate voluptatem, molestias magnam, tempore quam! Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit inventore dolorem libero temporibus dolores dicta repudiandae qui? Vero, delectus illo porro molestias assumenda, id animi facilis ratione sequi cum blanditiis.</p>
        </div>
      </div>
    </div>
  </div>

  <!-- Carousel wrapper -->
<div id="carouselBasicExample" class="carousel slide carousel-fade" data-mdb-ride="carousel">
  <!-- Indicators -->
  <div class="carousel-indicators">
    <button
      type="button"
      data-mdb-target="#carouselBasicExample"
      data-mdb-slide-to="0"
      class="active"
      aria-current="true"
      aria-label="Slide 1"
    ></button>
    <button
      type="button"
      data-mdb-target="#carouselBasicExample"
      data-mdb-slide-to="1"
      aria-label="Slide 2"
    ></button>
    <button
      type="button"
      data-mdb-target="#carouselBasicExample"
      data-mdb-slide-to="2"
      aria-label="Slide 3"
    ></button>
  </div>

  <!-- Inner -->
  <div class="carousel-inner">
    <!-- Single item -->
    <div class="carousel-item active">
      <img src="https://mdbcdn.b-cdn.net/img/Photos/Slides/img%20(15).webp" class="d-block w-100" alt="Sunset Over the City"/>
      <div class="carousel-caption d-none d-md-block">
        <h5>First slide label</h5>
        <p>Nulla vitae elit libero, a pharetra augue mollis interdum.</p>
      </div>
    </div>

    <!-- Single item -->
    <div class="carousel-item">
      <img src="https://mdbcdn.b-cdn.net/img/Photos/Slides/img%20(22).webp" class="d-block w-100" alt="Canyon at Nigh"/>
      <div class="carousel-caption d-none d-md-block">
        <h5>Second slide label</h5>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>

    <!-- Single item -->
    <div class="carousel-item">
      <img src="https://mdbcdn.b-cdn.net/img/Photos/Slides/img%20(23).webp" class="d-block w-100" alt="Cliff Above a Stormy Sea"/>
      <div class="carousel-caption d-none d-md-block">
        <h5>Third slide label</h5>
        <p>Praesent commodo cursus magna, vel scelerisque nisl consectetur.</p>
      </div>
    </div>
  </div>
  <!-- Inner -->

  <!-- Controls -->
  <button class="carousel-control-prev" type="button" data-mdb-target="#carouselBasicExample" data-mdb-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-mdb-target="#carouselBasicExample" data-mdb-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
<!-- Carousel wrapper -->

   
</template>
  
<script>

export default {
  name: 'AboutView',
  components: {},
}
</script>
  
<style>

</style>