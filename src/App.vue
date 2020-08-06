<template>
  <div id="app">
    <div class="min-h-screen">
      <Navbar />
      <!--  Main page content   -->
      <main class="font-mono">
        <div class="p-24">
          <h1 class="text-center text-5xl">Who I am ?</h1>
          <p class="text-center inline-block pb-5">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
            enimad
          </p>
          <div
            class="sm:flex flex-col justify-center md:flex-row md:mx-2 w-full"
          >
            <button
              class="sm:flex flex-col justify-center font-bold py-2 px-4 bg-limen"
            >
              Read More
            </button>
          </div>
        </div>
        <div class="bg-limen">
          <div class="container mx-auto">
            <div class="text-center text-5xl  mt-10 p-10">
              <h2 class="">Recent Posts</h2>
            </div>
            <div
              class="flex content-between pb-6 flex-wrap pb-20  sm:flex-row sm:-mx-2"
            >
              <ArticleCard />
              <ArticleCard />
              <ArticleCard />
              <ArticleCard />
              <ArticleCard />
              <ArticleCard />
            </div>
          </div>
        </div>
        <Form />
      </main>
      <footer class="bg-coral py-10 italic pb-8 tracking-wider text-center">
        <p>Copyright &copy; 2020 Made by SamuelALSN</p>
      </footer>
    </div>
  </div>
</template>

<style src="./assets/tailwind.css"></style>
<script>
import Navbar from '@/components/Navbar'
import ArticleCard from '@/components/ArticleCard'
import Form from '@/components/Form'
export default {
  components: {
    Form,
    Navbar,
    ArticleCard
  }
}
</script>
