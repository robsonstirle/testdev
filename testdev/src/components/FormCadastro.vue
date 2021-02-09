<template>
   <div class="container">
      <div class="field">
         <label class="label">Nome</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">E-mail</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">Cpf</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">RG</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      
      <div class="field">
         <label class="label">Telefone</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">Cep</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">Endereço</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">Cidade</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="field">
         <label class="label">Bairro</label>
         <div class="control">
            <input class="input" type="text">
         </div>
      </div>
      <div class="file">
         <label class="file-label">
         <input class="file-input" type="file" name="resume">
         <span class="file-cta">
         <span class="file-icon">
         <i class="fas fa-upload"></i>
         </span>
         <span class="file-label">
         Anexar CNH
         </span>
         </span>
         </label>
      </div>
      <br>
      <div class="file">
         <label class="file-label">
         <input class="file-input" type="file" name="resume">
         <span class="file-cta">
         <span class="file-icon">
         <i class="fas fa-upload"></i>
         </span>
         <span class="file-label">
         Anexar Comprovante Residencia
         </span>
         </span>
         </label>
      </div>
      <div class="field">
         <label class="label">Mensagem</label>
         <div class="control">
            <textarea class="textarea"></textarea>
         </div>
      </div>
      <div class="field is-grouped">
         <div class="control">
            <button class="button is-link">Enviar</button>
         </div>
         <div class="control">
            <button class="button is-link is-light">Cancelar</button>
         </div>
      </div>
      <br>
   </div>
</template>
<script>
   export default {
       
   }
</script>
<style scoped></style>