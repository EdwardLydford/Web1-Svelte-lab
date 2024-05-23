<script>
   
     import Sidebar from "../../components/Sidebar.svelte";
     
     
     let navItems = [
    { text: "Home", href: "/" },
    { text: "blog", href: "/blog" },
    { text: "My profile", href: "/profile" },
    { text: "business Card Collection", href: "/carding" },
]

</script>

<div class="container">


  <div class="left-side">
    <Sidebar {navItems} />
  </div>
  <main>
    <slot></slot>
  </main>


</div>
<section></section>

<style>

</style>
