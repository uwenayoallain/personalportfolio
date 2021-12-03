<script>
  let image = "/UWENAYO Alain Pacifique.png";
</script>

<svelte:head>
  <title>UWENAYO Alain Pacifique</title>
</svelte:head>

<div class="main">
  <div class="heading">
    <h1>I'm UWENAYO Alain Pacifique</h1>
    <p>
      a web developer and a ux/ui designer, i am Rwandan with a vision of being
      the key person in world development through high-quality software
    </p>
  </div>
  <div class="profile">
    <img src={image} alt="UWENAYO Alain Pacifique" />
  </div>
</div>

<style>
  * {
    padding: 0;
    margin: 0;
  }
  img {
    width: 60%;
  }
  .main {
    display: flex;
    width: 100%;
    flex-wrap: wrap;
  }
  .heading,
  .profile {
    width: 50%;
  }
  .heading h1 {
    background-clip: text;
    background: linear-gradient(to bottom, rgb(223, 68, 6), rgb(45, 6, 117));
    -webkit-text-fill-color: transparent;
    -webkit-background-clip: text;
    font-family: Operator Mono, sans-serif;
    font-weight: bold;
    font-size: 5rem;
    padding: 20px;
    margin: 1em 0 0 1em;
  }
  .heading p {
    font-family: Overpass Mono;
    font-weight: bold;
    font-size: 1rem;
    padding: 20px;
  }
  .profile {
    display: flex;
    justify-content: center;
  }
</style>
