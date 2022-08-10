<template>
    <div class="faq_block">
        <div class="faq_text">
            <div class="faq_text_center" v-on:click="slideToggle">
                <h3>
                    {{ question }}</h3>
            </div>
        </div>

        <transition name="topSlide" @before-enter="beforeEnter" @enter="enter" @before-leave="beforeLeave"
            @leave="leave">
            <div class="faq_text_sub" v-if="isActive">
                <div class="faq_text_sub_center">
                    <h4 v-html="answer">
                    </h4>
                </div>
            </div>
        </transition>
    </div>
</template>
<script>
export default {
    props: {
        question: {
            type: String
        },
        answer: {
            type: String
        },
    },
    data() {
        return {
            isActive: false,
        }
    },
    methods: {
        slideToggle() {
            this.isActive = !this.isActive;
        },
        beforeEnter(el) {
            el.style.height = '0'
        },

        enter(el) {
            el.style.height = el.scrollHeight + 'px'
        },

        beforeLeave(el) {
            el.style.height = el.scrollHeight + 'px'
        },

        leave(el) {
            el.style.height = '0'
        },
    }
}
</script>

<style>
.topSlide {
    transition: height 0.3s ease-in-out;
    overflow: hidden;
}

.topSlide-enter-active {
    animation-duration: 0.3s;
    animation-fill-mode: both;
}

.topSlide-leave-active {
    animation-duration: 0.3s;
    animation-fill-mode: both;
}
</style>