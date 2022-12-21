<template>
    <div :class=" open ? 'faq open' : 'faq'" @click ="$emit('toggleOpen', index)">
        <div class="question"><p class="question">{{faq.question}}</p></div>
        <div class="answer text-muted"><p class="answer text-muted">{{faq.answer}}</p></div>  
    </div>
</template>

<script>
export default {
    name: "FaqComponent",
    props: ['faq', 'index', 'open']
}
</script>

<style>

</style>

