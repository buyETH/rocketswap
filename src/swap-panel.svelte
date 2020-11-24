<script lang="ts">
  
  import Input from './input.svelte'
  import Quote from './quote.svelte'
  import SwapButtons from './swap-buttons.svelte'

</script>

<div class="container">
  <Input />
  <div class="switch-symbols-cont"><button><img class="down-arrow"src="/assets/images/down-arrow.png" alt="" /> </button></div>
  <Input />
  <Quote />
  <SwapButtons />
</div>

<style>
  .down-arrow {
    width: 1rem;
  }

  .switch-symbols-cont {
    margin: 0 auto;
    margin-top: 10px;
    width: 100%;
    text-align: center;
  }

  .container {
    background-color: white;
    /* height: 556px; */
    width: 26rem;
    height: 20rem;
    border-radius: 1.75rem;
    box-shadow: -1px 10px 82px 0px rgba(0, 0, 0, 0.19);
    -webkit-box-shadow: -1px 10px 82px 0px rgba(0, 0, 0, 0.19);
    -moz-box-shadow: -1px 10px 82px 0px rgba(0, 0, 0, 0.19);
    padding-top: 1rem;
    /* display: flex; */
    /* flex-direction: column;
    align-content: center; */
  }

  button,
  input[type='submit'],
  input[type='reset'] {
    background: none;
    color: inherit;
    border: none;
    padding: 0;
    font: inherit;
    cursor: pointer;
    outline: inherit;
  }
</style>
