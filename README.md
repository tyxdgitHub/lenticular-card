# 电子光栅卡

用手机倾斜角度模拟物理光栅卡的图片切换效果。

## 部署到 GitHub Pages（3 步）

### 1. 创建 GitHub 仓库
- 登录 GitHub → 点右上角 "+" → New repository
- 名字随便起，比如 `lenticular-card`
- 选 Public
- 点 Create

### 2. 推送代码
在本目录下执行：
```bash
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/你的用户名/lenticular-card.git
git push -u origin main
```

### 3. 开启 GitHub Pages
- 进入仓库页面 → Settings → Pages
- Source 选 **GitHub Actions**
- 等 1-2 分钟，自动部署完成

部署完成后访问：`https://你的用户名.github.io/lenticular-card/`

## 使用方法

1. 手机浏览器打开上面的链接（HTTPS 环境下传感器才能工作）
2. 上传两张图片
3. 调整参数，点击开始体验
4. 倾斜手机观看光栅切换效果

### 安装到桌面（像 APP 一样使用）
- **Android Chrome**：打开页面 → 右上角三个点 → "添加到主屏幕"
- **iOS Safari**：打开页面 → 底部分享按钮 → "添加到主屏幕"

安装后桌面会出现图标，打开后全屏运行，体验和原生 APP 一样。
