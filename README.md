**Jodus 機率分配互動實驗室 \(Jodus Probability Distribution Interactive Lab\)**

專為**大二統計學與商業決策分析課程**設計的沈浸式互動網頁實驗室。本專案將抽象的機率與統計理論轉化為直覺的視覺化互動，幫助學生透過生活化與商管情境，深刻體會各類機率分配的特性、期望值與變異數。

**🌟 專案特色 \(Features\)**

- **完整涵蓋 8 大經典機率分配**：
    - **離散型 \(Discrete\)**：二項分配、超幾何分配、幾何分配、卜瓦松分配、負二項分配。
    - **連續型 \(Continuous\)**：均勻分配、常態分配、指數分配。
- **直覺的參數滑桿與即時連動**：動態調整參數（如 $n, p, \\mu, \\sigma, \\lambda$ 等），圖表與統計量在毫秒內同步更新。
- **生活化與商管實例對應**：每項分配皆搭配專屬的生活情境（如籃球員投籃、品管抽檢、客服來電量、績效考核等）。
- **完整統計指標呈現**：即時計算並顯示對應的**平均數（期望值）與變異數**。
- **清爽高畫質介面**：採用極具質感的青藍色系 \(\#CCFFFF\) 背景與現代 Tailwind CSS 響應式寬螢幕設計，無須安裝任何套件，開啟即用。

**📊 收錄模組與實例**



<table><tr><td><p><strong>分配類型</strong></p></td><td><p><strong>模組名稱</strong></p></td><td><p><strong>生活/商管實例</strong></p></td></tr><tr><td><p><strong>離散型</strong></p></td><td><p>二項分配 (Binomial)</p></td><td><p>籃球員的投籃命中數</p></td></tr><tr><td><p><strong>離散型</strong></p></td><td><p>超幾何分配 (Hypergeometric)</p></td><td><p>批次品管瑕疵品抽檢</p></td></tr><tr><td><p><strong>離散型</strong></p></td><td><p>幾何分配 (Geometric)</p></td><td><p>直到首次推銷成功次數</p></td></tr><tr><td><p><strong>離散型</strong></p></td><td><p>卜瓦松分配 (Poisson)</p></td><td><p>客服中心單位時間來電數</p></td></tr><tr><td><p><strong>離散型</strong></p></td><td><p>負二項分配 (Negative Binomial)</p></td><td><p>達成第 r 筆訂單所需的總拜訪數</p></td></tr><tr><td><p><strong>連續型</strong></p></td><td><p>均勻分配 (Uniform)</p></td><td><p>公車班次隨機等候時間</p></td></tr><tr><td><p><strong>連續型</strong></p></td><td><p>常態分配 (Normal)</p></td><td><p>員工年度績效考核分數</p></td></tr><tr><td><p><strong>連續型</strong></p></td><td><p>指數分配 (Exponential)</p></td><td><p>機器設備故障間隔時間</p></td></tr></table>



**🚀 快速開始 \(Quick Start\)**

本專案採用**單一 HTML 檔案架構**，無須複雜的建置工具（Build Tools）或後端伺服器。

1. **Clone 本專案**：
2. git clone https://github\.com/jodusocnncwiy/jodus\-probability\-lab\.git
3. **開啟專案**： 直接將專案資料夾中的 index\.html 檔案用任何現代網頁瀏覽器（Chrome, Edge, Safari, Firefox）雙擊開啟即可！

**🛠️ 技術堆疊 \(Tech Stack\)**

- **前端結構**：HTML5, Tailwind CSS \(CDN\)
- **資料視覺化**：Chart\.js
- **圖示庫**：Font Awesome 6
- **字型排版**：Inter 現代無襯線字體

**💡 貢獻與回饋 \(Contributing\)**

歡迎提出 Issues 或 Pull Requests 來讓這個教學實驗室更加完善！

**📜 授權條款 \(License\)**

本專案採用 [MIT License](https://fgu365-my.sharepoint.com/personal/mttsai_vdi_fgu_edu_tw/Documents/LICENSE) 授權條款。