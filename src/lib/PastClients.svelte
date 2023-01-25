<script lang="ts">
	import ClientLogo from "./ClientLogo.svelte";
</script>
<section>
    <h3 class="text-2xl font-light italic mb-4">Fornøyde kunder</h3>

    <ul class="flex flex-col flex-wrap gap-4 md:gap-8 md:justify-between md:flex-row">
        <li>
            <ClientLogo
                organization="Frivillighet Norge"
                logo="images/fn-logo.svg"
            />
        </li>
        <li>
            <ClientLogo
                organization="Frivillig.no"
                logo="images/frivillig-logo.svg"
            />
        </li>
        <li>
            <ClientLogo
                organization="LNU"
                logo="images/lnu-logo.svg"
            />
        </li>
    </ul>
</section>