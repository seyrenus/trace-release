# Repositories with Latest Commits within 7 days

### [**fishjar/kiss-translator**](https://github.com/fishjar/kiss-translator)

```
更新内容：  - 移除多余的`wrangler`依赖 - 增加源语言远程识别功能（基于百度翻译接口）   - 之前仅扩展版能够本地语言识别，且准确率较低   - 启用远程识别后能增加语言识别准确性，但会降低翻译速度   - 可在设置页面酌情启用或禁用 - 修正`openai`的默认接口地址 - 更新`readme`描述 - 其他一些小修改 
```

### [**guozhigq/pilipala**](https://github.com/guozhigq/pilipala)

```
## 1.0.10  ### 修复 + 长按倍速抬起后未恢复默认倍速 
```

### [**nekomeowww/insights-bot**](https://github.com/nekomeowww/insights-bot)

```
## What's Changed * chore(mod): bump versions by @nekomeowww in https://github.com/nekomeowww/insights-bot/pull/177 * feat: support to specify token limits by @nekomeowww in https://github.com/nekomeowww/insights-bot/pull/179   **Full Changelog**: https://github.com/nekomeowww/insights-bot/compare/v0.21.3...v0.22.0 
```

### [**heqingpan/rnacos**](https://github.com/heqingpan/rnacos)

```
## What's Changed * 更新rnacos-web-dist-wrap版本到v0.2.2，优化控制台页面样式，解决控制台在windows浏览器默认显示滚动条样式不美观的问题 * znb 20231014 配置中心校验tenant by @zhangyubo in https://github.com/heqingpan/rnacos/pull/24 * znb 20231015  配置中心校验data_id、group、content等参数 by @zhangyubo in https://github.com/heqingpan/rnacos/pull/25 * Develop by @heqingpan in https://github.com/heqingpan/rnacos/pull/26 * znb 20231016 删除配置时对 tenant、group、data_id的字符有效性校验 by @zhangyubo in https://github.com/heqingpan/rnacos/pull/27  ## New Contributors * @zhangyubo made their first contribution in https://github.com/heqingpan/rnacos/pull/24  **Full Changelog**: https://github.com/heqingpan/rnacos/compare/v0.3.8...v0.3.9 
```

### [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
 ### Maintenance  * Update plugin commits to most recent commits   **Full Changelog**: https://github.com/AstroNvim/AstroNvim/compare/v3.37.6...v3.37.7 
