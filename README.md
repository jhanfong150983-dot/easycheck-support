# EasyCheck Support Website

EasyCheck App 的支援網站，部署在 GitHub Pages。

## 網站內容

- **index.html** - 支援中心主頁（FAQ + 聯絡表單）
- **privacy.html** - 隱私政策
- **css/style.css** - 樣式檔案

## 部署步驟

1. 在 GitHub 建立新的 repository：`easycheck-support`
2. 將此資料夾內的所有檔案上傳
3. 前往 Repository Settings → Pages
4. Source 選擇 `main` branch
5. 等待幾分鐘後，網站會在以下網址生效：
   - https://jhanfong150983-dot.github.io/easycheck-support/

## 聯絡表單設定

聯絡表單使用 [Formspree](https://formspree.io/) 服務：

1. 前往 https://formspree.io/ 註冊帳號
2. 建立新的 Form
3. 複製 Form endpoint（例如：`https://formspree.io/f/xyzabc`）
4. 在 `index.html` 中找到 `YOUR_FORM_ID` 替換成你的 Form ID

## App Store Connect 設定

在 App Store Connect 填入以下網址：

- **支援 URL**: `https://jhanfong150983-dot.github.io/easycheck-support/`
- **隱私政策 URL**: `https://jhanfong150983-dot.github.io/easycheck-support/privacy.html`

## 本地測試

直接在瀏覽器開啟 `index.html` 即可預覽。

## 授權

Copyright 2024 EasyCheck. All rights reserved.
