<template>
  <main>
    <section class="container row py-1">
      <div class="col-md-6 d-none d-md-block">
        <img class="" src="../assets/banner_1.jpg" />
      </div>
      <div class="col-md-6 p-lg-5 mx-auto my-5">
        <h1 class="display-4 fw-normal">Rajiv Dixit</h1>
        <p class="lead fw-normal">(30 November 1967 – 30 November 2010)</p>
        <p>An Indian activist who promoted ayurveda and opposed allopathic medicine and opposed multi-national
          corporations.</p>
        <a class="btn btn-outline-secondary" href="#">Coming soon</a>
      </div>

    </section>
    <div class="album py-5 bg-light">
      <div class="container">

        <div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
          <div class="col">
            <div class="card ratio ratio-16x9">
              <iframe width="560" height="315" src="https://www.youtube.com/embed/v3GyHyY0a9E"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
            </div><!-- end card -->
            <h5 class="py-2">अगर आपके बाल भी झड़ रहे हैं तो कीजिये एक काम, झड़ते बाल बंद | त्रिफला कैसे लें | पित्त नाशक
              औषधि</h5>
          </div>
          <div class="col">
            <div class="card ratio ratio-16x9">
              <iframe width="560" height="315" src="https://www.youtube.com/embed/vVa3IZmQsLQ"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
            </div>
            <h5 class="py-2">मरते दम तक कोई भी बीमारी नहीं होगी | Rajiv Dixit ji | Swasthay katha</h5>
          </div>
          <div class="col">
            <div class="card ratio ratio-16x9">
              <iframe width="560" height="315" src="https://www.youtube.com/embed/mqc9_7teU0Q"
                title="YouTube video player" frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen></iframe>
            </div>
            <h5 class="py-2">त्रिफला और चूना 30 दिन खाया तो फायदे देख Doctor भी हैरान हो गये- Rajiv dixit ji</h5>
          </div>
        </div>
      </div>
    </div>
    <section class="home-testimonial">
      <div class="container-fluid">
        <div class="row d-flex justify-content-center testimonial-pos">
          <div class="col-md-12 pt-4 d-flex justify-content-center">
            <h3>Testimonials</h3>
          </div>
          <div class="col-md-12 d-flex justify-content-center">
            <h2>Explore the patients experience</h2>
          </div>
        </div>
        <section class="home-testimonial-bottom">
          <div class="container testimonial-inner">
            <div class="row d-flex justify-content-center">
              <div class="col-md-4 style-3">
                <div class="tour-item ">
                  <div class="tour-desc bg-white">
                    <div class="tour-text color-grey-3 text-center">&ldquo;Best place if you want to cure yourself from
                      severe desease like cancer, diabetes etc. Treatment is totally ayurvedic.go and check it
                      out.&rdquo;</div>
                    <div class="link-name d-flex justify-content-center fs-4">Suraj</div>
                  </div>
                </div>
              </div>
              <div class="col-md-4 style-3">
                <div class="tour-item ">
                  <div class="tour-desc bg-white">
                    <div class="tour-text color-grey-3 text-center">&ldquo;I have an asthma problem from childhood, then
                      I start taking treatment from planet ayurveda and now from 1 year i don't need to use my inhaler
                      pump.&rdquo;</div>
                    <div class="link-name d-flex justify-content-center fs-4">Vinay kumar</div>
                  </div>
                </div>
              </div>
              <div class="col-md-4 style-3">
                <div class="tour-item ">
                  <div class="tour-desc bg-white">
                    <div class="tour-text color-grey-3 text-center">&ldquo;I'm very thankful to Late Mr. Rajiv Dixit ji.
                      I'm very happy & contented. I tried fresh Coriander leaves paste 1 tbsp in one glass of drinking
                      water before breakfast for Hyperthyroidism and it really works for me. I can feel the difference.
                      God Bless you Sir.&rdquo;</div>
                    <div class="link-name d-flex justify-content-center fs-4">Altafur Rahman</div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
    </section>
  </main>
</template>
<style>
.banner {
  /* background-image: url(../assets/banner.jpg);
  background-size: 100%;
  width: 100%;
  height: 200px;
  background-repeat: no-repeat;
  position: relative;
  background-position: center;
  display: block; */

  height: 400px;
  position: relative;
  display: block;
}

.product-device {
  position: absolute;
  right: 10%;
  bottom: -30%;
  width: 300px;
  height: 540px;
  transform: rotate(30deg);
}

.home-testimonial {
  background-color: #231834;
  height: 380px
}

.home-testimonial-bottom {
  background-color: #f8f8f8;
  transition: background 0.3s, border 0.3s, border-radius 0.3s, box-shadow 0.3s;
  margin-top: 20px;
  margin-bottom: 0px;
  position: relative;
  height: 130px;
  top: 190px
}

.home-testimonial h3 {
  color: var(--orange);
  font-size: 14px;
  font-weight: 500;
  text-transform: uppercase
}

.home-testimonial h2 {
  color: white;
  font-size: 28px;
  font-weight: 700
}

.testimonial-inner {
  position: relative;
  top: -174px
}

.testimonial-pos {
  position: relative;
  top: 24px
}

.testimonial-inner .tour-desc {
  border-radius: 5px;
  padding: 40px
}

.color-grey-3 {
  font-family: "Montserrat", Sans-serif;
  font-size: 14px;
  color: #6c83a2
}

.testimonial-inner img.tm-people {
  width: 60px;
  height: 60px;
  -webkit-border-radius: 50%;
  border-radius: 50%;
  -o-object-fit: cover;
  object-fit: cover;
  max-width: none
}

.link-name {
  font-family: "Montserrat", Sans-serif;
  font-size: 14px;
  color: #6c83a2
}

.link-position {
  font-family: "Montserrat", Sans-serif;
  font-size: 12px;
  color: #6c83a2
}
</style>