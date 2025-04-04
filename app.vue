<template>
  <button @click="reverse">reverse</button>
  <p v-if="toggle">you can see</p>
  <p>{{ toggle }}</p>
</template>

<script>
export default {
  data() {
    return {
      toggle: true
    }
  },
  methods: {
    reverse() {
      this.toggle = !this.toggle
    }
  }
}
</script>