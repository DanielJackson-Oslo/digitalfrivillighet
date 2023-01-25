<script lang="ts">
	import ClientLogo from "./ClientLogo.svelte";
</script>
<section>
    <h2 class="text-2xl md:text-3xl font-light italic mb-4">Fornøyde kunder</h2>

    <ul class="flex flex-col flex-wrap gap-4 md:gap-8 md:justify-between md:flex-row">
        <li>
            <ClientLogo
                organization="Frivillighet Norge"
                logo="images/fn-logo.svg"
                url="https://frivillighetnorge.no"
            />
        </li>
        <li>
            <ClientLogo
                organization="Frivillig.no"
                logo="images/frivillig-logo.svg"
                url="https://om.frivillig.no"
            />
        </li>
        <li>
            <ClientLogo
                organization="LNU"
                logo="images/lnu-logo.svg"
                url="https://lnu.no"
            />
        </li>
    </ul>

</section>