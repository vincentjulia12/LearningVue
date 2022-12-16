<template>
    <div class="faqs ">
        <div class="text-muted">
            <h6>Sample Faqs</h6>
        </div>
        <div>
            <FaqComponent v-for="(faq, i) in faqs" :faq="faq" :index="i" :key="i" :open="faq.open" @toggleOpen="toggleOpen"/>
        </div>
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
                    answer: "asda sdasd asda sdasdas dasd asda sdasd asd asd asda sd asda sdasasd asdasd asdasd asd asd asdas dasd asda sdas asd asdasdas dasd a",
                    open: false
                },
                {
                    question: "Tangina ka ba?",
                    answer: "a sdas dasdas dakmsd kasmdla smlfejr wemrwer wmskdsdfpskd pfkpkwepfk wkflsdfls,d pfkwefsdf;,sdf,s ldfsdlmfsdmf weofsmdfdmfkswefn sdf sdkn",
                    open: false
                },
                {
                    question: "Sino ka ba? ",
                    answer: "twinkle",
                    open: false
                },
                {
                    question: "favorite movie? ",
                    answer: "kantutan dsfsndj fnsdfj sdfs dfsdfs dfksdnk fnsdkfn skdnfsdfksldfslkdnfksldnf ksldnfsdfsd[sdf ksdfwepfj sdfjsdfjwf sdfos[df sdf sd[[sdfjs dfsdjfssd fsjdifskdjsdgosodf vincent julia 12 alam ko vovo kaasd asda]]]]",
                    open: false
                },
                {
                    question: "sdasdasdasasd? ",
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

<!-- try -->