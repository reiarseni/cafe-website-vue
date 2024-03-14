<template>

  <!-- contact section starts -->
  <section class="contact" id="contact">
    <h1 class="heading">contact <span> us</span></h1>
    <div class="row">
      <iframe  class="map" src="https://www.google.com/maps/embed?pb=!1m10!1m8!1m3!1d59218.56285326434!2d-79.429974!3d21.9283928!3m2!1i1024!2i768!4f13.1!5e0!3m2!1ses!2scu!4v1709757244445!5m2!1ses!2scu" allowfullscreen="" loading="lazy" frameborder="0"></iframe>
      <form action="">
        <h3>get in touch</h3>
        <div class="inputBox">
          <span class="fas fa-user"></span>
          <input type="text" placeholder="Name">
        </div>
        <div class="inputBox">
          <span class="fas fa-envelope"></span>
          <input type="email" placeholder="Email">
        </div>
        <div class="inputBox">
          <span class="fas fa-phone"></span>
          <input type="number" placeholder="Number">
        </div>
        <input type="submit" value="contact now" class="btn">
      </form>
    </div>
  </section>
  <!-- contact section ends -->

</template>

<script>

    export default{
        name: "Contact",
    }

</script>

<style scoped>

  /*contact section*/
  .contact .row{
    display: flex;
    background:var(--black);
    flex-wrap: wrap;
    gap:1rem;
  }

  .contact .row .map{
    flex:1 1 45rem;
    width: 100%;
    object-fit: cover;
  }

  .contact .row form{
    flex:1 1 45rem;
    padding:5rem 2rem;
    text-align: center;
  }

  .contact .row form h3{
    text-transform: uppercase;
    font-size: 3.5rem;
    color:#fff;
  }

  .contact .row form .inputBox{
    display: flex;
    align-items: center;
    margin-top: 2rem;
    margin-bottom: 2rem;
    background:var(--bg);
    border:var(--border);
  }

  .contact .row form .inputBox span{
    color:#fff;
    font-size: 2rem;
    padding-left: 2rem;
  }

  .contact .row form .inputBox input{
    width: 100%;
    padding:2rem;
    font-size: 1.7rem;
    color:#fff;
    text-transform: none;
    background:none;
  }

</style>