<template>
    <div>
        <Opening/>
        <Reason/>
        <Tutor/>
        <StudyPack/>
    </div>
</template>

<script>
import Opening from './Opening.vue'
import Reason from './Reason.vue'
import Tutor from './Tutor.vue'
import StudyPack from './StudyPack.vue'

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
        StudyPack
    }
}
</script>

<style>

</style>