<template>
  <div>
    <Header />
    <main class="main">
      <VideoTwo />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import VideoTwo from "@/components/VideoTwo";
export default {
  name: 'app',
  components: {
    VideoTwo,
    Footer,
    Header
  }
}
</script>