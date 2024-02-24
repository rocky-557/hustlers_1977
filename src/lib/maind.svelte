<script>

import M from "./m.svelte";
import { writable } from 'svelte/store';

export let auth = [["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"],["Auther Name","Song Name"]]
</script>


<div>
    <p>Welcome</p>
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
</style>