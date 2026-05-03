# 商品图 Prompt Skill · 使用教程

> `amazon-image-prompt-v3` 完整使用文档

---

## 这个 Skill 是干什么的

一键生成亚马逊主图所需的 **6张图的英文Prompt**：

1. **主图** —— 白底产品主图
2. **生活方式图** —— 真实使用场景
3. **痛点图** —— 解决什么问题
4. **卖点图** —— 核心功能特写
5. **规格图** —— 尺寸/材质等参数
6. **对比差异化图** —— 和竞品的差异

输出的Prompt是**英文的**，可以直接喂给：

- ChatGPT 的 GPT-4o / GPT-image
- Midjourney
- Gemini Nano Banana
- 即梦 / 可灵 等国产AI生图工具

---

## 准备工作

### 1. 你需要有 Claude

这个 skill 是为 **Claude** 设计的（claude.ai 或 Claude 桌面版均可）。

如果你还没用过Claude：

- 网页版：访问 [claude.ai](https://claude.ai)
- 桌面版：[claude.ai/download](https://claude.ai/download)

免费版即可使用，但建议升级 Claude Pro（每月 20 美元），消息额度更多，跑大任务更稳。

### 2. 解压下载的 zip

下载 `amazon-image-prompt-v3.zip` 后，解压会得到一个文件夹：

```
amazon-image-prompt/
├── SKILL.md          ← 核心skill文件
└── (其他辅助文件)
```

---

## 三种使用方式

### 方式一：Claude.ai 网页版（推荐小白）

**操作步骤：**

1. 打开 [claude.ai](https://claude.ai)，登录
2. 新建一个对话
3. 把整个 `amazon-image-prompt` 文件夹拖到对话框里上传
4. 输入你的产品信息（见下方"输入模板"）
5. 等 Claude 输出 6 段英文 Prompt

**优点**：操作最简单，零门槛
**缺点**：每次都要重新上传 skill

---

### 方式二：Claude 桌面版 + Skills 功能

**操作步骤：**

1. 下载并安装 Claude 桌面版
2. 打开 Settings → Capabilities → Skills
3. 启用 Skills 功能
4. 把解压后的 `amazon-image-prompt` 文件夹放到 Claude 的 skills 目录下
5. 重启 Claude
6. 之后每次直接对话，Claude 会自动识别并调用这个 skill

**优点**：永久生效，不用每次上传
**缺点**：需要桌面版，配置稍复杂

详细配置方法见星球答疑区。

---

### 方式三：复制 SKILL.md 的内容直接用（兜底方案）

如果上面两种方式都用不了：

1. 用文本编辑器打开 `SKILL.md`
2. 复制全部内容
3. 粘贴到 Claude / ChatGPT / Gemini 的对话框
4. 紧接着输入你的产品信息

**优点**：任何AI都能用
**缺点**：每次都要复制粘贴，麻烦

---

## 输入模板

把下面的模板填好，发给Claude：

```
我要为以下产品生成亚马逊6张图的英文prompt：

【产品名】：（中文+英文都写，例如：折叠桌 / Folding Table）
【目标人群】：（例如：露营爱好者 / 小户型家庭）
【核心卖点】：
1. 
2. 
3. 

【使用场景】：（例如：户外野餐、阳台、客厅）
【主要痛点】：（例如：传统桌子太大不便携）
【差异化优势】：（和竞品比，你最强的1-2个点）
【参考价格】：（例如：$59.99）
【材质/尺寸】：（例如：铝合金，60×40×30cm）

请按skill的逻辑，输出6张图的英文Prompt。
```

---

## 输出示例

Claude 会按以下结构输出（每个产品都不一样）：

```markdown
## 1. 主图 (Hero Image)
**Prompt:**
A pristine white background product shot of [产品], 
clean studio lighting, 4K, photorealistic, ...

## 2. 生活方式图 (Lifestyle)
**Prompt:**
A young couple enjoying a sunset picnic with [产品] 
on a wooden deck overlooking ...

[共6段]
```

**直接复制每段Prompt → 粘贴到生图工具 → 出图**

---

## 实战 Tips

### Tip 1：跑出来不满意？让Claude改

直接说："第3张痛点图改成更夸张的对比效果，强调收纳前后差距"

Claude 会重新生成那一段。

### Tip 2：英文 Prompt 跑出来的图风格不统一？

把 6 段 Prompt 一起发给 Claude，让它**统一加上风格描述词**，例如：
- "all images: cinematic lighting, warm tone, high contrast"

### Tip 3：生图工具选哪个？

- **追求质感**：Midjourney v6 / GPT-image
- **追求中文场景准确**：即梦
- **免费跑量**：Gemini Nano Banana

### Tip 4：图出来不能直接用怎么办？

AI 生图作为**素材底图**，再用 Photoshop / Canva 加文字、徽章、卖点标注。

直接发上亚马逊的图，**85% 的情况都需要人工再修一遍**——AI 是来加速，不是替代。

---

## 常见问题

**Q：免费版Claude够用吗？**
A：跑1-2个产品没问题。多了会触发额度限制，建议升级Pro。

**Q：可以用ChatGPT/Gemini代替吗？**
A：用方式三可以。但效果上Claude对skill的执行最稳，ChatGPT次之。

**Q：英文Prompt我看不懂，怎么验证质量？**
A：直接喂给生图工具看结果就行。或者让Claude把Prompt翻译成中文给你看。

**Q：生出来的图能直接做主图吗？**
A：不建议。亚马逊主图有严格规则（白底、产品占85%等），AI图基本要再加工。

---

## 还想要更多？

这只是 4 个 skill 中的 1 个。

完整工作流（评分 → 调研 → Listing → 图片）在**知识星球**提供：

- **亚马逊-东哥的AI工作流**（扫码加入）
- 持续更新版本
- 实战问题答疑
- 更多卖家工具陆续上新

---

## 反馈与建议

- 公众号留言：**假装很自律**
- 星球内置反馈：成员可直接发帖

---

*文档版本：v3 · 最后更新：2026年*
