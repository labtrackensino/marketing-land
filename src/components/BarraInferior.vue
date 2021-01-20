<template>
  <div class="py-1 bg-dark text-white fixed-bottom barra-inferior">
    <b-container class="clear-fix">
      <b-row>
        <b-col md="9">
          <b-button class="p-md-3" pill variant="success" size="lg">QUERO PARTICIPAR DO EVENTO</b-button>
        </b-col>
        <b-col md class="d-flex p-2 p-md-0 justify-content-between align-items-center">
          <b-button variant="link">QUER CONHECER O CURSO?</b-button>
          <a class="mr-md-5 float-right" href="https://api.whatsapp.com/send?phone=554891743111" target="_blank" rel="noopener noreferrer">
            <b-img class="img-whats" src="https://likemarketing.com.br/wp-content/uploads/2020/08/WhatsApp-icone.png" />
          </a>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>
export default {

}
</script>
<style lang="scss">
  .barra-inferior {
    .img-whats {
      height: 54px;
      width: 54px;
    }
  }
</style>