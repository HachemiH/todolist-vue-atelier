<template>
<section class="section">
  <div id="app"  class="container">
    <h1 class="title is-1">My Todo List</h1>
    <TodoList/>

    
  </div>
</section>
</template>

<script>
import TodoList from "./components/TodoList.vue";

export default {
  components: {
    TodoList,
  },
  name: 'app',
  
}
</script>

<style lang="scss">

</style>
