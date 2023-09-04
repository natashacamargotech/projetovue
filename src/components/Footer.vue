<template>
    <footer id="footer">
        <p>Make Your Burger &copy; 2023 | Desenvolvido por Natasha Camargo</p>
        <p>Projeto fictício sem fins comerciais | Baseado no curso de Vue - Matheus Battisti - Hora de Codar</p>
    </footer>
</template>

<script>
export default {
   name: "Footer"
}
</script>

<style scoped>
    #footer {
        height: 60px;
        background-color: #222;
        border-top: 8px solid #222;
        border-bottom: 8px solid #222;
        color: #FCBA03;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: space-between;
        width: auto;
    }
</style>