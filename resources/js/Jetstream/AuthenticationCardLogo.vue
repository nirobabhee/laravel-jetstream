<template>
    <Link :href="'/'">
       <img src="/images/300_300nirob.jpg" alt="Nitob" srcset="" class="w-10">
    </Link>
</template>

<script>
    import { defineComponent } from 'vue'
    import { Link } from '@inertiajs/inertia-vue3';

    export default defineComponent({
        components: {
            Link,
        },
    })
</script>
