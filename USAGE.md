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

输出的Prompt是**英文的**，可以直接喂给任何AI生图工具，比如 GPT-image、Midjourney、Gemini、即梦、可灵等。

---

## 怎么用（最简单的方式）

**这个skill兼容所有AI**——ChatGPT、Claude、Gemini、豆包、Kimi、DeepSeek 都可以。

只需要 3 步：

### 第 1 步：解压下载的 zip

下载 `amazon-image-prompt-v3.zip` 后，解压，得到一个 `SKILL.md` 文件。

### 第 2 步：复制 SKILL.md 全部内容

用任何文本编辑器（记事本、备忘录都行）打开 `SKILL.md`，**全选 → 复制**。

### 第 3 步：粘贴到 AI 对话框，加上你的产品信息

打开你常用的AI（ChatGPT / Claude / Gemini / 任意），新建对话：

1. **粘贴** 整个 SKILL.md 内容
2. **回车换行**
3. **填好产品信息**（用下方"输入模板"）
4. **发送**

AI 会按 skill 的逻辑，输出 6 段英文 Prompt，复制粘贴到生图工具就能用。

---

## 输入模板

把下面的模板填好，跟在 SKILL.md 后面一起发给 AI：

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

AI 会按以下结构输出（每个产品都不一样）：

```
## 1. 主图 (Hero Image)
Prompt:
A pristine white background product shot of [产品],
clean studio lighting, photorealistic, ...

## 2. 生活方式图 (Lifestyle)
Prompt:
A young couple enjoying a sunset picnic with [产品]
on a wooden deck overlooking ...

[共6段]
```

**直接复制每段Prompt → 粘贴到生图工具 → 出图**

---

## 进阶：在 Claude 桌面版长期使用

如果你经常用，每次复制粘贴有点麻烦。可以装到 Claude 桌面版里，永久生效：

1. 下载 Claude 桌面版（claude.ai/download）
2. Settings → Capabilities → Skills，启用 Skills 功能
3. 把解压后的 skill 文件夹放到 Claude 的 skills 目录
4. 重启 Claude

之后直接对话，Claude 会自动识别 skill。**详细配置方法在星球答疑区。**

---

## 实战 Tips

### Tip 1：跑出来不满意？让AI改

直接说："第3张痛点图改成更夸张的对比效果，强调收纳前后差距"

AI 会重新生成那一段。

### Tip 2：英文 Prompt 跑出来的图风格不统一？

把 6 段 Prompt 一起发给 AI，让它**统一加上风格描述词**，例如：
- "all images: cinematic lighting, warm tone, high contrast"

### Tip 3：生图工具怎么选？

- **追求质感**：GPT-image / Midjourney
- **追求中文场景准确**：即梦 / 可灵
- **免费跑量**：Gemini

每个工具风格都不一样，建议都试一下，找最贴合你产品的那个。

### Tip 4：图出来不能直接用怎么办？

AI 生图作为**素材底图**，再用 Photoshop / Canva 加文字、徽章、卖点标注。

直接发上亚马逊的图，**85%的情况都需要人工再修一遍**——AI 是来加速，不是替代。

---

## 常见问题

**Q：可以在哪个AI上用？**
A：任何AI都可以。ChatGPT、Claude、Gemini、豆包、Kimi、DeepSeek 都跑过，效果都不错。

**Q：英文Prompt我看不懂，怎么验证质量？**
A：直接喂给生图工具看结果就行。或者让AI把Prompt翻译成中文给你看一下逻辑对不对。

**Q：生出来的图能直接做主图吗？**
A：不建议。亚马逊主图有严格规则（白底、产品占85%等），AI图基本要再加工。

**Q：免费版的AI够用吗？**
A：跑1-2个产品没问题。多了可能触发额度限制，建议升级Plus/Pro。

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
