<script>
	import Competence from "$lib/Competence.svelte";
	import ContactMe from "$lib/ContactMe.svelte";
	import Hero from "$lib/Hero.svelte";
	import PastClients from "$lib/PastClients.svelte";
</script>

<style lang="postcss">
    :global(html) {
      background-color: theme(colors.stone.200);
    }
</style>

<main class="bg-stone-50 p-4 pb-24">
    <div class="max-w-prose mx-auto sm:mt-10 md:mt-20 flex flex-col gap-8 md:gap-10">
        <Hero />
        <ContactMe />
        <PastClients />   
    </div>
    <!-- <Quotes /> -->
    <!-- <Competence />  -->
    <!-- <NotCheapest /> --> 
</main>
<footer class="px-4 py-12">
    <section class="max-w-prose mx-auto">

        <p class="opacity-80">
            Full CV og personlig nettside på <a href="https://danieljackson.no">danieljackson.no</a>
        </p>
    
    </section>
</footer>


