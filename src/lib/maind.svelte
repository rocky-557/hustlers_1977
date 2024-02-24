<script>

import M from "./m.svelte";
import { writable } from 'svelte/store';
export let key=""
export let auth = [["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"]]
</script>


<div>
    <p>{key}</p>
    {#each auth as au}
        <M authr={au[0]} song={au[1]}/>
    {/each} 





</div>

<style>
div{
    margin-top: 1.5rem;
    margin-bottom: 1.5 rem;
    display:flex;
    overflow-x: scroll ;
}

div::-webkit-scrollbar{
    display: none;
}

p{
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bold;
}
</style>