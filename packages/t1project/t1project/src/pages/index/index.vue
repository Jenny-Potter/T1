<template>
  <div>
    <div>you see ?Iam a main page and main project include using components in other file</div>
    <cakeone></cakeone>
  </div>
</template>

<script>
import cakeone from 't1-2/src/components/cakeone'
export default {
  data () {
    return {
    }
  },
  components: {
    cakeone
  },
  methods: {},

  created () {
    // let app = getApp()
  }
}
</script>

<style scoped>

</style>
