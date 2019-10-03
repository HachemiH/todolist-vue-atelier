<template>
  <div class="control has-icons-left has-icons-right">
    <input
      class="input is-large"
      type="text"
      placeholder="Enter your Task"
      :value="value"
      v-on="listeners"
    />
    <span class="icon is-medium is-left">
      <i class="fas fa-check-square"></i>
    </span>
  </div>
</template>

<script>
export default {
  props: {
    value: {
      type: String,
      default: ""
    }
  },
  computed: {
    listeners() {
      return {
        // Pass all component listeners directly to input
        ...this.$listeners,
        // Override input listener to work with v-model
        input: event => this.$emit("input", event.target.value)
      };
    }
  }
};
</script>

<style>
</style>