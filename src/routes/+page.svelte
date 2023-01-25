<script>
	import Competence from "$lib/Competence.svelte";
	import ContactMe from "$lib/ContactMe.svelte";
	import Hero from "$lib/Hero.svelte";
	import PastClients from "$lib/PastClients.svelte";
</script>

<style lang="postcss">
    :global(html) {
      background-color: theme(colors.stone.50);
    }
</style>

<main class="max-w-prose mx-auto p-4 pb-12 sm:mt-10 md:mt-20 flex flex-col gap-8 md:gap-10">
    <Hero />
    <ContactMe />
    <PastClients />   
    <!-- <Quotes /> -->
    <!-- <Competence />  -->
    <!-- <NotCheapest /> --> 
</main>


