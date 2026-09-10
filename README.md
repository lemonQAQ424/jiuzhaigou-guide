# 九寨沟一日游攻略

手机 / 电脑均可打开的静态网页攻略（含地图与行程附图）。

## 本地预览

用浏览器直接打开本目录下的 `index.html` 即可。

## 上传 GitHub 并用手机访问（GitHub Pages）

### 1. 创建仓库并上传

1. 打开 [https://github.com/new](https://github.com/new)
2. Repository name 填写如：`jiuzhaigou-guide`（可自定义）
3. 选 **Public**，先不要勾选 Add README（本地已有文件）
4. 点 **Create repository**

在电脑上打开终端（PowerShell），执行（把 `你的用户名` 和仓库名换成自己的）：

```powershell
cd "e:\Workspace2\other\九寨沟旅行"
git init
git add index.html html_assets README.md
git commit -m "发布九寨沟一日游攻略网页"
git branch -M main
git remote add origin https://github.com/你的用户名/jiuzhaigou-guide.git
git push -u origin main
```

> 若尚未登录 GitHub，推送时会提示登录；也可先安装 [GitHub Desktop](https://desktop.github.com/) 用图形界面上传整个 `九寨沟旅行` 文件夹。

### 2. 开启 GitHub Pages

1. 打开仓库页面 → **Settings** → 左侧 **Pages**
2. **Source** 选 **Deploy from a branch**
3. Branch 选 `main`，文件夹选 `/ (root)`
4. 点 **Save**
5. 等 1～2 分钟，页面上方会出现访问地址，形如：

`https://你的用户名.github.io/jiuzhaigou-guide/`

### 3. 手机打开

用微信 / 浏览器打开上面的链接即可。  
行程里的缩略图可点击放大；顶部有「看地图 / 看行程」快捷跳转。

---

**说明：** 本站是纯静态页面，无需服务器、无需 Node。只要 GitHub Pages 开启成功，链接就能一直访问。
