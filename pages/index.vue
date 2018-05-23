<template>
    <section class="section"> 
      <div class="portada"></div>   
      <div class="container column">
        <div class="columns">
            <div class="column">
               <nuxt-link to="/green"> 
                <div class="card-image">
                   <figure class="image is-4by3">
                       <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
                   </figure>
                </div>
               </nuxt-link> 
            </div>
            <div class="column">
                <div class="card-image">
                   <figure class="image is-4by3">
                       <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
                   </figure>
                </div>
            </div>
            <div class="column">
                <div class="card-image">
                   <figure class="image is-4by3">
                       <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
                   </figure>
                </div></div>        
        </div>
        <div class="columns">
            <div class="column">
                <div class="card-image">
                   <figure class="image is-4by3">
                       <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
                   </figure>
                </div>
            </div>
            <div class="column">
                <div class="card-image">
                   <figure class="image is-4by3">
                       <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
                   </figure>
                </div>
            </div>
            <div class="column">
                <div class="card-image">
                   <figure class="image is-4by3">
                       <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
                   </figure>
                </div></div>        
        </div>
      </div>
    </section>
</template>

<script>


export default {
  name: 'HomePage',
}
</script>
<style>
  .portada{
      background-image: url('~assets/portada.jpg');
      background-position: center;
      background-size: cover;
      height: 100vh;
  }
  .section{
      padding-left: 0;
      padding-right: 0;
  }
</style>