```

### [**mozilla-mobile/firefox-android**](https://github.com/mozilla-mobile/firefox-android)

```
null 
```

### [**cppla/ServerStatus**](https://github.com/cppla/ServerStatus)

```
1、静态字符串参与断言计算，诸如：username/user/type/host/location，丰富限制条件和规则  - "cpu>90&load_1>4&memory_total<33554432&name!='俄勒冈'" - "online4=0&online6=0&name!='俄勒冈'&username!='s02'" - "tcp_count>600&type='Oracle'"  2、增加一个第三方极简主题Light。  **docker pull cppla/serverstatus:1.1.1** 
```

### [**linyimin0812/spring-startup-analyzer**](https://github.com/linyimin0812/spring-startup-analyzer)

```
feat: support hotswap #104 refactor: use input arguments to parse lib home #106 feat: add docker file #108 support docker push and native image #109 
```

### [**klzgrad/naiveproxy**](https://github.com/klzgrad/naiveproxy)

```
Rebased to 118.0.5993.65. 
```

### [**pot-app/pot-desktop**](https://github.com/pot-app/pot-desktop)

```
## 2.6.4 (2023-10-15)  ### New feature:  -   Support Select Component for Plugin([`37eb8d9`](https://github.com/pot-app/pot-desktop/commit/37eb8d93c44f9cd42abf92eb92ac774187f7f78b)) (by @Pylogmon) -   Support More App Language([`b2acd35`](https://github.com/pot-app/pot-desktop/commit/b2acd35b98c8416d32fdcebd7540623c9b03779c)) (by @Pylogmon)  ### Bugs fixed:  -   Fix Styles([`e5789cd`](https://github.com/pot-app/pot-desktop/commit/e5789cd9abfdd798178f4a4a420327ff3c69a0c7)) (by @Pylogmon) 
```

### [**kylelin1998/RssMonitorTelegramBot**](https://github.com/kylelin1998/RssMonitorTelegramBot)

```
更新内容： 1. 优化整体按钮交互， 尽量减少发送新消息来完成设置交互操作 2. 新增关键词排除不推送， 支持包含关键词和正则匹配，文本中含有指定文本将不推送消息 关键词排除功能使用 /admin 命令进行设置  ---  Updated content: 1. Optimize overall button interactions to minimize the need for sending new messages to complete setup interactions. 2. Add keyword exclusion for push notifications, supporting both keyword and regex matching. Messages containing specified text will not be pushed. The keyword exclusion feature can be set using the /admin command. 
```

### [**1Panel-dev/1Panel**](https://github.com/1Panel-dev/1Panel)

```
# 一、安装和升级  ## 1.1 一键安装  **CentOS/RHEL**  ```sh curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && sh quick_start.sh ```  **Ubuntu**  ```sh curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && sudo bash quick_start.sh ```  **Debian**  ```sh curl -sSL https://resource.fit2cloud.com/1panel/package/quick_start.sh -o quick_start.sh && bash quick_start.sh ```  ## 1.2 在线升级  登录 1Panel Web 控制台，在页面右下角点击 **【检查更新】** 进行在线升级。  >更多信息请查阅在线文档：https://1panel.cn/docs/  # 二、更新日志  # 2.1 功能优化  * 【容器】编辑容器页面增加部分提示信息。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/2529  # 2.2 问题修复  * 【网站】修复了证书详情页面其他域名一直为空的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/2542 * 【网站】修复了部分反向代理网站在 Firefox 浏览器中打开失败的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/2525 * 【容器】修复了部分容器无法打开编辑页面的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/2554  # 2.3 应用商店  * JumpServer 版本升级至 v3.7.2。 by @renovate in https://github.com/1Panel-dev/appstore/pull/487 * WordPress 版本升级至 v6.3.2。 by @renovate in https://github.com/1Panel-dev/appstore/pull/490 * frps 版本升级至 v0.52.1。 by @renovate in https://github.com/1Panel-dev/appstore/pull/489 * frpc 版本升级至 v0.52.1。 by @renovate in https://github.com/1Panel-dev/appstore/pull/488 * MeiliSearch 版本升级至 v1.4.1。 by @renovate in https://github.com/1Panel-dev/appstore/pull/486 
```

### [**LazyVim/LazyVim**](https://github.com/LazyVim/LazyVim)

```
## [10.5.0](https://github.com/LazyVim/LazyVim/compare/v10.4.4...v10.5.0) (2023-10-19)   ### Features  * **dashboard:** remove unnecessary brackets from keys ([#1791](https://github.com/LazyVim/LazyVim/issues/1791)) ([d73aee4](https://github.com/LazyVim/LazyVim/commit/d73aee4a934b0aa12e07039da9e2df0215ba2cba)) * **typescript:** added remove unused imports ([#1794](https://github.com/LazyVim/LazyVim/issues/1794)) ([8df44b3](https://github.com/LazyVim/LazyVim/commit/8df44b3bb54483e42a27dc30a8b343acc5d5d242))   ### Bug Fixes  * **conform:** allow overriding all conform format options. Fixes [#1790](https://github.com/LazyVim/LazyVim/issues/1790) ([ea3155a](https://github.com/LazyVim/LazyVim/commit/ea3155aef6d47e744cb2b4a7a3b567288d780f8d)) * **nvim-ts-autotag:** make it actually work :) ([82da244](https://github.com/LazyVim/LazyVim/commit/82da2440e4c9d7e604cf998aee0655f78ddfdd5c)) * **tabnine:** run `:CmpTabnineHub` automatically on build ([#1788](https://github.com/LazyVim/LazyVim/issues/1788)) ([fad3777](https://github.com/LazyVim/LazyVim/commit/fad37772967f06c65d6f0b52c2ea6f190b3218ee)) * **treesitter-context:** set default max_lines=3 ([0ac8f6f](https://github.com/LazyVim/LazyVim/commit/0ac8f6fb3b1705c2b675a0e3cbee4968370f047a)) 
```

### [**josStorer/chatGPTBox**](https://github.com/josStorer/chatGPTBox)

```
## Features - Add claude-v2 API (#516) [#516](https://github.com/josStorer/chatGPTBox/pull/516) ([ajkost](https://github.com/josStorer/chatGPTBox/commit/157399694aa5adcafdc7886d42f05ef4e3899df6))  ## Patches - d639d29: upgrade bing client (merge https://github.com/waylaidwanderer/node-chatgpt-api/pull/481) and some other adaptations (#505, #519, #525) (josc146)  ## Bug Fixes - under chatgpt web mode, due to API changes, stored responses became `undefined` ([josc146](https://github.com/josStorer/chatGPTBox/commit/634c9c95a4411c520c10258fca7c44cb9384a59e))  ## Chores - **deps**: bump actions/checkout from 3 to 4 [#507](https://github.com/josStorer/chatGPTBox/pull/507) ([dependabot[bot]](https://github.com/josStorer/chatGPTBox/commit/1e1d7db8aabc84e4a5f40fa6db37df08273ed27b)) - 83f44a3: improve claude api prompt (#516) (josc146) - b1b9c6a: Added Turkish Support, Create _locales/tr/main.json (Only1337) [#518](https://github.com/josStorer/chatGPTBox/pull/518) - c152d0b: update kagi query (#517) (josc146) - 96a0361: update locales (josc146) - 67febe3: Add site adapter for FAZ (Frankfurter Allgemeine Zeitung) (Martin Richtarsky) [#520](https://github.com/josStorer/chatGPTBox/pull/520) - 62e8c3b: fix firefox warning (#527) (josc146) - 843bfc3: update bing detection (josc146) - 4cc4144: improve claude.ai login prompt (josc146) - 86b9b20: improve error prompt (josc146) - adf95b3: release v2.4.1 (github-actions[bot]) - efe83f2: chore (josc146)  ## Known Issues - ChatGPT-4 Web Mode is not working, you have to use API Mode (#469, `arkose_token` is required, but i haven't found an efficient way to get it on client side) - Poe AI is not working (See more in https://github.com/ading2210/poe-api/issues/218 and https://github.com/ading2210/poe-api/issues/231) (Related: #471, #476, #495, #496) 
```

### [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- Update jcifs-ng to 2.1.10, commons-net to 3.10.0, sshj to 0.37.0  /!\ Please test if this release breaks ftp on firestick4k (not the max version) cf. https://github.com/nova-video-player/aos-AVP/issues/829 
```

