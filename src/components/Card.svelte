
<!-- SCRIPT-->
<script>

import Picture from "./Picture.svelte";
import Details from "./Details.svelte";
export let person;
</script>


<!-- html-->
<section>
<Picture {person}/>
<Details {person}/>

    
</section>


<!-- style for card-->
<style>
    section{
        display: flex;
        border: 1px solid rgb(0, 0, 0) ;
        padding: 1em;
    }

</style>