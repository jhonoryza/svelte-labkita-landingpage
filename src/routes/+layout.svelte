<script>
    import Header from "../components/Header.svelte";
    import Navigation from "../components/Navigation.svelte";
</script>

<html lang="en">
    <Header />

    <body>
        <Navigation />

        <main>
            <slot />
        </main>
        <script src="https://code.jquery.com/jquery-2.1.3.min.js"></script>
        <script
            src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
            integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
            crossorigin="anonymous"
        ></script>
    </body>
</html>
