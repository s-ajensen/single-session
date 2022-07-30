<script>
    import Styles from "../Styles.svelte";
</script>

<section class="bg-dark2">
    <h1 class="c-contrast">Single-Session</h1>
    <h2 class="c-contrast">Transient, end-to-end encrypted messaging for the web.</h2>
</section>

<div class="spacer layer1" />

<section class="bg-dark1">
    <button class="bg-contrast">
        <p class="c-dark1">Start a New Session</p>
    </button>
</section>

<style>
    :root {
        --dark1: #871400;
        --dark2: #931C1C;
        --contrast: #f5730a;
    }

    h1 {
        font-family: "Work Sans", sans-serif;
        font-size: 4em;
        text-transform: uppercase;
    }

    h2 {
        font-family: "Work Sans", sans-serif;
        font-size: 2em;
    }

    section {
        position: relative;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 2em;
    }

    .bg-dark1 {
        background: var(--dark1);
    }

    .bg-dark2 {
        background: var(--dark2);
    }

    .bg-contrast {
        background: var(--contrast)
    }

    .c-contrast {
        color: var(--contrast);
    }

    .c-dark1 {
        color: var(--dark1);
    }

    .c-dark2 {
        color: var(--dark2);
    }

    .spacer {
        aspect-ratio: 1024/256;
        width: 100%;
        background-repeat: no-repeat;
        background-position: center;
        background-size: cover;
    }

    .layer1 {
        background-image: url("/assets/layered-peaks-haikei.svg");
    }
</style>
