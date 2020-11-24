<template>
  <div>
    <div class="grid">
      <main>
        <div class="pt-fs" data-scroll-section>
          <div
            data-scroll
            data-scroll-speed="1"
            class="row-fixed header yellow"
            data-anchor="Page 1"
          >
            <div id="banner">
              <h1 data-scroll data-scroll-speed="1.5">
                We explore, develop <br />& solve <b>Digital problems</b><br />
                for humans.
              </h1>
              <p data-scroll data-scroll-speed="1">
                Learn how to solve simple to complex programming problems.
              </p>

              <a
                data-scroll
                data-scroll-speed="2"
                id="scroll-down"
                href="#page-2"
                ><DownArrow />
              </a>
            </div>
          </div>
          <!--<div class="row-fluid bg-white pb" data-anchor="Page 1">
            <div class="sticky ar col-span">
              <div data-scroll>01.</div>
              <h1 data-scroll class="heading">Research.</h1>
            </div>
            <div class="ml9vw mr9vw">
              <img
                data-scroll
                data-scroll-speed="2"
                class="scale-crop scale-crop-vw blend-mode"
                src="~../assets/img/uploads/research.jpg"
              />
            </div>
            <div class="pl pr">
              <h4 data-scroll data-scroll-speed="1" class="mt-vw5">
                Identify the current market to build something special.
              </h4>
              <p data-scroll data-scroll-speed="1">
                Once the brief has been received by the applicant and the market
                studied, our first reflex is to find out more about its
                customers: their expectations, their needs, their frustrations.
              </p>
              <p data-scroll data-scroll-speed="1" class="mrg-top-50">
                <a class="btn btn-fixed" href="/home/philosophy"
                  >Explore &rarr;</a
                >
              </p>
            </div>
          </div>

          <div class="row-fluid bg-lgrey pb" data-anchor="Page 2">
            <div class="sticky al col-span">
              <div data-ix="fade-in-on-load" class="number">02.</div>
              <h1 class="heading al">Branding.</h1>
            </div>
            <div class="pl9vw pr">
              <h4 class="mt-vw5" data-scroll data-scroll-speed="1">
                We develop a unique branding experience.
              </h4>
              <p class="" data-scroll data-scroll-speed="1">
                Branding is an essential component that requires research,
                prototyping and integration of unique elements to make you stand
                out from others.
              </p>
              <p class="mrg-top-50" data-scroll data-scroll-speed="1">
                <a class="btn btn-fixed" href="/home/philosophy"
                  >Explore &rarr;</a
                >
              </p>
            </div>
            <div class="mr">
              <img
                data-scroll
                data-scroll-speed="2"
                class="scale-crop scale-crop-vw blend-mode"
                src="~../assets/img/uploads/sketch-hand.jpg"
              />
            </div>
          </div>
          <div class="row-fluid pb bg-white" data-anchor="Page 3">
            <div class="sticky col-span">
              <div>03.</div>
              <h1 class="heading">Prototype.</h1>
            </div>
            <div class="pl9vw pr">
              <h4 class="mt-vw5" data-scroll data-scroll-speed="1">
                Refine ideas to build a unique user experience.
              </h4>
              <p class="" data-scroll data-scroll-speed="1">
                We teach from experience. Our educators are top-tier freelance
                web designers who will show you the frameworks they use in their
                own businesses.
              </p>
            </div>
            <div class="mr">
              <img
                data-scroll
                data-scroll-speed="2"
                class="scale-crop scale-crop-vw blend-mode"
                src="~../assets/img/uploads/app-dev.jpg"
              />
            </div>
          </div>
          <div class="row-fluid bg-white pb bg-lgrey" data-anchor="Page 4">
            <div class="sticky col-span">
              <div class="number">04.</div>
              <h1 class="heading">Development.</h1>
            </div>

            <div class="ml">
              <img
                data-scroll
                data-scroll-speed="2"
                class="scale-crop scale-crop-vw blend-mode"
                src="~../assets/img/uploads/dev-app.jpg"
              />
            </div>
            <div class="pl9vw pr">
              <h4 class="mt-vw5" data-scroll data-scroll-speed="1">
                Custom crafted applications for devices.
              </h4>
              <p class="" data-scroll data-scroll-speed="1">
                We teach from experience. Our educators are top-tier freelance
                web designers who will show you the frameworks they use in their
                own businesses.
              </p>
            </div>
          </div>-->
          <PortfolioList />
          <div class="row-fluid img-fluid bg-white" data-anchor="Page 3">
            <div class="col-span pl pr pt-vw10 pb bg-blue text-white">
              <h1 class="mrg-top poppins trans-stroke">Recent work.</h1>
              <p class="caption">
                Learn how to solve simple to complex programming problems.
              </p>
            </div>
            <article class="">
              <img src="~../assets/img/banner/programming.jpg" />
              <div class="overlay">
                <div class="text">
                  <h1>Depth First Search</h1>
                  <p>algorithm</p>
                </div>
              </div>
            </article>
            <article class="">
              <img src="~../assets/img/banner/ui-design.jpg" />
              <div class="overlay">
                <div class="text">
                  <h1>Mobile Development Concepts</h1>
                  <p>User Interface Design</p>
                </div>
              </div>
            </article>
            <article class="">
              <img src="~../assets/img/banner/ipad.jpg" />
              <div class="overlay">
                <div class="text">
                  <h1>Cross Platform Development</h1>
                  <p>PROGRAMMING</p>
                </div>
              </div>
            </article>
            <article class="">
              <div class="overlay">
                <div class="text">
                  <h1>Tablet Solutions</h1>
                  <p>Development</p>
                </div>
              </div>
            </article>
          </div>
          <div
            class="row-fluid bg-white"
            style="padding-top: 250px"
            data-anchor="Page 4"
          >
            <div>
              <img width="100%" src="../assets/img/services.png" />
            </div>
            <div
              class="row-space-right"
              data-aos="fade-up"
              data-aos-duration="3000"
            >
              <h1 class="br-top mrg-top">
                Featured<br />
                algorithms
              </h1>
              <p>
                We break down programming concepts to simple pseudocode and then
                show you how to program them.
              </p>
              <p class="mrg-top">
                <a class="btn btn-fixed" href="/home/philosophy"
                  >Explore &rarr;</a
                >
              </p>
            </div>
          </div>
        </div>
      </main>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({});
</script>

<style>
</style>
