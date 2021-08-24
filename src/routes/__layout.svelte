<script>
    import { onDestroy } from 'svelte'

    onDestroy(() => {
        console.log('!!!Destroyed')
    })
</script>

<slot />