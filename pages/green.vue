<template>
    <div class="section has-text-centered">
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
                <div class="column is-one-third">
                    <div class="hero">
                        <div class="hero-body">
                            
                               <h1 class="title">
                               Hero title
                               </h1>
                               <h2 class="subtitle">
                               Hero subtitle
                               </h2>
                            
                             <b-field position="is-centered" grouped group-multiline>
                               
                              <b-radio-button v-model="radioButton"
                              native-value="37"
                              type="is-success">
                              <span>37</span>
                              </b-radio-button>
                              

                              <b-radio-button v-model="radioButton"
                              native-value="38"
                              type="is-success">
                              <span>38</span>
                              </b-radio-button>
                              <b-radio-button v-model="radioButton"
                              native-value="39"
                              type="is-success">
                              <span>39</span>
                              </b-radio-button>
                              <b-radio-button v-model="radioButton"
                              native-value="40"
                              type="is-success">
                              <span>40</span>
                              </b-radio-button>
                              
                              
                              
                              <b-radio-button v-model="radioButton"
                              native-value="41"
                              type="is-success">
                              <span>41</span>
                              </b-radio-button>
                              <b-radio-button v-model="radioButton"
                              native-value="42"
                              type="is-success">
                              <span>42</span>
                              </b-radio-button>
                              <b-radio-button v-model="radioButton"
                              native-value="43"
                              type="is-success">
                              <span>43</span>
                              </b-radio-button>
                              <b-radio-button v-model="radioButton"
                              native-value="44"
                              type="is-success">
                              <span>44</span>
                              </b-radio-button>
                              
                              
                              
                              
            
                             </b-field>
                            
                             <p class="content">
                             <b>Selection:</b>
                             {{ radioButton }}
                             </p>
                            
                             <p class="control">
                             <button class="button add-to-cart snipcart-add-item" 
                             data-item-id="2"
                             data-item-name="Bacon"
                             data-item-price="3.00"
                             data-item-weight="20"
                             data-item-url="/green"
                             data-item-description="Some fresh bacon">
                             add to cart
                             </button>
                             </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    
</template>

<script>
    export default {
        data() {
            return {
                radioButton: ''
            }
        }
    }
</script>



<style>
   .img-alpargata{
       width: 100%;
   }
   .add-to-cart{
       width: 100%;
   }
   
</style>


