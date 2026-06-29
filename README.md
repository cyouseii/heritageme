<h1 align="center">Heritage Me · 非遗盲盒</h1>

<p align="center">
  <em>一物一世界，一器一灵魂 &nbsp;|&nbsp; One Object, One Soul</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/lang-中文_|_日本語_|_English-brightgreen" alt="languages" />
  <img src="https://img.shields.io/badge/tech-HTML_|_CSS_|_JS-blue" alt="tech" />
  <img src="https://img.shields.io/badge/items-14-red" alt="items" />
</p>

---

## 项目简介 | About

**Heritage Me（非遗盲盒）** 是一款面向中日青年的跨文化传播互动网页。用户通过选择语言、情绪状态、审美偏好等多维度问题，生成专属的「非遗人格卡片」，在探索自我的过程中自然接触中国传统非遗文化。

项目借鉴了日本青年群体熟悉的**扭蛋文化**与**人格测试**逻辑，以轻互动的形式降低文化理解门槛，探索非遗数字化传播与跨文化沟通的新可能。

**Heritage Me** is an interactive cross-cultural web experience designed for Chinese and Japanese youth. By answering questions about language, mood, and aesthetic preferences, users unlock a personalized "ICH Personality Card" — discovering Chinese intangible cultural heritage through self-exploration.

Drawing inspiration from Japan's **gacha (capsule toy)** culture and personality quiz formats, the project lowers cultural barriers through playful interaction, exploring new possibilities for digital heritage communication.

---

## 交互流程 | User Flow

```
语言选择 → 情绪状态 → 审美偏好 → 盲盒仪式 → 专属卡片
Language → Emotion  →   Vibe    →  Unboxing  →  Result Card
```

| 步骤 | Step | 说明 |
|------|------|------|
| 🌐 语言 | Language | 中文 / 日本語 / English |
| 🎭 情绪 | Emotion | 9种情绪状态选择 |
| 🎨 偏好 | Vibe | 多选审美风格标签 |
| 📦 开盒 | Unbox | 震动+发光仪式动画 |
| 🃏 结果 | Result | 生成个性化非遗人格卡片 |

---

## 非遗内容 | Heritage Items

涵盖14项中国非物质文化遗产，按类型分组：

| 类别 | 项目 |
|------|------|
| 🏺 陶瓷 | 青花瓷、紫砂壶、唐三彩 |
| 🎭 戏曲 | 皮影戏、京剧、昆曲 |
| 🧵 织绣 | 苏绣、云锦、蜡染 |
| 🎋 工艺 | 剪纸、竹编、漆器 |
| 🎵 音乐 | 古琴、编钟 |

---

## 技术栈 | Tech Stack

- **纯前端**：HTML + CSS + JavaScript，零依赖
- **响应式设计**：适配移动端与桌面端
- **三语支持**：中/日/英切换
- **CSS 动画**：盒子震动、粒子爆发、卡片揭示等东方美学动画

---

## 快速开始 | Quick Start

```bash
# 克隆仓库
git clone https://github.com/cyouseii/heritageme.git

# 直接用浏览器打开
open index.html

# 或启动本地服务器
python -m http.server 8080
# 访问 http://localhost:8080
```

---

## 在线体验 | Live Demo

🌐 **[cyouseii.github.io/heritageme](https://cyouseii.github.io/heritageme)**

---

## 项目结构 | Structure

```
heritageme/
├── index.html                # 主页面（单文件应用）
├── heritage-images/          # 非遗素材图片
│   ├── 01-qinghuaci.png      # 青花瓷
│   ├── 02-piying.png         # 皮影
│   └── ...
├── README.md                 # 本文件
└── .gitattributes
```

---

## 设计理念 | Design Philosophy

项目试图回答的核心问题：

> 面对日本青年对中国传统文化「知其貌不知其义」的现状，能否通过契合日本文化传统的讲述方式降低文化折扣？

三个设计原则：

1. **低门槛进入** — 以游戏化互动替代知识灌输
2. **文化转译** — 用目标受众熟悉的表达方式重新编码
3. **自我驱动** — 让用户在探索自身的过程中连接文化

---

## 许可 | License

MIT

---

<p align="center">
  <sub>Made with ❤️ for cross-cultural understanding<br/>
  <a href="https://github.com/cyouseii">@cyouseii</a></sub>
</p>
