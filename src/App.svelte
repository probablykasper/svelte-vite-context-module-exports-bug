<script lang="ts">
  import Counter, { visible } from './Counter.svelte'
</script>

<main>
  <Counter />
  <button on:click={() => visible.set(true)}>Show</button>
  <button on:click={() => visible.set(false)}>Hide</button>
</main>
