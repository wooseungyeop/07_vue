<script setup>
import {useRouter} from "vue-router";

const router = useRouter();
</script>

<template>
    <div>
        <h3>nested Home</h3>
        <button @click="()=> router.push('nested/hidden')">숨긴화면</button>
        <button @clcik="()=> router.go(1)">앞으로 가기</button>
    </div>
</template>