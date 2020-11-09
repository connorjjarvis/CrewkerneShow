<template>
<b-container fluid="lg" class="text-center">
     <Navbar />
     <div class="nextDate">
        <b-button  size="sm" id="nextDate">
            Next show to be announced!
        </b-button>
     </div>
</b-container>
</template>

<script lang="ts">
import Navbar from './Navbar.vue';
export default {
    name: 'Header',
    computed: {},
    methods: {}
};
</script>

<style>
.nextDate {
    padding-top:5px;
    height: 380px;
    border-radius: 20px 20px 0px 0px;
    background-image: linear-gradient(rgba(0, 0, 0, 0.1) 0%, rgba(0,0,0,0.4) 100%), url('../assets/backgrounds/image2.webp');
}
button#nextDate {
    margin-top:35px;
    background-color:#41935a;
    color:white;
    font-size: 1.5rem;
    box-shadow: 0 8px 16px 0 rgb(60, 112, 71), 0 6px 20px 0 rgba(0,0,0,0.2);
}
</style>
