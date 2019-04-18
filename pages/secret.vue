<template>
  <div>
    This is a secret page
    <br>
    If you not login, you can't see it
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  middleware: ['auth']
}
</script>

<style lang="scss" scoped>
</style>
