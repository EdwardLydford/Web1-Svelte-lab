<!--importing card from components below -->
<script>
 import Card from "../components/Card.svelte";
 export let data;
 const people = data.people;
 console.log(people);

</script>
   <h1>Home</h1>
   <main>
      {#each people as person}
      <Card {person} />
      {/each}
   </main>
    <style>

    </style>
 

