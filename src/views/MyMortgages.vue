<template>
  <div>
    <Header />
    <main class="main">
      <my-mortgages />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import MyMortgages from "@/components/MyMortgages";
export default {
  name: 'app',
  components: {
    MyMortgages,
    Footer,
    Header
  }
}
</script>