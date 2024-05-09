<!--importing card from components below -->
<script>  
import Card from "../components/Card.svelte";
import Header from "../components/Header.svelte";


</script>

<header>
    <Header/>
</header>

<section>
   
<!-- this is adding the cards-->
<Card /> 
<Card />
</section>

<style>
    section{
        display: flex;
    }
</style>