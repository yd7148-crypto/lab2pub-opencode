# GitHub Pages 部署指南

## 快速部署到 GitHub Pages

### 步驟一：創建 GitHub 倉庫

1. 在 GitHub 上創建一個新的倉庫
2. 倉庫名稱可以是任意名稱（建議：`lab2pub-website`）
3. 設置為 Public（公開）或 Private（私有）

### 步驟二：上傳文件

1. 將整個 `20260201-2-site` 文件夾內容上傳到倉庫根目錄
2. 或者使用 Git 命令：

```bash
# 初始化倉庫
git init
git add .
git commit -m "Initial commit: Lab 2 Pub website"

# 添加遠程倉庫
git remote add origin https://github.com/yourusername/lab2pub-website.git
git branch -M main
git push -u origin main
```

### 步驟三：啟用 GitHub Pages

1. 進入倉庫的 Settings 頁面
2. 在左側選單中找到 "Pages"
3. 在 "Build and deployment" 部分：
   - Source: 選擇 "Deploy from a branch"
   - Branch: 選擇 "main" 和 "/ (root)"
4. 點擊 "Save"

### 步驟四：訪問網站

等待幾分鐘後，您的網站將在以下地址可用：
`https://yourusername.github.io/lab2pub-website/`

## 注意事項

- GitHub Pages 預設使用 Jekyll，但這是一個純靜態網站，不需要 Jekyll
- 確保所有檔案都包含在倉庫中
- 檢查檔案路徑是否正確（使用相對路徑）
- 圖片和 CSS 檔案需要正確上傳

## 自定義域名（可選）

如果您想使用自定義域名：

1. 在倉庫的 Settings > Pages 中設置自定義域名
2. 在域名提供商處配置 DNS 記錄
3. 可選：添加 HTTPS 證書

## 故障排除

### 常見問題

1. **404 錯誤**：檢查檔案路徑和檔名是否正確
2. **樣式未載入**：確認 CSS 檔案路徑正確
3. **圖片不顯示**：檢查圖片路徑和檔名
4. **JavaScript 不工作**：檢查控制台錯誤訊息

### 調試技巧

- 使用瀏覽器開發者工具檢查網路請求
- 查看 Console 錯誤訊息
- 確認所有資源檔案都正確上傳

## 升級維護

要更新網站：

1. 修改本地檔案
2. 使用 Git 提交更改：
   ```bash
   git add .
   git commit -m "Update website content"
   git push origin main
   ```
3. GitHub Pages 會自動重新部署

## 效能監控

可以使用以下工具監控網站效能：
- Google PageSpeed Insights
- GTmetrix
- WebPageTest

部署完成後，建議測試：
- 首頁載入速度
- 響應式設計在不同設備上的表現
- 表單功能（如果使用第三方服務）