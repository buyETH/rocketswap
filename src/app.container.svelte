<script lang="ts">
  import Header from './components/header.svelte'
  import SwapPanel from './components/swap-panel.svelte'
  import Footer from './components/footer.svelte'
  import { WalletService } from './services/wallet.service'

  const walletService = WalletService.getInstance()
</script>

<main>
  <div class="bg-solid">
    <div class="bg-gradient flex">
      <Header />
      <SwapPanel />
      <Footer />
    </div>
  </div>
</main>

<svelte:head>
    <link href="https://fonts.googleapis.com/css2?family=PT+Sans:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@500&display=swap" rel="stylesheet">
</svelte:head>

<style>
  main {
    height: 100%;
    width: 100%;
  }

  .bg-gradient {
    position: absolute;
    height: 100%;
    width: 100%;
    background-image: radial-gradient(rgba(245, 235, 253, 0.801) , rgb(255, 255, 255));
  }

  .bg-solid {
    position: absolute;
    height: 100%;
    width: 100%;
    background-color: #1a127e;
  }

  .flex {
    display: flex;
    flex-direction: column;
    justify-items: space-between;
    justify-content: space-between;
    align-items: center;
  }
</style>
