<script>
  import Container from "./container.svelte"
</script>

<h1 class="h-4 w-3">Welcome to SvelteKit</h1>
<Container>
  <p
    slot="test"
    let:class={className}
    class="h-full w-full p-2 backdrop-blur-0 {className}"
  >
    Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation
  </p>
</Container>
