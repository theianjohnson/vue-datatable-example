<template>
  <div>
    <slot></slot>
    <table border="1">
      <tr>
        <td>Table cell 1</td>
        <td>Table cell 2</td>
        <td>Table cell 3</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {
  data() {
    return {}
  },
  methods: {
    queryData() {
      // eslint-disable-next-line
      console.log('Querying data from server (calling api endpoint, etc)');
    }
  }
}
</script>
