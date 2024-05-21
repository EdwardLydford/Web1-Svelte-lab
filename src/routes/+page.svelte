<!--importing card from components below -->
<script>  
import Card from "../components/Card.svelte";
    import Footer from "../components/Footer.svelte";
import Header from "../components/Header.svelte";
    import Sidebar from "../components/Sidebar.svelte";
    
    
    let navItems = [
      {text:"Classes", href: "/Classes"},
      {text:"TimeTable", href: "/Schedule"},
      {text:"Pricing", href: "/Prices"},
      {text:"Our Story", href: "/Our Story"},
    ]


</script>
    


<div class = "container">
<header><Header/></header>
</div>
<div class = "left-side"> 
<Sidebar navItems = {navItems} />
</div> 
   <main>
    <Card /> 
    <Card />
   </main>

   <footer><Footer/></footer>


<!-- more side bar and footer in here-->
<style>
    main{
        display:flex;
       flex-wrap: wrap;
        border: 1px solid violet;
        padding: 1em;
        gap: 1em;
        
    }
    .container{
        display: grid;
        grid-template: auto 1fr auto /auto 1fr;
    }
    header{
        padding: 0.25em;
        grid-column: 1 / 3;
    }
    
    footer{
        grid-column: 1 / 3;
    }
    .left-side{
        grid-column: 1 /2 ;
    }
</style>
