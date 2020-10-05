# 淘寶消費者行為資料
### 資料來源
* [User Behavior Data from Taobao for Recommendation](https://tianchi.aliyun.com/dataset/dataDetail?dataId=649&userId=1)   
原始有一億筆左右的資料，這裡取500萬筆資料做分析

   
### 資料欄位說明
| 欄位名 | 說明 |
|-------|:-----:|
| User Id   |   整數型態，用戶ID |
| Item Id   |   整數型態，商品ID |
| Category Id   |   整數型態，商品類別ID |
| Behavior   |   文字型態，用戶行為類別(pv、buy、cart、fav) |
| Time   |   行為發生的時間 |
   
| 行為類別 | 說明 |
|-------|:-----:|
| pv   |   瀏覽商品頁 |
| buy   |   商品購買 |
| cart   |   將商品放入購物車 |
| fav   |   收藏商品 |
   
### 利用python做資料處理後進到Tableau做資料視覺化的呈現
* [Tableau連結](https://public.tableau.com/profile/ting4945#!/vizhome/30226/sheet4)
![image](https://github.com/YiTing-Wu/Taobao_data/blob/main/%E6%B7%98%E5%AF%B6%E8%B3%87%E6%96%99%E8%A6%96%E8%A6%BA%E5%8C%96.png)
