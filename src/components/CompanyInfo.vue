<template>
  <div id="contact" class="text-white">
    <div v-for="info in infoList" :key="info.icon">
      <FlexBox align="center">
        <i class="block" :class="'el-icon-' + info.icon"></i>
        <div class="pl-2">{{info.text}}</div>
      </FlexBox>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import FlexBox from '@/components/FlexBox.vue'

export default {
  name: 'Contact',
  data() {
    return {
      infoList: [
        {
          icon: 'phone-outline',
          text: '150 0203 2816'
        },
        {
          icon: 'message',
          text: 'kyle@linkendtech.com'
        },
        {
          icon: 'map-location',
          text: '广州市天河区林和中路188号附楼三楼A之E45'
        }
      ]
    }
  },
  components: {
    FlexBox
  }
}
</script>
