<template>
  <div>
    <Header />
    <main class="main">
      <Interest />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Interest from "@/components/Interest";
export default {
  name: 'app',
  components: {
    Interest,
    Footer,
    Header
  }
}
</script>