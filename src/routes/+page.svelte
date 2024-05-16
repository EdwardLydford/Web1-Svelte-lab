<!--importing card from components below -->
<script>  
import Card from "../components/Card.svelte";
    import Footer from "../components/Footer.svelte";
import Header from "../components/Header.svelte";
    import Sidebar from "../components/Sidebar.svelte";
    


</script>

<header>
    <Header/>
</header>

<section>
   
<!-- this is adding the cards-->
<Card /> 
<Card />
</section>
<Sidebar/>
<Footer/>

<!-- more side bar and footer in here-->
<style>
    
    section{
        display:flex;
        
    }
</style>
