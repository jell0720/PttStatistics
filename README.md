# PttStatistics 
統計PTT看板推文 or 文章標題 熱門關鍵詞 for Windows and Linux  on python
* [Demo Video](https://youtu.be/kuLBL9ggBSg) - Windows 

## 特色
* 統計PTT看板 推文 or 文章標題 熱門關鍵詞

## 使用方法
```
pyhton PttStatistics.py [統計型態] [板名] [爬取頁數]
```

## 執行範例 
###範例一
``` 
python PttStatistics.py title gossiping 10
```
抓取PTT gossiping (八卦板) 10頁，統計 文章標題 熱門關鍵詞 <br>
###範例二
``` 
python PttStatistics.py push gossiping 10
```
抓取PTT gossiping (八卦板) 10頁，統計 推文內容 熱門關鍵詞 <br>

## 執行畫面
###範例一
![alt tag](http://i.imgur.com/ie24jt1.jpg)
![alt tag](http://i.imgur.com/5M7ZKE3.jpg)
###範例二
![alt tag](http://i.imgur.com/CbCz1qo.jpg)
![alt tag](http://i.imgur.com/fZXzb4e.jpg)
<br>
如斷詞不夠精準，可自行將詞加入至"dictNew.txt"裡面，以增加斷詞準確度<br>

## 輸出格式
文字檔(.txt)<br>
格式( "詞"    "次數" )<br>
![alt tag](http://i.imgur.com/n8WeUk2.jpg)
<br>
可借用[ tableau ](http://www.tableau.com/products)輸出圖片<br>
![alt tag](http://i.imgur.com/lle1oWq.jpg)

## External 
* 斷詞系統 [ jieba ](https://github.com/fxsjy/jieba)

## 執行環境
* Ubuntu 12.04
* Python 2.7.3

## License
MIT license

