<script>
  import Card from "$lib/components/Card.svelte";

  let people = [
    {
      fullName: "fsaFAFKJw",
      favSong: "I be",
      petName: "Pufsawney Phsasfil",
    },
    {
      fullName: "sdasdg",
      favSong: "asaf you babe",
      petName: "tawney Phil",
    },
    {
      fullName: "adsfasfkh;lkew",
      favSong: "I got ",
      petName: "Psdf Phildsf",
    }
  ];
  
</script>

<main>
  <!-- todo make loop -->
  <!-- <Card person={person}/>
    <Card />
    <Card /> -->
  {#each people as person}
    <Card {person} />
  {/each}
</main>

<style>
  main {
    display: flex;
    flex-wrap: wrap;
  }
</style>
