# FlowMotion Skill

<p align="center">
  <strong>把一段口播，变成能演示的动态流程图。</strong><br />
  FlowMotion Skill 可以把口播、SRT 字幕、会议碎片和脑暴记录，整理成有结构、有连接逻辑、有出场节奏的流程图与动效 brief。
</p>

<p align="center">
  <a href="https://github.com/julilaoshi/flowmotion-skill"><img alt="给仓库点星" src="https://img.shields.io/badge/给仓库-点星-f6c343?style=for-the-badge&logo=github&logoColor=111111" /></a>
  <a href="./skill/SKILL.md"><img alt="Read Skill" src="https://img.shields.io/badge/Read-Skill-1f6feb?style=for-the-badge" /></a>
  <a href="#安装方式"><img alt="Install" src="https://img.shields.io/badge/Install-111111?style=for-the-badge" /></a>
  <a href="./examples/srt_to_flowchart_example.md"><img alt="Example" src="https://img.shields.io/badge/View-Example-2da44e?style=for-the-badge" /></a>
</p>

Public `v1.0`。这是 FlowMotion Skill 的公开安全版本。

[English](./README.md) | 简体中文

## 演示

<p align="center">
  <img src="./site/assets/flowmotion-skill-demo.gif" alt="FlowMotion Skill 动态流程图演示" width="76%" />
</p>

<p align="center">
  <strong>视频演示：</strong>发布中。
</p>

## 先从这里开始

- [给仓库点星](https://github.com/julilaoshi/flowmotion-skill)
- [阅读 public Skill 文件](./skill/SKILL.md)
- [查看 SRT 转流程图示例](./examples/srt_to_flowchart_example.md)

## 它能帮你做什么

- 把散乱脑暴整理成流程结构。
- 把口播稿或 SRT 字幕转成流程图 brief。
- 为演示、教学、视频解释和产品故事准备流程图方案。
- 设计节点逐步出现、路径逐段揭示的动态流程图规格。
- 为 PPT、HTML、视频或后续 3D 图准备可交接 brief。
- 在实现前先拆清结构、布局、连接线和动效节奏。

## 为什么做这个仓库

很多想法采集会停在文字里。

FlowMotion Skill 处理的是下一步：把已经说出来、写下来、堆在一起的想法，整理成别人能在会议、课堂、视频或产品演示里看懂的流程。

public 版开放的是可复用方法：

- 汇聚碎片输入
- 压缩成主路径
- 设计连接逻辑
- 形成可动效化的视觉 brief

## 本仓库包含什么

- FlowMotion Skill 公开版。
- 公开安全示例。
- flow spec、connection spec、motion timeline 模板。
- 隐私检查和发布检查清单。
- 不包含本地私有工作流文件。

## 本仓库不包含什么

- 私人口播或字幕。
- 本地绝对路径。
- 内部项目报告。
- 内部评分记录或用户聊天原文。
- 私有 Skill 链路细节。
- 受版权保护的第三方案例。
- 浏览器自动化脚本或本地渲染脚本。
- 社交媒体里展示的完整内部生产流。

## 为什么社交媒体版本看起来更强

这个 public 仓库聚焦 FlowMotion Skill 本身。

在我的内部工作流里，更强的演示通常还会叠加：

- 视觉设计 Skill 做最终排版
- coding 工作流实现 HTML 或视频
- 媒体工具导出 GIF / MP4
- 更大量的私有案例和中间资产

public 版开放的是可复用方法和模板，不等于把完整内部生产系统全部放出来。

## 安装方式

### 推荐：让你的 coding agent 帮你安装

打开 Codex、Claude Code 或其他 coding agent，粘贴：

```text
请帮我安装 FlowMotion Skill。

仓库：
https://github.com/julilaoshi/flowmotion-skill

请执行：
1. 先读 README.md 和 skill/SKILL.md
2. 判断当前 coding agent 的 skills 目录在哪里
3. 把 skill/ 文件夹复制或链接到可读取的 skills 目录
4. 确认 skill/SKILL.md 可读
5. 做一个最小测试：把一段乱笔记转成 flow_spec 和 connection_spec
6. 不要改 FlowMotion Skill 的核心规则
```

安装后请重启 coding agent。

## 快速测试

```text
调用 FlowMotion Skill。

把下面这段乱想法转成：
1. 核心判断
2. flow_spec
3. connection_spec
4. motion_timeline

乱想法：
我经常从会议、语音备忘录和文章草稿里收集很多零散笔记。
我想要一个系统把它们分组，找出主路径，去掉噪音，
然后变成一张可以放进演示里的清楚流程图。
```

## 核心流程

FlowMotion Skill 的默认顺序：

1. 收集乱输入。
2. 提取核心判断、节点和关系。
3. 设计布局和连接规则。
4. 交付静态图、动态图或 3D 图可执行 brief。

核心规则：

```text
先结构，再布局，再连接，最后才动效。
```

## 示例与模板

- [SRT 转流程图示例](./examples/srt_to_flowchart_example.md)
- [动效流程图 brief 示例](./examples/motion_flow_brief_example.md)
- [flow_spec 模板](./templates/flow_spec_template.json)
- [layout_spec 模板](./templates/layout_spec_template.json)
- [connection_spec 模板](./templates/connection_spec_template.json)
- [motion_timeline 模板](./templates/motion_timeline_template.json)

## 目录结构

- `skill/SKILL.md` - FlowMotion Skill 公开版
- `agents/openai.yaml` - coding agent 展示元数据
- `examples/` - 公开安全示例
- `templates/` - 可复用 JSON 模板
- `references/` - 隐私与发布边界
- `site/assets/` - README 演示资产

## 默认使用流

1. 先读 `skill/SKILL.md`。
2. 输入公开安全的笔记、SRT 片段或乱想法。
3. 生成 `flow_spec`、`layout_spec`、`connection_spec` 和 `motion_timeline`。
4. 如需结构化文件，用 `templates/` 里的模板承接。
5. 再交给你自己的设计、PPT、视频或 coding 工具执行。

## 语言策略

- `README.md` 用英文优先，方便 GitHub 发现。
- `README.zh-CN.md` 是中文伴随页。
- Skill 名在两个版本里都保持 `FlowMotion Skill`。

## License 与品牌边界

代码、文档、模板和可复用框架采用 MIT License。

品牌身份与官方背书含义保留。见 [BRAND_NOTICE.md](./BRAND_NOTICE.md)。

## 内部版与 public 版边界

Public 开放：

- 方法
- 模板
- 合成示例
- 可复用框架

Public 不包含：

- 私人口播
- 内部项目文件
- 本地渲染脚本
- 私有工作流痕迹
- 未发布生产资产

## 公开边界

这个 public 包只开放可复用方法。

私人口播、内部项目文件、本地路径、未公开案例和个人工作流记录都不会进入 public 版。

见：

- [Privacy Checklist](./references/privacy_checklist.md)
- [Brand Notice](./BRAND_NOTICE.md)
- [Public Release Checklist](./PUBLIC_RELEASE_CHECKLIST.md)

## License

可复用代码、文档、模板和框架采用 MIT License。

品牌身份保留。见 [BRAND_NOTICE.md](./BRAND_NOTICE.md)。
