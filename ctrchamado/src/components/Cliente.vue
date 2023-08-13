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