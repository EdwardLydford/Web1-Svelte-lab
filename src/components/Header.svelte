<script>
    
    let navItems = [
   { text: "Home", href: "/" },
   { text: "blog", href: "/blog" },
   { text: "My profile", href: "/profile" },
   { text: "business Card Collection", href: "/carding" },
 ];
</script>

{#each navItems as item }
<a href={item.href}>{item.text}</a>
{/each}
  
<style>
    h1{
        color: hotpink;
        
    }
</style>