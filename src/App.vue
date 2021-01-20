<template>
  <div id="app">
    <BarraSuperior />
    <div is="RowFullContent" />
    <RowContentText class="px-md-5"/>
    <BarraInferior />
    <b-container class="px-md-5">
      <b-row class="px-md-5">
        <b-col md class="border-top content-bottom"></b-col>
      </b-row>
    </b-container>
    <!-- <ExitIntent v-show="isVisible" @closePopUp="close" @showPopUp="show" /> -->
  </div>
</template>

<script>
import BarraInferior from '@/components/BarraInferior'
import BarraSuperior from '@/components/BarraSuperior'
import RowContentText from '@/components/RowContentText'
import RowFullContent from '@/components/RowFullContent'
// import ExitIntent from '@/components/ExitIntent'

export default {
  name: 'App',
  components: {
    BarraInferior,
    BarraSuperior,
    RowContentText,
    // ExitIntent,
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

  body.labtrack {
    font-size: 18px;
    font-family: Roboto, sans-serif;
  }
  .font-size-2x {
    font-size: 2em;
  }
  .content-bottom {
    margin-bottom: 12rem;
  }
</style>
