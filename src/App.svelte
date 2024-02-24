<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '../src/assets/svgviewer.svg'
  import Counter from './lib/nav.svelte'
  import Btns from './lib/btns.svelte';
  import Maind from './lib/maind.svelte';
  import k from "/home/rocky/svelte-template/s1/hustlers_1977_Round1_easy/src/assets/k.jpeg"
  import l from "/home/rocky/svelte-template/s1/hustlers_1977_Round1_easy/src/assets/l.jpeg"
  
</script>

<svelte:head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css">
</svelte:head>

<main>
  <div>
    
    <Counter />
    
    <div class="box"></div>
    <Btns />
    <Maind key={"Live from the club"} />
    <Maind />
    <img src={k} alt="">
    <Maind />
    <Maind />
    <img src={k} alt="">
    <Maind/>
    <Maind />
    <img style="width:100%" src={l} >
  </div>



</main>

<style>

  .box{
    width: 100%;
    height: 25rem;
    background-color: rgb(0, 0, 0);
  }

  main{
    background-color: black;
    height: 100%;
  }
  .logo {
    height: 6em;

    will-change: filter;
    transition: filter 300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  
</style>
