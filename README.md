# 🎮 wyj的个人网站 - 8-bit复古风格

一个融合现代Web技术与复古游戏元素的创新个人网站，带有隐藏的科纳米秘籍彩蛋和完整的贪吃蛇游戏！

## 🌟 项目亮点

### 🎯 核心特色
- 📱 **响应式设计** - 完美适配桌面、平板、手机
- 🌓 **深色/浅色主题切换** - 用户友好的视觉体验
- 🎮 **科纳米秘籍彩蛋** - 隐藏的8-bit复古模式
- 🐍 **完整贪吃蛇游戏** - 纯JavaScript实现的经典游戏
- ⚡ **现代Web技术** - ES6+、Flexbox、Grid、Web Audio API

### 🎨 设计理念
将经典复古游戏文化与现代网页设计完美融合，为访客提供既实用又充满惊喜的浏览体验。

## 🗂️ 项目结构

```
my-homeproject/
├── 📄 index.html          # 主页 - 打字机效果、博客系统
├── 👤 about.html          # 关于页 - 动态技能条、雷达图
├── 💼 portfolio.html      # 项目展示 - GitHub API集成、语言过滤
├── 📞 contact.html        # 联系页面
├── 🐍 snake-game.html     # 贪吃蛇游戏页面
├── 🎨 style.css           # 主样式文件 + 复古主题
├── 📝 posts/              # 博客文章目录
│   ├── post1.md           # Markdown博客文章
│   ├── post2.md
│   ├── post3.md
│   └── posts.json         # 博客元数据
└── 📖 README.md           # 项目说明文档
```

## 🚀 主要功能

### 🎪 主页 (index.html)
- **✨ 动态打字机效果** - 循环展示个人介绍
- **📚 Markdown博客系统** - 支持本地Markdown文件解析
- **🎭 双栏布局动画** - 点击文章标题的优雅过渡效果

### 👨‍💻 关于页面 (about.html)
- **📊 动态技能条** - 使用Intersection Observer API触发动画
- **🕸️ 技能雷达图** - Chart.js可视化多维技能数据
- **🎯 一次性动画** - 滚动进入视口时触发，避免重复播放

### 💻 项目展示 (portfolio.html)
- **🔗 GitHub API集成** - 自动获取公开仓库数据
- **🏷️ 智能语言过滤** - 动态生成编程语言标签
- **🎴 项目卡片系统** - 面向对象的ProjectCard类设计
- **⚡ 实时更新** - GitHub仓库变化自动同步

### 📧 联系页面 (contact.html)
- **📱 多渠道联系方式** - 邮箱、社交媒体等
- **🎨 统一视觉风格** - 与整站设计保持一致

## 🎮 科纳米秘籍系统

### 🕹️ 激活方式

#### 🖥️ **桌面端**：
在任意页面依次按键：**↑ ↑ ↓ ↓ ← → ← → B A**

#### 📱 **手机端**：
使用手指在屏幕上依次执行：
1. **向上滑动** ↑ (2次)
2. **向下滑动** ↓ (2次) 
3. **向左滑动** ← (1次)
4. **向右滑动** → (1次)
5. **向左滑动** ← (1次)
6. **向右滑动** → (1次)
7. **轻点屏幕** 👆 (2次)

> 💡 **提示**：手势操作需在3秒内完成，滑动距离不少于30像素

### 🌈 8-bit复古模式特效
- **🎨 视觉变换** - 霓虹绿主色调、像素风格界面
- **🎵 复古音效** - Web Audio API生成的8-bit音乐
- **✨ 动画效果** - 像素雨、网格移动、霓虹发光
- **🔄 状态持久化** - 跨页面保持复古模式状态
- **🎪 入场动画** - 渐变缩放+模糊效果

### 🎯 跨页面功能
- **💾 localStorage状态管理** - 页面跳转不丢失游戏模式
- **🎮 游戏入口按钮** - 复古模式下显示贪吃蛇游戏入口
- **🔚 优雅退出** - 只有点击EXIT按钮才能退出模式

## 🐍 贪吃蛇游戏

### 🎮 游戏特色
- **🔧 纯原生JavaScript** - 无需外部游戏框架
- **🎨 Canvas 2D渲染** - 高性能图形绘制
- **🔊 8-bit音效系统** - 吃食物、升级、游戏结束音效
- **🏆 本地排行榜** - localStorage保存最高分记录

### 🕹️ 游戏机制
- **🎯 智能操作** - 按方向键自动开始游戏
- **📈 等级系统** - 每100分升级，速度递增
- **💀 碰撞检测** - 墙壁碰撞、自身碰撞判断
- **📱 多平台控制** - 键盘方向键、WASD、触屏按钮

### 🎨 视觉效果
- **✨ 霓虹发光效果** - 蛇头、蛇身、食物的发光渲染
- **🌟 动态背景** - 像素雨、网格动画
- **🎪 模态框动画** - 游戏结束的优雅提示
- **📱 响应式界面** - 适配不同屏幕尺寸

## 🛠️ 技术栈

### 前端核心技术
- **📱 HTML5** - 语义化标签、Canvas API
- **🎨 CSS3** - Flexbox、Grid、动画、渐变
- **⚡ JavaScript ES6+** - 类、模块、异步编程

### 高级JavaScript特性
- **🔄 异步编程** - `async/await`、`fetch` API
- **🏗️ 面向对象** - Class、Constructor、原型方法
- **🎯 函数式编程** - `map`、`filter`、`reduce`
- **👀 观察者模式** - Intersection Observer API
- **🎵 Web Audio API** - 动态音效生成

