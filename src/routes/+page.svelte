<script>
    import { goto } from '$app/navigation';
    import { onMount } from 'svelte';


    onMount(()=>{
        goto('/start');
    })


</script>



<style lang="postcss">
    :global(html) {
        background-color: theme('colors.gray.100');
    }
</style>
