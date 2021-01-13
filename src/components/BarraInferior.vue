<template>
  <div class="d-flex justify-content-end align-items-center bg-dark text-white fixed-bottom barra-inferior">
    <span class="mr-2">Teste</span>
    <a href="https://api.whatsapp.com/send?phone=554891743111" target="_blank" rel="noopener noreferrer">
      <b-img class="img-whats" src="https://likemarketing.com.br/wp-content/uploads/2020/08/WhatsApp-icone.png" />
    </a>
  </div>  
</template>

<script>
export default {

}
</script>
<style lang="scss">
  .barra-inferior {
    height: 6rem;

    .img-whats {
      height: 64px;
      width: 64px;
      margin-right: 120px;
      margin-bottom: 10px;
    }
  }
</style>