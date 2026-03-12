# 🎯 AI PPT 网页工具

> 乱资料 → 可交付 PPT，全程只需要一个网页 + Gamma

**🔗 直接使用：[wilingna.github.io/ai-ppt-web](https://wilingna.github.io/ai-ppt-web/)**

---

## 这是什么？

这是 [AI做PPT三件套工作流](https://github.com/wilingna/ai-ppt-toolkit) 的**网页版升级**。

原来的三件套需要你手动操作三个工具：

```
NotebookLM → Gemini → Gamma
（梳理大纲）  （升级表达）  （生成PPT）
```

现在只需要一个网页，Claude 直接替掉前两步：

```
【本工具】一个网页完成 → 复制 Markdown → Gamma 生成PPT
 Step 1: 资料梳理 + 大纲        （视觉呈现）
 Step 2: 演讲级内容 + 金句标题
```

---

## 两个版本对比

| | 三件套（GitHub Skill版） | 网页工具版 |
|---|---|---|
| 工具数量 | 3个（NLM + Gemini + Gamma） | 1个网页 + Gamma |
| 账号要求 | 3个账号 | OpenRouter账号 |
| 文件上传 | 手动分别处理 | 直接拖拽上传 |
| 适合人群 | 想理解底层逻辑 | 想直接出结果 |
| 推荐场景 | 学习工作流思维 | 日常快速使用 |

> 💡 **两个版本可以并存**。三件套帮你理解"为什么这样做"，网页版帮你"直接做"。建议先看三件套理解逻辑，再用网页版提效。

---

## 使用步骤

### 第一步：准备 OpenRouter API Key
1. 注册 [openrouter.ai](https://openrouter.ai)（支持微信/支付宝充值）
2. 充值 $5 够用约 50-100 次
3. 进入 Keys 页面 → Create Key → 复制

### 第二步：打开工具填写信息
- 填入 API Key（仅在本地浏览器使用，不经过任何服务器）
- 填写汇报主题、时长、汇报对象

### 第三步：上传资料
支持直接上传：
- 📄 PDF
- 📝 Word (.docx)
- 📊 Excel (.xlsx) / CSV
- 🖼 图片 (PNG/JPG)
- 📃 TXT / Markdown

或者直接粘贴文字，越乱越多越好，Claude 会帮你梳理。

### 第四步：生成大纲（Step 1）
Claude 帮你判断：
- 管理层真正关心什么
- 故事线怎么走
- 哪些信息值得放，哪些该舍弃

### 第五步：生成演讲内容（Step 2）
Claude 自动完成：
- 金句化标题（告别"现状分析""存在问题"）
- 场景化扩写
- 去 AI 味表达
- 输出 Gamma 专用 Markdown 格式

### 第六步：导入 Gamma
1. 复制 Markdown
2. 打开 [gamma.app](https://gamma.app) → 粘贴文本
3. ⚠️ **务必选择「保持此文本原样」**
4. 生成，微调视觉细节

---

## 常见问题

**Q：API Key 安全吗？**
Key 只在你本地浏览器里运行，代码完全开源可查，不经过任何第三方服务器。

**Q：每次生成花多少钱？**
完整跑一次（Step1 + Step2）约 $0.05-0.10，$5 够用 50-100 次。

**Q：不会翻墙怎么办？**
OpenRouter 支持国内直连，无需翻墙。

**Q：三件套还能用吗？**
完全可以，不会下架。两个工具定位不同，按需选择。

---

## 关于作者

[@wilingna](https://github.com/wilingna) · 喜欢把 AI 工作流做成真正能用的产品

觉得有用的话点个 ⭐ Star，或者把使用体验告诉我。
