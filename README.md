# 方天兵 · 作品集 2026

在线作品集，四组作品：会展视觉、文化短片、产品广告、三维动态。

## 部署到 GitHub Pages（三步）

### 1. 建仓库
打开 https://github.com/new ，仓库名填 `portfolio`（或任意名字），选 **Public**，不要勾 README，点 Create。

### 2. 上传文件
在本文件夹里打开命令行，把下面的 `你的用户名` 换成你的 GitHub 用户名：

```
cd /d E:\deepseek-harness\default-workspace\portfolio_ftb\site
git init
git add .
git commit -m "portfolio 2026"
git branch -M main
git remote add origin https://github.com/你的用户名/portfolio.git
git push -u origin main
```

第一次 push 会弹登录框，用 GitHub 账号登录即可。

### 3. 开启 Pages
进入仓库 → Settings → Pages → Source 选 **Deploy from a branch**，Branch 选 **main**，目录选 **/ (root)**，Save。

等 1—2 分钟，链接就是：

```
https://你的用户名.github.io/portfolio/
```

## 文件结构

```
site/
├─ index.html      作品集主页
└─ img/
   ├─ p01.jpg … p09.jpg
```

## 改内容

- 改姓名、电话、邮箱：编辑 `index.html` 搜「方天兵」「19730501932」「ai.soul@qq.com」
- 换作品图：直接替换 `img/` 下的 jpg，保持文件名不变即可
