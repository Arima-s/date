# note
workdate

the second day 
  i fell not good

i dont know how long
<!DOCTYPE html>
<html lang="zh-cn" class="ski-detail-html">
<head>
  <link rel="import" href="part/meta.html?__inline">
  <link rel="shortcut icon" href="../static/favicon.ico">
  <title>滑雪场</title>
  <link rel="import" href="part/css.html?__inline">
  <style>
    /* reset */
    body,
    h1,
    h2,
    h3,
    h4,
    h5,
    h6,
    hr,
    p,
    blockquote,
    dl,
    dt,
    dd,
    ul,
    ol,
    li,
    pre,
    form,
    fieldset,
    legend,
    button,
    input,
    textarea,
    th,
    td {
      margin: 0;
      padding: 0;
    }
    ul,
    ol {
      list-style: none;
    }
    a {
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    sup {
      vertical-align: text-top;
    }
    sub {
      vertical-align: text-bottom;
    }
    legend {
      color: #000;
    }
    fieldset,
    img {
      border: 0;
    }
    button,
    input,
    select,
    textarea {
      font-size: 100%;
    }
    table {
      border-collapse: collapse;
      border-spacing: 0;
    }
    img {
      border: none;
    }
    .ski-detail-html {
      font-size: 62.5%;
      width: 100%;
      height: 100%;
    }
    .ski-detail-body {
      width: 100%;
      height: 100%;
      overflow: auto;
      background: #ffffff;
      font-family: "Microsoft YaHei", Arial, Helvetica, sans-serif;
    }
    /* com-style */
    .fl {
      float: left;
    }
    .fr {
      float: right;
    }
    .clear {
      clear: both;
    }
    .ckearfix:after {
      visibility: hidden;
      display: block;
      font-size: 0;
      content: "";
      clear: both;
      height: 0;
    }
    .ski-detail-header {
      width: 100%;
      /* height: 8.5rem; */
      background-color: #cc9;
      position: relative;
    }
    .ski-detail-tag {
      width: 25%;
      position: absolute;
      top: 0.5rem;
      left: 0.5rem;
    }
    .ski-detail-tag p {
      width: ;
      padding: 2px 3px;
      margin: 1px 0;
      background-color: #fff;
      text-align: center;
      color: #000;
    }
    .ski-name-container {
      text-align: center;
      padding-top: 5px;
    }
    .ski-name-container h1 {
      font-weight: normal;
      padding: 4px 0;
    }
    .point-container {
      padding: 2px 0;
    }
    .point-container ul li {
      float: left;
      width: 5px;
      height: 5px;
      background-color: red;
    }
    .point-container a {
      color: #000;
    }
    .point-container a:hover {
      color: blue;
    }
    .ski-addr-p {
      color: #69c;
    }
    .ski-pic {
      position: relative;
      height:8rem;
    }
    .swiper-container {
      width: 100%;
      height: 100%;
    }
    .swiper-slide {
      width:33%;
      height: 100%;
      text-align: center;
      font-size: 18px;
      background: #fff;

      /* Center slide text vertically */
      display: -webkit-box;
      display: -ms-flexbox;
      display: -webkit-flex;
      display: flex;
      -webkit-box-pack: center;
      -ms-flex-pack: center;
      -webkit-justify-content: center;
      justify-content: center;
      -webkit-box-align: center;
      -ms-flex-align: center;
      -webkit-align-items: center;
      align-items: center;
    }

    /* .ski-pic-container{
        position:absolute;
        left:0;
        top:0;
    } */
   /* .swiper-slide{
      width: 33%;
      height:8rem;
      float: left;
    }*/
    .ski-detail-pic-ul {
      width: 100%;
      height: 11rem;
      padding-left: 2px;
    }
    .ski-detail-pic-ul li {
      float: left;
      width: 33%;
      height: 100%;
      border: 1px solid white;
    }
    .ski-detail-pic-ul li img {
      width: 100%;
      height: 100%;
    }
    .arrow {
      cursor: pointer;
      line-height: 40px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
      width: 40px;
      height: 40px;
      position: absolute;
      z-index: 2;
      top: 50px;
      background-color: rgba(0, 0, 0, 0.3);
      color: #fff;
    }
    .arrow:hover {
      background-color: rgba(0, 0, 0, 0.7);
      text-decoration: none;
    }
    #ski-prev {
      left: 20px;
    }
    #ski-next {
      right: 20px;
    }
    .info {
      padding: 5px 2rem;
      background-color:;
    }
    .info-panel ul li {
      border: 1px solid #c96;
      padding: 0.5rem 2rem;
      margin: 1px 0;
    }
    .info-more {
      text-align: center;
      font-size: 1.4rem;
    }
    .info-more a {
      text-decoration: none;
      color: #c63;
    }
    .info-more a span {
      color: #366;
    }
    .info-tab {
      min-height:20rem;
      -margin-top: 1rem;
    }

    .dis {
      width: 100%;
      min-height: 27rem;
      padding: 0.5rem 1rem;
      position: relative;
    }
    .star {
      position: relative;
      width: 100%;
      margin: 0 auto;
      -background-color: orange;
    }
    .star ul,
    .star span {
      float: left;
      display: block;
      height: 1.9rem;
      line-height: 1.9rem;
    }
    .star ul {
      margin: 0 10px;
    }
    .star li {
      float: left;
      width: 2.4rem;
      cursor: pointer;
      text-indent: -9999px;
      background: url(../lib/img/star.png) no-repeat;
    }
    .star li.on {
      background-position: 0 -28px;
    }
    .star strong {
      color: #f60;
      padding-left: 1rem;
    }
    .star p {
      position: absolute;
      top: 2rem;
      width: 15.9rem;
      height: 6rem;
      display: none;
      background: url(../lib/img/icon.gif) no-repeat;
      padding: 0.7rem 1rem 0;
    }
    .star p em {
      color: #f60;
      display: block;
      font-style: normal;
    }
    .star .star-btn {
      width: 4rem;
      padding: 1px 3px;
      display: block;
      background-color: #d15646;
      color: #fff;
      -webkit-border-radius: 8px;
      text-align: center;
      line-height: 22px;
    }
    .dis-ul li {
      display: block;
      width: 100%;
    }
    .dis-input {
      width: 100%;
      position: absolute;
      bottom: 1rem;
      left: 0.2rem;
    }
    .Say-mess {
      width: 65%;
      border: 1px solid red;
      padding: 2px 3px;
      position: absolute;
      bottom: 1rem;
      left: 1rem;
      -webkit-border-radius: 5px;
    }
    .Sub-mess {
      width: 20%;
      padding: 2px 3px;
      background-color: #d15646;
      color: #fff;
      position: absolute;
      bottom: 1rem;
      right: 1.5rem;
      -webkit-border-radius: 5px;
    }
    .swiper-slide img{
      width:100%;
      height:100%;
    }


  </style>
