<template>
 <!--Section -->
    <section class="pt-20 pb-48"   style="background: linear-gradient(90deg, #c4cffd 0%, #7e00f5 100%)">
      <div class="container mx-auto px-4" >
        <div class="flex flex-wrap justify-center text-center mb-24">
          <div class="w-full lg:w-6/12 px-4 ">
            <h2 class="text-shadow-lg shadow-lg shadow-indigo-900 com  text-white text-6xl font-semibold uppercase">
              Demo Projects
            </h2>
            <p class="text-2xl text-gray-300 leading-relaxed m-4 lato">
              Some test projects to give some examples and ideas for customers
            </p>
          </div>
        </div>
        <!-- Card Wrapper -->
        <div class="flex flex-wrap">
          <!-- Card 1 -->
          <div
            class="w-full md:w-4/12 lg:mb-0 mb-12 px-4 "
            data-aos="flip-right"
          >
            <div class="px-6"><a href="https://monsteria-vite.netlify.app/">
              <img
                id="learn"
                alt="..."
                src="../assets/Leaf.png"
                class="rounded max-w-full mx-auto shadow-indigo-900 shadow-xl"
                style="max-width: 250px"
              ></a>
              <div id="learn" class="pt-6 text-center">
                <a href="https://monsteria-vite.netlify.app/"><h5 class="text-xl text-emerald-300 font-bold">Monsteria</h5></a>
                <p class="mt-1 text-sm text-white uppercase font-semibold">
                  Mobile First Plant app
                </p>
              </div>
            </div>
          </div>
          <!-- Card 2 -->
          <div
            class="w-full md:w-4/12 lg:mb-0 mb-12 px-4"
            data-aos="flip-right"
          >
            <div class="px-6"><a href="https://vue-grocery-f79c2.web.app/">
              <img
                id="learn"
                alt="..."
                src="../assets/grocery-bag.png"
                class="rounded max-w-full mx-auto shadow-indigo-900 shadow-xl "
                style="max-width: 250px"
              ></a>
              <div id="learn" class="pt-6 text-center">
                <a href="https://vue-grocery-f79c2.web.app/"><h5 class="text-xl text-yellow-300 font-bold">Grocery List App</h5></a>
                <p class="mt-1 text-sm text-white uppercase font-semibold">
                  Tied to a backend database to handle grocery items
                </p>
              </div>
            </div>
          </div>
          <!-- Card 3 -->
          <div
            class="w-full md:w-4/12 lg:mb-0 mb-12 px-4"
            data-aos="flip-right"
          >
            <div class="px-6"><a href="http://www.github.com/pepe1776">
              <img
                id="learn"
                alt="..."
                src="../assets/Octocat.png"
                class="rounded max-w-full mx-auto shadow-indigo-900 shadow-xl"
                style="max-width: 250px"
              ></a>
              <a href="http://www.github.com/pepe1776"><div id="learn" class="pt-6 text-center">
                <h5 class="text-xl text-cyan-300 font-bold">
                  GitHub Repos
                </h5>
                <p class="mt-1 text-sm text-white uppercase font-semibold">
                  lots of projects in my public repositories
                </p>
              </div></a>
            </div>
          </div>
        </div>
      </div>
    </section>
</template>