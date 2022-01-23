<script>
  import { onDestroy, onMount, beforeUpdate, afterUpdate } from "svelte";

  beforeUpdate(() => {
    console.log("before update");
  });

  afterUpdate(() => {
    console.log("after update");
  });

  onMount(() => {
    console.log("Mounted");
  });

  onDestroy(() => {
    console.log("Before destroy");
  });
</script>

<h1>Something</h1>
