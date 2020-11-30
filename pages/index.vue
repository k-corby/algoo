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
