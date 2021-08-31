<template>
  <div>
    <Header />
    <main class="main">
    </main>
    <OfferOne />
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import OfferOne from "@/components/OfferOne";
export default {
  name: 'app',
  components: {
    OfferOne,
    Footer,
    Header
  }
}
</script>