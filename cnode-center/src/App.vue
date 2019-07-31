<template>
  <div id="app">
    <headers></headers>
    <div class="main">
      <router-view name='slidebar'></router-view>
      <router-view name='main'></router-view>
    </div>
  </div>
</template>

<script>
import headers from "./components/Header";
import PostList from "./components/PostList";
export default {
  name: "App",
  components: {
    headers,
    PostList
  }
};
</script>

<style>
.main {
  background: #e1e1e1;
  padding: 4px 75px;
}
body{
  margin: 0;
  
}
</style>
