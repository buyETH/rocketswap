<script lang="ts">
</script>

<div class="container">
  <div class="amount">
    <div class="label">From</div>
    <div class="amount-value">5.5132</div>
  </div>
  <div class="token-info">
    <div class="label">Balance: 50001</div>
    <div class="token-controls">
      <div class="max-button-cont"><button class="max-button">MAX</button></div>
      <div class="token-button-cont"><button class="token-select-button">TAU <img class="drop-down-arrow" src="assets/images/chevron-arrow-down.png" height="14" width="14" alt="" /></button></div>
    </div>
  </div>
</div>

<style>
.max-button-cont {

}

  .token-select-button { 
    color: #141414;
    font-size: 1.25rem;
  }

  .max-button {
    background-color: #a644ff8f;
    color: #690cfb;
    font-size: 1rem;
    height: 1.5rem;
    width: 2.8rem;
    border-radius: .485rem;
  }

  .container {
    width: 85%;
    padding: 10px;
    border-radius: 1.35rem;
    border: 1px solid #d7dbf0;
    display: flex;
    height: 4rem;
    justify-content: space-between;
    margin: 0 auto;
  }

  .amount {
    padding: 5px 0px 0px 15px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .token-info {
    padding: 5px 15px 0px 0px;
    display: flex;
    flex-direction: column;
    text-align: right;
  }

  .token-controls {
    margin-top: 1.3rem;
    display: flex;
    justify-content: space-around;
    align-items: center;
  }

  .label {
    color: #565969;
    font-size: .85rem;
  }

  .amount-value {
    font-size: 1.25rem;
    color: #141414;
  }

  .token-button-cont {
    margin-left: .65rem;
  }
  .drop-down-arrow {
    margin-left: .5rem;
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
