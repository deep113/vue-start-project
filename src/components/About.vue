<template>
  <div class="hello">
    <h1>{{ title }}</h1>
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      title: 'Welcome to Your About Page'
    }
  }
}
</script>

<style scoped>
h1, h2 {
  font-weight: normal;
}
</style>
