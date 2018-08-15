<template>
  <div>
    <a @click.prevent="$emit('dates-selected', {start: '2018-07-15', end: '2018-08-15'})" href="#">Select 2018-07-15 to 2018-08-15</a>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
}
</script>

<style scoped>

</style>
