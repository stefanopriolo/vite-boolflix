<script>
export default {
  methods: {
    fetchData() {
      axios.get("https://api.themoviedb.org/3/search/movie", {
           params: {
              api_key:"f834b7044843801c3b66bcb20772ea40",
              query: "avengers"
            }
      })
    }
  }
}
</script>

<template>
</template>

<style scoped>
</style>
