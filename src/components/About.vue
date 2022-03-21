<template>
    <section id="about" class="py-20 flex"
    >
    
      <div class="container mx-auto px-4">
        <div class="items-center flex flex-wrap">
          <div
            class="w-full md:w-4/12 ml-auto mr-auto px-4 "
            data-aos="fade-right"
          >
            <img
              alt="..."
              class="max-w-full rounded-lg shadow-lg "
              src="https://images.unsplash.com/photo-1568138373211-b15267dbf84d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
            >
          </div>
          <div
            class="w-full md:w-5/12 ml-auto mr-auto px-4"
            data-aos="fade-left"
          >
            <div class="md:pr-12">
              <small class="lato text-cyan-100 text-xl">About my work</small>
              <h3 class="com text-6xl uppercase font-bold text-white">
                Full Stack
              </h3>

              <ul class="list-none mt-6 flex flex-col justify-center align-center text-center">
                <li class="py-6">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="font-semibold align-center flex  text-indigo-100"
                      ><i class="fas fa-scissors fa-4x" /></span>
                    </div>
                    <div>
                      <h4 class="lato text-white text-2xl ml-20">
                        From custom tailored designs to full production deployment
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-6">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="font-semibold align-center flex  text-indigo-100"
                      ><i class="fas fa-bolt-lightning fa-4x" /></span>
                    </div>
                    <div>
                      <h4 class="lato text-2xl text-white ml-20">
                        Vue/Vite applications and web sites that run extremely fast
                      </h4>
                    </div>
                  </div>
                </li>
                <li class="py-6">
                  <div class="flex items-center">
                    <div>
                      <span
                        class="font-semibold align-center flex  text-indigo-100"
                      ><i class="fas fa-users fa-4x" /></span>
                    </div>
                    <div>
                      <h4 class="lato text-2xl text-white ml-20">
                        Systems integrations including Crestron, Qsys, Dante, Control4, BrightSign
                      </h4>
                    </div>
                  </div>
                </li>
              </ul>
              
            </div>
             <div
    class="py-20 flex section"
  >
    <div class="container mx-auto px-6">
      <h2 class="text-4xl font-bold mb-2 text-white flex justify-center">
        Newest and Fastest technology available
      </h2>
      <h3 class="text-2xl mb-8 text-gray-200 flex justify-center">
        bring your business to the public at light speed.
     </h3>
      <!-- <button
        id="learn"
        class="flex justify-center text-cyan-500 bg-white font-bold rounded-full py-4 px-8 shadow-lg uppercase tracking-wider"
      >
        Ignite
      </button> -->
    </div>
  </div>
          </div>
        </div>
      </div>
      
    </section>
    </template>

    <style>
  .section {
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  inset: 0;
  padding: 50px;
  height: 100%;
  width: 100%;
  background-image: linear-gradient(
    to bottom right,
    rgb(173, 2, 252) 0%,
    rgb(196, 86, 247) 40%,
    rgb(45, 29, 190) 60%,
    rgb(142, 197, 248) 100%
  );
  background-size: 800% 800%;
  animation: movingGradient 20s linear infinite alternate;
}
@keyframes movingGradient {
  from {
    background-position: 0 0;
  }
  to {
    background-position: 100% 100%;
  }
}
    
    </style>