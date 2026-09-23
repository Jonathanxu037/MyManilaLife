# Two Maridien 入住购物清单

这是一个纯静态、手机优先的购物清单网页，可直接部署到 GitHub Pages。

## 文件
- `index.html`：完整网页，无第三方依赖。

## GitHub Pages 部署
1. 新建一个 GitHub repository。
2. 将本文件夹中的 `index.html` 和 `README.md` 上传到仓库根目录。
3. 打开仓库 **Settings → Pages**。
4. 在 **Build and deployment** 中选择 **Deploy from a branch**。
5. Branch 选择 `main`，Folder 选择 `/ (root)`，保存。
6. 等待 GitHub Pages 发布。

## 手机功能
- 页面为响应式设计。
- 每件商品可以勾选，勾选状态保存在浏览器 Local Storage。
- 所有实体购买地点都提供 Google Maps 搜索/导航链接。
- 手机点击 Google Maps 链接时，如系统已安装 Google Maps，通常会由系统优先交给地图 App；否则会在浏览器打开 Google Maps。
- 不在网页中显示具体房号。

## 注意
价格、库存和门店营业时间会变化；购物前请再次确认。
