<style>
  div {
    height: 50px;
    width: 80px;
    padding: 0 8px;
    text-align:center;
    line-height: 45px;
    background-color: #4e5656;
    border-radius: 5px;
    box-shadow: 0 0 5px #4e5656;
  }

  span {
    font-size: 14px;
    color: white;
  }
</style>

<script>
  export let message = '';
</script>

{#if message}
  <div style="background-color: green; box-shadow: 0 0 5px green;">
    <span>Correcto</span>
  </div>
{:else}
  <div style="background-color: red; box-shadow: 0 0 5px red;">
    <span>Incorrecto</span>
  </div>
{/if}
