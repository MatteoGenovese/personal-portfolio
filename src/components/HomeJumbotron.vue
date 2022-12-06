<template>
  <div>

      <div class="jumbotron container d-flex">

          <div data-aos="fade-in" class="box d-flex">
              <div class="d-flex w-100 align-items-center">
                  <div data-aos="fade-left" class="d-flex flex-column w-100 justify-content-center">
                      <h1 class="">
                          Ciao, sono Matteo Genovese!
                      </h1>
                      <h2>
                          Sono un programmatore, e questo è il mio portfolio.
                      </h2>
                  </div>

              </div>
              <div class="d-flex w-100 align-items-center">
                  <div data-aos="fade-right" class="d-flex flex-column w-100 justify-content-center">
                      <img src="../assets/FotoLinkedin.jpeg" alt="" class="w-100 profile-photo">
                  </div>

              </div>


          </div>

      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.box{

  height: 900px;
  width: 100%;
  justify-content:flex-start;
}

.profile-photo{
  clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
}

</style>