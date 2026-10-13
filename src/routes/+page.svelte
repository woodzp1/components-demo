<script>
  import Card from "$lib/components/Card.svelte";
  import Pic from "$lib/assets/images/groundhog-day.webp";
  let people = [
    {
      fullName: "fsaFAFKJw",
      favSong: "I be",
      petName: "Pufsawney Phsasfil",
      img: "https://picsum.photos/400/600"
    },
    {
      fullName: "sdasdg",
      favSong: "asaf you babe",
      petName: "tawney Phil",
      img: "https://picsum.photos/100/150"
    },
    {
      fullName: "adsfasfkh;lkew",
      favSong: "I got ",
      petName: "Psdf Phildsf",
      img: "src/lib/assets/images/groundhog-day.webp"
    }
  ];
  
</script>

<main>
  <!-- todo make loop -->
  <!-- <Card person={person}/>
    <Card />
    <Card /> -->
  {#each people as person}
    <Card person={person} img={person.img} />
  {/each}
</main>

<style>
  main {
    display: flex;
    flex-wrap: wrap;
  }
</style>
