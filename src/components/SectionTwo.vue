<template>
    <div class="container border-hr">
        <div class="row">
            <div class="col-sm-4 p-2">
                <h3>💡 Intuitive</h3>
                <p>Stores are as familiar as components. API designed to let you write well organized stores.</p>
            </div>
            <div class="col-sm-4 p-2">
                <h3>🔑 Type Safe</h3>
                <p>Types are inferred, which means stores provide you with autocompletion even in JavaScript!</p>
            </div>
            <div class="col-sm-4 p-2">
                <h3>⚙️ Devtools support</h3>
                <p>Pinia hooks into Vue devtools to give you an enhanced development experience in both Vue 2 and Vue 3.</p>
            </div>
        </div>
        <div class="row">
            <div class="col-sm-4 p-2">
                <h3>🔌 Extensible</h3>
                <p>React to store changes to extend Pinia with transactions, local storage synchronization, etc.</p>
            </div>
            <div class="col-sm-4 p-2">
                <h3>🏗 Modular by design</h3>
                <p>Build multiple stores and let your bundler code split them automatically.</p>
            </div>
            <div class="col-sm-4 p-2">
                <h3>📦 Extremely light</h3>
                <p>Pinia weighs ~1.5kb, you will forget it's even there!</p>
            </div>
        </div>
    </div>
    br
</template>

<script>
export default {
    name: 'SectionTwo',
}
</script>

<style scoped>
.border-hr{
    border-top: 0.1px solid rgb(56, 56, 56);
}

.row{
    padding: 20px;
    padding-top: 50px;
}

h3{
    color: white;
    font-size: 25px;
}

p{
    color: white;
    font-size: 18px;
    font-weight: 300;
}

</style>