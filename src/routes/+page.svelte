<script>
    let name = 'Firdaus'
    let age = 30

    function incrementAge() {
        age += 1;
    }
</script>

<style>
    h1 {
        color: purple;
    }
</style>

<h1>Hello {name}, my age is {age}!</h1>
<button  on:click={incrementAge}>Increase Age</button>

<input type="text" bind:value={name}>

