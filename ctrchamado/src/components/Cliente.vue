<template>
    <div class="container">
        <h1></h1>


        <h1>Cadastro de Clientes</h1>
        Nome do Cliente: {{ nomeCliente }} <br>
        Endereço: {{ endereco }} <br><br>
        <input type="text" :value="nomeCliente"><br><br>        
        <input type="text" v-model="endereco"><br>
        <input type="text" v-model="nomeSistema"><br>
        <input type="button" value="Enviar">
    </div>
</template>

<script>
    export default {
        data() {
            return {
                codigo: 0,
                nomeCliente: 'jose',
                endereco: 'rua'
            }
        },
        props: {
            prop_nome: String
        }

    }

</script>

<style scoped></style>