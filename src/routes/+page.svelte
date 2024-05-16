<!--importing card from components below -->
<script>  
import Card from "../components/Card.svelte";
    import Footer from "../components/Footer.svelte";
import Header from "../components/Header.svelte";
    import Sidebar from "../components/Sidebar.svelte";
    
    
    let navItems = [
      {text:"Classes", href: "/Classes"},
      {text:"TimeTable", href: "/Shedule"},
      {text:"Pricing", href: "/Prices"},
      {text:"Our Story", href: "/Our Story"},
    ]


</script>

    <Header/>
    <Sidebar navItems = {navItems} />

   <main>
    <Card /> 
    <Card />
   </main>


<Footer/>

<!-- more side bar and footer in here-->
<style>
    main{
        display:flex;
        border: 1px solid violet;
        padding: 1em;
        gap: 1em;
        
    }
</style>
