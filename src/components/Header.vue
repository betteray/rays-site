<template>
    <div class="Header">
        <ul class="h-list">
            <li>首页</li>
            <li>归档</li>
            <li>关于</li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>

    .Header {
        font-weight: bold;
        text-align: center;
    }

    .h-list li {
        display: inline;
        line-height: 40px;
        margin: 20px;
    }


</style>