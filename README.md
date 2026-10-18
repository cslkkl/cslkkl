<picture>
  <source media="(max-width: 600px)" srcset="assets/banner-mobile-en.jpg">
  <img src="assets/banner-en.jpg" alt="KKLCSL — Follow the problem." width="100%">
</picture>

**I build tools for problems I run into, and share the useful ones.**
Currently working on AI workflows, DeepSeek Harness plugins, and music visualization.
<sub>(English · [中文](README.zh.md) · [toolboxonline.online](https://toolboxonline.online) — the same work as a web page)</sub>

## Selected work

### dsh-web-annotator

**Circle the problem on the page, then hand it to the Agent.**
In the DSH Browser, select part of a page, comment in place, then send the marked screenshot or the DOM locator into the session.

<a href="https://github.com/cslkkl/dsh-web-annotator"><img src="assets/dsh-web-annotator.png" alt="A region of a web page selected inside the DSH Browser, with the comment written in place next to it" width="100%"></a>

[View project](https://github.com/cslkkl/dsh-web-annotator) · [npm](https://www.npmjs.com/package/dsh-web-annotator)

### dsh-cpa-switch

**One less console tab: CLIProxyAPI accounts, managed inside DSH.**
Check balance, check in and switch accounts without leaving the workspace, and let CPA start and stop with DSH instead of by hand.

<a href="https://github.com/cslkkl/dsh-cpa-switch"><img src="assets/dsh-cpa-switch-demo.png" alt="The CPA switcher panel: four channel tabs, a remaining / used / quota summary, and three account cards labelled Demo Account A, B and C. Demo data, not a real account." width="100%"></a>

<sub>Illustration uses fictional demo accounts and demo balances.</sub>

[View project](https://github.com/cslkkl/dsh-cpa-switch) · [npm](https://www.npmjs.com/package/dsh-cpa-switch)

### discography-showcase

**A record catalogue, arranged as year-rings.**
Eight artists' complete studio discographies — 1,104 tracks — read year by year as concentric rings, with official 30-second previews and a full-screen lyric stage for the audio you own locally.

<a href="https://github.com/cslkkl/discography-showcase"><img src="assets/discography-showcase.png" alt="The year-ring view: one ring per album, ordered by year, with the album list beside it" width="100%"></a>

[View project](https://github.com/cslkkl/discography-showcase)

## Open-source contributions

Merged into projects other people maintain:

- **dsh-workbuddy-bridge** — credit spent per reply and remaining credit next to the model picker ([#3](https://github.com/dsh-plugin-lab/dsh-workbuddy-bridge/pull/3)); every model that can switch effort now reports its default, so the picker no longer offers a meaningless “Default” ([#4](https://github.com/dsh-plugin-lab/dsh-workbuddy-bridge/pull/4))
- **Cogniform/imagora** — prompt output flow and a zero-install Windows portable release ([#2](https://github.com/Cogniform/imagora/pull/2))

<sub>dsh-web-annotator is also listed in [awesome-dsh-plugin](https://github.com/awesome-dsh-plugin/awesome-dsh-plugin/pull/6833).</sub>

<div align="center">

🐾 <em>Keep sniffing, keep shipping.</em>
<sub>Mostly fixing bugs in tools I wrote for myself.</sub>

</div>
