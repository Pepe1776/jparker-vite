<template>
  <nav
    class="top-0 absolute z-50 w-full flex flex-wrap items-center justify-between  navbar-expand-lg"
  >
    <div
      class="container px-4 mx-auto flex flex-wrap items-center justify-between"
    >
      <div
        class="w-full relative flex justify-between lg:w-auto lg:static lg:block lg:justify-start"
      >
        <a id="learn"
          class="nter hover:text-cyan-200 text-lg font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white"
          href="/index.html"
          >NterFace</a
        ><button
          class="cursor-pointer text-xl leading-none px-3 py-1 border border-solid border-transparent rounded bg-transparent block outline-none focus:outline-none"
          type="button"
          onclick="toggleNavbar('example-collapse-navbar')"
        >
          <span class="text-cyan-500 lg:hidden">=</span>
        </button>
      </div>
      <div
        class="lg:flex flex-grow items-center bg-white lg:bg-transparent lg:shadow-none hidden"
        id="example-collapse-navbar"
      >
        <ul class="flex flex-col lg:flex-row list-none lg:ml-auto">
          <!-- Icon 1 -->
          <li class="flex items-center">
            <a
              id="learn"
          class="nter hover:text-cyan-200 text-lg font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white"
              href="https://www.instagram.com/j_not_query"
              ><span class="hover:text-cyan-200 inline-block ml-2">Instagram</span></a
            >
          </li>
          <!-- Icon 2 -->
          <li class="flex items-center">
            <a
                id="learn"
          class="nter hover:text-cyan-200 text-lg font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white"
              href="https://www.github.com/pepe1776"
              >
              <span class="lato hover:text-cyan-200 inline-block ml-2">GitHub</span></a
            >
          </li>
          <!-- Icon 3 -->
          <li class="flex items-center">
            <a
               id="learn"
          class="nter hover:text-cyan-200 text-lg font-bold leading-relaxed inline-block mr-4 py-2 whitespace-no-wrap uppercase text-white"
              href="mailto:justinp@aevio.com"
              ><span class="hover:text-cyan-200 inline-block ml-2">Email</span></a
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style>
</style>