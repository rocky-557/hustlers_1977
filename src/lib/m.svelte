<script>
    import au from '/home/rocky/svelte-template/s1/hustlers_1977_Round1_easy/src/assets/au.png'
    export let authr=""
    export let song="" 
</script>


<div class="sqr">
    <img src= {au} alt="">
    <h1 class="auth">{authr}</h1>
    <h2 class="song">{song}</h2>
</div>


<style>

@keyframes keyp{


    0%{
        transform:scale(1.0);
    }
    100%{
        transform: scale(1.15);
    }
}


.sqr{
    width:20rem;
    position: relative;
    display: flex;
    flex-direction: column;
    
    height: 20rem;
    background-color: white;
    border-radius: 6rem;

    margin: 1.5rem;
    will-change: filter;
    transition: filter 300ms;
}

.sqr:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
    animation-name: keyp  ;
    animation-duration: 1s;
  }

.sqr::-webkit-scrollbar{
    display: none;
}

.auth , .song{
    position: absolute;
    bottom: 2rem;
    text-align:left;
}

.song{
    bottom:4px;
    font-size: medium;
}
.auth{
    font-size: larger;
    font-weight: bolder;
}



</style>