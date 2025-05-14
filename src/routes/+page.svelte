<script>
    import About from "../content/About.svelte";
    import Footer from "../content/Footer.svelte";
    import Navbar from "../content/Navbar.svelte";
    import Project from "../content/Project.svelte";
</script>

<div>
    <Navbar />
    <About />
    <Project />
    <Footer />
</div>

<style lang="postcss">
    @reference "tailwindcss";
    :global(html) {
        background-color: theme(--color-neutral-900);
    }
</style>
