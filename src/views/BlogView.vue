<template>
    <h1>Blog section</h1>
    <ul>
        <li>
            <router-link :to="{name:'post', params:{id:1}}">Post 1</router-link>
        </li>
        <li>
            <router-link :to="{name:'post', params:{id:2}}">Post 2</router-link>
        </li>
        <li>
            <router-link :to="{name:'post', params:{id:3}}">Post 3</router-link>
        </li>
        <li>
            <router-link :to="{name:'post', params:{id:4}}">Post 4</router-link>
        </li>
    </ul>
</template>