<template>
  <h1>Hello world! {{name}}</h1>
</template>
<script>
export default {
  layout: 'dark',
  asyncData ({ req }) {
    return {
      name: "Taylor"
    }
  }
}
</script>
