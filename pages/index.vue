<template>
  <div class="container">
    <div>
      <div>
 

       <h1 class="title">
      
            
      </h1>
      <div class="links">
        <a
          href="https://www.linkedin.com/in/miguel-alejandro-cabrera-a2082515b/"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Contacto 
        </a>
        <a
          href="https://github.com/Ale-cm"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          Github
        </a>
      </div>
    </div>
  </div>
  </div>
</template>

<script>
export default {}
</script>

<style>


body {
  margin:0;
  min-height: 100vh;
  background-image: url(/imagen1-4.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
  

}
body:before{
  content:"";
  width: 100;
  min-height: 100vh;
  position: absolute;
  top: 0;
  left: 0;
   background: linear-gradient(90deg,rgb(37, 37, 202),rgb(27, 151, 22));
   }

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
   width: 10em;
  height: 10em;
  text-align: left;
  background-image: url("/logo.png") ;
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  
  
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top:15px;
}
</style>
