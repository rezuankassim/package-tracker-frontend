<template>
  <div class="font-sans">
    <Nav />

    <header class="bg-white shadow">
      <div class="max-w-7xl mx-auto py-6 px-4 sm:px-6 lg:px-8">
        <h1 class="text-3xl font-bold leading-tight text-gray-900">
          Dashboard
        </h1>
      </div>
    </header>

    <main>
      <div class="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
        <!-- Replace with your content -->
        <div class="px-4 py-6 sm:px-0">
          <div class="rounded-lg h-96">
            <Nuxt />
          </div>
        </div>
        <!-- /End replace -->
      </div>
    </main>
  </div>
</template>

<script>
import Nav from './nav.vue'

export default {
  head () {
    return {
      bodyAttrs: {
        class: 'antialiased font-sans bg-gray-200'
      }
    }
  },
  components: {
    Nav
  }
}
</script>