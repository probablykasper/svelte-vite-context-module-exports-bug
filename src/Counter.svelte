<script lang="ts" context="module">
  import { writable } from 'svelte/store'

  let text = writable('')

  export const visible = writable(false)
</script>

<h3>Update me</h3>
<p>Visible: {$visible}</p>
