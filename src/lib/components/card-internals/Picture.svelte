<script>
    // import billm from '$lib/assets/images/groundhog-day.webp';
    let { img } = $props();
    $inspect(img);
    
</script>

<img src="{img}" alt="Phil Connors">

<style>
    img {
            width: 200px;
            aspect-ratio: 1 / 1;
            object-fit: cover;
            object-position: center;
            border-radius: 30px;
            corner-shape: squircle;
        }
</style>