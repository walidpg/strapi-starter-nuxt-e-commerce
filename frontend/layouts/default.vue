<template>
<div class="flex justify-center bg-gray-200">
  <div class="max-w-screen-lg flex flex-col min-h-screen w-full">
    <NavBar />
    <Buttons />
    <Nuxt class="flex-grow" />
    <Footer />
  </div>
  <div hidden id="snipcart" data-api-key="YmJjMDgwZDEtN2E3Ny00Mzg1LTgwYTktODY5NjAyZTU2ZjEyNjM3NDk0ODE2NzA4Mzc3MjMx"></div>
</div>
</template>

<script>
import NavBar from './../components/Navbar'
import Footer from './../components/Footer'
import Buttons from './../components/Buttons'

export default {
  components: {
    NavBar,
    Footer,
    Buttons
  }
}
</script>
