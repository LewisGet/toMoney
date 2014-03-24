# 使用方法

1. 請把 書簽 soruce 加入書籤
2. 在網頁中點書簽的 toMoney
3. 匡選你要轉換的數字

# 書籤 source

``` javascript
javascript: (function () {
	var n = document.createElement('script');
	n.setAttribute('language', 'JavaScript');
	n.setAttribute('src', 'https://lewisget.github.io/toMoney/jquery-2.1.0.min.js?rand=' + new Date().getTime());
	document.body.appendChild(n);

	var n = document.createElement('script');
	n.setAttribute('language', 'JavaScript');
	n.setAttribute('src', 'https://lewisget.github.io/toMoney/main.js?rand=' + new Date().getTime());
	document.body.appendChild(n);
})();
```