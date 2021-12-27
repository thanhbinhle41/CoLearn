<template>
    <div>
        <Opening/>
        <Reason/>
        <Tutor/>
        <StudyPack/>
        <SignUpForm/>
    </div>
</template>

<script>
import Opening from './Opening.vue'
import Reason from './Reason.vue'
import Tutor from './Tutor.vue'
import StudyPack from './StudyPack.vue'
import SignUpForm from './SignUpForm.vue' 

export default {
    name: 'Body',
    data () {
        return {
        
        }
    }, 
    components: {
        Opening,
        Reason,
        Tutor,
        StudyPack,
        SignUpForm
    }
}
</script>

<style>

</style>