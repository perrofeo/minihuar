<template>
    <section class="section">
        <div class="container">
            <div class="columns">
                <div class="column is-two-thirds">
                   <no-ssr> 
                    <carousel :perPage="1">
                        <slide>
                           <img src="~/assets/negro.png" class="img-alpargata">
                        </slide>
                        <slide>
                           <img src="~/assets/azul.png" class="img-alpargata">
                        </slide>
                    </carousel>
                   </no-ssr> 
                </div>
                <div class="column"></div>
            </div>
        </div>
    </section>
</template>


<style>
   .img-alpargata{
       width: 100%;
   }
</style>


