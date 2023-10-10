<template>
  <div id="why-us" class="px-6 py-4 bg sm:py-12 sm:px-24">
    <div class="text-xl font-bold text-primary sm:text-4xl">選擇我們</div>
    <p class="w-4/5 pt-2 mx-auto text-center sm:text-xl">以客戶為中心，為企業保駕護航</p>
    <div class="flex flex-wrap items-center justify-around pt-6 sm:pt-10">
      <el-card
        class="flex flex-col w-64 mb-6 overflow-visible h-80"
        body-style="padding: 20px 0;"
        v-for="(flow, index) in dataList"
        :key="index"
      >
        <div class="flex items-center w-full px-2 py-3 transform -translate-x-4 shadow-lg bg-primary rounded-r-md">
          <div class="text-5xl text-gray-100 sm:text-6xl">{{index}}</div>
          <div class="flex-1 pl-3 text-2xl text-left text-white transform translate-y-1 sm:text-4xl">{{flow.label}}</div>
        </div>
        <div class="pt-12">
          <div class="text-xl font-bold text-gray-700">{{flow.desc}}</div>
          <div class="pt-2 text-xl">{{flow.subDesc}}</div>
        </div>
      </el-card>
    </div>
  </div>
</template>

<script>
export default {
  name: 'WhyUs',
  data() {
    return {
      dataList: [
        {
          label: '專業人員',
          desc: '10年以上技術團隊',
          subDesc: '實力雄厚'
        },
        {
          label: '經驗豐富',
          desc: '80+行業應用解決方案',
          subDesc: '供你選擇'
        },
        {
          label: '貼心服務',
          desc: '1對1專人對接需求',
          subDesc: '溝通無阻'
        },
        {
          label: '工匠精神',
          desc: '把握每一個細節',
          subDesc: '精益求精'
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
