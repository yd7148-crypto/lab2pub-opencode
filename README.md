# Lab 2 Pub - 靜態網站

這是一個完整複製 Google Sites 網站的靜態版本，包含所有必要的功能和內容。

## 網站結構

```
20260201-2-site/
├── index.html          # 首頁
├── contact.html         # 聯絡方式頁面
├── lab2pub.html        # Lab 2 Pub 介紹頁面
├── css/
│   └── styles.css      # 主要樣式文件
├── js/
│   └── main.js         # JavaScript 功能
├── images/
│   ├── hero-image.jpg  # 首頁主圖片
│   └── favicon.ico     # 網站圖標
└── README.md           # 說明文件
```

## 功能特色

- 🎨 **響應式設計**：支援桌面、平板和手機設備
- 🌐 **多語言支援**：中文和英文內容
- 📱 **手機選單**：專為移動設備優化的導航選單
- ✨ **動畫效果**：流暢的滾動動畫和互動效果
- 🔍 **SEO 優化**：包含完整的 meta 標籤和結構化數據
- ♿ **無障礙設計**：符合 WCAG 標準的無障礙功能

## 主要頁面

### 首頁 (index.html)
- 服務介紹
- 解決方案展示
- 客戶問題分析
- 行動呼籲區塊

### 聯絡方式 (contact.html)
- 完整的聯絡資訊
- 互動式聯絡表單
- 常見問題解答
- 客戶回饋

### Lab 2 Pub (lab2pub.html)
- 服務流程介紹
- 專業特色說明
- 成功案例展示
- 團隊優勢分析

## 技術規格

- **HTML5** 語義化標記
- **CSS3** 現代樣式設計
- **JavaScript ES6+** 現代 JavaScript 功能
- **Google Fonts** 專業字體
- **響應式設計** 適配所有設備

## 瀏覽器支援

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 部署說明

### 本地開發
1. 下載所有文件到本地
2. 使用任何 HTTP 伺服器（如 Python SimpleHTTPServer、Node.js http-server 等）
3. 在瀏覽器中打開 index.html

### GitHub Pages 部署
1. 將整個文件夾推送到 GitHub 倉庫
2. 在倉庫設置中啟用 GitHub Pages
3. 選擇主分支作為源
4. 即可通過 `https://username.github.io/repository` 訪問

### Netlify 部署
1. 將文件上傳到 Netlify
2. 設置構建命令為空（靜態文件）
3. 發布目錄為根目錄
4. 獲得自動部署的 URL

## 自訂修改

### 樣式修改
編輯 `css/styles.css` 文件來調整網站的外觀。

### 內容修改
直接編輯對應的 HTML 文件來更新內容。

### 功能擴展
在 `js/main.js` 中添加新的 JavaScript 功能。

## 連結結構

所有內部連結都使用相對路徑，確保在任何部署環境下都能正常工作：

- 首頁：`index.html`
- 聯絡方式：`contact.html`
- Lab 2 Pub：`lab2pub.html`
- 錨點連結：`#section-name`

## 圖片優化

所有圖片都已優化並使用適當的格式：
- JPG：適合照片和複雜圖像
- ICO：瀏覽器圖標
- 響應式圖片：使用 `srcset` 和 `sizes` 屬性

## 效能優化

- CSS 和 JavaScript 文件已壓縮
- 圖片已優化
- 使用字體預加載
- 實現了懶加載功能

## 版本歷史

- v1.0.0 (2024-02-01): 初始版本，完整複製 Google Sites 內容

## 聯絡資訊

如有任何問題或需要技術支援，請聯絡：
- Email: ianyhchentw@gmail.com

## 授權

本網站基於原 Google Sites 內容重新製作，所有版權歸原作者所有。