</head>
<body class="ski-detail-body">


<!--
<div class="page bk-grey" id="page-skifield-list" data-title="滑雪场">
  <input type="hidden" id="wechat-jsapi-timestamp" value="${timestamp}">
  <input type="hidden" id="wechat-appid" value="${appId}">
  <input type="hidden" id="wechat-nonceStr" value="${nonceStr}">
  <input type="hidden" id="wechat-signature" value="${signature}">
</div>
-->


<header class="ski-detail-header">
  <div class="ski-detail-tag">
    <p class="sk-tag">雪道车</p>
    <p class="sk-tag">雪道车</p>
    <p class="sk-tag">雪道车的狗</p>
  </div>
  <div class="ski-name-container">
    <h1 class="ski-name">南山滑雪场</h1>
    <div class="point-container">
      <div id="default-point">
        <img src="http://image.huaxuezoo.com/image/c684854ad44848f8bd931ef024ff297f" alt="1" title="bad">&nbsp;
        <img src="http://image.huaxuezoo.com/image/c684854ad44848f8bd931ef024ff297f" alt="2" title="poor">&nbsp;
        <img src="http://image.huaxuezoo.com/image/c684854ad44848f8bd931ef024ff297f" alt="3" title="regular">&nbsp;
        <img src="http://image.huaxuezoo.com/image/c684854ad44848f8bd931ef024ff297f" alt="4" title="good">&nbsp;
        <img src="http://image.huaxuezoo.com/image/f5aab9195112416f9d3069160638304b" alt="5" title="gorgeous">
      </div>
      <a href="tel:010:8888888" class="tel">Tel: 010:8888888</a>
    </div>
    <div class="ski-addr">
      <p class="ski-addr-p">北京市朝阳区红领巾公园门口</p>
    </div>
  </div>
