# 最简单部署方法 - 3分钟搞定

## 方法一：使用GitHub网页直接上传（推荐）

### 步骤1：注册GitHub账号
1. 访问 https://github.com
2. 点击"Sign up"注册账号（免费）

### 步骤2：创建仓库
1. 登录GitHub
2. 点击右上角"+" → "New repository"
3. 仓库名输入：`fitness-tracker`
4. 选择"Public"（公开）
5. **不要勾选**"Add a README file"
6. 点击"Create repository"

### 步骤3：上传文件
1. 进入刚创建的仓库页面
2. 点击"Add file" → "Upload files"
3. 将以下文件拖拽到上传区域：
   - 桌面上的 `Fittngboy.html`
   - 桌面上的 `Fittinggirl.html`
   - 我为你创建的 `index.html`（在部署文件夹中）
4. 点击"Commit changes"

### 步骤4：启用GitHub Pages
1. 在仓库页面，点击"Settings"
2. 左侧选择"Pages"
3. 在"Source"部分，选择"Deploy from a branch"
4. 在"Branch"部分，选择"main"分支，文件夹选择"/ (root)"
5. 点击"Save"

### 步骤5：访问网站
等待1-2分钟，然后访问：
```
https://你的用户名.github.io/fitness-tracker/
```

## 方法二：使用Netlify（更简单）

### 步骤1：注册Netlify账号
1. 访问 https://app.netlify.com/signup
2. 使用GitHub账号登录（最简单）

### 步骤2：部署网站
1. 登录后点击"Add new site" → "Import an existing project"
2. 选择"GitHub"
3. 授权访问你的GitHub账号
4. 选择 `fitness-tracker` 仓库
5. 点击"Deploy site"

### 步骤3：访问网站
部署完成后，你会得到一个类似这样的网址：
```
https://你的网站名.netlify.app
```

## 方法三：使用Vercel（最快）

### 步骤1：注册Vercel账号
1. 访问 https://vercel.com
2. 使用GitHub账号登录

### 步骤2：部署网站
1. 点击"New Project"
2. 导入 `fitness-tracker` 仓库
3. 点击"Deploy"

### 步骤3：访问网站
部署完成后，你会得到一个类似这样的网址：
```
https://你的网站名.vercel.app
```

## 手机访问测试

### 测试方法：
1. 在电脑上获取网站地址
2. 用手机浏览器访问该地址
3. 添加到手机主屏幕（方便下次访问）

### 添加到手机主屏幕：
- **iPhone**: 点击分享按钮 → "添加到主屏幕"
- **Android**: 点击菜单 → "添加到主屏幕"

## 网站功能说明

### 1. 主页 (index.html)
- 漂亮的引导页面
- 一键进入增肌或减脂训练

### 2. 增肌训练 (Fittngboy.html)
- 三分化训练计划（推力/拉/腿）
- 记录重量、组数、次数
- 动作视频指导链接
- 饮食建议
- 本地存储进度

### 3. 减脂训练 (Fittinggirl.html)
- 三分化训练计划
- 有氧和力量训练结合
- 卡路里消耗记录
- 饮食控制建议
- 本地存储进度

## 技术特点

### 响应式设计
- 自动适应手机屏幕
- 触摸友好的按钮和界面

### 本地存储
- 使用浏览器localStorage保存数据
- 无需登录，数据保存在本地
- 换设备时需要重新记录

### 离线使用
- 所有文件都在本地
- 第一次访问后可以离线使用
- 视频需要网络连接

## 常见问题

### Q: 数据会丢失吗？
A: 数据保存在浏览器本地，清除浏览器数据或换设备会丢失。建议定期截图备份。

### Q: 需要网络吗？
A: 第一次访问需要网络加载页面，之后可以离线使用。视频链接需要网络。

### Q: 可以多人使用吗？
A: 每个设备独立保存数据，适合个人使用。

### Q: 如何更新训练计划？
A: 联系我帮你修改HTML文件，然后重新上传。

## 开始使用
选择最简单的方法部署，然后就可以在手机上使用了！