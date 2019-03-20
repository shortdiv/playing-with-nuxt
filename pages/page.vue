<template>
  <div id="page">
    <h1>Netlify loves Nuxt</h1>
    <img src="../assets/netlify_logomark.png" alt="">
  </div>
</template>

<script>
  export default {
    name: "page"
  }
</script>

<style lang="scss" scoped>
#page {
  margin: 10em;

  & h1 {
    text-align: center;
  }

  & img {
    display: block;
    margin: 0 auto;
    width: 100px;
    margin-top: 1em;
  }
}
</style>