<template>
    <nav>
        <p><img src="../assets/images/pinialogo.png" height="50px" alt=""></p>
        <ul>
           <a href="">Guide</a>
           <a href="">API</a>
           <a href="">Links</a>
           <a href="">Languages</a>
           <a href="">GitHub</a>
        </ul>
    </nav>
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style scoped>

    *{
        text-decoration: none !important;
    }

    nav{
        background-color: #101827;
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 10px;
        border-bottom: 0.1px solid rgb(56, 56, 56);
    }

    nav ul{
        display: flex;
        margin-bottom: 0px;
    }
    ul a{
        padding: 10px;
        color: rgb(242, 242, 242);
        font-size: 16px;
    }


</style>