
<div class="page">


<div class="content">



<div class="menu">

<label for="search">
<h2>Søk</h2>
</label>
<input type="text" name="search">

<div class="categories">
<ul>
<!--loop here-->
<h2>Kategorier</h2>
{#each categories as category (category)}
    <li>{category}</li>
{/each}
</ul>
</div>

<div class="producers">
<ul>
<!--loop here-->
<h2>Produsenter</h2>
{#each producers as producer (producer)}
    <li>{producer}</li>
{/each}
</ul>
</div>

</div>


<div class="list">
<!--loop the tmp 5 times-->
{#each items as item (item.id)}
<div class="tmp">

      <div class="img" style="background-image: url({item.imagePath})"></div>

<div class="text">
<h3>{item.name}</h3>
<p>{item.status}</p>
</div>

</div>
{/each}

</div>

</div>
</div>


<style>

* {
    margin: 0;
}

ul {
  list-style-type: none;
  margin: 0;
}

.list {
    display: block;
    max-height: 100%;
    overflow: scroll;
}

.menu {
    display: flex;
    flex-direction: column;
    min-height: 50%;
    margin-left: 90px;
    margin-right: 25px;
    justify-content: space-evenly;
    align-items: start;
}



.content {
    display: flex;
    justify-content: center;
    flex-direction: row;
    background-color: #D9D9D9;
    height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height */
    min-width: 50%;
    width: fit-content;
    align-items: center;
}

.tmp  {
    background-color: #F5F5F7;
    width: 345px;
    height: 135px;
    min-height: 135px;
    margin: 10px;
    display: flex;
    justify-content: space-between;
    flex-direction: row;
    border-radius: 2px;
}

.text {
    flex-direction: column;
    justify-content: center;
    justify-content: center;
    height: 100%;
    display: flex;
    flex: 1;
}

.img {
    height: 100%;
    width: 60%;
    background-position: center;
    background-size: auto 100%;
    background-repeat: no-repeat;
}

.page {
    position: fixed;
    height: calc(100vh - 96px - 67px); /* 100vh - Header height - Footer height */
    margin-top: 96px;
    flex: 1;
    background-image: url(./background-database.png);
    background-size: cover;
    background-repeat: no-repeat;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: flex-end;
}


ul {
    padding: 0;
}

</style>


<script>
  import { items, categories, producers } from './data.js';
</script>
