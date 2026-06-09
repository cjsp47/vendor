# vendor

這是靜態網頁專案，已支援 GitHub Pages 正式部署。

## 自動部署

- 已新增 GitHub Actions 工作流程：`.github/workflows/deploy-pages.yml`
- 每次推到 `main` 分支後，GitHub Actions 會自動將此專案部署到 GitHub Pages。
- 若部署成功，正式網站網址預設為：
  `https://cjsp47.github.io/vendor/`

## 使用說明

1. 確認專案已推到 `main` 分支。
2. GitHub Action 會自動觸發並部署。
3. 部署完成後，可透過上面的網址直接開啟。

如果你希望使用自訂網域，也可以再設定 GitHub Pages 的 Custom domain。