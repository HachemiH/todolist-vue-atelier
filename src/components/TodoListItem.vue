<template>
  <li class="list-item">
    {{ todo.text }}
    <button @click="$emit('remove', todo.id)" class="button is-danger is-small">X</button>
  </li>
</template>

<script>
export default {
  props: {
    todo: {
      type: Object,
      required: true
    }
  }
};
</script>

<style>
</style>