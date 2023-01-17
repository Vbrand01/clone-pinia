<template>
    <div class="container">
        <div class="row align">
            <div class="col-sm-4"></div>
            <div class="col-sm-4">
                <h5>Gold Sponsors</h5>
                <img src="../assets/images/vuejobs.svg" height="40px" alt="">
                <h5>Silver Sponsors</h5>
                <div>
                </div>
                <button class="btn">Become a Sponsor!</button>
            </div>
            <div class="col-sm-4"></div>
        </div>
    </div>
    <br>
</template>

<script>
    export default {
        name: 'SectionTree'
    }
</script>

<style scoped>

.align{
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    background-color: #182337;
    padding: 20px;
    border-radius: 10px;
    border-bottom: 0.1px solid rgb(56, 56, 56);

}

h5{
    color: white;
    background: transparent;
    margin: 15px;
    font-size: 22px;
}

img{
    filter: saturate(100%);
}

.col-sm-4{
    background-color: transparent;
}

.btn{
    background-color: transparent;
    border-radius: 80px;
    color: white;
    border: solid 1px white;
    padding: 10px 30px;
    font-weight: 500;
    font-size: 18px;
}
.btn:hover{
    background-color: #FFD859;
    border: solid 1px #FFD859;
    color: #182337;
}


</style>