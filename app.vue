<template>
  <p>{{ count }}</p>
</template>

<script>
export default {
  data() {
    return {
      count: 1
    }
  },

  mounted() {
    console.log(this.count)
    this.count = 2
  }
}
</script>