
<section>
  <article>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Delectus iste provident quo voluptatem veritatis dolore, mollitia accusantium sed harum fuga aperiam vitae nobis maiores nulla obcaecati error, inventore saepe nostrum.
  </article>

  <img src="../background-main.png" alt="tromsokommune logo">

 


</section>


<!-- src/routes/page1.svelte -->
<script context="module">
  export const layout = import('./+layout.svelte');
</script>

<!-- Rest of the component -->

<style>

* {
  margin: 0;
  padding: 0;
}

section {
  display: flex;
  justify-content: right;
  top:0;
  
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
  height: 100%;
  background-color: rgba(0, 0, 0, 0.6);
  color: white;
  z-index: -1;
  width: 30%;
  margin: 0 auto;
  transform: translateX(50%); 
  display: flex;
  
  
  @media (max-width: 600px) {
    width: 80%;
    transform: translateX(0);
  }
}

</style>