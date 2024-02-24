<script>
    export let authr=""
    export let song="" 
</script>


<div class="sqr">

    <p class="auth">{authr}</p>
    <h2 class="song">{song}</h2>
</div>


<style>

.sqr{
    width:20rem;
    display: flex;
    flex-direction: column;
    height: 20rem;
    background-color: white;
    border-radius: 1rem;
    padding: 1rem;
    margin: 1.5rem;
}

.sqr::-webkit-scrollbar{
    display: none;
}

.auth , .song{

    text-align:left;
}

</style>