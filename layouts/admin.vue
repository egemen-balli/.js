<template>
  <div>
    <Header />
    <nuxt/>
  </div>
</template>
<script>
  export default {
    middleware: ["session-control", "auth"]
  }
</script>

