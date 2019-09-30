<template>
    <div>
        <div class="home">
            <div class="home-content">
                <EmailModal />
            </div>
        </div>
        <div class="home-section-one">
            <Headlines />
        </div>
    </div>
</template>

<script>
import EmailModal from './email-modal.vue';
import Headlines from './headlines.vue';

export default {
    components: {
        EmailModal,
        Headlines
    }
}
</script>
