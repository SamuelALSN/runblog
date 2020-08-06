<template>
  <div class="mt-12 py-12 w-full flex flex-col items-center">
    <h2 class="text-4xl">Subscribe to my Newsletter</h2>
    <form class="bg-white max-w-xl w-full mt-4 px-8 md:px-0">
      <div class="flex flex-col md:flex-row md:mx-2">
        <input
          class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight mt-6 md:mx-2"
          type="text"
          placeholder="Name"
        />
        <input
          class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight mt-6 md:mx-2"
          type="text"
          placeholder="Last Name"
        />
      </div>
      <div class="flex flex-col md:flex-row md:mx-2">
        <input
          class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight mt-6 md:mx-2"
          type="text"
          placeholder="lorem@gmail.com"
        />
        <input
          class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight mt-6 md:mx-2"
          type="text"
          placeholder="Title "
        />
      </div>
      <div class="sm:flex flex-col justify-center md:flex-row md:mx-2 w-full">
        <button
          class="mt-4 md:mx-2 rounded-lg py-2 px-4 block bg-coral text-white"
          type="submit"
        >
          Subscribe
        </button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: 'Form'
}
</script>

<style scoped></style>
