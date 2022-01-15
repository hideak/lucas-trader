<template>
  <div>
    <!-- Header -->
    <div class="section-1 mb-5">
      <div class="container col-12 col-lg-6 p-5 py-lg-5 text-light">
        <h2 class="mb-4">
          <i class="bi bi-bar-chart-steps me-3 brand-icon"></i>
          <span>LUCAS SALES TRADER</span>
        </h2>
        <h1 class="mb-3">TRANSFORME SUA VIDA FINANCEIRA HOJE!</h1>
        <p class="mb-3">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia
          obcaecati, rem beatae, eum, numquam ab cum placeat ipsam officiis
          architecto quia ipsum. Totam, aspernatur quia? Error ea deleniti
          labore aliquid!
        </p>
        <p class="mb-3">
          <b>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit est
            enim esse. Placeat quaerat incidunt non ut pariatur earum quod
            quibusdam.
          </b>
        </p>
        <button class="btn btn-primary btn-lg mb-3 px-5">ASSINAR AGORA</button>
        <p>Valor da assinatura: R$ 100,00</p>
      </div>
    </div>

    <!-- Payment Information -->
    <div class="section-2 container px-4 py-0 py-lg-4 mb-4">
      <div class="row">
        <div class="col-12 col-lg-4 d-flex">
          <h1 class="me-3">
            <i class="bi bi-shield-lock"></i>
          </h1>
          <div>
            <h5>Seu pagamento é seguro</h5>
            <p>
              Ambiente seguro. Seus dados estão protegidos e sua compra é 100%
              segura
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-4 d-flex">
          <h1 class="me-3">
            <i class="bi bi-phone"></i>
          </h1>
          <div>
            <h5>Acesso ao grupo privado</h5>
            <p>
              Seu acesso privado será enviado ao seu celular através do Whatsapp
              após a confirmação do pagamento.
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-4 d-flex">
          <h1 class="me-3">
            <i class="bi bi-bookmark-star"></i>
          </h1>
          <div>
            <h5>Garantimos sua compra</h5>
            <p>
              Você pode pedir a devolução de 100% do seu dinheiro dentro do
              período aquisitivo de 7 dias
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Course Information -->
    <div class="section-3">
      <div class="container px-4 py-4 py-lg-4">
        <div class="row mb-4 text-center">
          <div class="col-12 col-lg-6 m-auto">
            <h1>PARA QUAL TIPO DE PESSOA ESSE MÉTODO É ADEQUADO?</h1>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-lg-4">
            <h3>INICIANTE</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam
              excepturi perferendis aperiam beatae illum? Modi minus veritatis
              odio recusandae dolor. Voluptatem eaque cupiditate architecto?
              Deserunt excepturi error aperiam cumque fugit?
            </p>
          </div>
          <div class="col-12 col-lg-4">
            <h3>INTERMEDIÁRIO</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam
              excepturi perferendis aperiam beatae illum? Modi minus veritatis
              odio recusandae dolor. Voluptatem eaque cupiditate architecto?
              Deserunt excepturi error aperiam cumque fugit?
            </p>
          </div>
          <div class="col-12 col-lg-4">
            <h3>AVANÇADO</h3>
            <p>
              Lorem ipsum dolor sit amet consectetur, adipisicing elit. Magnam
              excepturi perferendis aperiam beatae illum? Modi minus veritatis
              odio recusandae dolor. Voluptatem eaque cupiditate architecto?
              Deserunt excepturi error aperiam cumque fugit?
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>

<style lang="scss">
div.section-1 {
  background-image: url("../assets/background.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

div.section-3 {
  background-image: linear-gradient(45deg, #e0ebff, #c7fff8);
}

i.brand-icon {
  display: inline-block;
  transform: rotate(-90deg);
}
</style>