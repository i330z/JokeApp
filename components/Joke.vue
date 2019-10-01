<template>
    <n-link :to="'jokes/' + id">
        <div class="joke">
            <p>{{ joke }}</p>
        </div>
    </n-link>
</template>

<script>
export default {
    name: 'Joke',
    props: ['joke', 'id']
}
</script>

<style scoped>
.joke{
    padding: 1rem;
    border: 1px dotted black;
    margin: 1rem 0rem;
}
</style>