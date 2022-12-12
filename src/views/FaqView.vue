<template>
    <div class="faqs">
        <FaqComponent v-for="(faq, i) in faqs" :faq="faq" :index="i" :key="i" :open="faq.open" @toggleOpen="toggleOpen"/>
    </div>
</template>

<script>
import FaqComponent from "../components/FaqComponent.vue";
export default {
    name: 'FaqView',
    components: {FaqComponent},
    data() {
        return {
            faqs: [
                {
                    question: "What is your name? ",
                    answer: "Vincent Julia",
                    open: false
                },
                {
                    question: "Tangina ka ba?",
                    answer: "Yes",
                    open: false
                },
                {
                    question: "San ka natakatira? ",
                    answer: "Di ko alam gago",
                    open: false
                },
            ]
        }
    },
    methods: {
        toggleOpen: function(index) {
            this.faqs = this.faqs.map((faq, i) => {
                if (index === i) {
                    faq.open = !faq.open;
                } else {
                    faq.open = false;
                }

                return faq;
            });
        }
    }
}
</script>

<style>

</style>