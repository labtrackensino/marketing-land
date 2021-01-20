<template>
  <b-container :style="`background-image: url(${require('@/assets/img/back.jpg')})`" class="full-height" fluid>
    <b-row class="d-flex h-md-75 h-50 align-items-center">
      <b-col>
      </b-col>
    </b-row>
    <b-row>
      <b-col>
        <ScrollDown />
      </b-col>
    </b-row>
  </b-container>
</template>

<script>
import ScrollDown from '@/components/ScrollDown.vue'

export default {
  components: { ScrollDown }
}
</script>
<style lang="scss">
.full-height {
  height: 95vh;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}
</style>