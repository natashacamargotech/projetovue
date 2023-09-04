<template>
    <div class="message-container">
        <p>{{msg}}</p>
    </div>
</template>

<script>
    export default{
        name: "Message",
        props: {
            msg: String
        }
    }
</script>

<style>
    .message-container {
        color: #004085;
        background-color: #CCE5FF;
        border: 2px soid #B8DAFF;
        border-radius: 5px;
        padding: 10px;
        max-width: 400px;
        margin: 30px auto;       
    }
</style>