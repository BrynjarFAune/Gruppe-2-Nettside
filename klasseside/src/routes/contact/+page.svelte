<div class="page">

    <div class="content">
        <div class="form-image">
            <img src="./background-form.png" alt="a girl holding a reed baloon">
        </div>
    <form class="Kontakskjema">
            
  <label for="name">Navn</label>
  <input type="text" id="name" required title="Name">
  
  <label for="email">E-post</label>
  <input type="text" id="email" required title="Email">

  <label for="hva-gjelder-det">Hva gjelder det?</label>
  <textarea id="Hva_gjelder_det" cols="30" rows="10"></textarea>   
  <button>Submit</button>
    </form>
    </div>

</div>

<style>


/*
.back_img{
position: fixed;
height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height *
flex: 1;
background-image: url(./background-contact.png);
background-size: cover;
background-repeat: no-repeat;
width: 100%;
display: flex;
flex-direction: row;
justify-content: flex-end;
}*/
.Kontakskjema{
display: flex;
justify-content: center;
text-align: center;
flex-direction: column;
font-family: Arial, Helvetica, sans-serif;
text-align: left;
background-color: lightgray;
width: 350px;
height: 100%;
padding: 0 20px;
}



button{
color: black;
background-color: white;
margin: 7px;
border-radius: 3px;
}


.page {
    position: fixed;
    height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height */
    margin-top: 96px;
    flex: 1;
    background-image: url(./background-contact.png);
    background-size: cover;
    background-repeat: no-repeat;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

.form-image {
    overflow: hidden;
    height: fit-content;
    width: fit-content;
}

img {
    width: auto;
    height: 100%;
}

.content {
    width: 735px;
    height: 507px;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    border-radius: 3px;
}

</style>
