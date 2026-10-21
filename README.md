# 法界相应 · 姓名法界相应点五行解读（fajie-xiangying）

一个可以装进任意 AI 助手（Claude、ChatGPT、Cursor、Grok 等）的 **Agent Skill**。它按传统姓名学的“法界相应点 + 偏旁五行 + 生克六亲”方法，从名字里看性格、长相、婚姻、家人与人际、财运、学业和流年大运。

## 一句话使用（复制到你的 AI 对话框）
```
请读取 https://github.com/aigchong-bot/fajie-xiangying/raw/main/SKILL.md 并严格按其中流程加载这个技能，然后开始。
```

> 如果你的智能体打不开 jsDelivr，可换用备用地址：`https://github.com/aigchong-bot/fajie-xiangying/raw/main/SKILL.md`，或直接把 SKILL.md 全文粘贴给它。

AI 读完后会直接发给你一个编号菜单。回复数字，再按提示给出姓名和性别就行。
或者：直接把 `SKILL.md` 的全文粘贴给 AI。SKILL.md 是单文件，所有规则都在里面，不含任何外链，AI 加载后不需要再去读别的网页。

## 作为 Agent Skill 安装（Claude Code 等）
```bash
# 个人技能目录
git clone https://github.com/aigchong-bot/fajie-xiangying ~/.claude/skills/fajie-xiangying
# 或者放进项目目录：.claude/skills/fajie-xiangying
```
其他支持 Agent Skills 规范的工具，把整个文件夹放进它们的 skills 目录即可。

## 菜单预览
1. 性格脾气
2. 长相与身材
3. 婚姻感情
4. 家人与人际
5. 财运
6. 学业
7. 流年大运（某一年或某一段年龄的运势）
8. 全部

## 文件结构
```
SKILL.md   单文件技能：菜单、流程、全部规则表（附录A–E）
evals/     测试提示词与断言
```

## 免责声明
本项目仅供**娱乐与传统文化学习**，结论不是事实判断，**不能替代医疗、法律、财务或心理等专业建议**。技能不判断健康、疾病，不看风水，也不给用药建议。规则整理自姓名学课程资料，人名均已匿名处理，原始讲义和转写不在本仓库中。
