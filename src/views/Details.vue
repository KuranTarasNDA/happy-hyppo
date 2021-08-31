<template>
  <div>
    <Header />
    <main class="main">
      <Details />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Details from "@/components/Details";
export default {
  name: 'app',
  components: {
    Details,
    Footer,
    Header
  }
}
</script>