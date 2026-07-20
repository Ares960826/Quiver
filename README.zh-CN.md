![Quiver——让可复用 Prompt 卡片飞回林间箭袋](assets/brand/quiver-cover.jpg)

# Quiver

[English](README.md) · [简体中文](README.zh-CN.md) · [한국어](README.ko.md)

**面向 macOS 的本地优先 Prompt 管理器与可复用模板启动器。**

## Why｜为什么需要 Quiver？

还在把四处收集珍藏的 Prompt 记在 Notion、Typora 或 Obsidian 里？还在手动
一遍遍复制粘贴——小拇指不酸吗，腱鞘炎不疼吗？好不容易找到的 Prompt，
上次用完，下次又丢？

花一个小时精雕细琢的 Prompt，下次还要重写？工作五分钟，Prompt 两小时？

可以来试试 **Quiver**：把 Prompt 存成一支 **Arrow**，把会变的部分挖成空格子；
下次只需搜索、填空、发射。同一套架子，换几个元素就能反复使用，也能轻松分享。

它当然也是一款轻量的泛 Prompt 管理器：短句、完整 Prompt、可填写模板和长篇
专业指令都能收纳。太小不值得做成 Skill 或 MCP，却又确实反复要用？正好交给 Quiver。

![从精心编写 Prompt、挖出空格子并把模板装进箭袋，到下次任务直接填写复用](assets/readme/reuse-story.jpg)

## What｜什么是 Arrow？

每条保存的 Prompt 都是一支 **Arrow（箭）**。保留稳定架子，只标出每次
变化的元素：

```markdown
请从{{视角}}解释{{概念}}，给出公式推导和一个面向{{受众}}的完整实例。
使用{{语言}}回答。
```

Quiver 会把每个 `{{空格子}}` 变成小表单。填写、预览，然后把完整 Prompt
复制到任意 AI Chat、IDE 或终端中。

没有空格子的 Prompt 也仍是一支 Arrow，可以直接复制。所有 Arrow 都只是
普通 Markdown 文件，因此即使离开 Quiver，仍然可以阅读、携带和传播。

## Where｜它处在哪条赛道？

| 当前需求 | 更合适的工具 |
|---|---|
| 更快表达刚刚想到的内容 | 语音输入或智能输入法 |
| 精确复用文字或一套纯文本架子 | **Quiver** |
| 调用工具或反复自动执行流程 | Skill、MCP 或 Agent |

真正的边界不是长度，而是行为：价值主要来自文字，并且只想在主动选择时
加入上下文，就适合保留为 Arrow；需要调用工具或自动行动时，再升级为工作流。

## How｜如何使用？

1. 把 Prompt 以 `.md` 文件保存在专用文件夹中。
2. 按下你在 Quiver 中配置的全局快捷键。
3. 输入自己记得的几个词进行搜索。
4. 填写空格子，按 `Return` 复制完整 Prompt。

Quiver 会同时模糊搜索标题、标签、分组和正文。最近常用的 Arrow 会自然
上升，不需要进入额外模式。

## Showcase｜实际使用是什么样？

**[打开完整图文展示 →](docs/SHOWCASE.zh-CN.md)**——集中查看 Quiver 的
Prompt 库、模板编辑器、空格子类型、分组和元模板输出，不让主页变成冗长的截图墙。

## Tips｜有哪些值得知道的技巧？

### 先收纳，后整理

刚复制到一段值得留下的内容？呼出 Quiver，点击**收纳**，或按下 `⌘⇧V`。
剪贴板内容会立刻变成一支 Arrow：Quiver 自动生成标题并添加 `#收纳箱` 标签，
全程不弹导入表单。等有空时搜索“收纳箱”，再慢慢改名、分组或挖成模板。

### 让 AI Agent 直接往箭袋里装箭

设置中显示的 **Prompt 文件夹**就是 Quiver 的根目录，每支 Arrow 都只是普通的
Markdown 文件。因此，可以让具备文件读写能力的 AI Agent 直接在该目录中批量
创建、翻译或整理 `.md` Prompt，不必逐条手工导入。Quiver 会在下次呼出时发现
外部改动；仅有正文的 Markdown 也能使用，写入 `{{名称}}` 就会生成可填写的空格子。

请只把专用 Prompt 文件夹交给 Agent，不要把普通笔记库作为根目录；大批量写入前，
先让 Agent 列出准备创建的文件名供你确认。

## Now｜目前能做什么？

