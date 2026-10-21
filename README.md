# 20261021_utsunomiya
<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #fffafa;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20261021_utsunomiya/20261021_00032.jpeg) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}


.media-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
}

.responsive-media {
  width: 100%;
  display: block;
}

.youtube-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9比率 */
  height: 0;
}

.youtube-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}





/* オープニング画面のスタイリング（写真を表示するように変更） */
#splash {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-color: #000000; /* 読み込み前の万一の背景（黒） */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  z-index: 9999; /* 最前面に表示 */
  opacity: 1;
  visibility: visible;
  transition: opacity 0.8s ease, visibility 0.8s ease; /* 0.8秒かけてふわっと消える */
  padding: 20px;
  box-sizing: border-box;
}

.splash-content {
  max-width: 800px;
  width: 100%;
  text-align: center;
}

.splash-content img {
  width: 100%;
  height: auto;
  max-height: 75vh;
  object-fit: contain;
  box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  border-radius: 4px;
}

.splash-text {
  color: #fff;
  margin-top: 15px;
  font-size: 1.2em;
}

/* 読み込み完了後に付与するクラス（非表示状態） */
#splash.loaded {
  opacity: 0;
  visibility: hidden;
}

/* メインコンテンツ */
#container {
  opacity: 1;
}




/* --- スクロールでズームインしながら浮き出るアニメーション --- */
.scroll-fade {
  opacity: 0;
  transform: translateY(40px) scale(0.85); /* 最初は少し下にいて、サイズも少し縮小（0.85倍）しておく */
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: opacity, transform;
}

/* 画面内に入ったときに、元のサイズ・透明度になりながらズームイン・アップする */
.scroll-fade.is-show {
  opacity: 1;
  transform: translateY(0) scale(1); /* 通常のサイズ・位置に戻る（ズームイン） */
}



</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>

<!-- オープニング（スプラッシュ画面に写真とタイトルを配置） -->
<div id="splash">
  <div class="splash-content">
    <img src="20261021_00003.jpeg" alt="オープニング画像">
    <div class="splash-text">最初の一枚はご近所の薔薇</div>
  </div>
</div>

<!-- メインコンテンツ -->
<div id="container">
  <h1>メインのホームページ画像</h1>
  <p><a href="20261021_00003.jpeg" target="_blank"><img src="20261021_00003.jpeg" alt="サンプル画像" class="responsive-media"></a></p>
</div>



<!--
    <p><a href="https://peyng.github.io/restart/">前回までの記録</a>><a><span class="grey">今回2026,05,28</span></a></p>
-->


<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
背景画像の横方向がご覧頂けます。
</p>


<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="QR_2026Oct21.png" alt="アクセス用QRコード" width="100">QR for Access</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~alis</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="left">!!! 2026/10/21、ご近所のお花達から、ペットショップのワンちゃん達とお花屋さんのサボテンまで !!!</marquee></span></h1>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<!--ここから下が、本体部分-->


<div class="media-container">

<h2><span class="yellow">2026Oct20、ご近所のコスモスが見事に満開</span></h2>
<a href="20261021_00001.jpeg" target="_blank"><img src="20261021_00001.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00002.jpeg" target="_blank"><img src="20261021_00002.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">薔薇の花は雨に濡れてしっとり</span></h2>
<a href="20261021_00003.jpeg" target="_blank"><img src="20261021_00003.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">キダチチョウセンアサガオも巨大な花を咲かせてニッコリ</span></h2>
<a href="20261021_00004.jpeg" target="_blank"><img src="20261021_00004.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00005.jpeg" target="_blank"><img src="20261021_00005.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00006.jpeg" target="_blank"><img src="20261021_00006.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">玄関先のゼラニウムのお花が鮮やか</span></h2>
<a href="20261021_00007.jpeg" target="_blank"><img src="20261021_00007.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00008.jpeg" target="_blank"><img src="20261021_00008.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">公園横の大先輩のお宅で、庭のお手入れ。葉っぱの処理で清掃車が来てました！</span></h2>
<a href="20261021_00009.jpeg" target="_blank"><img src="20261021_00009.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00010.jpeg" target="_blank"><img src="20261021_00010.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00011.jpeg" target="_blank"><img src="20261021_00011.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">庭にアゲハ蝶の幼虫が居ました</span></h2>
<a href="20261021_00012.jpeg" target="_blank"><img src="20261021_00012.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">ベルモールのペットショップ、ワンちゃん達の瞳がパッチリ</span></h2>
<a href="20261021_00013.jpeg" target="_blank"><img src="20261021_00013.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00014.jpeg" target="_blank"><img src="20261021_00014.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00015.jpeg" target="_blank"><img src="20261021_00015.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00016.jpeg" target="_blank"><img src="20261021_00016.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00017.jpeg" target="_blank"><img src="20261021_00017.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00018.jpeg" target="_blank"><img src="20261021_00018.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00019.jpeg" target="_blank"><img src="20261021_00019.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00020.jpeg" target="_blank"><img src="20261021_00020.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">平日の火曜日なので、人出は少なめ</span></h2>
<a href="20261021_00021.jpeg" target="_blank"><img src="20261021_00021.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">CDショップも空いてます</span></h2>
<a href="20261021_00022.jpeg" target="_blank"><img src="20261021_00022.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">山下達郎と竹内まりやのコーナーが出来てました</span></h2>
<a href="20261021_00023.jpeg" target="_blank"><img src="20261021_00023.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00024.jpeg" target="_blank"><img src="20261021_00024.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">FUJI ROCK FES '25 のレポート</span></h2>
<a href="20261021_00025.jpeg" target="_blank"><img src="20261021_00025.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">CDショップの後はエスカレーター下って、本屋さんコース</span></h2>
<a href="20261021_00026.jpeg" target="_blank"><img src="20261021_00026.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">この棚のチェックも定番ルート</span></h2>
<a href="20261021_00027.jpeg" target="_blank"><img src="20261021_00027.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">お昼はいつものフードコートでお弁当</span></h2>
<a href="20261021_00028.jpeg" target="_blank"><img src="20261021_00028.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">フードコート横のお花屋さんのお花達も元気に満開</span></h2>
<a href="20261021_00029.jpeg" target="_blank"><img src="20261021_00029.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00030.jpeg" target="_blank"><img src="20261021_00030.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00031.jpeg" target="_blank"><img src="20261021_00031.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00032.jpeg" target="_blank"><img src="20261021_00032.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00033.jpeg" target="_blank"><img src="20261021_00033.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">サボテンも鮮やかにこんにちは</span></h2>
<a href="20261021_00034.jpeg" target="_blank"><img src="20261021_00034.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261021_00035.jpeg" target="_blank"><img src="20261021_00035.jpeg" alt="サンプル画像" class="responsive-media"></a>

