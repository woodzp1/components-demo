<script>
    import Card from '$lib/components/Card.svelte';
    let person = {
        fullName: "Phill Connors",
        favSong:"I got you babe",
        petName: "Punxsutawney Phil"
    }
</script>

<main>
<!-- todo make loop -->
    <Card person={person}/>
    <Card />
    <Card />
</main>

<style>
    main {
        display: flex;
        flex-wrap: wrap;
    }
</style>