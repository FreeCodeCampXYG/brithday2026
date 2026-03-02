# 🎂 Birthday2026

一个精美的生日祝福网页，用代码传递最真挚的祝福。

## ✨ 功能特性

- 🔐 **登录页面** - 简洁的登录入口，输入姓名和密码即可进入
- 🎂 **生日蛋糕动画** - 精美的 SVG 动画蛋糕，蜡烛火焰跳动
- 📜 **全屏滚动祝福** - 使用 fullPage.js 实现的全屏滚动祝福展示
- 🎵 **背景音乐** - 自动播放的背景音乐，营造温馨氛围
- 🥚 **彩蛋页面** - 隐藏的惊喜页面

## 🛠️ 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式与动画效果
- **JavaScript** - 交互逻辑
- **jQuery** - DOM 操作与动画
- **fullPage.js** - 全屏滚动插件
- **SVG Animation** - 蛋糕动画

## 📁 项目结构

```
brithday2026/
├── index.html              # 入口文件
├── css/
│   ├── style.css           # 主样式
│   ├── styles.css          # 登录页样式
│   ├── styless.css         # 蛋糕页样式
│   └── jquery.fullPage.css # 全屏滚动样式
├── js/
│   ├── jquery.js           # jQuery 库
│   ├── jquery.fullPage.js  # 全屏滚动插件
│   └── diy.js              # 自定义脚本
├── html/
│   ├── login.html          # 登录页
│   ├── BirthdayCake.html   # 生日蛋糕页
│   ├── Memories.html       # 祝福展示页
│   └── EasterEgg.html      # 彩蛋页
├── img/                    # 图片资源
├── music/                  # 背景音乐
└── LICENSE
```

## 🚀 快速开始

### 本地运行

1. 克隆仓库
```bash
git clone https://github.com/your-username/birthday2026.git
```

2. 直接用浏览器打开 `index.html` 文件即可运行，无需服务器

或者使用本地服务器：
```bash
# 使用 Python
python -m http.server 8080

# 使用 Node.js (需安装 http-server)
npx http-server
```

3. 浏览器访问 `http://localhost:8080`

## 🎨 自定义修改

### 修改祝福语

编辑 `html/Memories.html` 文件，找到对应的 `<p>` 标签修改文字内容。

### 更换图片

将新图片放入 `img/` 文件夹，然后在 HTML 文件中修改对应的 `<img>` 标签的 `src` 属性。

### 更换背景音乐

将新的音乐文件放入 `music/` 文件夹，修改 HTML 文件中 `<audio>` 标签的 `src` 属性。

### 修改登录信息

编辑 `html/login.html` 文件中的 `value` 属性来设置默认姓名。

## 📝 页面流程

```
登录页 → 生日蛋糕页 → 祝福展示页 → 彩蛋页
```

## 🙏 致谢

本项目基于开源生日祝福页面进行个人修改，感谢原作者的创意分享。

## 📄 许可证

[MIT License](LICENSE)
