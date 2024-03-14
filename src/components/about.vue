<template>

  <!-- about section starts -->
  <section class="about" id="about">
    <h1 class="heading"><span>about</span> us</h1>
    <div class="row">
      <div class="image">
        <img src="src/asset/images/about-img.jpg" alt="">
      </div>
      <div class="content">
        <h3>what makes our coffe special?</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus qui ea ullam, enim tempora ipsum fuga alias quae ratione a officiis id temporibus autem? Quod nemo facilis cupiditate. Ex, vel?</p>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odit amet enim quod veritatis, nihil voluptas culpa! Neque consectetur obcaecati sapiente?</p>
        <a href="#" class="btn">learn more</a>
      </div>
    </div>
  </section>
  <!-- about section ends -->

</template>

<script>

    export default{
        name: "About",
    }

</script>

<style scoped>

  /*about section*/
  .about .row{
    display: flex;
    align-items: center;
    background: var(--black);
    flex-wrap: wrap;
  }
  .about .row .image{
    flex: 1 1 45rem;
  }
  .about .row .content{
    flex: 1 1 45rem;
    padding: 2rem;
  }
  .about .row .content h3{
    font-size: 3rem;
    color: #fff;
  }
  .about .row .content p{
    font-size: 1.6rem;
    color: #ccc;
    padding: 1rem 0;
    line-height: 1.8;
  }
  .about .row .image img{
    width: 100%;
  }

</style>