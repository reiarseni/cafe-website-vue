<template>

  <!-- products section starts -->
  <section class="products" id="products">
    <h1 class="heading">our <span> products </span></h1>

    <div class="box-container">

      <ProductBox
          name="Fresh Coffee"
          price="$15.99"
          oldPrice="$20.99"
          imageURL="src/asset/images/product-1.png"
      ></ProductBox>

      <ProductBox
          name="Fresh Coffee"
          price="$19.99"
          oldPrice="$23.99"
          imageURL="src/asset/images/product-2.png"
      ></ProductBox>

      <ProductBox
          name="Fresh Coffee"
          price="$12.99"
          oldPrice="$17.99"
          imageURL="src/asset/images/product-3.png"
      ></ProductBox>

    </div>
  </section>
  <!-- products section ends -->

</template>

<script>

    import ProductBox from './product_box.vue';

    export default{
      name: "Products",
      components: {
        ProductBox: ProductBox
      },
    }

</script>

<style>

  /*products section*/
  .products .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit , minmax(30rem,1fr));
    gap: 1.5rem;
  }
  .products .box-container .box{
    text-align: center;
    border: var(--border);
    padding: 2rem;
  }



</style>