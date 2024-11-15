<script>
import CommentList from './components/CommentList.vue';

export default {
  name: 'App',
  components: {
    CommentList
  }
};
</script>

<template>
  <div id="app">
    <h1>Tambahkan Komentar</h1>
    <CommentList />
  </div>
</template>

<style>
#app {
  font-family: 'Arial', sans-serif;
  background-color: #f9f9f9;
  padding: 30px;
}

h1 {
  text-align: center;
  font-size: 24px;
  color: #333;
  margin-bottom: 20px;
}
</style>
