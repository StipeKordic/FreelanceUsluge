<template>
    <div>
      <b-container-fluid>
        <b-navbar toggleable="lg" type="dark" variant="dark">
          <b-navbar-brand class="ms-3" href="/">Freelance usluge</b-navbar-brand>

          <b-navbar-toggle target="nav-collapse" class="me-2"></b-navbar-toggle>

          <b-collapse id="nav-collapse" is-nav>
            <!-- Right aligned nav items -->
            <b-navbar-nav class="ms-auto me-2">
              <b-nav-item href="/about" class="hover">O nama</b-nav-item>
              <b-nav-item href="/vizija" class="hover">Vizija</b-nav-item>
              <b-nav-item href="#kontakt" class="hover">Kontakt</b-nav-item>
              <b-nav-item href="#" class="hover">Prijavi se</b-nav-item>
              <a href="/register">
                <b-button variant="outline-light" class="my-2 my-sm-0" type="button">
                  Registriraj se
                </b-button>
              </a>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </b-container-fluid>
      <header class="page-header gradient">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <h1 class="text-light text-center mt-5">
                Pretraži usluge
              </h1>
            </div>
          </div>
          <div class="row">
            <div class="col-md-3"></div>
            <div class="col-md-6">
              <b-input-group size="sm" class="mt-3">
                <b-form-input></b-form-input>
                <b-input-group-append>
                  <b-button squared variant="outline-light">Pretraži</b-button>
                </b-input-group-append>
              </b-input-group>
            </div>
            <div class="col-md-3"></div>
          </div>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#f3f4f5" fill-opacity="1" d="M0,96L60,112C120,128,240,160,360,186.7C480,213,600,235,720,224C840,213,960,171,1080,144C1200,117,1320,107,1380,101.3L1440,96L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path></svg>
      </header>
      <header class="page-header second-part-bg mt-3">
          <div class="container">
            <div class="row">
            <div class="col-md-12">
              <h1 class="text-dark text-center mt-5 mb-5">
                Popularno
              </h1>
            </div>
            </div>
            <div class="row">
              <div class="col-xl-3 col-lg-6 mb-3 ">
                <p class="text-dark text-center">Fotografiranje</p>
                <a href="#"><img src="../assets/Slike/usluge/fotografiranje.jpg" class="text-center"></a>
              </div>
              <div class="col-xl-3 col-lg-6 mb-3">
                <p class="text-dark text-center">Izrada web stranica</p>
                <a href="#"><img src="../assets/Slike/usluge/izrada_web_stranica.jpg"></a>
              </div>
              <div class="col-xl-3 col-lg-6 mb-3">
                <p class="text-dark text-center">Voiceover</p>
                <a href="#"><img src="../assets/Slike/usluge/voiceover.jpg"></a>
              </div>
              <div class="col-xl-3 col-lg-6 mb-3">
                <p class="text-dark text-center">Izrada postera</p>
                <a href="#"><img src="../assets/Slike/usluge/izrada_postera.jpg"></a>
              </div>
            </div>
          </div>
      </header>
      <section class="gradient-section">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#f3f4f5" fill-opacity="1" d="M0,128L60,149.3C120,171,240,213,360,208C480,203,600,149,720,149.3C840,149,960,203,1080,229.3C1200,256,1320,256,1380,256L1440,256L1440,0L1380,0C1320,0,1200,0,1080,0C960,0,840,0,720,0C600,0,480,0,360,0C240,0,120,0,60,0L0,0Z"></path></svg>
        <div class="container">
            <div class="row">
              <div class="col-md-12">
                <h1 class="text-light text-center mb-5">
                Što nudimo
                </h1>
              </div>
            </div>
            <div class="row">
              <div class="col-md-9">
                <p class="text-light">Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet Lorem ipsum dolor sit amet</p>
                <p class="text-light">Lorem ipsum dolor sit amet</p>
                <p class="text-light">Lorem ipsum dolor sit amet</p>
                <p class="text-light">Lorem ipsum dolor sit amet</p>
              </div>
              <div class="col-md-3">
                <img src="../assets/Slike/drugi_dio_slika.jpg" class="img-fluid max-width: 100% height: auto">
              </div>
            </div>
        </div>
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#f3f4f5" fill-opacity="1" d="M0,224L60,234.7C120,245,240,267,360,266.7C480,267,600,245,720,218.7C840,192,960,160,1080,144C1200,128,1320,128,1380,128L1440,128L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path></svg>
      </section>
      <b-container-fluid>
        <hr>
        <b-navbar id="kontakt" type="light" variant="light">
          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav class="ms-auto me-auto">
              <b-nav-item href="#" class="icon"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-facebook" viewBox="0 0 16 16">
                  <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
                </svg>
              </b-nav-item>
              <b-nav-item href="#" class="icon"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-instagram" viewBox="0 0 16 16">
                  <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"/>
                </svg>
              </b-nav-item>
              <b-nav-item href="#" class="icon"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-twitter" viewBox="0 0 16 16">
                  <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
                </svg>
              </b-nav-item>
              <b-nav-item href="#" class="icon"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                  <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/>
                </svg>
              </b-nav-item>
            </b-navbar-nav>
          </b-collapse>
        </b-navbar>
      </b-container-fluid>
    </div>
</template>


<script>
export default {
  name: "HomePage",
};

</script>

<style>
.gradient-section {
  height: 130vh;
  background: rgb(65,67,67);
  background: linear-gradient(0deg, rgba(65,67,67,1) 10%, rgba(57,57,57,1) 32%, rgba(33,37,41,1) 74%);
}
.second-part-bg{
  background: #f3f4f5;
  height: 100vh;
}
.gradient{
  height: 60vh;
  background: rgb(65,67,67);
  background: linear-gradient(0deg, rgba(65,67,67,1) 10%, rgba(57,57,57,1) 32%, rgba(33,37,41,1) 74%);
}
.icon{
  height: 2rem;
  width: 2rem;
  font-size: 0.6rem;
  margin-right: 5rem;
  border: solid black 1px;
  border-radius: 100%;
}
.hover:hover{
  border-bottom: solid #F8F9FA 1px;;
}
@media(max-width: 1400px){
  .gradient{
    height: 50vh;
  }
  .second-part-bg{
    height: 105vh;
  }
  .gradient-section{
    height: 110vh;
  }
}
@media(max-width: 1100px){
  .gradient{
    height: 45vh;
  }
  .second-part-bg{
    height: 140vh;
  }
  .gradient-section{
    height: 95vh;
  }
}
@media(max-width: 1000px){
  .gradient{
    height: 39vh;
  }
  .second-part-bg{
    height: 250vh;
  }
  .gradient-section{
    height: 85vh;
  }
}
@media(max-width: 900px){
  .gradient{
    height: 39vh;
  }
  .gradient-section{
    height: 80vh;
  }
}
@media(max-width: 770px){
  .gradient-section{
    height: 125vh;
  }
}
@media(max-width: 700px){
  .gradient{
    height: 30vh;
  }
  .gradient-section{
    height: 115vh;
  }
}
@media(max-width: 540px){
  .gradient-section{
    height: 102vh;
  }
}
</style>