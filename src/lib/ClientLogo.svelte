<script lang="ts">
    export let organization: string;
    export let logo: string;
    export let url: string;
</script>

<a href="{url}" class="hover:opacity-70">
    <img
        src={logo}
        alt={organization}
        class="h-9 sm:h-10 md:h-11 md:w-fit mt-1.5 sm:mt-2 md:mt-2.5"
    />
</a>
