# 馬上下載！
[PiTT on App Store](https://itunes.apple.com/app/id1345822611)  
[PiTT on TestFlight](https://testflight.apple.com/join/TDrhSSs0)

# 操作手冊
[登入畫面](#登入畫面)  
[連線畫面](#連線畫面)  
[主畫面](#主畫面)

## 登入畫面

![Image of Login Page](https://kimieno.github.io/ios.pitt/images/login_page.png)

1. ### 關於 
點擊後進入關於頁面，可查看 PiTT 更新紀錄等資訊

2. ### 無法連線疑難排解
點擊後開啟疑難排解步驟，可簡單排除無法連線的問題

3. ### 設定
點擊後進入設定頁面，可調整連線方式、自動預覽圖片、調色盤、字型大小、封鎖名單等各項設定

4. ### 快速登入選單
在設定頁開啟此功能後將顯示此按鈕，可快速選擇帳號登入

5. ### 帳號
輸入帳號，12個字元以下英數字，不含空白及符號，若使用其他 App 註冊時可能因為該 App 未提醒此帳號格式導致輸入過長帳號而不自知，此時請輸入前 12 字元即可登入

6. ### 密碼
輸入密碼，8個字元以下任意字元

7. ### 登入按鈕
點擊後登入，若使用**長按**方法將在登入時自動將此帳號設為主帳號，下次啟動 PiTT 時將自動以主帳號登入，也可在登入後開啟主選單點擊帳號設定/取消主帳號

## 連線畫面

![Image of Connecting Page](https://kimieno.github.io/ios.pitt/images/connecting_page.png)

1. ### 站台負載
顯示目前站台負載情形
  * 檢測 - 取得狀態中
  * 順暢 - 可快速登入
  * 正常 - 可正常登入
  * 緩慢 - 稍難登入
  * 衰弱 - 較難登入，常出現連線超時或無法連線
  * 掛了 - 無法登入，站台出現問題  
    
    
2. ### 無法連線疑難排解
點擊後開啟疑難排解步驟，可簡單排除無法連線的問題

3. ### 目前狀態
顯示目前連線狀態

4. ### 連線位址
預設為 SSH 連線，可為 ptt.cc 或以 ip 顯示（供中國使用者連線用，可在設定內調整，ptt.cc 無法在中國連線），WebSocket 連線為 ws.ptt.cc，目前為實驗性質。  
**由於 SSH 連線使用人數較多，在熱門時段會因為 PTT 站台連線數限制導致常常出現連線超時或失敗等問題，因此雖然 WebSocket 尚在實驗階段，但還是建議使用此連線方式以便快速登入。**

## 主畫面

共有十種分頁，分別為最愛看板、熱門看板、分類看板、鄉民信箱、最新消息、延燒話題、關注話題、閱讀紀錄、最近造訪、鄉民名冊  
可在主選單 - 設定 - 設定分頁顯示與順序內調整首頁、排序與分頁開關。

![Image of Page View Page](https://kimieno.github.io/ios.pitt/images/page_view.png)

1. ### 首頁
點擊項目可設定為首頁，項目左方將有突顯標記，登入後將首先顯示此分頁

2. ### 編輯
點擊後可開始編輯排序與分頁開關

3. ### 調整排序、分頁開關
可拖曳各項目調整顯示排序，或放置於「關閉」區塊，此區塊內的分頁將不會顯示，至少需啟用三個以上的分頁。  

4. ### 完成編輯
點擊後完成分頁編輯，將在下次啟動 app 時生效。
