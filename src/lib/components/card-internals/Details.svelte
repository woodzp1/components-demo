<script>
    
    
    let { person =  {
        fullName: "default",
        favSong:"default",
        petName: "default"
    }} = $props();

</script>



<section>
    <h2>{person.fullName}</h2>
    <dl>
        <dt>Favourite song:</dt>
        <dd>{person.favSong}</dd>
        <dt>Pet's name:</dt>
        <dd>{person.petName}</dd>
    </dl>
</section>

<style>
    dl {
        display: grid;
        grid-template-columns: max-content 1fr;
        gap: 0.5rem 1rem;
    }

    dt {
        font-weight: bold;
    }

    dd {
        margin: 0;
    }
</style>