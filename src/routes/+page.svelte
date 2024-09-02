<script>
	import Product from './../components/Product.svelte';
  import Header from '../components/Header.svelte';
    import Hero from './../components/Hero.svelte';
  import Reviews from '../components/Reviews.svelte';
  import CtAs from '../components/CTAs.svelte';
  import FaQs from '../components/FAQs.svelte';
  import Footer from '../components/Footer.svelte';
  import Conversion from '../components/Conversion.svelte';
</script>

<main class="flex flex-col">
    <Header/>
    <Hero/>
    <Product/>
    <Reviews/>
    <FaQs/>
    <!-- <CtAs/> -->
    <Conversion/>
    <Footer/>
</main>