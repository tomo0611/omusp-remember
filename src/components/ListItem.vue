<script setup lang="ts">
const items =
    [
        {
            title: '阿多 信吾 (教授)',
            value: 1,
        },
        {
            title: '藤本 まなと (准教授)',
            value: 2,
        },
        {
            title: '勝間 亮 (講師)',
            value: 3,
        },
        {
            title: 'Kai Cai (教授)',
            value: 4,
        },
    ]
</script>

<template>
    <v-card class="mx-auto my-8" elevation="16" max-width="344">
        <v-card-item>
            <v-card-title>
                私は誰でしょう？
            </v-card-title>

            <v-img src="https://omusp.jp/wp-content/uploads/2022/03/ata-sensei.png" width="120px"
                class="mx-auto"></v-img>
            <v-list>
                <v-list-item-group>
                    <v-list-item v-for="item in items" :key="item.value" :value="item">
                        <v-list-item-title>{{ item.title }}</v-list-item-title>
                    </v-list-item>
                </v-list-item-group>
            </v-list>
        </v-card-item>
    </v-card>
</template>

<style scoped></style>