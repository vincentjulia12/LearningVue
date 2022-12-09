<template>
    <div class="faq">
        <div class="question"><p>{{faq.question}}</p></div>
        <div class="answer"><p>{{faq.answer}}</p></div>  
    </div>
</template>

<script>
export default {
    name: "FaqComponent",
    props: ['faq', 'index'],
    mounted(){
       
    }
}
</script>

<style>

</style>