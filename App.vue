<template>
  <div id="app">
    <CommonHeader></CommonHeader>
    <main>
    <div class="eyecatch">
        <img class="eyecatch-img" src="assets/img-4/eyecatch.jpg" alt=""/>
        <h1>機械ではできない仕事を</h1>
        <div class="news">
          <div class="news-content">
          <p class="date">2019/01/01</p>
          <p class="news-title">ニュースタイトルがここに入ります。三月の決算報告書</p>
          </div>
          <button>news</button>
        </div>
    </div>
    <div class="mission">
      <img class="mission-img" src="assets/img-4/mission-img.jpg" alt=""/>
      <div class="mission-content">
        <h2>お客様のために進化する成長企業であり続ける</h2>
        <p>顧客主導型サービスを提供する企業として、お客様の会社経営に必要なサービスと情報を提供し続ける企業支援会社を目指します。企業が現在直面している「勝ち残るため」の戦略を提供できる会社として、ホームページをはじめ、各種マーケティングをご提供します。
        </p>
        <div class="mission-detail">
        <p>ミッション詳細</p>
        </div>
        </div>
      </div>
    <div class="service">
     <h3>service</h3>
      <img class="camera" src="assetsimg-4/service2.jpg" alt=""/>
      <div class="service-content">
        <div class="service-text">
        <h4>web制作業務</h4>
        <p>コーチングのミッション</p>
        <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります。</p>
        <button class="service-detail">サービス詳細</button>
        </div>
      </div>
    </div>
    <div class="service2">
      <img class="wave" src="assetsimg-4/service1.jpg" alt=""/>
      <div class="service-content2">
        <div class="service-text">
        <h4>web制作業務</h4>
        <p>コーチングのミッション</p>
        <p>ユーザーが求める物を分析し、ユーザビリティを備えた最適なサイトを提供。建設業から美容、ブライダル、飲食店まで多種多様な業種の制作実績があります。</p>
        <button class="service-detail">サービス詳細</button>
       </div>
      </div>
      </div>
 <div class="company-recruit">
     <div class="company">
       <img src="assets/img-4/company.jpeg" alt=""/>
       <div class="company-text">
      <h4 >company</h4>
      <p>会社概要</p>
      </div>
     </div>
     <div class="recruit">
      <img src="assets/img-4/recruit.jpg" alt=""/>
      <div class="recruit-text">
      <h4>recruit</h4>
      <p>採用情報</p>
      </div>
     </div>
    </div>
    <div class="question">
    <p class="FAQ">FAQ</p>
    <p class="q">よくある質問</p>
    </div>
    <div class="contact">
      <img class="contact-img" src="assets/img-4/contact-bg.jpg" alt=""/>
      <div class="contact-content">
      <h4>Contact</h4>
      <p class="a1">お問い合わせ</p>
      <h5>お気軽にお問い合わせください。</h5>
      <p class="a2">資料請求・あ問い合わせなどなんでも気軽にお問い合わせください。お仕事のご連絡も音いわせページに飛んでいただいて、入力フォームにご記入お願いいたします。</p>
      <button >お問い合わせへ</button>
      </div>
    </div>
  </main>
  <CommonFooter></CommonFooter>
    </div>
