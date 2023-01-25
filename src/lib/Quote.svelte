<script lang="ts">
    export let name: string;
    export let title: string;
    export let avatar: string;
    export let organization: string;
    export let email: string;
    export let logo: string | undefined = undefined;
</script>

<blockquote class="flex flex-col gap-2 p-4">
    <div class="text-4xl">
        <slot>
        </slot>
    </div>
    <cite class="not-italic flex flex-row-reverse gap-4">
        <div class="flex-1 flex flex-col gap-0 ">
            <p class="leading-0">
                <strong>{name}</strong><br />
                <span>{title}{#if !logo }, { organization }{ /if}</span>    
            </p>
            <slot name="logo">
                {#if logo }
                    <img
                        src={logo}
                        alt={organization}
                        class="h-9 w-fit mt-1.5"
                    />
                {/if}
            </slot>
        </div>
        <img
            class="rounded-full w-16 h-16"
            src={avatar}
            alt={name}
        />

    </cite>
</blockquote>
