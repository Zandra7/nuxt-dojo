<template>
    <div>
        <p>Product details for {{ id }}</p>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore hic 
        laborum quidem dicta. Reiciendis, sed ipsum eveniet sint rem fugiat.</p>
    </div>
</template>

<script setup>
    const { id } = useRoute().params

    definePageMeta({
        layout: 'products'
    })
</script>
    
<style scoped>

</style>
