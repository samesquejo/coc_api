<template>
    <div class="w-full mb-12 px-4">
        <div class="relative flex flex-col min-w-0 break-words w-full mb-6 shadow-lg rounded bg-gray-800">
            <slot />
        </div>
    </div>
</template>

<script>
export default {
    name: 'TablePanel',
}
</script>