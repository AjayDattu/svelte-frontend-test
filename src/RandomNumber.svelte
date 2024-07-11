<script>
  let randomNumber = 0;

  function generateRandomNumber() {
    randomNumber = Math.floor(Math.random() * 100) + 1;
  }
</script>

<button on:click={generateRandomNumber}>Generate Random Number</button>
<p>Random Number: {randomNumber}</p>
