<template>
  <div class="mx-auto" style="max-width: 1050px">
    <header>
      <el-popover placement="bottom-start" width="400" trigger="click">
        <div>
            <ul class="grid grid-cols-6 gap-4">
                <li></li>
            </ul>
        </div>
        <el-button slot="reference" plain size="mini" round>全部视频</el-button>
      </el-popover>
    </header>
  </div>
</template>

<script>
export default {
    data() {
        return {
            videoList: []
        }
    },
    methods: {
        // 获取全部视频列表
        async getVideoTimelineAll() {
            // const res = await this.$api.getVideoTimelineAll();

        }
    },
}
</script>

<style scoped>
</style>