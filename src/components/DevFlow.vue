<template>
  <div id="dev-flow" class="px-6 py-4 sm:py-12 sm:px-24">
    <div class="text-xl font-bold text-primary sm:text-4xl">服務流程</div>
    <p class="w-4/5 pt-2 mx-auto text-center sm:text-xl">專業的服務造就一流的軟件</p>
    <div class="flex flex-wrap items-center justify-around pt-6 sm:pt-10">
      <div class="flex flex-col items-center justify-center" v-for="(flow, index) in flowList" :key="index">
        <el-image class="block w-20 h-20 sm:w-24 sm:h-24" :src="flow.icon" fit="fill"></el-image>
        <div class="text-xl sm:text-2xl">{{flow.label}}</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'DevFlow',
  data() {
    return {
      flowList: [
        {
          icon: require('@/assets/icons/flow-contact.svg'),
          label: '1.初步溝通'
        },
        {
          icon: require('@/assets/icons/flow-requirements.svg'),
          label: '2.需求分析'
        },
        {
          icon: require('@/assets/icons/flow-ui-design.svg'),
          label: '3.UI設計'
        },
        {
          icon: require('@/assets/icons/flow-coding.svg'),
          label: '4.迭代開發'
        },
        {
          icon: require('@/assets/icons/flow-debug.svg'),
          label: '5.測試&優化'
        },
        {
          icon: require('@/assets/icons/flow-release.svg'),
          label: '6.上线运营'
        },
        {
          icon: require('@/assets/icons/flow-maintenance.svg'),
          label: '7.後期維護'
        }
      ]
    }
  },
  components: {
  },
  mounted () {
  },
  methods: {
  }
}
</script>

<style scope lang="scss">
</style>
