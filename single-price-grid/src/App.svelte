<script lang="ts">
    import Join from "./components/Join.svelte";
    import Plan from "./components/Plan.svelte";
    import Why from "./components/Why.svelte";
</script>

<main>
    <div id="container">
        <div id="top">
            <Join />
        </div>
        <div id="bottom">
            <Plan />
            <Why />
        </div>
    </div>
</main>

<style>
    main {
        height: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    #container {
        width: 700px;
        border-radius: 10px;
        box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.25);
        display: flex;
        flex-direction: column;
        overflow: hidden;
    }
    #bottom {
        display: flex;
        align-items: stretch;
    }
    @media all and (max-width: 1440px) {
        main {
            display: block;
            padding: 50px 0;
            height: auto;
        }
        #container {
            width: 90%;
            margin: auto;
        }
        #bottom {
            flex-direction: column;
        }
    }
</style>
