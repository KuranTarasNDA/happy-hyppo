<template>
  <div>
    <Header />
    <main class="main">
      <Verification />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Verification from "@/components/Verification";
export default {
  name: 'app',
  components: {
    Verification,
    Footer,
    Header
  }
}
</script>