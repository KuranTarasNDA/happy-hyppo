<template>
  <div>
    <Header />
    <main class="main">
    </main>
    <OfferTwo />
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import OfferTwo from "@/components/OfferTwo";
export default {
  name: 'app',
  components: {
    OfferTwo,
    Footer,
    Header
  }
}
</script>