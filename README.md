# BS-HWK-WK5
作業相關訊息

## 第一大題
目前完成進度
* 列印資料內容
* 依類別查詢資料
## 第二大題
1. 回頭複習一下，C#的事件委派函式的原理是什麼?
2. JavaScript 的事件處理函式的原理是什麼? 
3. submit 事件和 click 事件有什麼差別?

### 1
委派(Delegate)
: 一個裝載事件的容器
事件(Event)
: 一個裝載程式需要執行啥的容器

舉例:
我建立一個 Button

同時我需要建立一個**委派**

而我可以在裡面加入一個**事件** 來偵測我有沒有按下 Button

### 2
JS事件 類似 C#事件
我們可以宣告一事件，加入DOM裡面來做一些事情。

### 3
submit 他會使用在 from 裡面，因為它會等待一個訊號才會送出。
click 基本上可以當上面那個例子最後一個按鈕來用，他不會限制需要另一個訊號他不會限制需要另一個訊號來讓它啟動。