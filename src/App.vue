<template>
  <div id="app">
    <Header/>
    <Body/>
  </div>
</template>

<script>


import Header from './components/Header/Header.vue'
import Body from './components/Body/Body.vue'

export default {
  name: 'app',
  data () {
    return {
    
    }
  }, 
  components: {
    Header,
    Body
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
  height: 9000px;
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
