<template>
    <div>
      <Header />
      <Banner />
      <nuxt/>
    </div>
  </template>    
  <script>
  export default {
    middleware: ["auth", "session-control"]
  }
</script>