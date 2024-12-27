<script setup>
defineProps({
    message: {
        type: String,
    },
});
</script>

<template>
    <div v-show="message" class="text-sm text-danger">
        
            {{ message }}
      
    </div>
</template>
