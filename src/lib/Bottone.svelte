<script>
    export let titolo;
</script>

<style>
    button.bottonePannello{
        margin-left: 1%;
        margin-right: 1%;
        color: white;
        background-color: #597ca3;
    }
    button.bottonePannello:hover{
        transition: all 0.25s;
        background-color: aliceblue;
        color: black;
    }
</style>

<button class="bottonePannello">
    {titolo}
</button>