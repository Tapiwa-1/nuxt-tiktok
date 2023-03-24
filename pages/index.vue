<template>
    <MainLayout>
        <div class="pt-[80px] w-[calc(100%-90px)] max-w-[690px]">
            <!-- <div v-for="post in $generalStore.posts" :key="post">
                <PostMain v-if="post" :post="post" />
            </div> -->
             <PostMain/>
        </div>
    </MainLayout>
</template>

<script setup>
import MainLayout from '~/layouts/MainLayout.vue'
</script>