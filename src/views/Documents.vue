<template>
  <div>
    <Header />
    <main class="main">
      <Documents />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Documents from "@/components/Documents";
export default {
  name: 'app',
  components: {
    Documents,
    Footer,
    Header
  }
}
</script>