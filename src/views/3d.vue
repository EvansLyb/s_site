<template>
  <div id="id-3d">
    <section class="relative flex items-center justify-center w-screen banner">
      <el-image class="absolute z-0 w-screen h-full opacity-50 el-img-object-top" :src="banner" fit="cover"></el-image>
      <div class="z-10 px-8 text-xl tracking-wide text-center text-white md:px-32 sm:text-4xl">
        <h3 class="w-1/2 py-2 mx-auto text-xl border border-gray-100 border-solid">3D應用研發</h3>
        <div class="pt-6">
          <div>為未來賦能</div>
          <div class="text-base sm:text-xl sm:pt-2">即刻咨詢：<a class="font-bold" href="mailto:kyle@linkendtech.com">kyle@linkendtech.com</a></div>
        </div>
      </div>
    </section>

    <section class="px-6 py-4 text-center sm:py-12 sm:px-24">
      <h1 class="text-xl font-bold text-primary sm:text-4xl">3D應用研發</h1>
      <p class="w-4/5 pt-6 mx-auto text-left sm:text-xl"><span v-html="space"></span>3D應用研發涉及多個技術領域，如計算機圖形學、計算機視覺、虛擬實境等。領燕科技掌握各種建模工具和渲染引擎，幫助客戶創造出逼真的立體場景、角色、特效等。</p>
      <p class="w-4/5 pt-1 mx-auto text-left sm:text-xl"><span v-html="space"></span>同時，3D技術在各行各業中都有著廣泛的應用。例如，在直播產業中，結合AI誕生了數字人，為主播帶來更豐富的內容與玩法；在建築和工程領域，幫助設計師和工程師更好地視覺化和模擬建築項目；在醫學領域 ，可以用來進行解剖學教學、手術模擬等。</p>
      <p class="w-4/5 pt-1 mx-auto text-left sm:text-xl"><span v-html="space"></span>隨著虛擬現實和人工智能的發展，領燕科技透過豐富的行業知識和多年的技術沉澱與3D相結合，創造出更智能和具現的應用，為以前我們只能在電影中看到的場景帶來了落地的可能性。</p>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">研發流程</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="serviceProcessImg" />
        <div class="flex-1 p-3 text-left sm:text-xl sm:pl-16">
          <p class="mb-5 font-bold">廣州領燕科技致力於為客戶提供高質量的3D應用研發服務</p>
          <li class="mb-1">我們透過深入溝通了解客戶的需求，以確保全面理解最終的目標。</li>
          <li class="mb-1">我們針對特定的場景提供合適的採樣方案，以低成本還原模型的輪廓和材質。</li>
          <li class="mb-1">我們使用先進技術和工具保證模型的準確性和細節。</li>
          <li class="mb-1">我們為模型添加逼真的光線和材質效果進行渲染，增強應用視覺吸引力。</li>
          <li class="mb-1">我們著重視覺呈現、操作方式、互動反饋等多方面因素，實現流暢和優秀的使用體驗。</li>
          <li class="mb-1">我們確保應用無縫接入系統，兼容性穩定性完整。</li>
        </div>
      </div>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">数字人</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <div class="flex-1 p-3 text-left sm:text-xl sm:pr-16">
          <p class="mb-1">数字人（Digital Human）是指透過程序生成的虛擬人物，他們擁有逼真的外貌、表情、動作和語音，幾乎可以與真實人類無異。數字人技術是3D、计算机圖形学、人工智能和機器學習等技術的結合，透過对人類外觀、動作和語音的模擬，創造出外觀和行為上都與真實人類相似的虛擬角色。</p>
          <p class="mb-1">數字人技術的發展使得虛擬角色在直播、遊戲、廣告和虛擬现实應用等領域中得以廣泛應用。數字人在直播中作為虛擬主播，具備低成本、24小時不間斷的特點；在電影和動畫中扮演角色，代替真實演員進行表演；在廣告中作為代言人，吸引觀眾的注意。</p>
          <p>目前騰訊、阿里、百度、華為等多家雲端服務商已相繼推出數位人底層服務，領燕科技與多家雲端廠商合作，為客戶提供成熟的數字人應用技術方案與接入研發服務。</p>
        </div>
        <el-image class="w-full rounded-md digital-human-img h-fit sm:w-1/2" :src="digitalHumanImg" fit="cover" />
      </div>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">AR/VR/MR</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="arMarketing" />
        <div class="flex-1 p-3 text-left sm:text-xl sm:pl-16">
          <p class="mb-1">領燕科技幫助Burberry研發的AR营销應用將虛擬商品投入到真實環境中。透過此AR應用，消費者可以直接在真实環境中查看虛擬商品的樣式、顏色、尺寸等，更可以透過手勢互動近距離觀察商品的精美細節，更準確地解商品，深度還原了線下的購物體驗。此外，AR購物還可以為消費者提供更多的商品資訊和推薦，例如價格、評論、相關商品等，為商家提供了更多的推廣和銷售機會，可以吸引更多的消費者並提高購買率 。</p>
          <p class="mb-1">除了AR應用，領燕科技針對VR和MR也進行了充分的行业研究與研發試驗，力求為客戶提供專業的諮詢方案。AR/VR/MR的應用前景非常廣闊，隨著相關技術的不斷發展與普及，基於視覺、3D視覺化與感測技術，虛擬世界與現實世界的相互融合將成為未來的重要趨勢之一。</p>
        </div>
      </div>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">智慧行業/數字孿生</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <div class="flex-1 p-3 text-left sm:text-xl sm:pr-16">
          <p class="mb-1">數字孿生是基於WebGL+3D視覺化技術建構的3D模擬工廠、樓宇、園區等真實場景，把錯綜複雜的圖紙、資料以三維虛擬數字整體復刻的形式展現給管理員，對於所要展示的數據視覺化內容還原出真實場景，並即時接入數據，從更高維度來運籌帷幄，管理決策、交互互動展示。</p>
          <p>相較於與傳統的平面展示，數字孿生具備：（1）實時性：數字孿生能夠實時地反映現實世界的狀態與變化。透過與實際物體或系統的連接，可以實時更新和呈現數據，並即時反饋變化。（2）交互性：數字孿生允許使用者與虛擬模型進行交互，透過手勢、觸控等方式來探索和操作模型。使用者可以對模型進行靈活的操作，以獲取更詳細的信息。（3）多維度展示：數字孿生可以同時展示多個維度的數據，如空間維度、時間維度、屬性維度等。透過將不同維度的數據進行視覺化，可以更全面地了解和分析模型。（4）可視化分析：領燕科技為數字孿生提供了豐富的分析工具和功能。使管理員可以透過可視化手段來發現模式、趨勢和異常，從而做出更準確的決策。</p>
        </div>
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="screenImg" fit="cover" />
      </div>
    </section>

    <section class="px-6 py-4 text-center bg sm:py-12 sm:px-24">
      <h2 class="text-xl font-bold text-primary sm:text-4xl">元宇宙</h2>
      <div class="flex flex-wrap items-center pt-6 sm:text-center">
        <el-image class="w-full rounded-md h-fit sm:w-1/2" :src="metaverseImg" />
        <div class="flex-1 p-3 text-left sm:text-xl sm:pl-16">
          <p class="mb-1">元宇宙（Metaverse）是一個虛擬的、與現實世界相互連接的數字世界。它是一種由多個虛擬現實、增強現實和混合現實空間組成的網絡，用戶可以透過數字身分在其中進行互動、探索和創造。</p>
          <p class="mb-1">在元宇宙中，用戶可以自由地探索各種虛擬環境，與其他用戶交流、合作或競爭，還可以參與各種虛擬活動，如購物、娛樂、教育、工作等。元宇宙為使用者提供獨一無二的數字化身，讓他們可以在虛擬世界中展現自己的興趣、才能和個性。同時，元宇宙也為企業和創作者提供了全新的商機和創意發揮空間，例如在其中創造和銷售各種虛擬產品和服務。</p>
          <p>目前，有科技巨頭和創業公司已經開始投資和開發元宇宙技術，以實現這一概念的商業化。元宇宙被認為是下一代互聯網的演進方向，有望成為一個全新的數字化社交和經濟系統。</p>
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
import { postList } from '@/posts/postList'

export default {
  name: '3d',
  metaInfo: {
    title: '3D應用研發',
  },
  data() {
    return {
      banner: require('@/assets/3d-banner-bg.jpg'),
      space: '&emsp;&emsp;',
      logoFinal: require('@/assets/logo_final.png'),
      serviceProcessImg: require('@/assets/3d-service-process-hk.png'),
      digitalHumanImg: require('@/assets/3d-digital-human-hk.png'),
      arMarketing: require('@/assets/3d-ar-marketing.png'),
      screenImg: require('@/assets/3d-screen.png'),
      metaverseImg: require('@/assets/3d-metaverse.webp'),
      postList,
      shadow: 0
    }
  },
  components: {
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
#id-3d {
  .banner {
    height: 50vh;
    background: #001847;
    .el-img-object-top {
      img {
        object-position: top;
      }
    }
  }
  .h-contrast {
    height: 26rem;
  }
  .h-fit {
    height: fit-content;
  }
  .digital-human-img {
    img {
      transform: scale(1.05);
    }
  }
}
</style>
