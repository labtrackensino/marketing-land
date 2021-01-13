<template>
  <div id="app">
    <b-container class="content-container">
      <RowFullContent />
      <RowContent />
      <RowContent />
      <RowContent />
      <RowContent />
      <RowContent />
      <RowContent />
      <RowContent />
      <RowContent />
    </b-container>
    <BarraInferior />
    <ExitIntent v-show="isVisible" @closePopUp="close" @showPopUp="show" />
  </div>
</template>

<script>
import BarraInferior from '@/components/BarraInferior'
import RowContent from '@/components/RowContent'
import RowFullContent from '@/components/RowFullContent'
import ExitIntent from '@/components/ExitIntent'

export default {
  name: 'App',
  components: {
    BarraInferior,
    RowContent,
    ExitIntent,
    RowFullContent
  },
  data() {
    return {
      isVisible: false
    };
  },
  methods: {
    show() {
      this.isVisible = true;
    },
    close() {
      this.isVisible = false;
    }
  }
}
</script>

<style lang="scss">
  @import 'node_modules/bootstrap/scss/bootstrap.scss';
  @import 'node_modules/bootstrap-vue/src/index.scss';

  .content-container {
    margin-top: 2rem;
    margin-bottom: 6rem;
  }
</style>
