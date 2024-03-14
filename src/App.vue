<script>

import Header from './components/header.vue';
import About from './components/about.vue';
import Menu from './components/menu.vue';
import Products from './components/products.vue';
import Reviews from './components/reviews.vue';
import Contact from './components/contact.vue';
import Blogs from './components/blogs.vue';
import Footer from './components/footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    About,
    Menu,
    Products,
    Reviews,
    Contact,
    Blogs,
    Footer
  },
  mounted() {

    import('./asset/script.js')

  },
}

</script>

<template>
    <Header></Header>
    <About></About>
    <Menu></Menu>
    <Products></Products>
    <Reviews></Reviews>
    <Contact></Contact>
    <Blogs></Blogs>
    <Footer></Footer>
</template>

<style>

</style>
