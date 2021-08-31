<template>
  <div>
    <Header />
    <main class="main">
      <Signed />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Signed from "@/components/Signed";
export default {
  name: 'app',
  components: {
    Signed,
    Footer,
    Header
  }
}
</script>