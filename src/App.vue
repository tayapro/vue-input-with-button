<script setup>
import InputWithButton from './components/InputWithButton.vue'
</script>

<template>
    <InputWithButton prop_text="your text" prop_button="Bla" />
    <div class="parent">
        <InputWithButton prop_text="enter your text here" prop_button="Send" />
    </div>
    <div class="parent1">
        <InputWithButton prop_text="your message" prop_button="Deliver" />
    </div>
</template>

<style scoped>
.parent {
    background-color: blueviolet;
    width: 300px;
    height: 4rem;
    margin-top: 20px;
}

.parent1 {
    background-color: rgb(226, 43, 86);
    width: 400px;
    height: 4rem;
    margin-top: 20px;
}
</style>
