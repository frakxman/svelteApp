<!-- TimeLine.js -->
<script>
    import Card from './Card.svelte';

    export let posts = [];
</script>

<!-- TimeLine.css -->
<style>
    .TimeLine {
      padding: 4em 0 0 0;
    }
</style>

<!-- TimeLine.html -->
<div class="TimeLine">
    { #each posts as post }
        <Card { ...post } />
    { :else }
        <p>Loading...</p>
    {/each}
</div>