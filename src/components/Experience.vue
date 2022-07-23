<template>
  <div>
    <VueTimeline :timeline-items="timelineItems" />
  </div>
</template>

<script>
import VueTimeline from "bs-vue-timeline";

export default {
  name: "Experience",
  components: {
    VueTimeline,
  },
  data: () => ({
    timelineItems: [
      {
        from: new Date(2014, 10),
        to: new Date(),
        title: "1",
        subtitle: "公司名稱預查",
        content:
          "可以使用經濟部─公司名稱暨所營事業預查輔助查詢，輸入 1-5 個想要設立的公司名稱，可以先行確認公司名稱是否有人使用，接著經由公司與商業及有限合夥一站式線上申請作業申請名稱預查，申請後大約1~4個工作內便可收到預查核定書，確定正式公司名稱後，就可以刻印公司大章。接下來，就可以依據公司提供的服務項目或參考同業的服務項目，登記營業項目。",
        image: "microsoft.png",
      },
      {
        from: new Date(2009, 5),
        to: new Date(2013, 5),
        title: "2",
        subtitle: "營業場所土地使用分區查核辦理",
        content:
          "根據自身需要，可以自行準備或向房東索取建物謄本，下載營業場所土地使用分區管制與建築管理規定查詢表並填寫，接著拿著上述兩份文件，前往台中市商業處的都發局臨櫃，辦理營業場所土地使用分區查核。",
        image: "oracle.png",
      },
      {
        from: new Date(2000, 3),
        to: new Date(2008, 12),
        title: "3",
        subtitle: "到銀行開籌備戶",
        content:
          "選擇一間距離公司近的銀行或是任何常去的銀行，開立「○○有限公司籌備處」戶頭，負責人要記得準備公司/商業登記預查函、大小印章、雙證件。等資本額存入並申辦登記完成後，便可將銀行帳戶名稱改為正式公司名稱。",
        image: "google.png",
      },
      {
        from: new Date(2000, 3),
        to: new Date(2008, 12),
        title: "4",
        subtitle: "向會計師申請資本額驗資",
        content:
          "資本額存入三天（建議最少10萬元），備齊資料以後，通常需要找會計事務所協助。申請完存款餘額證明，便可請會計師進行資本額驗資，簽核出資本額查核簽證報告，證明公司資本的真實性。",
        image: "google.png",
      },
      {
        from: new Date(2000, 3),
        to: new Date(2008, 12),
        title: "5",
        subtitle: "公司設立申請",
        content:
          "以上四步完成後即可與房東簽約，並準備以下資料，親自至公司所在地市政府的聯合服務中心商業登記處送件申請統編和稅籍。",
        image: "google.png",
      },
      {
        from: new Date(2000, 3),
        to: new Date(2008, 12),
        title: "6",
        subtitle: "國稅局申請購票憑證",
        content:
          "接下來到國稅局申請發票憑證，大約7天拿到國稅局寄來的公文後，之後憑核准函即可前往國稅局購買發票。",
        image: "google.png",
      },
      {
        from: new Date(2000, 3),
        to: new Date(2008, 12),
        title: "7",
        subtitle: "公司籌備處戶頭轉為正式帳戶",
        content:
          "取得核准函後，記得拿大小章回銀行將籌備戶轉為正式帳戶喔! 這樣設立公司的程序就完成囉!",
        image: "google.png",
      },
    ],
  }),
};
</script>

<style>
</style>
