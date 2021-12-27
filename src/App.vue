<template>
  <div id="app">
    <Header/>
    <Body/>
    <Footer/>
  </div>
</template>

<script>


import Header from './components/Header/Header.vue'
import Body from './components/Body/Body.vue'
import Footer from './components/Footer/Footer.vue'

export default {
  name: 'app',
  data () {
    return {
    
    }
  }, 
  components: {
    Header,
    Body,
    Footer
  }
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@900&display=swap');

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
    
}

#app {
  font-family: 'Roboto', sans-serif;
}

.title_1 {
  color: #003294;
}

.title_2 {
  color: #FFA216;
}

p {
  margin: 0;
}
</style>
