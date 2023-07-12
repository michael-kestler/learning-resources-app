<template>
    <div>
        <ul id="storedResources">
            <li v-for="resource in storedResources" :key="resource.id" :title="resource.title">
                {{title}}
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
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
