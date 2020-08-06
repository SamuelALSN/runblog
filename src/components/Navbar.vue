<template>
  <nav
    class="bg-coral sm:flex sm:justify-between sm:items-center sm:px-4 sm:py-3"
  >
    <div class="flex items-center justify-between px-4 py-3 sm:p-0">
      <div>
        <img src="@/assets/runblog-logo.png" alt="" />
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
      <a href="#" class="block px-2 py-1 text-white font-semibold rounded "
        >Home
      </a>
      <a
        href="#"
        class="mt-1 block px-2 py-1 sm:mt-0 sm:ml-2 text-white font-semibold rounded "
        >Courses</a
      >
      <a
        href="#"
        class="mt-1 block px-2 py-1 sm:mt-0 sm:ml-2 text-white font-semibold rounded "
        >About me
      </a>
      <a
        href="#"
        class="mt-1 block px-2 py-1 sm:mt-0 sm:ml-2 text-white font-semibold rounded"
        >Contact
      </a>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
  data() {
    return {
      isOpen: false
    }
  }
}
</script>

<style scoped></style>
