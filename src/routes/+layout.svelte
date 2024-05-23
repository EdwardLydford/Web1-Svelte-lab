<script>
     import Header from "../components/Header.svelte";
     import Sidebar from "../components/Sidebar.svelte";
     import Footer from "../components/Footer.svelte";
     
     let navItems = [
    { text: "Home", href: "/" },
    { text: "blog", href: "/blog" },
    { text: "My profile", href: "/profile" },
    { text: "business Card Collection", href: "/carding" },
    

  ];
</script>
<div class="container">
    <header><Header /></header>
  
    <div class="left-side">
     
    </div>
    <main>
        <slot></slot>
    </main>

    <footer><Footer /></footer>
  </div>

  <style>
    main {
      display: flex;
      flex-wrap: wrap;
      padding: 1em;
      gap: 1em;
    }
    .container {
      display: grid;
      grid-template: auto 1fr auto / auto 1fr;
    }
    header {
      padding: 0.25em;
      grid-column: 1 / 3;
    }
  
    footer {
      grid-column: 1 / 3;
      float: left;
    }
    .left-side {
      grid-column: 1 /2;
    }
  </style>