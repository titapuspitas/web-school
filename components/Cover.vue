<template>
          <div class="container">
                    <div class="row">
                              <div class="col">
                                        <div class="carousel fixed-top mt-5">
                                                  <div id="carouselExampleIndicators" class="carousel slide"
                                                            data-bs-ride="true">
                                                            <div class="carousel-indicators">
                                                                      <button type="button"
                                                                                data-bs-target="#carouselExampleIndicators"
                                                                                data-bs-slide-to="0" class="active"
                                                                                aria-current="true"
                                                                                aria-label="Slide 1"></button>
                                                                      <button type="button"
                                                                                data-bs-target="#carouselExampleIndicators"
                                                                                data-bs-slide-to="1"
                                                                                aria-label="Slide 2"></button>
                                                                      <button type="button"
                                                                                data-bs-target="#carouselExampleIndicators"
                                                                                data-bs-slide-to="2"
                                                                                aria-label="Slide 3"></button>
                                                            </div>
                                                            <div class="carousel-inner">
                                                                      <div class="carousel-item active">
                                                                                <img src="~/assets/img/brosur.jpeg"
                                                                                          class="d-block w-100 image image-center"
                                                                                          alt="brosur">
                                                                      </div>
                                                                      <div class="carousel-item">
                                                                                <img src="~/assets/img/guru.jpeg"
                                                                                          class="d-block w-100"
                                                                                          alt="guru">
                                                                      </div>
                                                                      <div class="carousel-item">
                                                                                <img src="~/assets/img/siswa.jpg"
                                                                                          class="d-block w-100"
                                                                                          alt="siswa">
                                                                      </div>
                                                            </div>
                                                            <button class="carousel-control-prev" type="button"
                                                                      data-bs-target="#carouselExampleIndicators"
                                                                      data-bs-slide="prev">
                                                                      <span class="carousel-control-prev-icon"
                                                                                aria-hidden="true"></span>
                                                                      <span class="visually-hidden">Previous</span>
                                                            </button>
                                                            <button class="carousel-control-next" type="button"
                                                                      data-bs-target="#carouselExampleIndicators"
                                                                      data-bs-slide="next">
                                                                      <span class="carousel-control-next-icon"
                                                                                aria-hidden="true"></span>
                                                                      <span class="visually-hidden">Next</span>
                                                            </button>
                                                  </div>
                                        </div>
                              </div>
                    </div>
          </div>
</template>

<style scoped>
/* .carousel-inner img {
  width: 50vw;
  padding-top: 15vh;
  height: 85vh;
  display: flex;
} */
.mt-5 {
          margin-top: 120px !important;
}

.image {
          height: 500px;
          object-fit: none;
}

.image-center {
          object-position: 50% 50%;
}
</style>