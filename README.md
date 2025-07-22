# web
## heading
### heading
#### heading
##### heading
###### heading


* 這是清單
* 這是清單
* 這是清單
* 這是清單

1. 這是清單
2. 這是清單
3. 這是清單
4. 這是清單
5. 這是清單

```html
<!DOCTYPE html>
<html lang="zh-Hant-TW">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Document</title>
	<link rel="stylesheet" href="./style/normalize.min.css">
	<link rel="stylesheet" href="./style/all.css">
</head>

<body>
	<article class="post fix-collapse">
		<header class="post-head post-item">CSS class 優化、精簡輕量化、複用化課程</header>
		<div class="post-body post-item">
			各位還在用一個類別刻到底的 CSS 寫法嗎？您可曾想過這樣的擴展性、複用性、可維護性高嗎？這門課程將帶您深入探討多重類別的使用，並體驗靈活使用多重類別的好處。
			各位是否曾有過撰寫完的 CSS，後續重複套用時，卻要加倍覆寫回來的窘境呢？ 時間久了，新功能又不斷地加上去，不知不覺地，您的 CSS 就愈寫愈肥大，這樣技術債何時才能償還呢？
			這門課程會帶各位抽離 HTML 共用元素，並針對此元素區塊撰寫專屬的樣式規則，以便未來靈活運用。讓您的 CSS 撰寫方法也能達到物件導向的高內聚、低耦合，避免撰寫重覆的樣式規則。這樣的觀念及技巧對於網頁設計師相當重要，能讓您的
			CSS 樣式檔最小化，降低頻寬的消耗以及優化加速網頁的呈現速度。
			另外，也將共用的樣式整併至單一的 CSS 樣式表檔案中，以供全域作用，方便未來管理，大幅降低重複性動作與成本，提高 CSS 管理的方便性。
		</div>
		<footer class="post-foot post-item">分享此篇文章</footer>
	</article>

	<p class="text-center">佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~佔位文字~</p>

</body>

</html>
```
```css
@charset "utf-8";

body {
	background-color: #ddd;
	font-family: '微軟正黑體', Arial, Helvetica, sans-serif;
}

.text-center {
	text-align: center;
}

.fix-collapse {
	/* overflow: hidden; */
	border-top: solid 1px transparent;
	border-bottom: solid 1px transparent;
}

.post {
	background-color: #fff;
	width: 700px;
	margin: 10px auto;
}

.post-head,.post-body,.post-foot{
	margin: 30px;
}

.post-item {
	margin: 30px;
}

.post-head {
	background-color: yellowgreen;
}

.post-body {
	background-color: aquamarine;
}

.post-foot {
	background-color: pink;
}
```

