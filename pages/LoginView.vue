<template>
    <div>
        <login-wrapper></login-wrapper>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import LoginWrapper from '~/components/organisms/LoginWrapper.vue'
export default defineComponent({
  components: { LoginWrapper },
    name: 'LoginView',
    setup () {
        return {}
    }
})
</script>

<style scoped>

</style>