
<section>
  <article>
    <h1>Klassen 2023</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis tristique purus eu euismod sagittis. Nam tincidunt eros quam, id sodales mi pellentesque vehicula. Sed commodo felis sit amet massa pellentesque</p>
  </article>

  <img src="../background-main.png" alt="tromsokommune logo">

 


</section>


<!-- src/routes/page1.svelte -->
<script context="module">
  export const layout = import('./+layout.svelte');
</script>

<!-- Rest of the component -->

<style>

@import url('https://fonts.googleapis.com/css2?family=Helvetica:wght@400;300&display=swap');

  * {
    margin: 0;
    padding: 0;
  }
  
  section {
    display: flex;
    justify-content: center;
    position: relative;
  }
  
  section img {
    position: fixed;
    top: 0;
    width: 100%;
    margin: 0;
    padding: 0;
    z-index: -2;
  }
  
  article {
    border-radius: 4px;
    background: rgba(30, 30, 30, 0.80);
    color: white;
    z-index: -1;
    height: 600px;
    width: 520px;
    max-width: 600px;
    margin: 0 auto; 
    padding: 20px;
    box-sizing: border-box; 
    margin-left: 65%;
    margin-top: 10%;
    
  }

  article h1 {
    color: #F5F5F7;

    text-align: center;
    font-family: Helvetica;
    font-size: 36px;
    font-style: normal;
    font-weight: 400;
    line-height: normal;
    letter-spacing: 1.555px;
  }
  
  article p {
  color: #FFF;
  margin-top: 15%; /* Increased margin-top for more space */
  text-align: center;
  font-family: 'Helvetica';
  font-size: 24px;
  font-style: normal;
  font-weight: 300;
  line-height: 42px; /* Increased line-height for more space between lines */
  letter-spacing: 0.691px;
}
  
  @media (max-width: 600px) {
    article {
      width: 80%;
    }
  }
  
  </style>