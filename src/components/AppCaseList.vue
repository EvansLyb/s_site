<template>
  <div id="app-case-list" class="px-6 py-4 bg sm:py-12 sm:px-24">
    <h2 class="text-xl font-bold text-primary sm:text-4xl">项目案例</h2>
    <!-- WSC場地預約 -->
    <div class="p-5 mt-3 bg-white rounded">
      <div class="flex flex-wrap pt-3">
        <el-image class="w-full sm:w-1/2" :src="appBookingImg" />
        <div class="flex-1 p-3 text-xl text-left">
          <h1 class="pb-5 text-2xl font-bold text-center">WSC場地預約</h1>
          <p class="mb-5">WSC場地預約APP旨在讓用戶能夠輕鬆預約球場，提供一個方便快捷的平台，讓愛好運動的人們能夠更輕鬆地享受到打球的樂趣。</p>
          <p class="mb-5">基於LBS定位技術，用戶可以輕鬆找到附近的球場，並查看球場的詳細資訊，例如價格、開放時間、場地大小、設施等。利於用戶更好地做出符合自己需求的選擇。</p>
          <p class="mb-5">APP提供了簡單又方便的預約流程。用戶只需要點擊幾個按鈕，就可以輕鬆預約心儀的球場。APP支持即時預約和提前預約，讓用戶有更多的彈性。用戶可以選擇預約一小時、兩小時甚至整天的時間，滿足不同用戶的需求。</p>
        </div>
      </div>
    </div>
    <!-- 山姆会员卡 -->
    <div class="p-5 mt-3 bg-white rounded">
      <div class="flex flex-wrap pt-3">
        <el-image class="w-full sm:w-1/2" :src="appSamsClubImg" />
        <div class="flex-1 p-3 text-xl text-left">
          <h1 class="pb-5 text-2xl font-bold text-center">山姆会员卡</h1>
          <p class="mb-5">山姆会员卡APP提供了山姆會員商店實體會員卡的電子版本。用戶可以在APP上綁定他們的會員卡號，將積分、優惠券等同步到線上，而無需攜帶實體卡片。</p>
          <p class="mb-5">該APP還提供了會員專屬的促銷活動和優惠券。用戶可以通過APP獲取到最新的促銷信息和優惠券，使用戶可以享受到更多的福利和優惠。</p>
          <p class="mb-5">此外，領燕科技為APP實現了完善的數據系統。通過對用戶數據的分析，山姆會員商店可以了解用戶的消費習慣和喜好，並根據這些數據來制定更有效的促銷策略。還可以通過分析用戶的反饋和評價來改進產品，提供更好的用戶體驗。</p>
          <p class="mb-5">領燕科技為山姆會員商店從功能、用戶體驗和數據分析等多方面來提升產品的價值和用戶滿意度。吸引更多的會員加入並提高他們對山姆會員商店的忠誠度。</p>
        </div>
      </div>
    </div>
    <!-- 珠寶商城 -->
    <div class="p-5 mt-3 bg-white rounded">
      <div class="flex flex-wrap pt-3">
        <el-image class="w-full sm:w-1/2" :src="appJewelryEcomImg" />
        <div class="flex-1 p-3 text-xl text-left">
          <h1 class="pb-5 text-2xl font-bold text-center">Pascal珠寶商城</h1>
          <p class="mb-5">領燕科技為Pascal研發的線上珠寶商城APP具有直觀且易於使用的界面設計，讓用戶可以輕鬆尋找和選購心儀的珠寶產品。APP提供了豐富的珠寶分類和搜索功能，以及詳細的產品展示頁面，讓用戶可以全面了解每款珠寶的特點、材質和價格等相關信息。</p>
          <p class="mb-5">我們與可靠的物流合作夥伴合作，提供物流追蹤功能，讓用戶隨時了解訂單的送貨進度。此外，建立了完善的售後服務系統，處理用戶的退換貨、維修和投訴等事宜，確保用戶的權益得到保護。</p>
          <p class="mb-5">除了購物功能，APP還提供了豐富的珠寶相關內容。用戶可以在APP上瀏覽珠寶的歷史和文化知識，了解不同文化中對珠寶的特殊意義和傳統，增加用戶對珠寶的情感聯繫。</p>
          <p class="mb-5"></p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Case',
  props: {
    bg: {
      type: String,
      default: 'white'
    },
    img: {
      type: String
    },
    desc: {
      type: String
    }
  },
  data() {
    return {
      appBookingImg: require('@/assets/case/app-booking.png'),
      appSamsClubImg: require('@/assets/case/app-sams-club.png'),
      appJewelryEcomImg: require('@/assets/case/app-jewelry-ecom.png'),
    }
  },
  components: {
  }
}
</script>

<style scoped>
</style>
