<template>
    <li>{{ name }}?!</li>
</template>

<script>
export default {
    props: {
        name: {
            type: String,
            default: ""
        }
    }
}
</script>

<style scoped lang="scss"> // scoped: 유효범위, 이 속성 추가 하면 style이 여기만 적용됨
    h1 {
        color: red;
    }
</style>
