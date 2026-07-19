![Quiver — reusable prompt cards flying back into a woodland quiver](assets/brand/quiver-cover.jpg)

# Quiver

[English](README.md) · [简体中文](README.zh-CN.md) · [한국어](README.ko.md)

**A local-first prompt manager and reusable template launcher for macOS.**

![Save a proven prompt, mark what changes, then fill and reuse it anywhere](assets/readme/reuse-flow.svg)

## Why Quiver?

Some prompts are too valuable to reconstruct from memory, yet too small and
situational to become a Skill, MCP or always-on agent rule.

They may be a reasoning constraint that changes the answer, a teaching style
you carefully refined, a professional brief, or an output structure that
already works. Quiver keeps that wording exact, searchable and dormant until
you choose it.

It is also a general prompt manager: short snippets, complete prompts, reusable
templates and long specialist instructions all live in the same lightweight
library.

## What is an Arrow?

Every saved prompt is an **Arrow**. Keep the stable scaffold and mark only what
changes:

```markdown
Explain {{concept}} from {{perspective}}, with a derivation and a worked
example for {{audience}}. Answer in {{language}}.
```

Quiver turns each `{{slot}}` into a small form. Fill it, preview the completed
prompt and copy the result into any AI chat, IDE or terminal.

No slots? It is still an Arrow—ready to copy immediately. Every Arrow remains
an ordinary Markdown file, so templates are readable, portable and easy to
share even without Quiver.

## Where does it fit?

| Your need | Best fit |
|---|---|
| Say something new more quickly | Voice input or a smart keyboard |
| Reuse precise wording or a text-only scaffold | **Quiver** |
| Run tools or repeat an autonomous workflow | Skill, MCP or agent |

The boundary is behavior, not length. If the value is in the wording and you
want it in context only when selected, keep it as an Arrow. If it must call
tools or act automatically, promote it to a workflow.

## How does it work?

1. Save prompts in a dedicated folder as `.md` files.
2. Press the global hotkey—`⌥Space` by default.
3. Search by whatever words you remember.
4. Fill any slots and press `Return` to copy the completed prompt.

Quiver fuzzy-searches titles, tags, groups and prompt bodies. Recently and
frequently used Arrows naturally rise to the top, without a separate mode.

## What can you do today?

- Summon Quiver above the app you are using with one customizable hotkey.
- Create, edit, search and organize complete prompts and templates.
- Use text, choice and clipboard-powered slots with a live preview.
- Switch the app interface between English and Simplified Chinese.
- Choose from five themes, including low-blue, colour-safe and high-contrast.
- Keep everything local: no account and no prompt-content upload.

Your files remain the source of truth. Quiver may add stable `id` and
`updated_at` metadata, but usage history stays in a disposable local cache.

This repository is Quiver's official distribution and support home. It
contains customer-facing documentation and downloadable releases; development
source and internal project history are maintained privately.

> **Use a prompt-only folder.** Do not select an Obsidian vault, documentation
> tree or general notes folder: every Markdown file inside the selected folder
> is treated as a prompt. Cloud-drive folders must remain downloaded locally.

## How do I install the Community Preview?

Open [Releases](https://github.com/Ares960826/Quiver/releases), then:

1. Download `Quiver_0.1.0_aarch64.dmg` for Apple Silicon or
   `Quiver_0.1.0_x64.dmg` for Intel.
2. Verify the download with `SHA256SUMS.txt` and drag Quiver to Applications.
3. Try to open it once. If macOS blocks it, go to **System Settings → Privacy &
   Security → Open Anyway**, then confirm **Open**.

The Community Preview is ad-hoc signed and not notarized by Apple. This is the
transparent limitation of distributing without a paid Apple Developer
membership; preview updates are installed manually.

## What comes next?

- [x] **Local macOS foundation** — search, templates, editor and bilingual UI.
- [ ] **Windows version** — the first post-macOS platform target.
- [ ] **Voice quick match** — speak a few remembered words to retrieve an Arrow.
- [ ] **Quiver Sync** — optional cross-device sync with local-first reads.
- [ ] **AI-assisted templating** — suggest which elements should become slots.
- [ ] **Prompt community** — publish, discover, share and remix templates.

Korean is provided for repository documentation; the app itself currently
supports English and Simplified Chinese.

## Support Quiver

If Quiver saves you time, you can voluntarily support its continued
development.

[![Buy me a book](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20book&emoji=%F0%9F%93%96&slug=ares960826w&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff)](https://buymeacoffee.com/ares960826w)

The temporary personal collection codes below are for voluntary tips only—not
payment for a product or service. Always verify the recipient shown by your
payment app before confirming.

| Alipay | WeChat Pay |
|:---:|:---:|
| <img src="assets/support/alipay-qr.PNG" width="220" alt="Alipay voluntary support QR code"> | <img src="assets/support/wechat-pay-qr.JPG" width="220" alt="WeChat Pay voluntary support QR code"> |

Thank you to everyone who keeps Quiver moving. See the
[Sponsor List](SPONSOR_LIST.md). Buy Me a Coffee supporters can include the
display name they want published in their message; Alipay and WeChat Pay
supporters remain anonymous unless they explicitly authorize publication.

Quiver does not place ads inside the app, track prompt contents or sell access
to user data. Partnership contact and additional support options will be added
here after verification.
