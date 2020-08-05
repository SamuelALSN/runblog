<template>
  <div id="app">
    <div class="min-h-screen">
      <nav
        class="bg-salmon sm:flex sm:justify-between sm:items-center sm:px-4 sm:py-3"
      >
        <div class="flex items-center justify-between px-4 py-3 sm:p-0">
          <div>
            <img src="./assets/runblog-logo.png" alt="" />
          </div>
          <div class="sm:hidden">
            <button @click="isOpen = !isOpen" type="button">
              <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
                <path
                  v-if="isOpen"
                  fill-rule="evenodd"
                  d="M18.278 16.864a1 1 0 0 1-1.414 1.414l-4.829-4.828-4.828 4.828a1 1 0 0 1-1.414-1.414l4.828-4.829-4.828-4.828a1 1 0 0 1 1.414-1.414l4.829 4.828 4.828-4.828a1 1 0 1 1 1.414 1.414l-4.828 4.829 4.828 4.828z"
                />
                <path
                  v-if="!isOpen"
                  fill-rule="evenodd"
                  d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                />
              </svg>
            </button>
          </div>
        </div>
        <div
          :class="isOpen ? 'block' : 'hidden'"
          class="px-4 pt-2 pb-4 sm:flex sm:p-0"
        >
          <a href="#" class="block px-2 py-1">Home </a>
          <a href="#" class="mt-1 block px-2 py-1 sm:mt-0 sm:ml-2">Courses</a>
          <a href="#" class="mt-1 block px-2 py-1 sm:mt-0 sm:ml-2"> A propos </a>
          <a href="#" class="mt-1 block px-2 py-1 sm:mt-0 sm:ml-2">Contact </a>
        </div>
      </nav>
      <!--  Main page content   -->
      <main class="container mx-auto font-mono">
        <div class="p-24">
          <h1 class="text-center text-2xl uppercase">Who I am ?</h1>
          <p class="text-center inline-block">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad
          </p>
          <button
            class="bg-blue-500 :hover:bg-blue-600 text-white font-bold py-2 px-4"
          >
            Read More
          </button>
        </div>
        <div class="flex content-start flex-wrap  sm:flex-row sm:-mx-2">
          <article class="max-w-sm mx-auto  p-6 bg-white rounded-lg shadow-xl">
            <img
              class="rounded-lg"
              src="https://images.unsplash.com/photo-1593642533144-3d62aa4783ec?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
              alt=""
            />

            <div class="">
              <h2 class="m-4 font-bold underline uppercase">
                5 reasons to learn Vue.js
              </h2>
              <p class="text-xs text-center m-5 p-5 tracking-wider">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              </p>
            </div>
          </article>
          <article class="max-w-sm mx-auto p-6 bg-white rounded-lg shadow-xl">
            <img
              class="rounded-lg"
              src="https://images.unsplash.com/photo-1593642533144-3d62aa4783ec?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
              alt=""
            />
            <div class="">
              <h2 class="m-4 font-bold underline uppercase">
                5 reasons to learn Vue.js
              </h2>
              <p class="text-xs text-center m-5 p-5 tracking-wider">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              </p>
            </div>
          </article>
          <article class="max-w-sm mx-auto p-6 bg-white rounded-lg shadow-xl">
            <img
              class="rounded-lg"
              src="https://images.unsplash.com/photo-1593642533144-3d62aa4783ec?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
              alt=""
            />
            <div class="">
              <h2 class="m-4 font-bold underline uppercase">
                5 reasons to learn Vue.js
              </h2>
              <p class="text-xs text-center m-5 p-5 tracking-wider">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              </p>
            </div>
          </article>
          <article class="max-w-sm mx-auto p-6 bg-white rounded-lg shadow-xl">
            <img
              class="rounded-lg"
              src="https://images.unsplash.com/photo-1593642533144-3d62aa4783ec?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
              alt=""
            />
            <div class="">
              <h2 class="m-4 font-bold underline uppercase">
                5 reasons to learn Vue.js
              </h2>
              <p class="text-xs text-center m-5 p-5 tracking-wider">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              </p>
            </div>
          </article>
          <article class="max-w-sm mx-auto  p-6 bg-white rounded-lg shadow-xl">
            <img
              class="rounded-lg"
              src="https://images.unsplash.com/photo-1593642533144-3d62aa4783ec?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
              alt=""
            />
            <div class="">
              <h2 class="m-4 font-bold underline uppercase">
                5 reasons to learn Vue.js
              </h2>
              <p class="text-xs text-center m-5 p-5 tracking-wider">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              </p>
            </div>
          </article>
          <article class="max-w-sm mx-auto p-6 bg-white rounded-lg shadow-xl">
            <img
              class="rounded-lg"
              src="https://images.unsplash.com/photo-1593642533144-3d62aa4783ec?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
              alt=""
            />
            <div class="">
              <h2 class="m-4 font-bold underline uppercase">
                5 reasons to learn Vue.js
              </h2>
              <p class="text-xs text-center m-5 p-5 tracking-wider">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              </p>
            </div>
          </article>
        </div>
        <div class="mt-12 py-12 w-full flex flex-col items-center">
          <h2>Subscribe to my Newsletter</h2>
          <form class="max-w-xl w-full mt-4 px-8 md:px-0">
            <div class="flex flex-col md:flex-row md:mx-2">
              <input class="mt-4 md:mx-2 border border-black rounded-lg" type="text" placeholder="Name" />
              <input class="mt-4 md:mx-2 border border-black rounded-lg" type="text" placeholder="Last Name" />
            </div>
             <div class="flex flex-col md:flex-row md:mx-2">
               <input class="mt-4 md:mx-2 border border-black rounded-lg" type="text" placeholder="lorem@gmail.com" />
               <input class="mt-4 md:mx-2 border border-black rounded-lg" type="text" placeholder="Title ">
             </div>
            <div class="flex flex-col md:flex-row md:mx-2 w-full">
              <button class="mt-4 md:mx-2 rounded-lg py-2 px-4 block" type="submit"> Subscribe </button>
            </div>

          </form>
        </div>
      </main>
      <footer class="italic pb-8 tracking-wider text-center">
        <p>Copyright &copy; 2020 Made by SamuelALSN</p>
      </footer>
    </div>
  </div>
</template>

<style src="./assets/tailwind.css"></style>
<script>
export default {
  data() {
    return {
      isOpen: false
    }
  }
}
</script>