### [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### [**zurawiki/gptcommit**](https://github.com/zurawiki/gptcommit)

```
## What's Changed * Update DEFAULT_FILES_TO_IGNORE with new lock files by @zurawiki in https://github.com/zurawiki/gptcommit/pull/248   **Full Changelog**: https://github.com/zurawiki/gptcommit/compare/v0.5.13...v0.5.14 
```

### [**LlmKira/Openaibot**](https://github.com/LlmKira/Openaibot)

```
# ⚒Attention  We fixed a forensic issue and recommend you update to this version after! 我们修复了一个鉴权问题，推荐您更新到此版本之后！  ## 🔨Fix  - [x] Fix a secure bug  ## Change  - [X] Better Schema - [X] Better Prompt  ## What's Changed * Change To Apache License by @sudoskys in https://github.com/LlmKira/Openaibot/pull/285 * Media Converter by @sudoskys in https://github.com/LlmKira/Openaibot/pull/286 * Discord Pair by @sudoskys in https://github.com/LlmKira/Openaibot/pull/287   **Full Changelog**: https://github.com/LlmKira/Openaibot/compare/lib0.25.2...lib0.25.3 
```

### [**nxtrace/NTrace-core**](https://github.com/nxtrace/NTrace-core)

```
增加--file参数支持文件读取列表进行路由测试 ```shell nexttrace --file /path/to/your/iplist.txt ``` 
```

### [**Binaryify/OneDark-Pro**](https://github.com/Binaryify/OneDark-Pro)

```
- Update README.md 
```

### [**be5invis/Sarasa-Gothic**](https://github.com/be5invis/Sarasa-Gothic)

```
Release version: 0.42.2 
```

### [**rustdesk/rustdesk**](https://github.com/rustdesk/rustdesk)

```
 ![image](https://github.com/rustdesk/rustdesk/assets/71636191/83754a64-31b8-47f0-8570-da22207759a9)   > Winget, FDroid update will come soon.   x86-64: [Windows](https://github.com/rustdesk/rustdesk/releases/download/1.2.3/rustdesk-1.2.3-x86_64.exe) | [Ubuntu](https://github.com/rustdesk/rustdesk/releases/download/1.2.3/rustdesk-1.2.3-x86_64.deb) | [Mac](https://github.com/rustdesk/rustdesk/releases/download/1.2.3/rustdesk-1.2.3-x86_64.dmg)  AArch64 (ARM64):  [Ubuntu](https://github.com/rustdesk/rustdesk/releases/download/1.2.3/rustdesk-1.2.3-aarch64.deb) | [Android](https://github.com/rustdesk/rustdesk/releases/download/1.2.3/rustdesk-1.2.3-aarch64-signed.apk) | [Mac](https://github.com/rustdesk/rustdesk/releases/download/1.2.3/rustdesk-1.2.3-aarch64.dmg)   More: [check below please](#)   <details>  <summary>Changelog</summary>  - Improve Wayland support, cursor/clipboard/multi-monitors etc, but highly depends on Xwayland, working well on GNOME, bad compatibility on KDE. We will continue working on Wayland - Add group tab - Add software update check based on github latest tag - Some fixes for Kaspersky compliance, https://github.com/rustdesk/rustdesk/discussions/5624, but they requested more - A lot of fixes since 1.2.2 - We are still working hard on dual-monitors-dual-windows and new hardware codecs, hopefully be in 1.2.4   </details> 
```

