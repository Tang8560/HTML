## HTML 基礎
***
> ### 基本語法
```html
<!DOCTYPE html>
<html>
<head> <title>This is head</title></head>
<body>
    <h1> Test heading </h1>
    <h2> Test heading </h2>
    <p> Test paragraph </p>
    <p><kbd>Test paragraph</kbd>鍵盤格式</p>
    <p><samp>Test paragraph</samp>計算機格式</p>
    <p><code>Test paragraph</code>代碼格式</p>

    <!--insert link-->
    <p><a href="http://www.google.com">Google link</a>插入連結</p>
    <!--line feed-->
    <p><br/>換行</p>
    <!--insert image-->
    <p><img src="test.jpg" width="104" height="142"/>插入圖片</p>
</body>
</html>
```

> ### HTML 連結

- 建立超連結
```html
<p> <a href="/INDEX.html">Test link</a>建立超連結</p>
```

- 圖片上建立超連結
```html
<!--make image as a hyperlink-->
<a href="/example/html/lastpage.html">
    <img border="0" src="/i/eg-button.gif/"> </a>
```
 Target屬性 : 定義連結資料在何處顯示

```html
<a href="http://www.google.com/" target="_blank">google</a>
<p>"_blank": 在新視窗中開啟連結</p>
```  




- Name屬性 : 用來定錨或建立書籤 (CSS選擇器使用)

 創建書籤
```html
<a name = "tips">注意事項</a>
```

創建指向定錨的連結
```html
<a href = "#tips">提示</a>
```

可在其他頁面創建指向該定錨的連結
```html
<a href = "http://www.google.com #tips">提示</a>
```

建立Email連結
```html
<a href = "mailto:someone@gmail.com?subject=Hello%20again">發送郵件</a>
```







