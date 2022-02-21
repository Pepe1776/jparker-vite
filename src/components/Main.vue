<template>
  <!-- Main Area -->
  <main>
    <!-- Hero -->
    <div
    @mousemove="onMousemove"
  :style="{ backgroundColor: `hsl(${x}, 50%, 20%)` }"
   class="movearea relative pt-32 pb-32 flex content-center items-center justify-center"
   style="min-height: 95vh"
    >
      <div
        :class="enhance ? 'opacity-10' : 'hidden'"
        class="absolute opacity-10 top-0 w-full h-full bg-top bg-cover"
        style="
          background-image: url('https://images.unsplash.com/photo-1511447333015-45b65e60f6d5?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=955&q=80');
        "
      >
        <span
          id="blackOverlay"
          class="w-screen h-full absolute  border-box"
        />
      </div>
      <div class="container relative mx-auto" data-aos="fade-in">
        <div class="items-center flex flex-wrap">
          <div id="name" class="w-full lg:w-full px-4 ml-auto mr-auto text-center">
            <div>

              
              <h1 id="j" class=" font-semibold text-9xl text-shadow-xl">
                J <span class="parker">Parker</span>
              </h1>
              <p class="p-2 mt-5 text-2xl text-shadow-xl text-white">
                Fully responsive and extremely fast modern applications and web pages tailor made for each customers needs and wants
              </p>
              <p class="text-white">x: {{ x }}</p>

              <a
                id="learn"
                @click="enhance = !enhance"
                class="shadow-2xl text-shadow-2xl nter bg-transparent hover:bg-white text-white font-bold hover:text-indigo-500 p-4 border border-white hover:border-transparent rounded inline-block mt-5 cursor-pointer hover:translate-y-5 active:translate-y-5"
              >Enhance</a>
            </div>
          </div>
        </div>
      </div>
      <div
        class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon points="2560 0 2560 100 0 100" />
        </svg>
      </div>
    </div>


   
  </main>
</template>
<script>

export default {
    data() {
    return {
      enhance: false,
      x: 1007
    };
  },
  methods: {
    onMousemove(e) {
      this.x = e.clientX
    }

  },
}
</script>

<style>
* {
  font-family: 'Comfortaa', cursive;
}
.movearea {
  transition: 0.3s background-color ease;
}

#learn:hover {
 transition: all .5s ease-in-out;
 transform: translateY(-5px);
}
#learn:active {
transition: all .1s ease-in-out;
 transform: translateY(5px);
 opacity: 0.5;
}
com
h1 {
  font-family: 'Comfortaa', cursive;
}
.com {
 font-family: 'Comfortaa', cursive;
}
#j {
  color: rgb(255, 255, 255);
  font-family: 'Great Vibes', cursive;
}
.parker {
  color: rgb(255, 255, 255);
  font-family: 'Great Vibes', cursive;
}
.vibes {
  font-family: 'Great Vibes', cursive;
}
</style>
