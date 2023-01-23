<!-- 

  Importing the global status here enables utilization of HMR (Hot Module Replacement)[Hot reload].
  This can also be done at the index.html file too.
 -->
<script lang="ts">
  import '$root/styles/global.css'
  import Todos from './components/Todos.svelte';
</script>

<Todos/>