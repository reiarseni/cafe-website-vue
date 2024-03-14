<template>

  <div class="box">
    <div class="icons">
      <a href="#" class="fas fa-shopping-cart"></a>
      <a href="#" class="fas fa-heart"></a>
      <a href="#" class="fas fa-eye"></a>
    </div>
    <div class="image">
      <img :src=imageURL alt="">
    </div>
    <div class="content">
      <h3>{{name}}</h3>
      <div class="stars">
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star"></i>
        <i class="fas fa-star-half-alt"></i>
      </div>
      <div class="price">{{price}} <span>{{oldPrice}}</span></div>
    </div>
  </div>

</template>

<script>

    export default{
        name: "ProductBox",
        props: {
            name: {
                type: String,
                default: "",
                required: true
            },
            price: {
              type: String,
              default: ""
            },
            oldPrice: {
              type: String,
              default: ""
            },
            imageURL:{
                type: String
            }
        }
       
    }
    
</script>

<style scoped>

  .products .box-container .box .icons a{
    height: 5rem;
    width: 5rem;
    line-height: 5rem;
    font-size: 2rem;
    border: var(--border);
    color: #fff;
    margin: 0.3rem;
  }

  .products .box-container .box .icons a:hover{
    background: var(--main-color);
  }
  .products .box-container .box .image{
    padding: 2.5rem 0;
  }

  .products .box-container .box .image img{
    height: 25rem;
  }
  .products .box-container .box .content h3{
    color: #fff;
    font-size: 2.5rem;
  }
  .products .box-container .box .content .stars{
    padding: 1.5rem;
  }
  .products .box-container .box .content .stars{
    font-size: 1.7rem;
    color: var(--main-color);
  }
  .products .box-container .box .content .price{
    color: #fff;
    font-size: 2.5rem;
  }
  .products .box-container .box .content .price span{
    font-size: 1.5rem;
    text-decoration: line-through;
    font-weight: lighter;
  }

</style>