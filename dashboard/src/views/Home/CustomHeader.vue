<template>

  <div class="main_header">

    <div class="main_header_content">

      <header class="main_header_navigation">
        <h1>
          <img src="../../assets/images/logo_white.svg" alt="Feedbacker" title="Feedbacker" />
          <span class="indent-none">Feedbacker</span>
        </h1>

        <div>
          <button class="px-6 py-2 font-bold rounded-full text-white focus:outline-none">Criar uma conta</button>
          <button class="btn_white px-6 py-3">Entrar</button>
        </div>
      </header>

      <section class="main_header_hero">

        <div class="flex flex-col items-start space-y-10 ax-w-screen-md">

          <h2 class="text-white font-bold text-5xl">
            Tenha um feedback e faça seus clientes mais felizes
          </h2>

          <p class="text-white text-3xl">
            Receba ideias, reclamações e feedbacks com um<br> simples widget na página.
          </p>

          <a title="Crie uma conta grátis" href="#" class="btn_white px-6 py-3 lg:py-4">
            Crie uma conta grátis
          </a>

        </div>
      </section>

    </div>

  </div>

</template>

<script>
export default {

}
</script>

<style lang="postcss" scoped>
  /* Containers */
  .main_header{
    @apply bg-brand-main flex justify-center
  }

  .main_header_content{
    @apply flex flex-col space-y-4 w-4/5 max-w-6xl py-14
  }

  .main_header_content .main_header_navigation{
    @apply flex justify-between
  }

  .main_header_content .main_header_hero{
    @apply py-44 lg:py-48
  }

  @media (min-width: 640px) {
    .main_header_content{
      background-image:  url('../../assets/images/blue-balloons.svg');
      background-repeat: no-repeat;
      background-size: 630px;
      background-position: center 100%;
    }
  }

  @media (min-width: 940px) {
     .main_header_content{ background-position: 120% 100%; }
  }

  /* Buttons */
  .btn_white{
    @apply bg-white hover:bg-black  text-brand-main hover:text-white rounded-full font-bold shadow-md
  }

</style>
