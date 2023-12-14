<div class="back_img">
    <div class="content">
        <div class="form-image"></div>
    <form class="Kontakskjema">
            
  <label for="name">Name</label>
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



.back_img{
position: fixed;
height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height */
flex: 1;
background-image: url(./background-contact.png);
background-size: cover;
background-repeat: no-repeat;
width: 100%;
display: flex;
flex-direction: row;
justify-content: flex-end;
}
.Kontakskjema{
display: flex;
justify-content: center;
text-align: center;
flex-direction: column;
font-family: Arial, Helvetica, sans-serif;
text-align: left;
background-color: lightgray;
padding: 20px;
}
button{
color: black;
background-color: white;
margin: 7px;
border-radius: 3px;
}
.content {
min-height: 10px;
height: fit-content;
width: fit-content;
display: flex;
flex-direction: row;
margin-left: 50%;
margin-right: 15%;
margin-top: 15%;
transform: translateX(-50%) translateY(-50%);

}
.form-image {
background-color: black;
width: 300px;
height: 330px;
}
</style>