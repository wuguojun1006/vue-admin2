<template>
  <div class="dashboard-container">
    <hah></hah>
    {{val()}}
  </div>
</template>

<script>
import Hah from './hahah'

export default {
  name: 'Dashboard',
  components: {
    Hah
  },
  methods: {
    val() {
      console.log(23)
    }
  }
}
</script>