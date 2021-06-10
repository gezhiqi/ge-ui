<template>
  <div class="hm-checkbox-group">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "HmCheckboxGroup",
  props: {
    value: {
      type: Array
    }
  },
  data() {
    return {};
  },
  provide() {
    return {
      CheckboxGroup: this
    };
  }
};
</script>

<style lang="scss"></style>
