<template>
  <div>
    <Header />
    <main class="main">
      <Review />
      <Fixed />
      <Indentity />
      <Confirm />
    </main>
    <Footer />
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from "@/components/Footer";
import Review from "@/components/Review";
import Fixed from "@/components/Fixed";
import Indentity from "@/components/Identity";
import Confirm from "@/components/Confirm";
export default {
  name: 'app',
  components: {
    Confirm,
    Indentity,
    Fixed,
    Review,
    Footer,
    Header
  }
}
</script>