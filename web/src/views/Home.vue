<template>
  <div>
    <!-- Section 1 (Header) -->
    <div class="section-1">
      <div class="container p-5 text-light">
        <div class="row">
          <!-- Left side -->
          <div class="col-lg-7 text-center text-lg-start">
            <!-- Page Title -->
            <h4 class="mb-4">
              <i class="bi bi-bar-chart-steps me-3 brand-icon"></i>
              <span>LUCAS SALES TRADER</span>
            </h4>

            <!-- Product description -->
            <h1 class="mb-4">POR QUE SE TORNAR UM VISIONÁRIO?</h1>
            <p class="mb-4">
              Visionários são pessoas que pensam à frente da grande maioria.
              <b><em> São os futuros milionários </em></b>. Aqui você apenas
              copia, cola e ainda aprende, e por isso, eu afirmo com toda
              certeza que isso vai mudar a sua vida da mesma forma que anda
              mudando a de várias pessoas.
            </p>

            <!-- Product detail -->
            <p class="mb-4">
              <b>
                Vou te fazer uma pergunta:
                <em>"vai perder tempo até quando?"</em>. <br />
                Você vai ganhar dinheiro e conhecimento. <br />
                Sua virada de vida está aqui. <br />
                <em>Corra e não perca esta oportunidade!</em>
              </b>
            </p>

            <!-- Payment buttons -->
            <div class="mb-4">
              <div class="d-grid mb-4">
                <a href="#products">
                  <button class="btn btn-warning btn-lg w-100">
                    <b>ASSINAR AGORA</b>
                  </button>
                </a>
              </div>
              <div>Mentoria: R$ 200,00 à vista | Sala VIP: R$ 283,00</div>
              <h4>ou 12x de R$ 28,30 por mês</h4>
            </div>
          </div>

          <!-- Middle space -->
          <div class="col-1"></div>

          <!-- Right side -->
          <div class="col-lg-4">
            <div
              id="profileCarousel"
              class="carousel slide rounded-3"
              data-bs-ride="carousel"
            >
              <div class="carousel-indicators">
                <button
                  type="button"
                  data-bs-target="#profileCarousel"
                  data-bs-slide-to="0"
                  class="active"
                ></button>
                <button
                  type="button"
                  data-bs-target="#profileCarousel"
                  data-bs-slide-to="1"
                ></button>
                <button
                  type="button"
                  data-bs-target="#profileCarousel"
                  data-bs-slide-to="2"
                ></button>
              </div>
              <div class="carousel-inner">
                <div class="carousel-item active" data-bs-interval="5000">
                  <img
                    src="../assets/profile/profile-1.jpeg"
                    class="d-block w-100 rounded-3"
                  />
                  <div class="carousel-caption d-none d-md-block">
                    <h5>Lucas Sales</h5>
                    <p>@lucassalestrader</p>
                  </div>
                </div>
                <div class="carousel-item" data-bs-interval="5000">
                  <img
                    src="../assets/profile/profile-2.jpeg"
                    class="d-block w-100 rounded-3"
                  />
                  <div class="carousel-caption d-none d-md-block">
                    <h5>Lucas Sales</h5>
                    <p>@lucassalestrader</p>
                  </div>
                </div>
                <div class="carousel-item" data-bs-interval="5000">
                  <img
                    src="../assets/profile/profile-3.jpeg"
                    class="d-block w-100 rounded-3"
                  />
                  <div class="carousel-caption d-none d-md-block">
                    <h5>Lucas Sales</h5>
                    <p>@lucassalestrader</p>
                  </div>
                </div>
              </div>
              <button
                class="carousel-control-prev"
                type="button"
                data-bs-target="#profileCarousel"
                data-bs-slide="prev"
              >
                <span class="carousel-control-prev-icon"></span>
                <span class="visually-hidden">Previous</span>
              </button>
              <button
                class="carousel-control-next"
                type="button"
                data-bs-target="#profileCarousel"
                data-bs-slide="next"
              >
                <span
                  class="carousel-control-next-icon"
                  aria-hidden="true"
                ></span>
                <span class="visually-hidden">Next</span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Section 2 (Payment Information) -->
    <div class="section-2">
      <div class="container p-5 pb-4">
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
                Seu acesso privado será enviado ao seu celular através do
                Whatsapp após a confirmação do pagamento.
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
    </div>

    <!-- Section 3 (Course Information) -->
    <div class="section-3">
      <div class="container p-5 text-center">
        <div class="row">
          <div class="col-12 mb-4">
            <h2 class="mb-4">
              <i class="bi bi-coin"></i>
            </h2>
            <h2>TRANSFORME SUA VIDA HOJE!</h2>
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-lg-6">
            <h3 class="mb-3">
              <i class="bi bi-bar-chart me-3"></i>
              <span>Mentoria Trader Consistente</span>
            </h3>
            <p>
              Tenha acesso a um materia feito com muita dedicação, voltado para
              todos que querem se tornar traders consistentes e independentes
              financeiramente.
            </p>
          </div>
          <div class="col-12 col-lg-6">
            <h3 class="mb-3">
              <i class="bi bi-bank me-3"></i>
              <span>Sala VIP de Operações</span>
            </h3>
            <p>
              Obtenha lucros no curto prazo investindo em opções binárias, com
              uma sala VIP de operações e alta assertividade com um grupo que já
              opera há 4 anos no mercado.
            </p>
          </div>
        </div>
      </div>
    </div>

    <!-- Section 4 (Students) -->
    <div class="section-4">
      <div class="container p-5 text-center">
        <h2>
          <i class="bi bi-star-fill me-2 text-warning"></i>
          <i class="bi bi-star-fill me-2 text-warning"></i>
          <i class="bi bi-star-fill me-2 text-warning"></i>
          <i class="bi bi-star-fill me-2 text-warning"></i>
          <i class="bi bi-star-fill text-warning"></i>
        </h2>
        <h2 class="mb-2">
          "Minha missão é permitir que vidas sejam transformadas"
        </h2>
        <div class="mb-4">
          Veja o resultado que nossos alunos e mentorados estão obtendo com as
          minhas técnicas
        </div>

        <div class="d-flex d-lg-none justify-content-center">
          <div
            id="feedbackCarousel"
            class="carousel slide rounded-3"
            data-bs-ride="carousel"
          >
            <div class="carousel-indicators">
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="0"
                class="active"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="1"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="2"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="3"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="4"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="5"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="6"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarousel"
                data-bs-slide-to="7"
              ></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-1.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-2.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-3.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-4.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-5.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-6.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-7.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
              <div class="carousel-item" data-bs-interval="5000">
                <img
                  src="../assets/feedbacks/feedback-8.png"
                  class="d-block w-100 rounded-3"
                />
              </div>
            </div>
            <button
              class="carousel-control-prev"
              type="button"
              data-bs-target="#feedbackCarousel"
              data-bs-slide="prev"
            >
              <span class="carousel-control-prev-icon"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button
              class="carousel-control-next"
              type="button"
              data-bs-target="#feedbackCarousel"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>

        <div class="d-none d-lg-flex justify-content-center">
          <div
            id="feedbackCarouselWide"
            class="carousel slide rounded-3"
            data-bs-ride="carousel"
          >
            <div class="carousel-indicators">
              <button
                type="button"
                data-bs-target="#feedbackCarouselWide"
                data-bs-slide-to="0"
                class="active"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarouselWide"
                data-bs-slide-to="1"
              ></button>
              <button
                type="button"
                data-bs-target="#feedbackCarouselWide"
                data-bs-slide-to="2"
              ></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active" data-bs-interval="15000">
                <div class="row">
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-1.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-2.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-3.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="15000">
                <div class="row">
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-4.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-5.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-6.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                </div>
              </div>
              <div class="carousel-item" data-bs-interval="15000">
                <div class="row">
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-7.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-8.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                  <div class="col-4">
                    <img
                      src="../assets/feedbacks/feedback-9.png"
                      class="d-block w-100 rounded-3"
                    />
                  </div>
                </div>
              </div>
            </div>
            <button
              class="carousel-control-prev"
              type="button"
              data-bs-target="#feedbackCarouselWide"
              data-bs-slide="prev"
            >
              <span class="carousel-control-prev-icon"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button
              class="carousel-control-next"
              type="button"
              data-bs-target="#feedbackCarouselWide"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>
      </div>
    </div>

    <!-- Section 5 (Who is Lucas Sales) -->
    <div class="section-5">
      <div class="container p-5 text-center">
        <h2 class="mb-4">Quem é Lucas Sales?</h2>
        <div class="mb-4">
          <img
            class="profile-face rounded-circle"
            src="../assets/profile/face.jpeg"
          />
        </div>
        <div>
          Me chamo Lucas Sales. Sou conhecido por ser tão novo e já ter
          <em class="red"><b>movimentado milhões</b></em> em corretoras. Sou um
          <em class="red"><b>trader, investidor e mentor</b></em
          >. Estou aqui porque minha maior satisfação é ver vocês tendo
          liberdade financeira e geográfica. Quero ficar conhecido por mudar a
          vida de milhões de pessoas.
        </div>
      </div>
    </div>

    <!-- Section 6 (Payment Banner) -->
    <div class="section-6">
      <div class="container p-5 text-center">
        <div class="row justify-content-center">
          <div class="col-lg-6">
            <h2 class="mb-4">SEJA UM VISIONÁRIO!</h2>
            <div class="mb-4">
              Chega de ficar perdendo tempo com cursos caros e que não agregam
              em nada. Somente aqui você terá acesso à conteúdo de qualidade e
              com garantia para que você se desenvolva na área de investimentos
              por um preço justo e acessível.
            </div>

            <h4 id="products" class="text-danger mb-2">
              <b>OFERTA DE LANÇAMENTO</b>
            </h4>

            <h5 class="mb-4">Entre agora para a primeira turma</h5>
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="col-lg-6">
            <div class="d-grid mb-4">
              <div class="youtube-embed mb-3">
                <iframe
                  width
                  src="https://www.youtube.com/embed/gueibUq5dcc"
                  title="YouTube video player"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                ></iframe>
              </div>

              <a href="https://p.eduzz.com/1087492" target="_blank">
                <button class="btn btn-primary btn-lg w-100">
                  <div>Assine Agora</div>
                  <div>
                    <b>TRADER CONSISTENTE por</b>
                  </div>
                  <div>
                    <h1><b>R$ 200,00 à vista</b></h1>
                  </div>
                  <div>
                    <b>com Acesso Imediato</b>
                  </div>
                </button>
              </a>
            </div>
          </div>

          <div class="col-lg-6">
            <div class="d-grid mb-4">
              <div class="mb-3 youtube-embed">
                <iframe
                  src="https://www.youtube.com/embed/ceZafXJ7ByY"
                  title="YouTube video player"
                  frameborder="0"
                  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen
                ></iframe>
              </div>
              <a href="https://sun.eduzz.com/1277241" target="_blank">
                <button class="btn btn-warning btn-lg w-100">
                  <div>Assine Agora</div>
                  <div>
                    <b>SALA VIP DE OPERAÇÕES por</b>
                  </div>
                  <div>
                    <h1><b>12x de R$ 28,30</b></h1>
                  </div>
                  <div>
                    <b>ou R$ 283,00 à vista</b>
                  </div>
                </button>
              </a>
            </div>
          </div>
        </div>

        <div class="row justify-content-center">
          <div class="col-lg-6">
            <h4 class="text-danger mb-2">
              <i class="bi bi-check-circle me-3"></i>
              <b>Compra Segura</b>
            </h4>
            <h4 class="text-danger mb-2">
              <i class="bi bi-award me-3"></i>
              <b>Satisfação 100% Garantida</b>
            </h4>
            <h4 class="text-danger">
              <i class="bi bi-lock me-3"></i>
              <b>Privacidade Protegida</b>
            </h4>
          </div>
        </div>
      </div>
    </div>

    <!-- Section 7 (Disclaimer) -->
    <div class="section-7">
      <div class="container p-5 text-center bg-dark text-white">
        <p>
          <small>
            Aviso Legal: "Nenhuma informação contida neste produto deve ser
            interpretada como uma afirmação da obtenção de resultados. Qualquer
            referência ao desempenho passado ou potencial de uma estratégia
            abordada no conteúdo não é, e não deve ser interpretada como uma
            recomendação ou como garantia de qualquer resultado específico."
          </small>
        </p>
        <div>
          <small>
            Os dados coletados serão utilizados com a única intenção de entrar
            em contato com você e disponibilizar mais conteúdos e ofertas. Caso
            você não queira mais receber os nossos conteúdos, você pode
            solicitar a remoção dos seus dados através do e-mail:
            <a href="mailto:lucas100gol157@gmail.com"
              >lucas100gol157@gmail.com</a
            >
          </small>
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
  background-image: url("../assets/background/background.jpg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
}

div.section-3,
div.section-5 {
  background-image: linear-gradient(45deg, #ffffff, #ffc107);
}

div.section-7 {
  font-size: 0.75rem;
}

img.profile-face {
  max-width: 10rem;
}

div#feedbackCarousel {
  max-width: 20rem;
}

div#feedbackCarouselWide {
  max-width: 60rem;
}

i.brand-icon {
  display: inline-block;
  transform: rotate(-90deg);
}

em {
  color: yellow;
}

em.red {
  color: red;
}

div.youtube-embed {
  position: relative;
  width: 100%;
  height: 0;
  padding-bottom: 56.25%;
}

iframe {
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
}
</style>