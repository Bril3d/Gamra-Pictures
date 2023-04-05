<script>
export default {
    props:{
        users:Object,
    }
};
</script>

<template>
    <div
        class="bg-slate-900 flex flex-col items-center justify-center min-h-screen"
    >
        <div class="flex flex-column">
            <div class="p-4" v-for="user in users">
                {{ user.name }}
            </div>
        </div>
    </div>
</template>
