<template>
  <div id="app">
    <Datatable>
      <template slot-scope="{ queryData }">
        <DateFilter v-on:dates-selected="queryData()"></DateFilter>
      </template>
    </Datatable>
  </div>
</template>

<script>
import Datatable from './components/Datatable.vue'
import DateFilter from './components/DateFilter.vue'

export default {
  name: 'app',
  components: {
    Datatable,
    DateFilter,
  }
}
</script>