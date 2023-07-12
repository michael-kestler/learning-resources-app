<template>
    <ul id="storedResources">
            <li v-for="resource in storedResources" :key="resource.id" :title="resource.title">
                {{title}}
            </li>
        </ul>
</template>