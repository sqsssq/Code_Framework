<!--
 * @Description: 
 * @Author: Qing Shi
 * @Date: 2022-11-20 23:25:35
 * @LastEditTime: 2022-11-21 00:48:20
-->
<template>
    <div>
        {{ msg1 }}
        {{ msgH }}
    </div>
</template>
<script>
export default {
    name: 'APP',
    props: ["msgH"],
    data () {
        return {
            msg1: "Hello, main!"
        }
    },
    methods: {
    },
    created () {
    },
    mounted () {
        console.log(111)
    },
}
</script>
<style lang="scss" scoped>

</style>
