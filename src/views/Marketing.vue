<template>
  <div id="marketing">
    <section class="relative flex items-center justify-center w-screen banner">
      <el-image class="absolute z-0 w-screen h-full opacity-30" :src="banner" fit="cover"></el-image>
      <div class="z-10 px-8 text-xl tracking-wide text-center text-white md:px-32 sm:text-4xl">
        <h3 class="w-1/2 py-2 mx-auto text-xl border border-gray-100 border-solid">H5互動營銷</h3>
        <div class="pt-6">
          <div>營銷是品牌的主心骨，互動是營銷的催化劑</div>
          <div class="text-base sm:text-xl sm:pt-2">即刻咨詢：<a class="font-bold" href="mailto:kyle@linkendtech.com">kyle@linkendtech.com</a></div>
        </div>
      </div>
    </section>

    <section class="px-6 py-4 text-center sm:py-12 sm:px-24">
      <h1 class="text-xl font-bold text-primary sm:text-4xl">H5互動營銷</h1>
      <p class="w-4/5 pt-6 mx-auto text-left sm:text-xl"><span v-html="space"></span>品牌離不開營銷，領燕科技結合品牌元素，為各類品牌提供營銷活動頁面的設計和研發服務。H5互動營銷比起傳統的廣告投放具有自發裂變的優勢，用戶可以通過打卡或者將互動結果分享到社群媒體上，從而吸引更多的用戶參與到活動中。H5互動營銷可以收集用戶的行為數據，透過分析這些數據可以了解用戶的興趣和喜好，從而精準地進行銷售和推廣。這種數據驅動的營銷方式可以大幅提高品牌的轉換率和ROI。</p>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">尋禮遊戲</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="giftFinderImg" />
        <div class="flex-1 p-3 text-left sm:text-xl sm:pl-16">
          <p class="mb-1">領燕科技為Tiffany在2022年成功上線一個互動營銷小遊戲。在遊戲開始後，會不斷掉落著各種時尚飾品和精心挑選的詞語，飾品和詞語會受到重力的影響而移動，彷彿置於真實世界之中！遊戲也融合了品牌與節日的元素，利於用戶在互動過程中對品牌留下深刻的印象。</p>
          <p class="mb-1">尋禮遊戲為品牌與用戶之間提供了更深層次互動的機會。用戶通過選擇喜愛的詞語，將獲得一份個性化的商品推薦列表，從而不再為購買決策而猶豫不決。</p>
          <p class="mb-1">在遊戲過程中，我們也為Tiffany詳細記錄了用戶的行為數據。活動結束後通過對數據進行分析，更好地了解目標客戶的喜好和需求，為日後實行更加精準的營銷提供支援。</p>
        </div>
      </div>
    </section>

    <!-- <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">贺卡活动</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <div class="flex-1 p-3 text-left sm:text-xl sm:pr-16">
          <p class="mb-1">在活动期间</p>
          <p class="mb-1"></p>
          <p class="mb-1"></p>
        </div>
        <el-image class="w-full rounded-md digital-human-img h-fit sm:w-1/2" :src="giftCardImg" fit="cover" />
      </div>
    </section> -->

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">天天紅包</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <div class="flex-1 p-3 text-left sm:text-xl sm:pr-16">
          <p class="mb-1">紅包營銷是一種簡單而有效的策略，通過給予用戶獎勵，吸引用戶參與和推廣，從而提高品牌或產品的知名度和影響力。紅包營銷有以下作用：</p>
          <p class="mb-1">（1）拉新。基於人的天性，大部分用戶容易被免費或小利所吸引，通過紅包對用戶進行補貼，用戶獲得紅包進而產生消費行為。獲得新用戶的同時，也起到了培養用戶習慣，佔領市場份額的作用，典型的如滴滴剛崛起時發的乘客紅包。</p>
          <p class="mb-1">（2）提升轉換率。通過向目標用戶發放紅包，鼓勵用戶產生或盡快完成購買落單的行為，從而提高訂單轉換率。</p>
          <p class="mb-1">（3）促活。紅包還有一個重要的作用，提升產品的用戶活躍度。如簽到紅包、抽獎紅包等，刺激用戶持續使用產品，從而達到目的。</p>
          <p class="mb-1">（4）完成某些指標。有時候營運部門為完成某些任務和指標，亦會向用戶發放紅包，當用戶完成指定的行為之後會獲得或激活紅包。通常發生在提高註冊率、激活量、綁卡量等場景中。</p>
        </div>
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="redPacketImg" fit="cover" />
      </div>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">數據及行為分析</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="dataDashboardImg" />
        <div class="flex-1 p-3 text-left sm:text-xl sm:pl-16">
          <p class="mb-1">基於H5的互動營銷是為企業與用戶互動的重要方式。而在當今數字化時代，數據收集和用戶行為分析的重要性和優點絕不可忽視。通過數據收集，企業能夠深入了解用戶的喜好、需求和行為模式，從而更加精準地滿足用戶的期待。這種數據驅動的營銷策略讓企業能夠基於事實而非猜測來制定營銷決策。</p>
          <p class="mb-1">其次，數據收集和用戶行為分析的優點在於實現個性化營銷。通過分析用戶行為和偏好，企業可以根據不同用戶的需求和興趣進行定向推送和個性化推薦，從而提高用戶參與度和轉換率。這種精準的個性化營銷不僅能增強用戶對品牌的黏著度，還能夠提升用戶體驗，讓用戶感受到個體化的關懷。</p>
          <p class="mb-1">领燕科技以丰富的经验和专业的能力，已经成功为多个品牌定制了H5互动营销活动。我们懂得如何通过合理的数据收集方法和高效的用户行为分析手段，洞察用户需求，深入了解用户行为，从而为品牌提供最具针对性的营销解决方案。</p>
        </div>
      </div>
    </section>

    <section class="flex flex-wrap items-center py-8 bg">
      <div class="w-1/2 py-10 pl-6 text-2xl text-left text-black sm:w-2/5 sm:text-center sm:pl-0 sm:text-4xl">最新資訊</div>
      <div class="flex-1 px-6 text-left sm:pr-10 sm:pl-0">
        <!-- <div class="text-xl leading-tight text-black sm:text-4xl">We bring tech, design, data and business chops together to deliver software solutions to tens of millions of users.</div> -->
        <!-- <el-button class="mt-6">查看更多</el-button> -->
        <el-divider class="mx-auto"></el-divider>
        <div class="post-group">
          <el-card class="mt-6 border-none cursor-pointer bg" v-for="(post, i) in postList" :key="i" shadow="hover" @click.native="tapToPost(i)">
            <div class="flex">
              <el-image class="w-16 h-16" :src="post.thumbnail ? require('@/assets/post/' + post.thumbnail) : logoFinal" fit="fill"></el-image>
              <div class="flex-1 pl-6 pr-0 sm:pl-8 sm:pr-8">
                <div class="text-xl font-bold text-black sm:text-2xl" to="/post">{{post.title}}</div>
                <div class="text-sm sm:text-md">{{post.subTitle}}</div>
              </div>
            </div>
          </el-card>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import DevFlow from '@/components/DevFlow.vue'
import AppCaseList from '@/components/AppCaseList.vue'
import { postList } from '@/posts/postList'

export default {
  name: 'Marketing',
  metaInfo: {
    title: 'H5互动营销',
  },
  data() {
    return {
      banner: require('@/assets/app-banner-bg.jpg'),
      space: '&emsp;&emsp;',
      shortSpace: '&emsp;',
      giftFinderImg: require('@/assets/marketing-gift-finder.png'),
      giftCardImg: require('@/assets/marketing-gift-card.png'),
      redPacketImg: require('@/assets/marketing-red-packet.png'),
      dataDashboardImg: require('@/assets/marketing-data-dashboard.png'),
      logoFinal: require('@/assets/logo_final.png'),
      postList,
    }
  },
  components: {
    DevFlow,
    AppCaseList,
  },
  mounted () {
  },
  methods: {
    tapToPost(id) {
      this.$router.push({
        name: 'Post',
        params: {
          id
        }
      })
    }
  }
}
</script>

<style scope lang="scss">
#marketing {
  .banner {
    height: 50vh;
    background: #001847;
  }
  .h-contrast {
    height: 26rem;
  }
  .h-fit {
    height: fit-content;
  }
}
</style>
