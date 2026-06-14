<script>
    let count = 0;
</script>

<p>Count: {count}</p>

<button on:click={() => count++}>
    Tambah
</button>

<button on:click={() => count--}>
    Kurang
</button>

<style>
    button {
        padding: 10px 20px;
        cursor: pointer;
    }
</style>