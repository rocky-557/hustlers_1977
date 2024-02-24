<script>

import M from "./m.svelte";
import { writable } from 'svelte/store';
export let key=""
export let auth = [["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"]]
</script>

<p>{key}</p>
<div>
    
   
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

p{  margin: 12px;
    font-size: 1.5rem;
    text-align: left;

    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    font-weight: bold;
}
</style>