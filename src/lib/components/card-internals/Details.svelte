<script>
    
    let person = {
        fullName: "Phill Connors",
        favSong:"I got you babe",
        petName: "Punxsutawney Phil"
    }

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