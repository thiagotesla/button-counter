<script>
export default {
  data() {
    return {
      count: 0
    }
  }
}
</script>

<template>
  <button @click="count++">
    This button was clicked {{ count }} times.
  </button>
</template>