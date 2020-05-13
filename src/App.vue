<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12 superior">
        <div class="container-fluid">
          <div class="row">
            <div class="col-md-6">
              <img class="m-2 logo" src="./assets/logo-portfolio-branco.svg" alt srcset />
            </div>
            <div class="col-md-6 d-flex justify-content-md-end justify-content-sm-end">
              <div
                class="link-port"
                v-scroll-to="{ 
        el: '#element',
        easing: [0, .20, .50, 1.0],
        duration: 1000,
      
    }"
              >Serviços</div>
              
              <div class="link-port" v-scroll-to="{ 
        el: '#contact',
        easing: [0, .20, .50, 1.0],
        duration: 1000,
      
    }">Contato</div>
            </div>
          </div>
        </div>
        <div class="container">
          <div class="row">
            <div class="col-md-6 d-flex justify-content-center tm align-items-center">
              <div>
                <div class="title-1">Olá!!!</div>
                <div class="title-2">Meu nome é Eriton</div>
                <div class="title-1">Sou desenvolvedor full stack</div>
              </div>
            </div>
            <div class="col-md-6 d-flex justify-content-center">
              <img class="tm-img" src="./assets/person-main.svg" alt srcset />
            </div>
          </div>
        </div>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-md-12 d-flex flex-column justify-content-center align-items-center">
            <div class="whats">O que faço?</div>
            <div
              class="whatssub mb-5"
            >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ut metus lobortis, sodales tortor euismod, ornare dolor. Aliquam lobortis urna neque.</div>
          </div>
          <div
            id="element"
            class="col-md-4 d-flex flex-column justify-content-center align-items-center"
          >
            <img width="150px" src="./assets/design.svg" alt srcset />
            <div class="title-card">UI Design</div>
            <div
              class="phrase-card"
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa maxime autem tenetur ullam illo voluptate repudiandae asperiores sunt fugit minima sint eligendi sequi excepturi accusamus numquam optio, eveniet quasi officia.</div>
          </div>

          <div class="col-md-4 d-flex flex-column justify-content-center align-items-center">
            <img width="150px" src="./assets/html.svg" alt srcset />
            <div class="title-card">Front-end</div>
            <div
              class="phrase-card"
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa maxime autem tenetur ullam illo voluptate repudiandae asperiores sunt fugit minima sint eligendi sequi excepturi accusamus numquam optio, eveniet quasi officia.</div>
          </div>

          <div class="col-md-4 d-flex flex-column justify-content-center align-items-center">
            <img width="105px" src="./assets/mobile.svg" alt srcset />
            <div class="title-card">Mobile</div>
            <div
              class="phrase-card"
            >Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa maxime autem tenetur ullam illo voluptate repudiandae asperiores sunt fugit minima sint eligendi sequi excepturi accusamus numquam optio, eveniet quasi officia.</div>
          </div>
        </div>
      </div>

      <div class="container-fluid">
        <div class="row">
          <div class="col-md-12 footer-er">
            <div class="container-fluid">
              <div class="row">
                <div
                  class="col-md-6 d-flex flex-column justify-content-end align-items-center ajuste-1"
                >
                  <div
                    data-aos="fade-up"
                    data-aos-delay="200"
                    data-aos-duration="700"
                    data-aos-easing="ease-in-out"
                    data-aos-mirror="true"
                    data-aos-once="true"
                    class="mt-5"
                  >
                    <a
                      class="social-media"
                      href="https://www.facebook.com/profile.php?id=100010861334492"
                      target="_blank"
                    >
                      <i class="fab fa-facebook"></i>
                    </a>
                    <a
                      class="social-media"
                      href="https://www.linkedin.com/in/eriton-gomes-323713ba/"
                      target="_blank"
                    >
                      <i class="fab fa-linkedin"></i>
                    </a>
                    <a
                      class="social-media"
                      href="https://github.com/eritondev-stack"
                      target="_blank"
                    >
                      <i class="fab fa-github"></i>
                    </a>
                    <a
                      class="social-media"
                      href="https://www.behance.net/eritongomes"
                      target="_blank"
                    >
                      <i class="fab fa-behance-square"></i>
                    </a>
                  </div>
                </div>
                <div
                  class="col-md-6 d-flex flex-column justify-content-end align-items-center ajuste-2"
                >
                  <div
                    class="text-white contact"
                  >
                    <div>
                      <i class="far fa-envelope"></i> eriton.gomes.souza@gmail.com
                    </div>
                    <div>
                      <i class="fas fa-phone"></i> +55 11 960655281
                    </div>
                    <div id="contact">
                      <i class="fas fa-map-marked-alt"></i> São Paulo
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Signika:wght@300;400;600;700&display=swap");

body {
  font-family: "Signika", sans-serif;
  font-weight: 300;
}

.social-media {
  color: white;
  font-size: 30px;
  transition: 0.2s cubic-bezier(0, 0, 0.7, 1);
  margin: 0px 3px;
}
.social-media:hover {
  color: blueviolet;
  margin: 0px 15px;
}

.link-port {
  margin: 14px 14px;
  font-weight: 400;
  font-size: 20px;
  color: white;
  cursor: pointer;
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  transition: 0.5s ease-in-out;
  transition: 0.5s ease-in-out;
}

.link-port:hover {
  font-size: 25px;
  color: blueviolet;
}

.title-card {
  font-size: 35px;
  font-weight: 400;
  line-height: 50px;
  color: rgb(50, 50, 50);
}

.phrase-card {
  line-height: 20px;
  color: rgb(50, 50, 50);
  padding: 0px 15px;
}

.whatssub {
  font-size: 15px;
  color: rgb(50, 50, 50);
  width: 40%;
}
.whats {
  font-size: 40px;
  font-weight: 600;
  line-height: 50px;
  color: rgb(50, 50, 50);
}

.title-1 {
  font-size: 33px;
  line-height: 40px;
  color: rgb(193, 192, 192);
}

.title-2 {
  font-size: 59px;
  font-weight: 700;
  line-height: 50px;
  color: white;
}

.superior {
  background-image: url("./assets/superior.png");
  min-height: 450px;
  width: 100vw;
  background-size: cover;
}

.footer-er {
  background-image: url("./assets/footer.png");
  min-height: 300px;
  width: 100vw;
  background-position-y: 30px;
  background-position-x: -5px;
  background-repeat: no-repeat;
  background-size: cover;
}

.tm {
  height: 400px;
  position: relative;
  top: -60px;
}

.tm-img {
  width: 325px;
  position: relative;
  top: -70px;
}
.logo {
  width: 60px;
}

.ajuste-1 {
  min-height: 200px;
}
@media only screen and (max-width: 768px) {
  /* For mobile phones: */
  div.ajuste-1 {
    min-height: 200px;
  }

  .tm {
    height: 300px;
        position: relative;
    top: -10px;
  }

  .logo {
    display: none;
  }

  .tm-img {
    width: 325px;
    position: relative;
    top: -60px;
  }

  .link-port{
    margin-left: 30px;
     margin-right: 14px;
    margin-bottom: 50px;
    margin-top: 30px;
  }

  .whatssub {
  font-size: 20px;
  color: rgb(50, 50, 50);
  width: 90%;
  margin-top: 20px;
}

.contact{
  font-size: 20px;
}

}
</style>