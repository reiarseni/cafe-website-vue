<template>
  <!-- header section starts  -->

  <header class="header">

    <a href="#" class="logo">
      <img src="src/assets/images/logo.png" alt="">
    </a>

    <nav class="navbar">
      <a href="#home">home</a>
      <a href="#about">about</a>
      <a href="#menu">menu</a>
      <a href="#products">products</a>
      <a href="#review">review</a>
      <a href="#contact">contact</a>
      <a href="#blogs">blogs</a>
    </nav>

    <div class="icons">
      <div class="fas fa-search" id="search-btn"></div>
      <div class="fas fa-shopping-cart" id="cart-btn"></div>
      <div class="fas fa-bars" id="menu-btn"></div>
    </div>

    <div class="search-form">
      <input type="search" id="search-box" placeholder="search here...">
      <label for="search-box" class="fas fa-search"></label>
    </div>

    <div class="cart-items-container">
      <div class="cart-item">
        <span class="fas fa-times"></span>
        <img src="src/assets/images/cart-item-1.png" alt="">
        <div class="content">
          <h3>cart item 01</h3>
          <div class="price">$15.99/-</div>
        </div>
      </div>
      <div class="cart-item">
        <span class="fas fa-times"></span>
        <img src="src/assets/images/cart-item-2.png" alt="">
        <div class="content">
          <h3>cart item 02</h3>
          <div class="price">$15.99/-</div>
        </div>
      </div>
      <div class="cart-item">
        <span class="fas fa-times"></span>
        <img src="src/assets/images/cart-item-3.png" alt="">
        <div class="content">
          <h3>cart item 03</h3>
          <div class="price">$15.99/-</div>
        </div>
      </div>
      <div class="cart-item">
        <span class="fas fa-times"></span>
        <img src="src/assets/images/cart-item-4.png" alt="">
        <div class="content">
          <h3>cart item 04</h3>
          <div class="price">$15.99/-</div>
        </div>
      </div>
      <a href="#" class="btn">checkout now</a>
    </div>

  </header>
  <!-- header section ends -->

  <!--home section starts-->
  <section class="home" id="home">
    <div class="content">
      <h3>fresh coffee in the morning</h3>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Placeat labore, sint cupiditate distinctio tempora reiciendis.</p>
      <a href="#" class="btn">get yours now</a>
    </div>
  </section>
  <!--home section ends-->

</template>

<script>
  export default{
    name: "Header",
  }

</script>

<style>



</style>