<template>
  <div>
    <Header />
    <main class="main">
      <Video />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Video from "@/components/Video";
export default {
  name: 'app',
  components: {
    Video,
    Footer,
    Header
  }
}
</script>