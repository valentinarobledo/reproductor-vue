<template>
  <div id="app">
    <div class="container">
      
      <div class="slide">
        <Slide/>
      </div>
      <div class="search">
        <Search/>
      </div>
      <div class="recent">
        <Recent/>
      </div>
      <div class="list">
        <List/>
      </div>
      <div class="play">
        <Play/>
      </div>
    </div>
  </div>
</template>

<script>
import List from './components/List.vue'
import Play from './components/Play.vue'
import Recent from './components/Recent.vue'
import Search from './components/Search.vue'
import Slide from './components/Slide.vue'

export default {
  name: 'App',
  components: {
    List,
    Play,
    Recent,
    Search,
    Slide
  }
}
</script>

<style lang="scss">
body{
  background-color:#f5f5f5ad;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.container{
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 10px;
  grid-auto-rows: minmax(100px, auto);
}
.slide{
  grid-column: 1;
  grid-row: 1/4;
}
.search{
  grid-column:2/4;
  grid-row:1;
  width:80%;
}
.recent{
  grid-column: 2/4;
  grid-row:2;

}
.list{
  grid-column: 2;
  grid-row:3;

}
.play{
  grid-column:3;
  grid-row:3;

}
</style>
