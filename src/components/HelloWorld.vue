<template>
  <div>
    <h1>{{ swiperType }}</h1>
    <HomePage/>
  </div>  
</template>

<script>
import HomePage from './HomePage'
export default {
  name: 'HelloWorld',
  components: {
    HomePage
  },
  data () {
    return {
      swiperType : 'Easy Vertical Swiper'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 20px;
    display: flex;
    align-items: center;
    flex-direction: column;
  }
  h1{
    color: #ffffff;
}
</style>
