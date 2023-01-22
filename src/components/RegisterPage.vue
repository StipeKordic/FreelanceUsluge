<template>
  <div>
    <b-container-fluid>
      <b-navbar toggleable="lg" type="dark" variant="dark">
        <b-navbar-brand class="ms-3" href="/">Freelance usluge</b-navbar-brand>

        <b-navbar-toggle target="nav-collapse" class="me-2"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ms-auto me-2">
            <span class="text-light text-center me-4 mt-1">Već imate račun?</span>
            <b-button
              variant="outline-light"
              class="my-2 my-sm-0"
              type="button">
              Prijavi se
            </b-button>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>

      <header class="page-header gradient">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#ffffff" fill-opacity="1" d="M0,32L80,69.3C160,107,320,181,480,197.3C640,213,800,171,960,149.3C1120,128,1280,128,1360,128L1440,128L1440,320L1360,320C1280,320,1120,320,960,320C800,320,640,320,480,320C320,320,160,320,80,320L0,320Z"></path></svg>
      </header>


    </b-container-fluid>
    <b-container class="mt-5">
        <div class="row mb-2">
            <div class="col-md-6">
                <b-form-group id="input-group-1" label="Ime:" label-for="input-1">
                    <b-form-input id="input-1" placeholder="Unesite ime..."></b-form-input>
                </b-form-group>
            </div>
            <div class="col-md-6">
                <b-form-group id="input-group-2" label="Prezime:" label-for="input-2">
                    <b-form-input id="input-2" placeholder="Unesite prezime..."></b-form-input>
                </b-form-group>
            </div>
        </div>
        <div class="row mb-2">
            <div class="col-md-9">
                <b-form-group id="input-group-3" label="Email adresa:" label-for="input-3">
                    <b-form-input id="input-3" placeholder="Unesite vaš email..."></b-form-input>
                </b-form-group>
            </div>
            <div class="col-md-3">
                <b-form-group id="input-group-4" label="Broj mobitela:" label-for="input-4" description="npr. 063/123-456">
                    <b-form-input id="input-4" placeholder="Unesite vaš broj mobitela..."></b-form-input>
                </b-form-group>
            </div>
        </div>
        <div class="row mb-2">
            <div class="col-md-6">
                <b-form-group id="input-group-5" label="Lozinka:" label-for="input-5" description="Lozinka ne smije imati manje od 8 znakova i mora imati jedan broj!">
                    <b-form-input type="password" id="input-5" placeholder="Unesite lozinku..."></b-form-input>
                </b-form-group>
            </div>
            <div class="col-md-6">
                <b-form-group id="input-group-6" label="Potvrda lozinke:" label-for="input-6">
                    <b-form-input type="password" id="input-6" placeholder="Potvrdite lozinku..."></b-form-input>
                </b-form-group>
            </div>
        </div>
        <button class="btn btn-dark">Kreiraj račun!</button>
    </b-container>
  </div>
</template>

<script>
export default {
  name: "RegisterPage",
};
</script>

<style>
.gradient{
  height: 30vh;
  background: rgb(65,67,67);
  background: linear-gradient(0deg, rgba(65,67,67,1) 10%, rgba(57,57,57,1) 32%, rgba(33,37,41,1) 74%);
}

@media(max-width: 1020px){
  .gradient{
    height: 22vh;
  }
}
@media(max-width: 870px){
  .gradient{
    height: 18vh;
  }
}
@media(max-width: 630px){
  .gradient{
    height: 14vh;
  }
}
</style>