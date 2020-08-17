<template lang="html">
  <div class="sample">
    {{ title }}
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      default: 'Defalut Title',
    },
  },
  data() {
    return {
      num: 0,
      name: 'takanorip',
    }
  },
  methods: {
    plus() {
      this.num++
    },
  },
}
</script>

<style lang="scss" scoped>
.hide {
  display: none;
}
</style>
