# Fb-api-example
一些 Facebook Graph API 的應用範例
* WordCount
<br />

## WordCount
計算貼文中的字詞被使用次數並排序

* 使用 Jieba 將貼文分詞

```
今天台北的天氣很好 -> 今天 台北 的 天氣 很好
 ```
* 分別加總分詞後產生的字詞的出現次數
* 依照加總的結果做排序
* 列出最常使用的字詞與使用次數
