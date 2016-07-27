# Backend Team - 7/24 ~ 7/30

### 週次 & 日期

第二週 7/24 ~ 7/30

### 撰寫人

ㄅㄌ (最後更新 7/27)

### 預定開發進度

+ 圖書館收藏 API 完成
+ 登出 API
+ 行事曆 API 完成

### 本週開發進度

+ 圖書館收藏 API （進行中）



### 新增 issue ＆ 處理

+ [#10](https://github.com/bingluen/HeyYZU/issues/10) Status code of login failed and param illegal are ambiguous.
  已修改狀態碼！
  
  > 帳號密碼錯誤 satus code修改為 1104

+ [#11](https://github.com/bingluen/HeyYZU/issues/11) Book publish year on Library search result is contain space character
  
  > 已修改相關 module 移除非數字的其他字元，並仍以字串格式輸出
  
+ [#12](https://github.com/bingluen/HeyYZU/issues/12) 為何登入一直缺參數？

  > 確定為烏龍 issue ，因為前後端 API 定義沒有溝通清楚，導致模擬器送出之 device token 為空字串時，Server 視為參數錯誤。

### 未解決 issue

#### 本週新增

+ [#13](https://github.com/bingluen/HeyYZU/issues/13) 希望圖書館搜尋後callback的json array用出版年做排序

#### 累積未解決

+ [#7](https://github.com/bingluen/HeyYZU/issues/7) 
+ [#6](https://github.com/bingluen/HeyYZU/issues/6)
+ [#5](https://github.com/bingluen/HeyYZU/issues/5)
+ [#4](https://github.com/bingluen/HeyYZU/issues/4)

### 其他問題

考慮設計「所有裝置登出」，配合重新設計 Token ＆ 登入機制