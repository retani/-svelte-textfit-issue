<script>
  import { textfit } from 'svelte-textfit';
  let parent;
</script>
<div bind:this={parent}>
  <h1 use:textfit={{parent,mode:"single"}}>
    Fat headline!
  </h1>
</div>