<!--
<h2><span class="yellow">宇都宮市北部、カインズホームと吉野家までの走行経路はこのルート</span></h2>
<a href="20261019_00001.png" target="_blank"><img src="20261019_00001.png" alt="サンプル画像" class="responsive-media"></a>
-->

<h2><span class="yellow">ベルモール地下駐車場への入庫と出庫走行動画</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/jN2MTc4yarM?si=HgQ87fb84ZbrPtJl&autoplay=1&mute=1&loop=1&playlist=jN2MTc4yarM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>


<h2><span class="yellow">以上、今回は、お花達とワンちゃんとサボテンでした</span></h2>


<br><br><!--
<h2><span class="yellow">月齢の説明リンク貼ります</span></h2>
<h2><a href="https://starwalk.space/ja/moon-calendar" target="_blank"><span class="snow">月齢カレンダー・リンク</span></a></h2>
-->
<br><br>
<br><br>

<h2><span class="yellow">今日のBGMは、Piano Bamboo Water Sounds for Sleeping, Relaxation 24/7 自然の音とともに音楽をリラックス バンブーウォーターファウンテン</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/oc2QEAnTjeU?si=4rNgvaZwl1i32wy-&autoplay=1&mute=0&loop=1&playlist=oc2QEAnTjeU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

<br><br><br>
<h2><span class="yellow">2026Oct21、ご近所のお花達から、ペットショップのワンちゃん達とお花屋さんのサボテンまででした<br>Thank you for reading this far.</span></h2>

<br><br><br>

<!-- hitwebcounter Code START -->
<a href="https://www.hitwebcounter.com" target="_blank">
<p>you are <img src="https://hitwebcounter.com/counter/counter.php?page=21345151&style=0018&nbdigits=5&type=page&initCount=0" title="Counter Widget" Alt="Visit counter For Websites"   border="0" />visitor<br>The numbers are cumulative for the Bangkok ＆ Utsunomiya series websites launched since 2025 August 1st.</p></a>  



<style>
.responsive-media {
    opacity: 1 !important;
    filter: brightness(100%) !important;
}
</style>


<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->
    </div>

<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2026/10/21 alis</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>


<script>
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});
</script>


<script>
// オープニング画面を消す既存のコード
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});

// --- スクロール連動のフェードイン処理 ---
document.addEventListener("DOMContentLoaded", function() {
  // 動きをつけたい要素（ここでは画像と見出し h2）を指定
  const targets = document.querySelectorAll('.responsive-media, h2');

  const observer = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
      // 画面に少し入ってきたら
      if (entry.isIntersecting) {
        entry.target.classList.add('is-show');
        // 何度もアニメーションさせたい場合は unobserve を外してください
        // observer.unobserve(entry.target); 
      }
    });
  }, {
    threshold: 0.25 // 要素が25%見えたタイミングで発火
  });

  targets.forEach(target => {
    target.classList.add('scroll-fade'); // 初期状態のクラスを付与
    observer.observe(target); // 監視を開始
  });
});
</script>

    </body>
    
</html>