### 第三方库集成
- **📝 Marked.js** - Markdown解析和渲染
- **📊 Chart.js** - 数据可视化图表
- **🔗 GitHub API** - 仓库数据获取

### 现代Web特性
- **💾 localStorage** - 客户端数据持久化
- **📱 响应式设计** - 移动优先的布局策略
- **🎨 CSS自定义属性** - 主题色彩管理
- **⚡ 事件委托** - 高效的事件处理

## 🎯 核心技术实现

### 🖊️ 打字机效果
```javascript
class TypeWriter {
    constructor(textArray, typeSpeed, deleteSpeed, pauseTime) {
        // 实现字符逐个打印和删除的动画效果
    }
}
```

### 📊 动态技能条
```javascript
class SkillBarAnimator {
    constructor() {
        // 使用Intersection Observer API实现滚动触发动画
        this.observer = new IntersectionObserver(this.animateSkillBars);
    }
}
```

### 🎮 科纳米秘籍检测
```javascript
class KonamiCodeManager {
    constructor() {
        this.konamiCode = ['ArrowUp', 'ArrowUp', 'ArrowDown', 'ArrowDown', 
                          'ArrowLeft', 'ArrowRight', 'ArrowLeft', 'ArrowRight', 
                          'KeyB', 'KeyA'];
        // 实现按键序列检测和状态管理
    }
}
```

### 🐍 游戏引擎
```javascript
class SnakeGame {
    gameLoop() {
        // 游戏主循环：移动、碰撞检测、绘制
    }
    
    draw() {
        // Canvas 2D渲染：蛇身、食物、特效
    }
}
```

## 📱 响应式设计

### 🖥️ 桌面端 (≥768px)
- 完整功能展示
- 大尺寸游戏画布
- 丰富的动画效果

### 📱 移动端 (<768px)
- 紧凑布局设计
- 触屏优化控制
- 性能优化处理

### 🎯 关键断点
```css
@media (max-width: 768px) { /* 平板适配 */ }
@media (max-width: 480px) { /* 手机适配 */ }
```

## 🔧 本地运行

### 📋 环境要求
- 现代浏览器 (Chrome 80+, Firefox 75+, Safari 13+)
- 本地HTTP服务器 (推荐)

### 🚀 快速启动
```bash
# 克隆项目
git clone [your-repo-url]
cd my-homeproject

# 启动本地服务器 (Python)
python -m http.server 8000

# 或使用Node.js
npx http-server

# 浏览器访问
http://localhost:8000
```

### 🎮 体验科纳米秘籍

#### 🖥️ **桌面端体验**：
1. 打开网站任意页面
2. 依次按键：↑ ↑ ↓ ↓ ← → ← → B A
3. 享受8-bit复古世界！
4. 点击"🐍 贪吃蛇游戏"进入游戏

#### 📱 **手机端体验**：
1. 打开网站任意页面
2. 用手指按顺序滑动：上上下下左右左右+点击两次
3. 看到激活提示后享受复古模式！
4. 触摸游戏按钮进入贪吃蛇游戏

## 🎨 自定义配置

### 🎯 个性化设置
```javascript
// 修改打字机文本
const texts = [
    '你好，我是wyj',
    '一名计算机开发爱好者',
    '期待与你的相遇'
];

// 调整技能数据
const skillsData = {
    labels: ['前端开发', '后端开发', '数据库', '算法', '项目管理', '团队协作'],
    data: [85, 75, 70, 80, 75, 90]
};

// 更新GitHub用户名
const GITHUB_USERNAME = 'aniamdwyj';
```

### 🎨 主题色彩
```css
:root {
    --primary-color: #8b7355;
    --secondary-color: #6b5b73;
    --accent-color: #5d4e6d;
    --retro-green: #00ff41;
    --retro-red: #ff6b6b;
    --retro-cyan: #4ecdc4;
}
```

## 📈 性能优化

### ⚡ 加载优化
- **🖼️ 图片懒加载** - Intersection Observer实现
- **📦 代码分割** - 按需加载第三方库
- **🗜️ 资源压缩** - CSS/JS文件优化

### 🎮 游戏性能
- **🎯 高效碰撞检测** - 优化算法减少计算量
- **🎨 Canvas优化** - 合理的重绘策略
- **📱 移动端适配** - 降低复杂动画开销

## 🔮 未来规划

### 🚀 功能扩展
- [ ] 🎵 更多8-bit背景音乐
- [ ] 🎮 新增经典游戏 (俄罗斯方块、打砖块)
- [ ] 🌍 多语言支持
- [ ] 💬 评论系统集成

### 🛠️ 技术升级
- [ ] ⚡ PWA支持 (离线缓存)
- [ ] 🔄 Vue.js/React重构
- [ ] 📊 访问统计分析
- [ ] 🎨 主题编辑器

## 📄 开源协议

本项目采用 MIT 协议开源，欢迎 Fork 和贡献代码！

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📧 联系方式

- **开发者**: wyj
- **项目地址**: [GitHub Repository]
- **演示网站**: [Live Demo]

---

## 🎮 彩蛋提示

> *"有些最好的发现来自于意外的探索..."*
> 
> 试试在键盘上输入一些经典的游戏秘籍，也许会有惊喜等着你！ 😉

**记住**: ↑ ↑ ↓ ↓ ← → ← → B A

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给个Star支持一下！ ⭐**

Made with ❤️ by wyj | © 2024

</div>
