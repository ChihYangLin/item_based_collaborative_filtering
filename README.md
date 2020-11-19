# Item_based Collaborative Filtering

### 計算物品之間的相似度，將最相關的物品推薦給消費者。(建立在假設你喜歡某樣商品，那你也會喜歡與此商品相似的物品)

# 實作步驟
* 整理資料成[顧客ID, 商品ID, 評分] 三個欄位
* 做圖觀察評分的趨勢
  ![image](https://github.com/ChihYangLin/item_based_collaborative_filtering/blob/master/demo_photos/seaborn.png)
* 做出顧客對商品的評分矩陣
* 找出與商品相關的TOP-N商品
* 針對每一項使用者購買的商品，找出與其相似的30樣商品 --> 剔除原使用者購買過的商品 --> 依商品的相關性排名做推薦








