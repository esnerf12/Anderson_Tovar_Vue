<template>
    <div class="main__container">
        <div class="avalaible__container">
            <label for="avalaible">Avalaible Options</label>
            <input class="avalaible" type="text">
        </div>
        <div class="disabled__container">
            <label for="disabled">Disabled Options</label>
            <input class="disabled" type="text">
        </div>
    </div>
</template>

<script>

</script>

<style>
.main__container {
    display: flex;
    justify-content: baseline;
    align-items: baseline;
    gap: 5px;
}

.avalaible__container, .disabled__container {
    display: flex;
    flex-direction: column;
}

.avalaible, .disabled {
    background-color: black;
    color: white;
    width: 300px;
    height: 200px;
    justify-content: baseline;
}
</style>