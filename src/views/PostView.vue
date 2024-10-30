<template>  
    <h1> Post View {{ routeId }} </h1>
</template>


<script setup>
    import { ref, onMounted } from 'vue';
    import { useRoute } from 'vue-router';

    let routeId = ref('');

    onMounted(()=>{
        const route = useRoute();
        routeId.value = route.params.id;
    })

</script>