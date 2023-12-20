<template>
  <div>
    <span>{{
      this.prefix + Number.parseFloat(this.value).toFixed(this.precision)
    }}</span>
  </div>
</template>

<script>
export default {
  props: {
    value: Number,
    prefix: {
      default: "Rp",
      type: Number
    },
    precision: {
      default: 2,
      type: Number
    }
  }
};
</script>
