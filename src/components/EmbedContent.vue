<template>
  <b-container>
    <b-row class="px-md-5">
      <b-col class="px-md-4 border-left border-right">
        <b-embed type="iframe" :aspect="aspect" src="https://www.lp.labtrack.com.br/teste/embed/q/67"></b-embed>
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
export default {
  computed: {
    aspect() {
      const windowWidth = window.innerWidth
      if (windowWidth >= 1200) {
        return '16by9'
      }
      if (windowWidth >= 992) {
        return '4by3'
      }
      return '1by1'
    }
  }
}
</script>
<style lang="scss">
  .barra-inferior {
    height: 6rem;
  }
</style>