<script>
  let count =0; 

  function incrementCount() {
    count +=1;
  }
  
  let count2 =0; 

  function incrementCount2() {
    count2 +=5;
  }
</script>

<!--minimum code while it's still working-->
<button on:click={incrementCount}>
  {count}
</button> <hr>

<!-- if you click more than 1 it shows clicked times(in plural)-->
<button on:click={incrementCount2}>
  Clicked {count2} {count2  === 1 ? 'time':'times'}
</button> <hr>
