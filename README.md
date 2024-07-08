# [ python tutorial ] 實戰计算PV和UV

到訪日誌 : 記錄用戶的訪問事件

格式 : [ 日誌日期 時間, 用戶ID, 頁面ID, 事件 ] and [頁面ID  頁面名稱] 


衡量流量的兩個指標PV和UV:

PV (Page View) : 即頁面瀏覽量，用戶每次訪問頁面都算一個PV
UV (Unique Visitor) : 網頁獨立訪客，用戶多次訪問頁面只能算一個UV


<img width="385" alt="截圖 2024-07-08 下午3 57 22" src="https://github.com/MarckHuang/Implement-PV-and-UV-cal/assets/76237925/3e367917-7875-4d15-9e47-0f47f87ec16a">

步驟:

step1 : 利用dict(page_id)=page_name, 存取頁面ID與頁面名稱關係


step2 : PV/UV累積計算

hint : 利用len(user_ids)獲得UV


step3 : 輸出結果
