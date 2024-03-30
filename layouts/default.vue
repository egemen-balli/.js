<template>
    <div>
      <Header />
      <Banner />
      <nuxt/>
    </div>
  </template>    
  <script>
  export default {
    middleware: ["session-control", "auth"]
  }
</script>