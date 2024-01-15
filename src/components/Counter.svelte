<script>
    let count = $state({ 
      value: 0,
      note: "single digits",
    });
  
    // setInterval(() => {
    //   count.value++;
    //   if (count.value > 9) {
    //   count.note = "not single digits";
    // }
    // }, 1000);

    const incrementCount = () => {
    count.value++;
    if (count.value > 9) {
      count.note = "not single digits";
    }
  };
  </script>
  <button on:click={incrementCount}>Increment</button>
  <p>Count: {count.value} ({count.note})</p>
