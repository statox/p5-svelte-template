<script lang="ts">
    import { base } from '$app/paths';
</script>

<header>
    <h1>P5+Svelte template</h1>

    <nav>
        <a href="{base}/">Home</a> |
    </nav>
</header>

<slot />

<style>
    :global(.svelte-tabs li.svelte-tabs__tab) {
        background-color: #bfbec6;
        margin-right: 4px;
    }
</style>