- 使用一个可自定义的快捷键，在当前 App 上方呼出 Quiver。
- 创建、编辑、搜索并整理完整 Prompt 和模板。
- 使用文字、选项和剪贴板空格子，并实时预览结果。
- 在设置中切换英文与简体中文界面。
- 使用夜晚、白天、护眼、色盲友好和高对比度主题。
- 所有内容保持本地：无需账号，也不会上传 Prompt 正文。

Prompt 文件永远是真相。Quiver 可能写入稳定的 `id` 和 `updated_at` 元数据，
但使用历史只保存在可以随时重建的本地缓存中。

本仓库是 Quiver 的官方分发与用户支持主页，仅包含面向用户的文档和可下载
版本；开发源码及内部项目历史保持私有。

> **请选择只存放 Prompt 的文件夹。** 不要选择 Obsidian 仓库、文档树或普通
> 笔记目录，否则其中每个 Markdown 文件都会被视为 Prompt。云盘目录必须
> 始终下载在本机。

## Download｜如何安装 Community Preview？

直接打开[当前 Community Preview Release](https://github.com/Ares960826/Quiver/releases/tag/v0.1.1-preview.1)查看说明，或按 Mac 类型直接下载：

| Mac | 直接下载 |
|---|---|
| Apple Silicon（M1–M4） | [下载 `Quiver_0.1.1_aarch64.dmg`](https://github.com/Ares960826/Quiver/releases/download/v0.1.1-preview.1/Quiver_0.1.1_aarch64.dmg) |
| Intel | [下载 `Quiver_0.1.1_x64.dmg`](https://github.com/Ares960826/Quiver/releases/download/v0.1.1-preview.1/Quiver_0.1.1_x64.dmg) |

1. 在上表中选择与你的 Mac 匹配的版本。
2. 使用 [`SHA256SUMS.txt`](https://github.com/Ares960826/Quiver/releases/download/v0.1.1-preview.1/SHA256SUMS.txt)核验文件，然后把 Quiver 拖入“应用程序”。
3. 先尝试打开一次。如果 macOS 阻止运行，请进入**系统设置 → 隐私与安全性
   → 仍要打开**，再确认**打开**。

Community Preview 采用 ad-hoc 签名，没有经过 Apple 公证。这是无需购买 Apple
Developer 会员进行分发的公开限制；Preview 更新暂时需要手动下载安装。

## Next｜接下来做什么？

- [x] **macOS 本地基础能力**——搜索、模板、编辑器和中英文界面。
- [ ] **Windows 版本**——macOS 之后的第一个平台目标。
- [ ] **语音快速匹配**——说出几个记得的词，快速召回 Arrow。
- [ ] **网络 Prompt 搜索**——接入 Prompt 聚合与分享平台；始终优先显示本地
  Arrow，网络结果可以直接使用，也可以一键“内化”为用户的本地 Arrow。
- [ ] **Quiver 云同步**——可选的跨设备同步，本地读取永不等待网络。
- [ ] **AI 辅助模板化**——建议哪些元素应该挖成空格子。
- [ ] **Prompt 站点社区**——发布、发现、分享和二次改造模板。

韩文目前仅用于 GitHub 文档；软件界面只包含英文和简体中文。

## Support｜支持 Quiver

如果 Quiver 为你节省了时间，可以自愿支持后续开发。

[![Buy me a book](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20book&emoji=%F0%9F%93%96&slug=ares960826w&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff)](https://buymeacoffee.com/ares960826w)

以下暂时使用个人收款码，仅用于自愿赞赏，不作为购买商品或服务的付款入口；
确认付款前，请务必核对支付 App 显示的收款方和金额。

| 支付宝 | 微信支付 |
|:---:|:---:|
| <img src="assets/support/alipay-qr.PNG" width="220" alt="支付宝自愿赞赏收款码"> | <img src="assets/support/wechat-pay-qr.JPG" width="220" alt="微信支付自愿赞赏收款码"> |

感谢每一位帮助 Quiver 继续前进的朋友，名单见
[赞助感谢名单](SPONSOR_LIST.md)。Buy Me a Coffee 支持者可在留言中写明希望公开的
显示名称；支付宝和微信支持者默认保持匿名，除非本人明确授权公开。

Quiver 不会在软件内投放广告、跟踪 Prompt 内容或出售用户数据访问权。合作联系
方式和其他支持入口完成核验后，也会直接添加在这里。
