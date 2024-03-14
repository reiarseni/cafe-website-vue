<template>

  <!-- blog section starts -->
  <section class="blogs" id="blogs">

    <h1 class="heading"> our <span>blogs</span> </h1>

    <div class="box-container">

      <div class="box">
        <div class="image">
          <img src="src/asset/images/blog-1.jpg" alt="">
        </div>
        <div class="content">
          <a href="#" class="title">tasty and refreshing coffee</a>
          <span>by admin / 21st may, 2021</span>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, dicta.</p>
          <a href="#" class="btn">read more</a>
        </div>
      </div>

      <div class="box">
        <div class="image">
          <img src="src/asset/images/blog-2.jpg" alt="">
        </div>
        <div class="content">
          <a href="#" class="title">tasty and refreshing coffee</a>
          <span>by admin / 21st may, 2021</span>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, dicta.</p>
          <a href="#" class="btn">read more</a>
        </div>
      </div>

      <div class="box">
        <div class="image">
          <img src="src/asset/images/blog-3.jpg" alt="">
        </div>
        <div class="content">
          <a href="#" class="title">tasty and refreshing coffee</a>
          <span>by admin / 21st may, 2021</span>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, dicta.</p>
          <a href="#" class="btn">read more</a>
        </div>
      </div>

    </div>

  </section>
  <!-- blog section ends -->

</template>

<script>

    export default{
        name: "Blogs",
    }

</script>

<style scoped>

.blogs .box-container{
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
  gap:1.5rem;
}

.blogs .box-container .box{
  border:var(--border);
}

.blogs .box-container .box .image{
  height: 25rem;
  overflow:hidden;
  width: 100%;
}

.blogs .box-container .box .image img{
  height: 100%;
  object-fit: cover;
  width: 100%;
}

.blogs .box-container .box:hover .image img{
  transform: scale(1.2);
}

.blogs .box-container .box .content{
  padding: 2rem;
}

.blogs .box-container .box .content .title{
  font-size: 2.5rem;
  line-height: 1.5;
  color: #fff;
}
.blogs .box-container .box .content .title:hover{
  color: var(--main-color);
}
.blogs .box-container .box .content span{
  color: var(--main-color);
  display: block;
  padding-top: 1rem;
  font-size: 2rem;
}
.blogs .box-container .box .content p{
  font-size: 1.6rem;
  line-height: 1.8;
  color: #ccc;
  padding: 1rem 0;
}

</style>