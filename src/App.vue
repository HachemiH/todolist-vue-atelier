<template>
<section class="section">
  <div id="app"  class="container">
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