### [**TophantTechnology/ARL**](https://github.com/TophantTechnology/ARL)

```
1. 域名查询插件 添加 Chaos 源，感谢 @NAXG  #622 2. 增加一些常见的WAF和CDN的CNAME, 感谢 @ox01024  #586 3. 更新 GeoLite2 db 文件, 感谢 @ox01024 #587 4. 添加企业微信和飞书消息推送 (监控任务) #447 5. 资产 IP 选项卡可以分别导出域名和IP 6. 任务详情 添加 导出 C 段 按钮 7. nuclei 版本更新  8. HTTP 存活探测改为 GET 请求 9. 增加 js文件敏感信息搜集 (WebInfoHunter)工具调用 #474 #532 10. 添加 WebInfoHunter 任务和监控任务 11. 修复 策略配置 - 新建策略时勾选掉了"跳过CDN"，但实际不会生效 #618 12. 全端口扫描速率参数调大 13. PoC 信息第一次启动时更新优化  #604 14. 任务界面添加全局查看的按钮 #625   
```

### [**zh-google-styleguide/zh-google-styleguide**](https://github.com/zh-google-styleguide/zh-google-styleguide)

```
## What's Changed * 更正了缩进的“错误示范”中有错误。 by @jeffery82 in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/146 * 修正C++文档class章节错别字 (#140) by @Luohaothu in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/141 * 修复C++规范规则描述不清晰 by @rainmiao2048 in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/144 * 修复C++规范中错误标题：[缺点] => [结论] by @rainmiao2048 in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/145 * 更新 Python 语言规范并添加 LICENSE 文件 by @LouYu2015 in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/149 * 更新《Python风格规范》并添加《HTML/CSS 风格指南》的目录 by @LouYu2015 in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/150 * Update README.rst by @y122972 in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/151 * Java风格指南翻译 by @Eumenides-K in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/154 * 修复部分饮用错误 by @neeyongliang in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/155  ## New Contributors * @jeffery82 made their first contribution in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/146 * @Luohaothu made their first contribution in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/141 * @rainmiao2048 made their first contribution in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/144 * @LouYu2015 made their first contribution in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/149 * @y122972 made their first contribution in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/151 * @Eumenides-K made their first contribution in https://github.com/zh-google-styleguide/zh-google-styleguide/pull/154  **Full Changelog**: https://github.com/zh-google-styleguide/zh-google-styleguide/compare/v0.3...v0.4 
```

### [**casibase/casibase**](https://github.com/casibase/casibase)

```
## [1.26.1](https://github.com/casibase/casibase/compare/v1.26.0...v1.26.1) (2023-10-17)   ### Bug Fixes  * fix ernie model request parameters ([#681](https://github.com/casibase/casibase/issues/681)) ([229f246](https://github.com/casibase/casibase/commit/229f2465c916856e17f78e1df682b7edb8c57b0b)) 
```

### [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/4227/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/4227/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### [**codota/tabnine-vscode**](https://github.com/codota/tabnine-vscode)

```
 
```

### [**miniflux/v2**](https://github.com/miniflux/v2)

```
* Implement structured logging using `log/slog` package. New config options available:     * `LOG_FORMAT`: `json` or `text`     * `LOG_LEVEL`: `debug`, `info`, `warning`, or `error`     * `LOG_FILE`: `sdterr`, `stdout`, or a file path     * The `DEBUG` option is now deprecated in favor of `LOG_LEVEL` * API Improvements:     * Add endpoint `/v1/version`     * Add endpoint `PUT /v1/entries` to update entry title and content     * Add endpoint `/v1/icons/{iconID}`     * Add endpoint `/v1/flush-history` to flush history     * Make the category optional when creating feeds for API clients who don't support categories     * Add enclosures to `GET /v1/entries` endpoint     * Add `published_after`, `published_before`, `changed_after` and `changed_before` options to `/v1/entries` endpoint * Telegram integration improvements:     * Replace feed HTML link with a button to avoid page preview issues     * Add the possibility to disable buttons * Add Bruno Miniflux API collection in `contrib` folder (Bruno is an open source alternative to Postman/Insomnia) * Add command line argument to export user feeds as OPML * Add new rewrite rules `add_hn_links_using_hack` and `add_hn_links_using_opener` to open HN comments with iOS apps * Fix timestamp format for `Expires` response header * Fix Javascript error when reading time option is disabled * Fix Apprise logic to handle feed service URLs * Fix missing word in force refresh message * Remove deprecated `PreferServerCipherSuites` TLS option * Replace `github.com/rylans/getlang` with `github.com/abadojack/whatlanggo` because `getlang` doesn't seems to be updated anymore * Bump `github.com/mccutchen/go-httpbin/v2` from `2.11.0` to `2.11.1` * Bump `golang.org/x/*` dependencies 
```

