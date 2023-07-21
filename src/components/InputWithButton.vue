<script setup>
defineProps({
    prop_text: String,
    prop_button: String,
})
</script>

<template>
    <div class="container">
        <input type="text" :placeholder="prop_text" />
        <button>{{ prop_button }}</button>
    </div>
</template>

<style scoped>
.item1 {
    background-color: blue;
    width: 50px;
    height: 3rem;
}

.item2 {
    background-color: rgb(255, 0, 162);
    width: 50px;
    height: 3rem;
}

.parent {
    background-color: blueviolet;
    width: 300px;
    height: 4rem;
    margin-top: 20px;
}

.container {
    display: flex;
    justify-content: space-between;
}

.parent1 {
    background-color: rgb(226, 43, 86);
    width: 400px;
    height: 4rem;
    margin-top: 20px;
}

input {
    border: 1px solid rgb(36, 36, 255);
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
    padding: 0.5rem;
    flex-grow: 1;
    border-right: none;
}

input:focus {
    outline: none;
    border: 1px solid rgb(220, 31, 198);
    border-right: none;
}

button {
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    border-color: rgb(36, 36, 255);
    /* border-left: none; */
    background-color: rgb(36, 36, 255);
    color: aliceblue;
    padding: 0.5rem;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: rgb(220, 31, 198);
    border: none;
    border-color: rgb(220, 31, 198);
}
</style>
