<template>
   <div>
      <div>
         <nav class="navbar" role="navigation" aria-label="main navigation">
            <div class="navbar-brand">
               <a class="navbar-item" href="https://bulma.io">
               <img src="https://www.grupointegrado.br/img/logo-horizontal.png" >
               </a>
               <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
               <span aria-hidden="true"></span>
               <span aria-hidden="true"></span>
               <span aria-hidden="true"></span>
               </a>
            </div>
            <div id="navbarBasicExample" class="navbar-menu">
               <div class="navbar-start">
                  <div class="navbar-item has-dropdown is-hoverable">
                     <a class="navbar-link">
                     Cursos
                     </a>
                     <div class="navbar-dropdown">
                        <ul class="menu-list">
                           <li>
                              <a class="menu-label">Graduação</a>
                              <ul>
                                 <li> <router-link to="/graduacaopresencial">Presencial</router-link></li>
                                 <li> <router-link to="/graduacaoead">EAD</router-link></li>
                                 <li> <router-link to="/graduacaoead">Híbrido</router-link></li>
                              </ul>
                           </li>
                           <li>
                              <a class="menu-label">Pós Graduação</a>
                              <ul>                                 
                                 <li> <router-link to="/graduacaopresencial">Presencial</router-link></li>
                                 <li> <router-link to="/graduacaoead">EAD</router-link></li>
                                 <li> <router-link to="/graduacaoead">Híbrido</router-link></li>
                              </ul>
                           </li>
                        </ul>
                     </div>
                  </div>
               </div>
               <div class="navbar-end">
                  <div class="navbar-item">
                     <div class="buttons">
                        
                        <a class="button is-dark">
                        <router-link to="/formcadastro">Matricule-se</router-link>
                        </a>
                     </div>
                  </div>
               </div>
            </div>
         </nav>
      </div>
  <div class="container">
   <router-view></router-view>  
  </div>
      
   </div>
</template>
<script>

import GraduacaoPresencial from './GraduacaoPresencial.vue'
import GraduacaoEAD from './GraduacaoEAD.vue'
import FormCadastro from './FormCadastro.vue'
import VueRouter from 'vue-router'

var router = new VueRouter({

   routes:[
      { path: '/graduacaopresencial', component: GraduacaoPresencial},
       { path: '/graduacaoead', component: GraduacaoEAD},
       { path: '/formcadastro', component: FormCadastro},
   ]

});

export default {
  name: 'menu',
  components: {
    
  },
  router
}

</script>
<style scoped></style>