Node 12.18.1 
Npm 6.14.5

Instalar o cli vue 
   npm install @vue/cli@4.4.0 --save

- Criar o primeiro projeto
   vue create guiaClientes

- Criar um componente
  crie um arquivo arquivo.vue na pasta components
  com a seguinte estrutura 

<template>
    <div class="container">
        <h1>Cadastro de Clientes</h1>
        Nome do Cliente: {{ nome }} <br>
        Endereço: {{ endereco }} <br>
        <input type="button" value="Enviar">
    </div>
</template>

<script>
    export default {
        data() {
            return {
                codigo: 0,
                nome: 'jose',
                endereco: 'rua'
            }
        }

    }

</script>

<style scoped></style>


- Utilizando interpolação
   {{}}



   