</template>
<script>
import CommonHeader from "components/CommonHeader";
import CommonFooter from "components/CommonFooter";
export default {
  components: {
    CommonHeader,
    CommonFooter
  }
};
</script>
<style>
html, body, div, span, object, iframe,
h1, h2, h3, h4, h5, h6, p, blockquote, pre,
abbr, address, cite, code,
del, dfn, em, img, ins, kbd, q, samp,
small, strong, sub, sup, var,
b, i,
dl, dt, dd, ol, ul, li,
fieldset, form, label, legend,
table, caption, tbody, tfoot, thead, tr, th, td,
article, aside, canvas, details, figcaption, figure,
footer, header, hgroup, menu, nav, section, summary,
time, mark, audio, video {
    margin:0;
    padding:0;
    border:0;
    outline:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

body {
    line-height:1;
}

article,aside,details,figcaption,figure,
footer,header,hgroup,menu,nav,section {
    display:block;
}

nav ul {
    list-style:none;
}

blockquote, q {
    quotes:none;
}

blockquote:before, blockquote:after,
q:before, q:after {
    content:'';
    content:none;
}

a {
    margin:0;
    padding:0;
    font-size:100%;
    vertical-align:baseline;
    background:transparent;
}

/* change colours to suit your needs */
ins {
    background-color:#ff9;
    color:#000;
    text-decoration:none;
}

/* change colours to suit your needs */
mark {
    background-color:#ff9;
    color:#000;
    font-style:italic;
    font-weight:bold;
}

del {
    text-decoration: line-through;
}

abbr[title], dfn[title] {
    border-bottom:1px dotted;
    cursor:help;
}

table {
    border-collapse:collapse;
    border-spacing:0;
}

/* change border colour to suit your needs */
hr {
    display:block;
    height:1px;
    border:0;  
    border-top:1px solid #cccccc;
    margin:1em 0;
    padding:0;
}

input, select {
    vertical-align:middle;
}
.eyecatch{
position: relative;
}
.eyecatch-img{
  width: 100%;
  height: 100%;

}
.eyecatch h1{
  color: white;
  font-size: 48px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
}
.news{
    background-color:white;
    position: absolute;
    bottom: 0;
    right: 0;
    display: flex;
    width: 50%;
    height: 60px;
    display: flex;
    justify-content: space-between;
}
.news-content p{
    font-size: 14px;
    line-height: 1.5;
}
.date{
    padding-left: 10px;
}
.news-title{
    padding-left:20px;
}
.news button{
    background-color: black;
    color: white;
    width: 150px;
    height: 60px;
}
.mission{
    background-color: black ;
    width: 100%;
    height: 500px;
    margin-top: 0;
    position: relative;
}
.mission-content{
    position: absolute;
    top: 33%;
    left: 150px;
     color:white;
     width: 60%;
     height: 40%;
     text-align: left;
}
.mission-content h2{
    font-size: 24px;

}
.mission-content p{
    padding-top: 20px;
    font-size: 14px;
    line-height: 1.5;
}
.mission-detail{
    background-color: white;
    width: 150px;
    height: 40px;
    margin-top: 20px;
    display: flex;
    justify-content: center;
    align-items: center;   
}
.mission-detail p{
 color: black;
 padding-top: 0;
 font-size: 14px;
}
.mission-img{
    width: 30%;
    position: absolute;
    bottom:0px;
    right: 10px;
}
.service{
    background-color:#f2f2f2 ;
    width: 100%;
    height: 600px;
    position: relative;
    margin-top: 100px;
}
.service h3{
    text-align: center;
    padding-top: 20px;
    font-size: 36px;
}
.camera{
    width: 50%;
    position: absolute;
    top: 70px;
    right: 0px;
}
.service-content{
    background-color: white;
    width: 40%;
    height: 200px;
    position: absolute;
    top: 30%;
    left: 200px;
}
.service-text{
text-align: left;
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%,-50%);
 width: 80%;
 height: 50%;
}
.service-detail{
    margin-left: 65%;
     margin-top: 10px;
     background-color: white;
     width: 150px;
     height: 40px;
}
.service2{
    background-color:#f2f2f2 ;
    display: flex;
    width: 100%;
    height: 600px;
    position: relative;
}
.wave{
    width: 40%;
    position: absolute;
    top: 100px;
    left: 0px; 
}
.service-content2 {
    background-color: white;
    width: 40%;
    height: 200px;
    position: absolute;
    left: 650px;
    top: 30%;
}
.company-recruit {
    display: flex;
    justify-content: space-between;
    margin-top: 120px;
}

.company{
    position:relative;
}
.company img {
   width: 650px;
   height: 300px;
    
}
.company-text{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    color: white;
}
.company-recruit h4{
    font-size: 30px;
}
.company-recruit p{
    padding-top: 10px;
}
.recruit{
    position: relative;
}
.recruit img{
    width: 650px;
    height: 300px;
}
.recruit-text{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    color: white;
}
.question{
    background-color: black;
    display: flex;
    align-items: center;
    height: 70px;
    margin: 120px;
    position: relative;
}
.FAQ{
    color: white;
    padding-left: 20px;
    font-size: 20px;
}
.q{
    color: white;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
}
.contact{
    position: relative;
    margin-bottom: 0;
}
.contact-img{
    width: 100%;
}
.contact-content{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    text-align: center;
    color: white;
    width: 85%;
}
.contact-content h4{
    font-size: 30px;
}
.a1{
    padding-top:18px
}
.contact-content h5{
    padding-top: 12px;
}
.a2{
    padding-top: 15px;
    font-size: 14px;
}
.contact-content button{
    background:rgba(0,0,0,0);
    color: white;
    font-size: 15px;
    margin-top:30px ;
}
@media screen and (max-width: 768px){
  .eyecatch-img{
    height: 600px;
}
.news{
    width: 100%;
}
.service, 
.service2{
  display: block;
}
.camera,
.wave {
    width: 100%;
    
    padding: 0;

} 
.service-content,
.service-content2{
    width: 100%;
   left: 0; 
   margin-top:200px ;
}
.company-recruit{
    display: block;
    width: 100%;
}
.company img,
.recruit img{
    width: 100%;
}
.question{
    width: 100%;
    height: 100px;
    margin:10px 0px;
}
}
</style>
