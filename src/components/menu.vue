<template>

  <!--  menu section starts -->
  <section class="menu" id="menu">
    <h1 class="heading"><span>our</span> menu</h1>
    <div class="box-container">
      <div class="box">
        <img src="src/assets/images/menu-1.png" alt="">
        <h3>test and healthy</h3>
        <div class="price">$15.99 <span>$20.99</span></div>
        <a href="#" class="btn">add to cart</a>
      </div>
      <div class="box">
        <img src="src/assets/images/menu-2.png" alt="">
        <h3>test and healthy</h3>
        <div class="price">$15.99 <span>$20.99</span></div>
        <a href="#" class="btn">add to cart</a>
      </div>
      <div class="box">
        <img src="src/assets/images/menu-3.png" alt="">
        <h3>test and healthy</h3>
        <div class="price">$15.99 <span>$20.99</span></div>
        <a href="#" class="btn">add to cart</a>
      </div>
      <div class="box">
        <img src="src/assets/images/menu-4.png" alt="">
        <h3>test and healthy</h3>
        <div class="price">$15.99 <span>$20.99</span></div>
        <a href="#" class="btn">add to cart</a>
      </div>
      <div class="box">
        <img src="src/assets/images/menu-5.png" alt="">
        <h3>test and healthy</h3>
        <div class="price">$15.99 <span>$20.99</span></div>
        <a href="#" class="btn">add to cart</a>
      </div>
      <div class="box">
        <img src="src/assets/images/menu-6.png" alt="">
        <h3>test and healthy</h3>
        <div class="price">$15.99 <span>$20.99</span></div>
        <a href="#" class="btn">add to cart</a>
      </div>
    </div>
  </section>
  <!--  menu section ends -->

</template>

<script>

    export default{
        name: "Menu",
    }

</script>

<style>

/* menu section*/
.menu .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit , minmax(30rem,1fr));
  gap: 1.5rem;
}
.menu .box-container .box{
  padding: 5rem;
  text-align: center;
  border: var(--border);
}

.menu .box-container .box img{
  height: 10rem;
}
.menu .box-container .box h3{
  color: #fff;
  font-size: 2rem;
  padding: 1rem 0;
}
.menu .box-container .box .price{
  color: #fff;
  font-size: 2.5rem;
  padding: 0.5rem 0;
}
.menu .box-container .box .price span{
  color: #fff;
  font-size: 1.5rem;
  text-decoration: line-through;
}
.menu .box-container .box:hover{
  background: var(--main-color-box-bg);
}

.menu .box-container .box:hover >*{
  color: var(--black);
}

</style>