<template>
  <div>
    <p>AppPropriedade $style:{{style}}</p>
    <Header />
    <h1>Componente App</h1>
    <Body />
    
    <Footer />
  </div>
  
</template>

<script>
import Header from '@/components/layout/MainHeader.vue'
import Body from '@/components/layout/MainBody.vue'
import Footer from '@/components/layout/MainFooter.vue'

export default {
  name: 'App',  
  components: {
    Header,
    Body,
    Footer
  }
}
</script>

<style>
h1{ 
  color: red;
}
</style>
