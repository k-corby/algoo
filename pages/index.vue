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
             <div style="position:fixed; top:-4%; right:20%">
             <svg width="100%" height="100%">
                <defs>
                    <pattern id="polka-dots" x="0" y="0" width="30" height="30" patternUnits="userSpaceOnUse">
                         
                        <circle fill="#000" cx="10" cy="10" r="5">
                        </circle>
                    </pattern>
                </defs>
                 
                <rect x="0" y="0" width="100%" height="100%" fill="url(#polka-dots)"></rect>
            </svg>  
             </div> 
             <div style="position:fixed; top:-30%; right:25%; z-index:-1; width:400px; height:400px;">
             <svg  width="100%" height="100%">
                <circle cx="200" cy="120" r="200" fill="white" />
              </svg>
             </div>                          
              <h1 data-scroll data-scroll-speed="1.5" class="br-top">
             <!--DIGITAL AGENCY<br>
              modern brands<span style="font-family:Muli; color:#FFC300;">.</span><br>
              <span style="font-weight:500; text-transform:uppercase; font-size:7.5vw;">digital agency</span> 
              <!--a digital agency<br><b>crafting unique </b><br>
                ideas for humans.
              <!--<b style="font-size:10vw; font-weight:700; letter-spacing:5px;">A Unique </b><br>
                <b style="margin-left:0vw;font-size:9vw; text-transform:;letter-spacing:-4px; line-height:10vw;">Digital Agency.</b><br>
               -->
               <b>Design Agency</b><br>
               Ideas <span class="text-white">&</span> Brands<span class="poppins text-white">.</span>
              
               
               
              </h1>
              <p data-scroll data-scroll-speed="1" class="caption">
              A design agency built to build modern brands.
                              <!-- Learn how to solve simple to complex programming problems.-->
              </p>
              <p class="bold"><br>01</p>
             <!--<div id="circle"></div>
              <div id="circle1"></div>-->
             <div id="scroll-down">scroll<DownArrow /></div>
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
                show you how to program them....
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