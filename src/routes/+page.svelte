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



<!-- more side bar and footer in here-->
<style>
    
    section{
        display: flex;
    }
</style>
