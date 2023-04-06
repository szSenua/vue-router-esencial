<template>
    <a :href="dest">{{ name }}</a>
</template>

<script>
export default {
    name: 'RouterLink',

    props: {
        name: {
            type: String,
            required: true
        },
        dest: {
            type: String,
            required: true
        }
    }
}
</script>