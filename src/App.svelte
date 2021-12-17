<script lang="ts">
  import * as THREE from 'three';
	import * as SC from 'svelte-cubed'
</script>

<main>
  <SC.Canvas>
    <SC.Mesh geometry={new THREE.BoxGeometry()} />
    <SC.PerspectiveCamera position={[3, 1, 3]} />
  </SC.Canvas>

</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }


</style>
