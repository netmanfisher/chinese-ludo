# Chinese Ludo / 中国飞行棋

> **⭐ If you find this project helpful, please star it before downloading! / 如果觉得这个项目有用，请先点亮星星再下载！**

[English](#english) | [中文](#中文)

---

## English

![Chinese Ludo](img/xx.jpeg)

# Chinese Ludo - Classic Chinese Board Game / 中国飞行棋

A complete implementation of the classic Chinese board game **飞行棋 (Fei Xing Qi)** in vanilla JavaScript. This is one of the first open-source Chinese Ludo games on GitHub.

**[🎮 Play Online / 在线玩](../../)** | **[⭐ Star on GitHub](../../stargazers)**
**https://netmanfisher.github.io/chinese-ludo/** 
https://netmanfisher.github.io/chinese-ludo/

## 📋 What is Chinese Ludo?

Chinese Ludo (中国飞行棋) is a classic childhood board game in China, similar to Ludo/Aeroplane Chess but with unique rules including:
- **Color jumping** - Jump to next cell of your color
- **Flying shortcuts** - Special paths across the board
- **Safe zones** - Colored cells protect from capture
- **Rolling 6** - Get bonus turns

## 🎮 Game Features

- ✅ **100% Client-side** - No server required, runs entirely in browser
- ✅ **No dependencies** - Pure vanilla JavaScript, HTML, CSS
- ✅ **2-4 Players** - Support 2, 3, or 4 players
- ✅ **Responsive Design** - Works on desktop and mobile
- ✅ **Smooth Animations** - Dice rolling, piece movement
- ✅ **Complete Rules** - All traditional Chinese Ludo rules implemented

## 🎯 How to Play

### Quick Start

1. **Open game.html** in any modern browser
2. **Select players** (2-4 players, choose colors)
3. **Click "开始游戏"** to start
4. **Roll dice** by clicking the dice button
5. **Click a piece** to move it

### Game Rules

**Starting:**
- Roll a **6** to move a piece out of base (飞机起飞)
- Rolling a 6 gives you an **extra turn**

**Movement:**
- Roll dice and select a piece to move
- Pieces move clockwise around the board

**Special Actions:**
- 🎯 **Color Jump (颜色飞跃)**: Land on your color → jump to next same-colored cell
- ✈️ **Flying Shortcut (飞行通道)**: After color jump, fly across the board if on flight path
- 🛡️ **Safe Zone (安全区)**: Colored cells on main path protect from capture
- ⚔️ **Capture (吃子)**: Land on opponent → send their piece back to base

**Winning:**
- First player to get **all 4 pieces** to the center wins!

## 📁 Project Structure

```
chinese-ludo/
├── game.html      # Main game page / 游戏主页面
├── ludo.js        # Game logic / 游戏逻辑
├── ludo.css       # Game styles / 游戏样式
├── img/           # Board and dice images / 图片资源
├── LICENSE.md     # MIT License
└── README.md      # This file
```

## 🚀 Quick Start

### Option 1: Play Directly
Simply open `game.html` in Chrome, Firefox, Safari, or Edge.

### Option 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Then visit http://localhost:8000
```

### Option 3: GitHub Pages
1. Fork this repository
2. Enable GitHub Pages in Settings
3. Select `game.html` as source
4. Access at `https://your-username.github.io/chinese-ludo`

## 🔧 Technical Details

- **Language:** Vanilla JavaScript (ES6+)
- **No Frameworks:** No React, Vue, jQuery - pure JS!
- **Browser Support:** Chrome 60+, Firefox 60+, Safari 12+, Edge 79+
- **File Size:** < 50KB total

## 🎯 Why This Project?

When I searched GitHub for "Chinese Ludo 中国飞行棋", I found very few complete implementations. Most were:
- Incomplete projects
- Required complex setup
- Missing key rules like color jumping and flying shortcuts

**This project aims to be:**
- ✅ Complete and playable
- ✅ Easy to use (just open HTML file)
- ✅ Faithful to original Chinese rules
- ✅ Well-documented in both English and Chinese

## 🤝 Contributing

Contributions are welcome! Feel free to:
- 🐛 Report bugs
- 💡 Suggest new features
- 🔧 Submit pull requests
- 📖 Improve documentation

## 📄 License

MIT License - Feel free to use this project for learning, personal projects, or commercial applications.

## ⭐ Show Your Support

If you find this project helpful:
1. ⭐ **Star this repository**
2. 🍴 **Fork it** if you want to modify it
3. 📢 **Share it** with others who might need it

**Every star makes me happy and encourages me to create more open-source projects!**

---

## 中文

# 中国飞行棋 (Chinese Ludo)

经典的中国飞行棋游戏完整实现，使用纯 JavaScript 编写。这是 GitHub 上最早的开源中国飞行棋游戏之一。

## 📋 游戏简介

中国飞行棋是许多人童年的经典棋盘游戏，类似 Ludo 但有独特的规则：
- **颜色飞跃** - 跳到下一个同色格子
- **飞行通道** - 棋盘上的特殊捷径
- **安全区** - 彩色格子可保护棋子
- **掷出 6** - 获得额外回合

## 🎮 游戏特色

- ✅ **纯客户端** - 无需服务器，浏览器直接运行
- ✅ **零依赖** - 纯 JavaScript，无需框架
- ✅ **2-4 人游戏** - 支持 2、3 或 4 人对战
- ✅ **响应式设计** - 支持电脑和手机
- ✅ **流畅动画** - 骰子滚动、棋子移动动画
- ✅ **完整规则** - 实现所有传统中国飞行棋规则

## 🎯 怎么玩

### 快速开始

1. 用浏览器打开 `game.html`
2. 选择玩家人数（2-4 人，选择颜色）
3. 点击"开始游戏"
4. 点击骰子按钮掷骰子
5. 点击棋子移动

### 游戏规则

**起飞规则：**
- 掷出 **6** 才能让棋子离开基地（飞机起飞）
- 掷出 6 后可以**再掷一次**

**移动规则：**
- 掷骰子后选择一个棋子移动
- 棋子顺时针绕棋盘移动

**特殊规则：**
- 🎯 **颜色飞跃**：停在相同颜色的格子上 → 跳到下一个同色格子
- ✈️ **飞行通道**：颜色飞跃后，如果在飞行通道上，可以飞跃棋盘
- 🛡️ **安全区**：主路径上的彩色格子不会被吃掉
- ⚔️ **吃子**：停在对手棋子位置 → 将其送回基地

**胜利条件：**
- 第一个让**所有 4 个棋子**到达中心的玩家获胜！

## 🚀 开始游戏

### 方法 1：直接打开
用 Chrome、Firefox、Safari 或 Edge 浏览器直接打开 `game.html`

### 方法 2：本地服务器
```bash
# 使用 Python
python -m http.server 8000

# 使用 Node.js
npx serve

# 然后访问 http://localhost:8000
```

### 方法 3：GitHub Pages
1. Fork 本仓库
2. 在 Settings 中启用 GitHub Pages
3. 选择 `game.html` 作为源文件
4. 通过 `https://your-username.github.io/chinese-ludo` 访问

## 🔧 技术细节

- **语言：** 纯 JavaScript (ES6+)
- **无框架：** 不依赖 React、Vue、jQuery - 纯原生 JS！
- **浏览器支持：** Chrome 60+、Firefox 60+、Safari 12+、Edge 79+
- **文件大小：** 总计 < 50KB

## 🎯 为什么做这个项目？

当我在 GitHub 上搜索"中国飞行棋 Chinese Ludo"时，发现很少能找到完整可用的项目。大多数项目要么：
- 功能不完整
- 配置复杂
- 缺少颜色飞跃和飞行通道等关键规则

**本项目的目标是：**
- ✅ 功能完整、可直接游戏
- ✅ 简单易用（直接打开 HTML 文件）
- ✅ 忠实于中国飞行棋原版规则
- ✅ 中英文双语文档

## 🤝 贡献

欢迎贡献！你可以：
- 🐛 报告问题
- 💡 提出新功能建议
- 🔧 提交代码
- 📖 改进文档

## 📄 许可证

MIT 许可证 - 可以自由用于学习、个人项目或商业应用。

## ⭐ 支持本项目

如果你觉得这个项目有用：
1. ⭐ **给项目点星**
2. 🍴 **Fork** 如果你想修改它
3. 📢 **分享** 给其他可能需要的人

**每一个星星都是对我的鼓励，让我有动力创作更多开源项目！**

---

**⭐ 如果觉得好，请先收藏和点亮星星⭐，然后再下载程序！谢谢支持！**
