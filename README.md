# 🍁 故事花园 Story Garden

收集每一个温暖的瞬间。

> 一个基于 GitHub Pages 的互动故事收集站，用来存放和分享那些想讲的故事。

## ✨ 特性

- 🎭 **多分支剧情** - 每个故事支持不同的选择分支
- ❤️ **好感度系统** - 选择影响角色好感度和剧情走向
- 📱 **响应式设计** - 手机桌面都能完美体验
- 🎨 **统一视觉风格** - 温暖的橙金色调主题
- 🚀 **零依赖部署** - 纯静态 HTML，直接推送到 GitHub Pages

## 📁 项目结构

```
story-garden/
├── index.html              # 首页 - 故事列表
├── stories/                # 故事页面目录
│   └── tohma-tea.html     # 稻妻午后 · 与托马的茶会
├── assets/
│   ├── css/common.css      # 公共样式
│   ├── js/                # 公共脚本（待扩展）
│   └── images/            # 图片资源
├── _config.yml            # GitHub Pages 配置
└── README.md
```

## 🚀 部署到 GitHub Pages

1. 点击右上角 **Use this template** 创建你的仓库
2. 进入仓库 Settings → Pages
3. Source 选择 `Deploy from a branch`，Branch 选择 `main` / `root`
4. 点击 Save，稍等几分钟就能访问了！

## 📝 添加新故事

只需要两步：

1. 在 `stories/` 下创建新的 HTML 文件，参考 `tohma-tea.html` 的格式
2. 在 `index.html` 中添加新的故事卡片

剧情数据格式：
```javascript
const scenes = {
    0: {
        text: "对话内容",
        choices: [
            { next: 1, delta: 5, text: "选项1" },
            { next: 2, delta: -5, text: "选项2" }
        ]
    },
    // ...更多场景
}
```

## 🎨 已有故事

### 🍁 稻妻午后 · 与托马的茶会
> 在社奉行邸的走廊上，与托马共度一个安静的午后。
> 枫叶飘落，茶香四溢，有些话，只说给懂的人听。

- **标签：** 原神、多分支、好感度
- **分支数：** 11 个场景节点

---

🌱 用故事温暖时光