<script>
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment} class=" bg-blue-400 border">
  count is {count}
</button>
