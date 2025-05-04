<script setup>

</script>

<template>
  <!-- Designed by Atlantox https://atlantox.pythonanywhere.com/ -->
  <main class="row col-12 m-0 p-0">

    <section class="row col-12 m-0 p-0 ">
      <figure class="m-0 p-0 d-flex align-items-center justify-content-center shadowed-h">
        <img class="w-100 text-center my-hero" src="@/assets/images/grand-coliseum-cropped.jpg" alt="Coliseo image">
        <h1 class=" text-shadow position-absolute text-break text-center fw-bold main-title text-title">
          Formato Coliseo  
        </h1>
        <h3 class="position-absolute text-shadow italic text-center mt-5 pt-5 fw-bold main-subtitle text-title">« Donde cada mazo tiene su momento de gloria »</h3>        
      </figure>
    </section>

    <section class="row col-12 m-0 p-0 lb-bg-primary-dark text-white fs-5 py-5 text-center" id="content">
      <div class="row col-12 m-0 p-0 justify-content-center align-items-center">
        <h2 class="col-12 text-center text-white fw-bold mb-4">
          ¿Qué es coliseo?
        </h2>

        <div class="col-12 col-md-5 text-center">
          <figure class="col-12">
            <img class="col-10 col-md-8" src="@/assets/images/banned_cards.png" alt="">
          </figure>
        </div>

        <p class="col-12 col-md-7 fs-5 px-3">
          <strong>Coliseo</strong> es una interesante variación del formato multijugador <strong>Commander</strong>, diseñada para brindar una experiencia 
          de juego más equilibrada y divertida. Su filosofía es que la mayor cantidad de mazos y estrategias tengan una oportunidad real de alcanzar ana victoria.
          Eto se logra ajustando ciertas cartas clave como - <strong>Sol Ring</strong> y <strong>Thassa's Oracle</strong> — para limitar el dominio 
          de los mazos que abusan de combos infinitos o aceleración excesiva para ganar la partida. Esto crea un entorno donde la interacción, creatividad y 
          variedad estratégica florecen. Ya sea que juegues con un mazo preconstruido o uno personalizado, en Coliseo tendrás la oportunidad de competir 
          en igualdad de condiciones y disfrutar de partidas dinámicas, intensas y cargadas de sorpresas.
        </p>        
      </div>
    </section>

    <section class="row col-12 m-0 p-0 lb-bg-primary-l text-black fs-5 pt-4 py-5 text-center" id="info">
      <div class="row col-12 m-0 p-0 col-md-6 lb-border-r justify-content-center" id="objectives">
        <h2 class="col-12 text-center fw-bold mb-4">
          Objetivos
        </h2> 

        <div class="col-12 d-flex justify-content-center fs-6 text-start">
          <ul class="col-11 fs-5">
            <li class="my-3">
              Promover la realización de torneos en los que tanto los jugadores novatos como los experimentados tengan la oportunidad de 
              competir en un ambiente de transparencia y equidad, donde la inversión económica no represente una ventaja limitante.
            </li>
            <li class="my-3">
              Promover la viabilidad de la mayoría de arquetipos posibles en el juego con posibilidades reales de ganar.
            </li>
            <li class="my-3">
              Velar por la integración de todos los jugadores de comander en la comunidad fomentando espacios seguros y respetuosos.
            </li>
          </ul>
        </div>
      </div>

      <div class="row col-12 m-0 p-0 col-md-6 lb-border-r justify-content-center" id="rules">
        <h2 class="col-12 text-center fw-bold mb-3">
          Reglas para torneos
        </h2> 

        <div class="col-12 d-flex justify-content-center fs-6 text-start">
          <ul class="col-11 fs-5">
            <li class="my-3">
              Reglas estándar de Commander, vidas iniciales, impuesto de comandante, daño de comandante, orden de turnos, etc.
            </li>
            <li>
              Estrictamente 4 jugadores por juego.
            </li>
            <li class="my-3">
              90 minutos por ronda.
            </li>
            <li class="my-3">
              Prohibido señalar directamente a otros jugadores para dirigir el foco de la partida 
              (Pedir que ataquen a un jugador específico, decir que una carta en específica debe ser contrarrestada o destruída)
            </li>
            <li class="my-3">
              Prohibido ofrecer y realizar tratos con otros jugadores en medio de la partida, mejor conocido como <strong>Política</strong>
              (Si me atacas, lanzaré counter a tu comandante, atácalo a él y no mataré a tus criaturas)
            </li>
          </ul>
        </div>
      </div>
    </section>

    <section class="row col-12 m-0 p-0 lb-bg-primary-dark text-white fs-5 pt-4 py-5 text-center" id="banlists">
      <div class="row col-12 m-0 p-0 justify-content-center">
        <h2 class="col-12 text-center text-white fw-bold mb-4">
          Banlist
        </h2>
  
        <p class="col-12 col-lg-9 text-center">
          <strong>Coliseo</strong> cuenta con dos listas de baneos, las cartas prohibidas que no se pueden jugar bajo ningún concepto,
          y las que solo están prohibidas como comandante.
          <br><br>
          La lista de cartas prohibidas toman como referencia la banlist oficial de 
          <a class="fw-bold text-white text-decoration-underline" href="https://magic.wizards.com/en/banned-restricted-list" target="_blank">EDH</a> 
          añadiendo cartas que van en contra de los objetivos de <strong>Coliseo</strong> las cuales son elegidas minuciosamente
          por las personas encargadas del comité del formato.
          
        </p>
  
        <div class="col-12 col-lg-9 d-flex justify-content-center flex-wrap">
          <div class="col-6 col-md-3 px-3">
            <a href="https://manabox.app/decks/rg-uh4KUSY6EwM4Pp-vwgw" target="_blank">
              <button class="rounded lb-bg-secondary-l shadow-l border-0 p-2 fw-bold">
                Prohibidas totalmente
              </button>
            </a>
          </div>

          <div class="col-6 col-md-3 px-3">
            <a href="https://manabox.app/decks/93ZwKsK8SaWY85X27xWeOQ" target="_blank">
              <button class="rounded lb-bg-secondary-l shadow-l border-0 p-2 fw-bold">
                Prohibidas como comandante
              </button>
            </a>
          </div>

        </div>
      </div>
    </section>

    <section class="row col-12 m-0 p-0 lb-bg-primary text-white fs-5 pt-4 py-5 text-center" id="pointSystem">
      <div class="row col-12 m-0 p-0 justify-content-center">
        <h2 class="col-12 text-center text-white fw-bold mb-4">
          Sistema de puntos
        </h2>
  
        <p class="col-12 col-lg-9 text-center">
          En <strong>Coliseo</strong> se maneja un sistema de puntos para posicionar a los jugadores en un torneo, este sistema tiene la siguiente lógica.          
        </p>
  
        <div class="col-12 d-flex justify-content-center fs-6 text-start">
          <ul class="col-12 col-md-8 fs-5">
            <li class="my-3">
              Todas las partidas almacenan un total de 5 puntos.
            </li>
            <li class="my-3">
              Siempre que un jugador de muerte a un oponente, se lleva un punto, por ejemplo: daño de combate, proliferando contadores de veneno
              u obligando al oponente a robar una carta cuando este no tiene biblioteca.
            </li>
            <li class="my-3">
              El jugador que sea el último con vida gana dos puntos.
            </li>
            <li class="my-3">
              Una vez acabado el tiempo, se marca el turno del jugador activo, a partir de ahí se dará una vuelta de turnos extra antes de finalizar la partida.
              La partida acaba cuando llega el siguiente turno del jugador activo marcado.
            </li>
            <li class="my-3">
              Al suceder un empate, se suman los puntos restantes de la partida y se dividen entre los supervivientes. Los puntos restantes se calculan como:
              "Cantidad de jugadores supervivientes + 1". Se redondea a 2 decimales.
            </li>
            <li class="my-3">
              Una vez terminado un torneo, se suman los puntos que hizo cada jugador en cada una de sus partidas para formar el ranking del torneo y definir a los ganadores.
            </li>
          </ul>
        </div>

      </div>
    </section>
  </main>

  <footer class="row col-12 m-0 p-0 lb-bg-primary-dark pt-3 text-white fs-5">
    <div class="row col-12 m-0 p-0 align-items-center justify-content-center">

      <div class="row m-0 p-0 col-4 d-flex align-items-center justify-content-center">
        <div class="col-12 text-center">
          <ul class="list-unstyled">
            <li>
              <a class="text-white text-decoration-underline" href="https://www.youtube.com/@ComandMancos" target="_blank">Youtube</a>
            </li>
            <li>
              <a class="text-white text-decoration-underline" href="https://orc-ranking.onrender.com/" target="_blank">Ranking</a>              
            </li>
          </ul>
        </div>
      </div>

      <div class="col-3 col-md-2 text-center">
        <figure class="col-12">
          <img class="col-12 col-md-8 rounded" src="@/assets/images/grand-coliseum-cropped.jpg" alt="Coliseo image">
        </figure>
      </div>

      <div class="row m-0 p-0 col-4 d-flex align-items-center justify-content-center fs-6">
        <div class="col-12 text-center">
          <ul class="list-unstyled">
            <li>
              <a class="text-white text-decoration-underline" href="#content">Coliseo</a>              
            </li>
            <li>
              <a class="text-white text-decoration-underline" href="#objectives">Objetivos</a>              
            </li>
            <li>
              <a class="text-white text-decoration-underline" href="#rules">Reglas</a>              
            </li>
            <li>
              <a class="text-white text-decoration-underline" href="#banlists">Banlist</a>              
            </li>
            <li>
              <a class="text-white text-decoration-underline" href="#pointSystem">Puntos</a>              
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="row col-12 bg-black p-0 m-0">
      <div class="col-12 p-0 text-center text-white fs-6">
          Made by 
          <a href="https://atlantox.pythonanywhere.com/" target="_blank">
              Atlantox7
              <img style="width:40px;" src="@/assets/icons/atlantox-icon.png">
          </a>
      </div>
    </div>
  </footer>

</template>


<style scoped>
.my-hero{
  width:100vw;
  height:500px;  
}

.main-title{
  bottom:75%;
}

.main-subtitle{
  bottom:60%;
}

@media (max-width: 720px) {
    .my-hero{
        height:260px;
    }

    .main-title{
      bottom:90%;
      font-size: 30px !important;
    }

    .main-subtitle{
      bottom:75%;
      font-size: 18px !important;
    }

}
</style>