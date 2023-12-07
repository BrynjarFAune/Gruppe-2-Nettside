
    <form class="Kontakskjema">
        <label>Name</label>
        <input type="text" required title="Name">
        <label>E-post</label>
        <input type="text" required title="Email">
        <label>Hva gjelder det?</label>
        <textarea required id="Hva_gjelder_det" cols="30" rows="10"></textarea>
        <button>Submit</button>
    </form>

<style>

.Kontakskjema{
    display: flex;
    justify-content: center;
    text-align: center;
    flex-direction: column;
    margin-left: 500px;
    margin-right: 500px;
    margin-top: 10px;
    margin-bottom: 10px;
    font-family: Arial, Helvetica, sans-serif;
    text-align: left;
}

button{
    color: black;
    background-color: white;
    margin: 7px;
    border-radius: 3px;
}

</style>
