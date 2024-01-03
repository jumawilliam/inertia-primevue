<script setup>
import Button from 'primevue/button';
import Chips from 'primevue/chips';
import {ref} from 'vue';
const value =ref([])

</script>
<template>
<Button label="Submit" /> <br>
<Chips v-model="value" separator=","  />


</template>
