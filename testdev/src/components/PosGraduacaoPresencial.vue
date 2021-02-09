<template>
   <div class="tile is-ancestor">
            <div class="tile is-vertical is-4">
               <div class="tile">
                  <div class="tile is-parent">
                     <article class="tile is-child notification">
                        <p class="title">Desenvolvimento Web</p>
                        <p class="subtitle">Mensalidade: R$ 350,00</p>
                        <p class="subtitle">Duração do Curso: 2 anos</p>
                        <figure class="image is-4by3">
                           <img src="../assets/web.jpg">
                        </figure>
                        <br>
                        <button class="button is-primary">Matricule-se</button>
                     </article>
                     
                  </div>
               </div>
            </div>            
         </div>
         
</template>
<script>

import FormCadastro from './FormCadastro.vue'
import VueRouter from 'vue-router'

var router = new VueRouter({

   routes:[
      { path: '/formcadastro', component: FormCadastro},
   ]

});

   export default {
       router
   }
</script>
<style scoped>
</style>