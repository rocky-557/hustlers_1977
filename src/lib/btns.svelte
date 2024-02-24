<script>
import log from '/home/rocky/svelte-template/s1/hustlers_1977_Round1_easy/src/assets/logo.jpeg'

</script>

<div class="btns">
<div class="btn">
    <img src={log}> Rinse UK</div>
<div class="btn"><img src={log}> Rinse France</div>
<div class="btn"><img src={log}> Kool FM</div>
<div class="btn"><img src={log}> SWFU FM</div>


</div>

<style>
.btns{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    gap: 1.5rem;
    background-color: white; 
}

.btn{
    margin: 1.5rem ;
    background-color: white;
    border-radius: 3rem;
color: black;
    padding: 1rem;
    text-align: center;
}

</style>