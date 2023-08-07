<script>
  import "../app.css";
  import Footer from "../components/Footer.svelte";
  import Header from "../components/Header.svelte";
  import Navigation from "../components/Navigation.svelte";
</script>

<html lang="en" class="font-quicksand">
  <Header />

  <body class="flex flex-col min-h-screen">
    <Navigation />

    <main class="flex-grow container-mx-auto px-3">
      <slot />
    </main>

    <Footer />
  </body>
</html>
