<template>
  <div id="aboutSection">
    <div id="aboutTitle">
      About Me
    </div>
    <div id="aboutExplain">
      北海道出身。青森県の弘前大学で化学を専攻。
      アルバイトでは大学生協で保険や家具、パソコンなどの商品を販売する。その経験で、ニーズを汲み取り、お客様の目線に立って商品を提案する重要性を学ぶ。
      大学生活を通して、チームで活動することで様々な面で良い効果をもたらすと実感する。
      大学卒業後はTeamTechに共感してシアトルコンサルティングに入社。TeamTechの浸透やITの先端技術で課題解決ができる人材を目指す。
    </div>
  </div>
</template>
<script>
export default {
}
</script>
<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+JP&display=swap');

  #aboutSection {
    display: block;
    font-family: 'Noto Sans JP', sans-serif;
    background-color: #f5f5f5;
    width: 100%;
    height: auto;
    padding-top: 45px;
    padding-bottom: 40px;
  }

  #aboutTitle {
    color: #20879f;
    font-family: 'Noto Sans JP', sans-serif;
    font-weight: bold;
    font-size: 18pt;
    text-shadow: -2px 2px 3px #808080;
  }

  #aboutExplain {
    display: inline-block;
    color: #707070;
    font-family: 'Noto Sans JP', sans-serif;
    font-size: 12pt;
    word-break: normal;
    width: 650px;
    text-align: center;
    line-height: 1.25em;
  }
</style>
