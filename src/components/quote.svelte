<script>
</script>

<div class="container">
  <div class="label">Price</div>
  <div class="quote-container">
    <div class="quote-text">5.5132 XMG per TAU</div>
    <button class="switch"> 
        <svg xmlns="http://www.w3.org/2000/svg" width="14" height="14" 
      viewBox="0 0 24 24" fill="none" stroke="#7a7f91" stroke-width="2" 
      stroke-linecap="round" stroke-linejoin="round"><polyline points="17 1 21 5 17 9">
      </polyline><path d="M3 11V9a4 4 0 0 1 4-4h14"></path><polyline points="7 23 3 19 7 15">
      </polyline><path d="M21 13v2a4 4 0 0 1-4 4H3"></path></svg>
    </button>
  </div>
</div>

<style>
  .container {
    color: #7a7f91;
    font-weight: semibold;
    display: flex;
    justify-content: space-between;
    align-content: center;
    
    margin-top: .5rem;
    margin-left: 1.65rem;
  }

  .quote-container {
    display: flex;
    align-content: center;
    line-height: 30px;
  }

  .quote-text {
    margin-right: 10px;
  }

  .quote-container button {
      height: 20px;
  }

  .label {
    line-height: 30px;
  }

  .switch {
    height: 22px;
    width: 22px;
    background-color: rgb(247, 248, 250);
    border: none;
    border-radius: 50%;
    margin-top: auto;
    margin-right: 1rem;
    cursor: pointer;
    display: flex;
    -webkit-box-pack: center;
    justify-content: center;
    -webkit-box-align: center;
    align-items: center;
    float: right;
  }

  button {
    background: none;
    color: inherit;
    border: none;
    padding: 0;
    font: inherit;
    cursor: pointer;
    outline: inherit;
  }
</style>
