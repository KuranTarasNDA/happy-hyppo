<template>
  <div>
    <Header />
    <main class="main">
      <Request />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Request from "@/components/Request";
export default {
  name: 'app',
  components: {
    Request,
    Footer,
    Header
  }
}
</script>