<div class="page">

<div class="background">
    <div class="background-img">
        <img src="./background-event.png" alt="Cool irrelevant graphic">
    </div>

</div>

<div class="content">
        
    <div class="content-info">
        <h1>Oversikt</h1>
        <ul>
            <h2>00.11.2023 - BreiLAN</h2>
            <h2>00.11.2023 - BreiLAN</h2>
            <h2>00.11.2023 - BreiLAN</h2>
            <h2>00.11.2023 - BreiLAN</h2>
            <h2>00.11.2023 - BreiLAN</h2>
        </ul>
    </div>
    
</div>

</div>


<style>

.page {
    display: flex;
    flex-direction: row;
    flex: 1;
    height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height */
    margin-top: 96px;
    justify-content: center;
    position: absolute;
    max-width: 100%;
}

.background-img > img{
    width: auto;
    height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height */
}   

.content{
    display: flex;
    flex-direction: row-reverse;
    justify-content: center;
    list-style: none;
    position: relative;
    width: 70vw;
}

.content-info{
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center; 
    width: 100%;
}

h1{
    margin-bottom: 30px;
    position: relative;
    left: -10px;
}

h2{
    margin-bottom: 90px;
    list-style: none;
}

</style>

