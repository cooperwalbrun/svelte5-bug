<script lang=ts">
  import example from './example.svelte';

  // If you change "component" to "Component" on the line below, it works
  const component = $state(example);
</script>

<!-- If you change "component" to "Component" on the line below, it works -->
<component />
