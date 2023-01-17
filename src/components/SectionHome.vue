<template>
    <div class="container">
        <div class="row">
            <div class="col-sm-12 pt-5">
                <div class="image-pinia">
                    <img src="../assets/images/logo.svg" height="220px" alt="">
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-sm-12">
                <h2>Pinia</h2>
                <p>The Vue Store that you will enjoy using</p>
            </div>
        </div>
        <div class="row">
            <div class="col-sm-12 buttons">
                <button class="start">Get Started</button>
                <button class="demo">Demo</button>
            </div>
            <p class="pt-2">
                <a class="link-yellow"
                    href="https://vueschool.io/lessons/introduction-to-pinia?friend=vuerouter&utm_source=pinia&utm_medium=link&utm_campaign=homepage">
                    Watch Video Introduction
                </a>
            </p>
        </div>
        <div class="row">
            <div class="col-sm-3"></div>
            <div class="col-sm-6">
                <div class="back-drop">
                    <p>🏁 Get the
                        <a href="https://www.vuemastery.com/pinia/?coupon=PINIA-DOCS&via=eduardo#cheat-sheet">Pinia
                            Cheat Sheet</a>
                        from Vue Mastery
                    </p>
                </div>
            </div>
            <div class="col-sm-3"></div>
        </div>
    </div>
</template>

<script>

</script>

<style scoped>
* {
    /* margin: 0;
    padding: 0; */
    box-sizing: border-box;
    text-decoration: none;
}

.image-pinia {
    display: flex;
    justify-content: center;
    align-items: center;
}

h2 {
    color: white;
    text-align: center;
    margin-top: 40px;
    font-weight: 600;
    font-size: 52px;
}

p {
    text-align: center;
    color: rgb(209, 209, 209);
    font-weight: 400;
    font-size: 28px;
}

.buttons {
    display: flex;
    justify-content: center;
}

button {
    margin: 10px;
    width: 16%;
}

.start {
    background-color: #FFD859;
    padding: 18px;
    border-radius: 8px;
    font-weight: 500;
}

.start:hover {
    background-color: #ffcc23;
}

.demo {
    padding: 15px;
    border-radius: 8px;
    background-color: transparent;
    border: solid 1px white;
    color: white;
    font-weight: 500;
}

.demo:hover {
    background-color: #ffcf0e;
    border: solid 1px #ffcf0e;
    color: #182337;
}

.link-yellow {
    color: #FFD859;
    font-weight: 400;
    font-size: 20px;
}

.back-drop p {
    background-color: #162033;
    padding: 5px;
    padding-left: 0px;
    border-radius: 8px;
    font-weight: 400;
    font-size: 18px;
}

.back-drop a {
    color: #FFD859;
    background: transparent;
}

@media(max-width: 800px) {
    h2 {
        color: white;
        text-align: center;
        margin-top: 20px;
        font-weight: 600;
        font-size: 40px;
    }

    p {
        font-size: 20px;
    }

    button {
    margin: 5px 10px;
    width: 100%;
    }

}
</style>