<template>

  <!-- footer section starts -->
  <section class="footer">

    <div class="share">
      <a href="#" class="fab fa-facebook-f"></a>
      <a href="#" class="fab fa-twitter"></a>
      <a href="#" class="fab fa-instagram"></a>
      <a href="#" class="fab fa-linkedin"></a>
      <a href="#" class="fab fa-pinterest"></a>
    </div>

    <div class="links">
      <a href="#">home</a>
      <a href="#">about</a>
      <a href="#">menu</a>
      <a href="#">products</a>
      <a href="#">review</a>
      <a href="#">contact</a>
      <a href="#">blogs</a>
    </div>
    <div class="credit">
      created by
      <span class="developer-info"> <a href="https://www.facebook.com/nobody" target="https://www.facebook.com/nobody">Rei </a></span> | all rights reserved <br> <br>
      <p class="orignal">orignal template | Mr. Web Designer</p>
    </div>
  </section>
  <!-- footer section ends -->

</template>

<script>

    export default{
        name: "Footer",
    }

</script>

<style scoped>

/*footer section*/
.footer{
  background:var(--black);
  text-align: center;
}

.footer .share{
  padding:1rem 0;
}

.footer .share a{
  height: 5rem;
  width: 5rem;
  line-height: 5rem;
  font-size: 2rem;
  color:#fff;
  border:var(--border);
  margin:.3rem;
  border-radius: 50%;
}

.footer .share a:hover{
  background-color: var(--main-color);
}

.footer .links{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  padding:2rem 0;
  gap:1rem;
}

.footer .links a{
  padding:.7rem 2rem;
  color:#fff;
  border:var(--border);
  font-size: 2rem;
}

.footer .links a:hover{
  background:var(--main-color);
}

.footer .credit{
  color:#fff;
  font-weight: lighter;
  font-size: 2rem;

}

.footer .credit .developer-info a{
  color: var(--main-color);
  font-weight: 400;
  font-size: 2rem;
}
.footer .credit .developer-info{
  font-size: 2rem;
}
.footer .credit .orignal{
  color: #fff;
  font-size: 16px;
  margin-bottom: 15px;
}

</style>