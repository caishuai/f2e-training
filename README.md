# F2E Training

[講者介紹](https://speakerdeck.com/u/josephj/p/introduction)

## Lesson 1 - 基本架構 (HTML)
* 目標：對於 HTML 有正確的觀念
* 投影片：[語意與HTML](https://speakerdeck.com/u/josephj/p/html)
* 推薦參考資料：[The Elements of Meaningful XHTML](http://tantek.com/presentations/2005/09/elements-of-xhtml)
* 常用到的 HTML 樣板：

    ````html
    <!DOCTYPE html>
    <html>
    <head>
    <meta charset="utf-8">
    <title>Prototype</title>
    <link rel="stylesheet" href="http://yui.yahooapis.com/3.5.1/build/cssreset/reset-min.css">
    <link rel="stylesheet" href="http://yui.yahooapis.com/3.5.1/build/cssfonts/fonts-min.css">
    <script type="text/javascript" src="http://yui.yahooapis.com/3.5.1/build/yui/yui-min.js"></script>
    <style type="text/css">

    </style>
    </head>
    <body class="yui-skin-sam">

        <div id="foo">
        </div>

        <script>
        YUI().use("node", function (Y) {

        });
        </script>
    </body>
    </html>
    ````

## Lesson 2 - 樣式之美 (CSS)
* 目標：使用 CSS
* 投影片：[模組基礎與常用 CSS](https://speakerdeck.com/u/josephj/p/css)
* 上課大綱：[JavaScript Basic](https://github.com/josephj/f2e-training/blob/master/javascript-basic.md)
* 免費 Compass 桌面軟體（通用 MAC 與 Windows）- [Scout](http://mhs.github.com/scout-app/)
* Compass 試做 Auto Sprite 與 DataURI - [下載範例](http://josephj.com/training/compass.zip)
* [用 setInterval 製作倒數計時](http://jsfiddle.net/josephj/jZrgW/)

## Lesson 3 - 賦予生命 (JavaScript)
* 目標：了解最常用的 JavaScript 基本
* 上課大綱：[JavaScript Basic](https://github.com/josephj/f2e-training/blob/master/javascript-basic.md)
* 範例列表：
  * [用 on 綁定事件](http://jsfiddle.net/josephj/AW2EU/)
  * [命名空間](http://jsfiddle.net/josephj/uE3hP/)
  * [型別 - 物件 (JSON)](http://jsfiddle.net/josephj/AW2EU/)
  * [型別 - 函式 (Function)](http://jsfiddle.net/josephj/DJ2qB/)
  * [型別 - 函式的 Closure](http://jsfiddle.net/josephj/nz4ne/)
  * [邏輯判斷 - if… else if… else](http://jsfiddle.net/josephj/ysJGA/)
  * [借錢給同事、單複利的計算](http://jsfiddle.net/josephj/NcSPk/)

## Lesson 4 - 合而為一 (Javacript 操控 HTML/CSS)
* 目標：深入了解 JavaScript，並利用前面所學、製作簡易動畫
* 上課大綱：[JavaScript DOM / Event](https://github.com/josephj/f2e-training/blob/master/javascript-dom-event.md)
* 本日實作：
  * [Animation 實作](https://github.com/josephj/f2e-training/blob/master/sample/animation.html)
  * [刪除節點實作](https://github.com/josephj/f2e-training/blob/master/sample/remove-all-items.html)
* 範例列表：
  * [了解物件導向](http://jsfiddle.net/josephj/9ry9a/1/)
  * [字串物件的操作](http://jsfiddle.net/josephj/fFtX7/6/)
  * [陣列物件的操作](http://jsfiddle.net/josephj/4LqfQ/2/)
* Q & A
  * [DOM 2 與 DOM 3 的差別](https://github.com/josephj/f2e-training/blob/master/sample/qa/dom.md)
  * [String 及 DOM 物件的 concat 方法該如何使用](http://jsfiddle.net/josephj/TdAqq/2/)

## Lesson 5 - YUI Basic
* 目標：開始使用 YUI。
* 投影片：Modularization & Loader
  * [了解 YUI 架構](http://jsfiddle.net/josephj/fK4BE/)
  * 如何使用 [YUI 官網](http://yuilibrary.com)
  * 活用 DOM 跟 Event 處理 Lesson 4 的議題
  * 使用 Y.Anim 製作動畫
* 課堂實作：
  * [YUI Module](https://github.com/josephj/f2e-training/blob/master/sample/yui-module.html)
  * [NodeList](https://github.com/josephj/f2e-training/blob/master/sample/yui-nodelist.html)
  * [Event - 綁定事件](https://github.com/josephj/f2e-training/blob/master/sample/yui-event.html)
  * [Event - preventDefault 與 stopPropagation](https://github.com/josephj/f2e-training/blob/master/sample/yui-event-prevent.html)

## Lesson 6 - YUI Advance
* 目標：繼續使用 YUI 各式各樣的 Utilities 與 Widget，並結合外部資料、玩玩動畫！
* 資料來源：
  * [Flickr JSON 格式的 Feed](http://api.flickr.com/services/feeds/photos_public.gne?tags=yahootw&lang=en-us&format=json&jsoncallback=getFlickrData()
  * [YQL Console](http://developer.yahoo.com/yql/console)
  * [Yahoo! Pipes](http://pipes.yahoo.com/pipes/)
* Q & A
  * [YUI 不同 Instance 間的變數傳遞](http://jsfiddle.net/josephj/Gswe6/4/)
  * [讓外部的 Function 也能用 YUI](http://jsfiddle.net/josephj/XRyUa/)
    * 請參考：[石頭閒語 - Function.prototype.call() and Function.prototype.apply()](http://blog.roodo.com/rocksaying/archives/2532303.html)
* 課堂實作：
  * [了解 Script Tag Hack](http://josephj.com/training/f2e-training/sample/script-tag-hack.html)
  * [使用 Y.Get 取得 Flicrk 的照片](http://josephj.com/training/f2e-training/sample/yui-get.html) ([範例結果](http://josephj.com/training/f2e-training/sample/yui-get-sample.html))
   * 更簡單的用法 JSONP - [使用 Y.jsonp 取得 Flickr 的照片](http://josephj.com/training/f2e-training/sample/yui-jsonp.html) ([範例結果](http://josephj.com/training/f2e-training/sample/yui-jsonp-sample.html))
  * [使用 Y.Anim](http://josephj.com/training/f2e-training/sample/yui-anim.html) ([範例結果](http://josephj.com/training/f2e-training/sample/yui-anim-sample.html))
  * [使用 Y.Panel](http://josephj.com/training/f2e-training/sample/yui-panel.html) ([範例結果](http://josephj.com/training/f2e-training/sample/yui-panel-sample.html))
* 回家功課：
  * 利用今天教的 Y.Get.script() 取得外部網站得資料 (可使用 Flickr, 可透過 Pipe 或 YQL...)
  * Ex - [知識+ 的 API](http://tw.knowledge.yahooapis.com/v1/SEARCH?appid=Fbn2UILIkYoPqtaNTG6aFYgkHY9piA2A8A--&p=ipod&kf=CD&intl=tw&format=json&callback=getData)
  * [以 Y.YQL 取得 Flickr 的資料](http://josephj.com/training/f2e-training/sample/yui-yql.html)
    * [Flickr API Key 申請頁面](http://www.flickr.com/services/apps/create/)
  * [以 Y.jsonp 取得 Yahoo! Pipes 所組合出來的 Flickr 資料](http://josephj.com/training/f2e-training/sample/yui-pipes.html)
    * [帥哥與正妹的 Y! Pipes](http://pipes.yahoo.com/pipes/pipe.info?_id=7d48dfb65ddd5ee643dce51df2326a33)
      * JSON Feed 可以多加一個 "_callback" 的 GET 參數
    * [帥哥 Feed](http://api.flickr.com/services/feeds/photos_public.gne?id=10912301@N06&tags=%E7%BE%8E%E5%A5%B3&lang=en-us&format=rss_200)
    * [正妹 Feed](http://api.flickr.com/services/feeds/photos_public.gne?id=33784581@N07&tags=%E5%B8%A5%E5%93%A5&lang=en-us&format=rss_200)

## Lesson 7 - Script Injection
* 目標：使用 Fiddler、了解載入 &lt;script/&gt; 的數種方式及其優缺點
  * Fiddler - 除錯超好用的工具
    * [Fiddler 下載點](http://www.fiddler2.com/fiddler2/version.asp)
    * [CustomRules.js](http://josephj.com/training/f2e-training/sample/CustomRules.js)

    ```
    請各位點選 http://josephj.com/training/f2e-training/sample/CustomRules.js 會看到一堆 JavaScript
    打開 Fiddler 工具列的 Rules > Custom Rules... 把原本的內容另存新檔做備份
    再以上面的連結的內容全部取代、儲存
    順利的話就會聽到「搭搭」的音效（當然喇叭要打開）
    然後你再去工具列的 Rules 就會看到 "Inject JavaScript." 的選項
    點選後去 Reload 任意網頁，都會出現我們昨天那個得等很久的 JavaScript alert
    ```

* &lt;script/&gt; 的擺放位置
  * 在 &lt;/head&gt; 前
    * 所有 DOM 物件皆未產生，需要配合 load 或 domready 事件（或其他偵測的方式）。
    * 因 JavaScript 有 Blocking 的行為，使用者得等到 JavaScript 下載完畢才能看到網頁內容。
  * 在 &lt;/body&gt; 前
    * 所有 DOM 物件皆已經產生，不需要特別的處理即可存取。
    * 所有的內容皆會在第一時間被看到。
* 在 &lt;/body&gt; 到處都有的廣告 &lt;script/&gt; 為何討人厭？
  * [大圖不會 Block 頁面讀取](http://josephj.com/training/f2e-training/sample/blocking-image.html) - 我錯了 :p
  * [會在 Server 等 10 秒才結束的 JavaScript](http://josephj.com/training/f2e-training/sample/sleep-10.php)
  * [Blocking JavaScript](http://josephj.com/training/f2e-training/sample/blocking-javacript.html)
    * [Use document.write 1](http://josephj.com/training/f2e-training/sample/document-write-javascript.html)
    * [Use document.write 2](http://josephj.com/training/f2e-training/sample/document-write-javascript-2.html)
  * [Non-blocking JavaScript](http://josephj.com/training/f2e-training/sample/non-blocking-javacript.html)
* 參考文件：
 * [Non-blocking JavaScript Downloads](http://www.yuiblog.com/blog/2008/07/22/non-blocking-scripts/)
 * [Put Scripts at the bottom](http://developer.yahoo.com/performance/rules.html#js_bottom)
 * [Bye Bye Embed - A List Apart](http://www.alistapart.com/articles/byebyeembed/)
 * [Fiddler Extensions](http://www.fiddler2.com/Fiddler2/extensions.asp)
 * [YQL 利用 XPath 直接抓取網頁內容](http://developer.yahoo.com/yql/console/#h=select%20*%20from%20html%20where%20url%3D%22http%3A//finance.yahoo.com/q%3Fs%3Dyhoo%22%20and%0A%20%20%20%20%20%20xpath%3D%27//div%5B@id%3D%22yfi_headlines%22%5D/div%5B2%5D/ul/li/a%27)
 * [Non-blocking 載入 JavaScript - josephj.com](josephj.com/entry.php?id=349)
 * [Cross Frame: 與不同網域的 Frame 做互動 - josephj.com](http://josephj.com/entry.php?id=338)
 * [了解 embed 及 param 標籤中 wmode 屬性、並且動態修改它 - josephj.com](http://josephj.com/entry.php?id=364)

## Lesson 8 - Performance
* [Performance Rules](http://developer.yahoo.com/performance/rules.html)
* [HTML5 Presentation](http://slides.html5rocks.com/)
  * [HTML5 Study](https://github.com/josephj/f2e-training/blob/master/html5-study.md)


