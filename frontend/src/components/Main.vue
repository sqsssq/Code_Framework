<!--
 * @Description: 
 * @Author: Qing Shi
 * @Date: 2022-11-20 23:25:35
 * @LastEditTime: 2022-11-22 17:19:07
-->
<template>
    <div>
        {{ msg1 }}
        {{ msgH }}
    </div>
</template>
<script>
import { dataService } from '@/service'
export default {
    name: 'APP',
    props: ["msgH"],
    data() {
        return {
            msg1: "Hello, main!"
        }
    },
    methods: {
    },
    created() {
    },
    mounted() {
    },
}
</script>
<style lang="scss" scoped>

</style>
