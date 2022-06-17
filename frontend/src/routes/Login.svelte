<script>
    let email=' '
    let password=' '

    const processForm =()=>{
        console.log('todo funcionando')}
</script>

<div>
    <h1>Access</h1>
    <form on:submit|preventDefault={processForm}>
        <input type="text"
                placeholder="Enter email"
        >
        <input type="text"
                placeholder="Enter password"
        >
        <button type="submit">Submit</button>
    </form>
</div>