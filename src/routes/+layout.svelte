<script>
  import "../app.css";
  import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import Navigation from "../components/Navigation.svelte";
</script>

<html class="font-quicksand" lang="en">
<Header/>

<body class="flex flex-col min-h-screen">
<Navigation/>

<main class="flex-grow container mx-auto px-3 max-w-7xl">
    <slot/>
</main>

<Footer/>
</body>
</html>