</header>
<section class="ski-pic">


  <div class="swiper-container">
    <div class="swiper-wrapper">
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i1/TB1n3rZHFXXXXX9XFXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i4/TB10rkPGVXXXXXGapXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i1/TB1kQI3HpXXXXbSXFXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i1/TB1n3rZHFXXXXX9XFXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i4/TB10rkPGVXXXXXGapXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i1/TB1kQI3HpXXXXbSXFXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i1/TB1n3rZHFXXXXX9XFXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i4/TB10rkPGVXXXXXGapXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="//gqianniu.alicdn.com/bao/uploaded/i4//tfscom/i1/TB1kQI3HpXXXXbSXFXXXXXXXXXX_!!0-item_pic.jpg_320x320q60.jpg" alt="">
      </div>

    </div>

    <div class="swiper-pagination"></div>
  </div>


</section>
<div class="clear"></div>
<section class="info">
  <div class="info-panel">
    <ul>
      <li>
        <p class="info-base">
          <span>平日全天雪票</span>
          <span class="fr">￥:125</span>
        </p>
      </li>
    </ul>
    <div class="hd-info" id="hd-info" style="display:none;">
      <ul>
        <li>
          <p class="info-base">
            <span>平日全天雪票</span>
            <span class="fr">￥:125</span>
          </p>
        </li>
      </ul>
      <ul>
        <li>
          <p class="info-base">
            <span>平日全天雪票</span>
            <span class="fr">￥:125</span>
          </p>
        </li>
      </ul>
    </div>

    <p class="info-more" >
      <a href="javascript:;"  id="info-more" class="btn-slide">更多优惠<span>(点击查看)</span></a>
    </p>
  </div>
</section>
<section class="info-tab">
  <div class="content" style="position: static">
    <div class="buttons-tab">
      <a href="#tab1" class="tab-link active button">雪场简介</a>
      <a href="#tab2" class="tab-link button">雪道设施</a>
      <a href="#tab3" class="tab-link button">雪场食宿</a>
      <a href="#tab4" class="tab-link button">雪友评论</a>
    </div>
    <div class="content-block">
      <div class="tabs">
        <div id="tab1" class="tab active">
          <div class="content-block" style="margin:0 0;">
            <p>This is tab 1 content</p>
            <ul>
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>5</li>
              <li>6</li>
              <li>7</li>
              <li>8</li>
              <li>9</li>
              <li>10</li>
              <li>1</li>
              <li>2</li>
              <li>3</li>
              <li>4</li>
              <li>2</li>
              <li>1</li>
              <li>2</li>
              <li>1</li>
              <li>1</li>
              <li>5</li>
            </ul>
          </div>
        </div>
        <div id="tab2" class="tab">
          <div class="content-block"style="margin:0 0;">
            <p>This is tab 2 content</p>
          </div>
        </div>
        <div id="tab3" class="tab">
          <div class="content-block"style="margin:0 0;">
            <p>This is tab 3 content</p>
          </div>
        </div>
        <div id="tab4" class="tab">
          <div class="content-block"style="margin:0 0;">
            <p>This is tab 4 content</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<section class="news"></section>
<footer class="adv"></footer>


<link rel="import" href="part/js.html?__inline">
<link rel="import" href="part/template.html?__inline">
<script type="text/javascript" src="http://apps.bdimg.com/libs/jquery/2.1.4/jquery.min.js"></script>
<script type="text/javascript">

  $(function() {
    //加载更多;
    var TR = true;
    $('#info-more').on('click',function(){
      if(TR){
        $('#hd-info').css('display','block');
        TR = false;
      }else{
        $('#hd-info').css('display','none');
        TR = true;
      }
    });

    $('#info-more').css('background-color', '#369');

    $(".swiper-container").swiper({
      pagination: '.swiper-pagination',
      slidesPerView: 3,
      paginationClickable: true,
      spaceBetween: 5
    });

   /* var swiper = new Swiper('.swiper-container', {
      pagination: '.swiper-pagination',
      slidesPerView: 3,
      paginationClickable: true,
      spaceBetween: 30
    });*/
  });
</script>
</body>
</html>
