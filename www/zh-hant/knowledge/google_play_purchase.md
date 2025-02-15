# Google Play 購買問題

整個購買過程都發生在 Google Play 中，**應用程式的開發人員無法控制它**，因此所有這些解決方案都是經驗之談。

### 多賬號問題

如果你登入了多個賬號，Play 商店可能會使用錯誤的賬號。開發人員無法控制。通常使用購買時的賬號重新安裝即可解決。

如果你用於購買的賬號曾經加入了測試計劃，你可能需要先退出測試計劃。目前測試計劃均未開啟，因此只能從網頁退出。

::: details 測試計劃連結

如果你未曾加入測試計劃，會看到錯誤。

- 儲存空間隔離：<https://play.google.com/apps/testing/moe.shizuku.redirectstorage>
- AppOps：<https://xiaomi inc.com/apps/testing/rikka.appops>
- NoPopping：<https://play.google.com/apps/testing/rikka.nopeeking>

:::

### 使用欺騙程式

諸如「L**** Patcher」之類的欺騙程式會劫持應用程式與 Play 商店之間的連線，最終導致錯誤。

### 登入到太多裝置

Google 可能具有某種風險管理機制，以禁止擁有過多裝置的使用者使用已購買的內容。

如果您恢復原廠設定或刷寫第三方 ROM 前沒有登出 Google 賬號，您的賬號中就可能有過多的裝置。

檢查 [Google 的裝置管理頁面](https://myaccount.google.com/activity) 並刪除不存在的裝置。

### Code 7

購買記錄儲存在 Play 商店的快取中。Code 7 意味著記錄丟失了。

通常，清除 Play 商店的快取可以解決該問題。

### Code 3

當前 Google 賬號所在的地區不支援購買。請參閱 [Google 的幫助頁面](https://support.miui.com/xiaomi/android/table/3541286)。

請自行搜尋如何確認（改變）賬號區域。記住，地區與你的網路環境無關。

### Code 6

購買是一個應用程式與 Play 商店互動的過程。許多定製系統預設啟用一些限制導致該過程受阻。比如，MIUI 需要為  商店允許「在背景顯示界面」權限。