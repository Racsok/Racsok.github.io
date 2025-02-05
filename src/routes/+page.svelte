<script lang="js">
    import Header from '$lib/componentes/header.svelte'
    import Footer from '$lib/componentes/footer.svelte';

    // MAIN
    import SobreMi from '$lib/componentes/main/sobre_mi.svelte';
    import Habilidades from '$lib/componentes/main/habilidades.svelte';
    import Proyectos from '$lib/componentes/main/proyectos.svelte';
</script>

<Header />

<main id="principal" class="container mx-auto p-6 bg-violet-100">

    <SobreMi />
    <Habilidades />
    <Proyectos />

    
</main>

<Footer />

