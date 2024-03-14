<template>

  <!-- review section starts -->
  <section class="review" id="review">
    <h1 class="heading">customer's <span> review</span></h1>
    <div class="box-container">
      <div class="box">
        <img src="src/assets/images/quote-img.png" alt="" class="quote">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi nulla sit libero nemo fuga sequi nobis? Necessitatibus aut laborum, nisi quas eaque laudantium consequuntur iste ex aliquam minus vel? Nemo.</p>
        <img src="src/assets/images/pic-1.jpg" class="user" alt="">
        <h3>jone doe</h3>
        <div class="stars">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star-half-alt"></i>
        </div>

      </div>
      <div class="box">
        <img src="src/assets/images/quote-img.png" alt="" class="quote">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi nulla sit libero nemo fuga sequi nobis? Necessitatibus aut laborum, nisi quas eaque laudantium consequuntur iste ex aliquam minus vel? Nemo.</p>
        <img src="src/assets/images/pic-2.jpg" class="user" alt="">
        <h3>jone doe</h3>
        <div class="stars">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star-half-alt"></i>
        </div>

      </div>
      <div class="box">
        <img src="src/assets/images/quote-img.png" alt="" class="quote">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi nulla sit libero nemo fuga sequi nobis? Necessitatibus aut laborum, nisi quas eaque laudantium consequuntur iste ex aliquam minus vel? Nemo.</p>
        <img src="src/assets/images/pic-3.jpg" class="user" alt="">
        <h3>jone doe</h3>
        <div class="stars">
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star"></i>
          <i class="fas fa-star-half-alt"></i>
        </div>

      </div>
    </div>
  </section>
  <!-- review section ends -->

</template>

<script>

    export default{
        name: "Reviews",
    }

</script>

<style scoped>

  /* review section*/
  .review .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit , minmax(30rem,1fr));
    gap: 1.5rem;
  }
  .review .box-container .box{
    border: var(--border);
    text-align: center;
    padding:  3rem 2rem;
  }
  .review .box-container .box p{
    font-size: 1.5rem;
    line-height: 1.8;
    color: #ccc;
    padding: 2rem 0;
  }
  .review .box-container .box .user{
    height: 7rem;
    width: 7rem;
    border-radius: 50%;
    object-fit: cover;
  }
  .review .box-container .box h3{
    padding: 1rem 0;
    font-size: 2rem;
    color: #fff;
  }

  .review .box-container .box .stars i{
    font-size: 1.5rem;
    color: var(--main-color);
  }

</style>