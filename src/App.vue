<template>
    <div>
        <learning-resource></learning-resource>
    </div>
</template>

<script>
    import LearningResource from './components/learning-resources/LearningResources.vue'

    export default {
        components: {
          LearningResource  
        },

        data(){
        return {
        storedResources: [
            { id: 'official-guide', 
            title: 'Official Guide',
            description: 'The official Vue.js documentation.',
            link: 'https://vuejs.org'

            },
            {
                id: 'google',
                title: 'Google',
                description: 'Learn to google...',
                link: 'https://google.com'
            }
        ]
    }
}
}
</script>
