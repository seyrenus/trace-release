# Repositories with Latest Commits within 7 days

### 2023-11-04T08:18:43Z [**LeslieLeung/reaper**](https://github.com/LeslieLeung/reaper)

```
## Changelog * 0214f53 build: fix docker and add usage in README.md 
```

### 2023-11-03T10:44:39Z [**mdaylight/actions-openwrt-x86**](https://github.com/mdaylight/actions-openwrt-x86)

```
 
```

### 2023-11-03T02:58:09Z [**tiny-craft/tiny-rdm**](https://github.com/tiny-craft/tiny-rdm)

```
##  ### Features  - Added flush database operation. - Introduced slow log query.  ### Optimizations  - Optimized the automatic decode logic.  ##  ### 新特性  - 为数据库操作增加清空数据库 - 加入慢日志查询  ### 功能优化  - 优化自动转码逻辑 
```

### 2023-11-04T13:24:44Z [**gngpp/ninja**](https://github.com/gngpp/ninja)

```
## What's Changed * fix(har): Prevent rename update har file by @gngpp in https://github.com/gngpp/ninja/pull/253 * feat(arkose): Enable API callback by @gngpp in https://github.com/gngpp/ninja/pull/254 * feat(ui): Synchronously update the official website UI by @gngpp in https://github.com/gngpp/ninja/pull/255   **Full Changelog**: https://github.com/gngpp/ninja/compare/v0.7.5...v0.7.6 
```

### 2023-10-29T03:52:41Z [**mylxsw/aidea**](https://github.com/mylxsw/aidea)

```
本次更新内容如下  1. 服务端地址通过环境变量配置，编译时可以指定环境变量来为不同环境打包 2. 支付宝支付支持沙箱环境 3. 增加群聊功能，现在可以把多个大模型拉到一个群里，同时向它们进行提问了 4. 聊一聊页面的历史就来移动到单独的页面，首页只展示最近 3 条 5. 聊天记录支持以图片的形式进行分享 6. 聊天协议由 OpenAI 兼容的 SSE 转换为了 WebSocket，解决最新版 Chrome 浏览器无法使用问题 #36 7. 智慧果使用明细增加日维度的使用记录 8. 其它 Bugfix，如 #37 等  最新版本体验下载地址：  - Web 端：https://web.aicode.cc/ - Android/IOS：https://aidea.aicode.cc/ - Mac 桌面端：见附件，或者在这里[下载](https://cdn.aicode.cc/ai-server/release/macos/aidea-1.0.7-macos.dmg - Win 桌面端：见附件，或者在这里[下载](https://cdn.aicode.cc/ai-server/release/win/aidea-1.0.7-win.zip) 
```

### 2023-11-03T18:33:44Z [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
 ### Maintenance  * Update plugin commits to most recent commits  **Full Changelog**: https://github.com/AstroNvim/AstroNvim/compare/v3.37.8...v3.37.9 
```

### 2023-11-01T17:17:48Z [**gyroflow/gyroflow**](https://github.com/gyroflow/gyroflow)

```
### ✨ Improvements - Added a very basic way to stabilize files without gyro data. Simply load the video without gyro data, load lens profile and click "Autosync". It should analyze the video using optical flow and use that as gyro data. Note that this is not a proper feature yet. May work for simple cases, so it's there, but will probably fail for more tricky movements. - Added grid guide (right click on the video preview). - Updated timeline scrolling/scaling behavior on macOS (by @pacoccino) - Added support for Senseflow device data (by @HiDream) - Added a way to clear trim range (`C` shortcut) - Added a way to disable lens profile updates. You can now delete lens profiles you won't use and make the startup faster. Then place `noupdate` file in the lens profile directory - Relaxed H.264 resolution restriction allowing to render vertical 2160x3840  - Added "Created at" to Video information panel - Updated macOS icon  ### 🐛 Bug fixes - Fixed crash when opening multiple BRAW files - Fixed BRAW timeline scrubbing - Fixed BRAW preview with OpenCL - Fixed rendering on older devices - Fixed background color in rendered file - Fixed AppImage "Permission denied" error - Fixed rendering crash with Intel on Windows - Fixed queue progress indicator in some cases (by @pacoccino) - Fixed playback slowdown when using video speed keyframes on macOS - Fixed rendering to image sequences - Fixed gyro data timings with older Insta360 cameras - Fixed opening files with non-ascii characters on Android - Fixed loading of OpenCamera Sensors csv logs  Installing from the platform store is recommended for most users. Downloading zip or dmg shouldn't be needed anymore.  [Microsoft Store](https://apps.microsoft.com/store/detail/gyroflow/9NZG7T0JCG9H) | [macOS/iOS App Store](https://apps.apple.com/us/app/gyroflow/id6447994244) | [Google Play](https://play.google.com/store/apps/details?id=xyz.gyroflow) 
```

### 2023-11-03T12:13:41Z [**KitsunePie/AppErrorsTracking**](https://github.com/KitsunePie/AppErrorsTracking)

```
1. 修复异常信息界面存在时不会展示最新内容问题，感谢 @klxiaoniu @ZQDesigned 2. 更新底层 Hook API，适配 Android 14 3. 优化异常堆栈分享信息相关内容与风格 4. 新增支持在分享异常堆栈时的可选信息对话框 (隐私保护) 5. 更换新的 Hook 点修复在部分系统上无法展示错误对话框的问题 6. 新增 APP 目标 SDK 和最小 SDK 版本展示 
```

### 2023-10-30T12:51:39Z [**TodePond/DreamBerd**](https://github.com/TodePond/DreamBerd)

```
[Last week](https://github.com/TodePond/DreamBerd/releases/tag/v0.0), we shut down the company, so there's no need to stay in character anymore.  For the first time ever, these release notes will contain no jokes, no sarcasm, and no humour of any kind. Instead, it's time to answer all the questions you ask us most. Questions like...  • Is DreamBerd a joke? • What is DreamBerd making fun of? • Will you accept my PR full of offensive jokes?  It's time to answer them all. No more lies! Here's the truth:  # The Truth About DreamBerd  ## Is DreamBerd a joke?  Yes.  ## What is DreamBerd making fun of?  DreamBerd is making fun of **JavaScript**.  JavaScript is a terrible language, full of terrible design decisions. Just look at this abomination:  js !!!!!!!true   Yeah... You read that right. JavaScript lets you put multiple exclamation marks at the start of a line. Dreamberd mocks this by allowing you to put multiple exclamation marks at the end of the line.  *That's the kind of high-level satire you can expect from DreamBerd.*  Here's another one:  js typeof NaN === "number"   Yeah... You read that right. JavaScript thinks that 'not a number' is a 'number'. You probably didn't know this.  *Not everyone will get these jokes. You have to be thinking quite laterally.*  ## Will you accept my PR full of offensive jokes?  No.  ---  Tune in next week for more DreamBerd release notes.  > If you love anti-javascript humour, then you'll *love* my video about how bad it is. Watch (or re-watch) it [here](https://youtu.be/ZMklf0vUl18). 
```

### 2023-10-31T14:32:47Z [**Ajaxy/telegram-tt**](https://github.com/Ajaxy/telegram-tt)

```
null 
```

### 2023-10-30T06:12:27Z [**pot-app/pot-desktop**](https://github.com/pot-app/pot-desktop)

```
## 2.6.7 (2023-10-30)  ### New feature:  -   I18n for Tray Menu([`5798932`](https://github.com/pot-app/pot-desktop/commit/5798932bd12c0c38d21694b105daa2a3968a7a0f)) (by @Pylogmon) -   Add Font Size Option([`20772b9`](https://github.com/pot-app/pot-desktop/commit/20772b9d494204ab31e003729b364e06a0ef9464)) (by @Pylogmon) -   Add Persian Support([`9a2dbcd`](https://github.com/pot-app/pot-desktop/commit/9a2dbcd179fe072bcd6f54be264b5f6b6ab80b2b)) (by @Pylogmon) -   Collapse translation area([`6bb6741`](https://github.com/pot-app/pot-desktop/commit/6bb6741255f7aa01838d33c2aad4060f150f17c1)) (by @Pylogmon)  ### Bugs fixed:  -   Optimize local backup error messages([`f6acaf7`](https://github.com/pot-app/pot-desktop/commit/f6acaf72c8170b4e1c0783ef9023f1a0f74c1c07)) (by @Pylogmon) 
```

### 2023-11-04T10:13:53Z [**LazyVim/LazyVim**](https://github.com/LazyVim/LazyVim)

```
## [10.8.0](https://github.com/LazyVim/LazyVim/compare/v10.7.1...v10.8.0) (2023-11-04)   ### Features  * **catppuccin:** enable more integrations ([#1922](https://github.com/LazyVim/LazyVim/issues/1922)) ([4312e5e](https://github.com/LazyVim/LazyVim/commit/4312e5e28348560e018da4535de27dfcc675c32b))   ### Bug Fixes  * **extras:** dont show extras that give errors (user's extras). Fixes [#1895](https://github.com/LazyVim/LazyVim/issues/1895) ([b32b4fd](https://github.com/LazyVim/LazyVim/commit/b32b4fd581018cf14bf30ae4cd8d94cd43552813)) * **mini.indentscope:** remove duplicated filetype ([#1871](https://github.com/LazyVim/LazyVim/issues/1871)) ([09eafc6](https://github.com/LazyVim/LazyVim/commit/09eafc60eff2ba7d7b78c1717d07ce26b762a8a8)) * **plugin:** LazyFile now properly deals with deleted buffers. Fixes [#1877](https://github.com/LazyVim/LazyVim/issues/1877) ([4558407](https://github.com/LazyVim/LazyVim/commit/4558407574d0cdbe55720ab349df201bd4d5f5de)) * **sessions:** added folds to sessions ([e01ad51](https://github.com/LazyVim/LazyVim/commit/e01ad513aa4f50bdb385a7454c9e1ec3a0d5dc94)) * **spectre:** don't build nvim-spectre ([3986169](https://github.com/LazyVim/LazyVim/commit/39861698235c03d30096b3fb315ce38eeaef95e2)) 
```

### 2023-11-04T09:45:32Z [**josStorer/chatGPTBox**](https://github.com/josStorer/chatGPTBox)

```
## Changes - d36f6ea: improve render performance (#265) (josc146) - 3d08919: force scroll to bottom after submission (josc146)  ## Documentation - add Japanese README [#549](https://github.com/josStorer/chatGPTBox/pull/549) ([Ikko Eltociear Ashimine](https://github.com/josStorer/chatGPTBox/commit/838da652aeb96e49c410633442665fa9abb76066)) - phrase translation according language README_IN [#552](https://github.com/josStorer/chatGPTBox/pull/552) ([Guspan Tanadi](https://github.com/josStorer/chatGPTBox/commit/84dfdde8c0ed43cef814c008dba75664c545f207)) 
```

### 2023-10-29T14:05:42Z [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- Fix F-Droid checkupdates bot release pickup 
```

### 2023-11-04T22:37:02Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2023-10-30T07:52:06Z [**chathub-dev/chathub**](https://github.com/chathub-dev/chathub)

```
 
```

### 2023-11-04T05:16:09Z [**rustq/3body-lang**](https://github.com/rustq/3body-lang)

```
Fix the redeclare case https://github.com/rustq/3body-lang/pull/36 
```

### 2023-10-29T13:34:28Z [**krahets/hello-algo**](https://github.com/krahets/hello-algo)

```
该版本为《Hello 算法》1.0.0 版的预发布 b6 版本。  现已支持 Python, C++, Java, C#, Go, Swift, JavaScript, TypeScript, Dart, Rust, C 的 PDF 电子书下载。  ## 主要改动  - 新增 Rust 和 C 语言版 PDF 电子书。 - 重新实现开放寻址哈希表、归并排序。 - 更新部分章节 Q&A 。 - 统一 C# 代码样式为 PascalCase 。 - 添加 auto-bulid-and-check workflow ，现已包括 Python, C#, Swift, Dart。 - 优化暗色主题样式、页面交互。 - 减小图片文件大小，提升加载速度。 - 修复各类已知问题。  ## 贡献者  感谢 @0130w, @52coder, @Evilrabbit520, @FreddieLi, @Gonglja, @Horbin-Magician, @MwumLi, @Nigh, @Phoenix0415, @QiLOL, @Transmigration-zhou, @Turing-1024-Lee, @Zuoxun, @coderlef, @foursevenlove, @gledfish, @gvenusleo, @hpstory, @hts0000, @huawuque404, @justin-tse, @keshida, @kilikilikid, @krahets, @lclc6, @lhxsm, @logan-qiu, @longsizhuo, @lucaswangdev, @lyl625760, @malone6, @night-cruise, @noobcodemaker, @nuomi1, @qingpeng9802, @reeswell, @sjinzh, @syd168, @theNefelibatas, @wenjianmin, @zhouLion 对该版本的贡献！ 
```

### 2023-10-30T17:38:38Z [**zzzgydi/clash-verge**](https://github.com/zzzgydi/clash-verge)

```
### Features  - update clash meta core - add default valid keys - adjust the delay display interval and color  ### Bug Fixes  - fix connections page undefined exception 
```

### 2023-11-01T04:30:18Z [**LlmKira/Openaibot**](https://github.com/LlmKira/Openaibot)

```
## Changed - [x] Fix Slack - [x] Fix Chain Release - [x] Fix Chain System  - [x] Delete NLP MOD   #### 性能指标测试(Until 2023/11/1)  注意，不包括pm2，redis，rabbitmq，mongodb，docker等服务的内存占用。  Telegram单端运行总计 200MB   |`receiver` | 120.202MB | `python3 -m memray run --live start_receiver.py` | | `sender`   | 83.375MB  | `python3 -m memray run --live start_sender.py`   |   | 进程         | 内存均值      | 测算命令                                             | |------------|-----------|--------------------------------------------------| | `receiver` | 120.202MB | `python3 -m memray run --live start_receiver.py` | | `sender`   | 83.375MB  | `python3 -m memray run --live start_sender.py`   |  ## What's Changed * 300 - > 200 by @sudoskys in https://github.com/LlmKira/Openaibot/pull/322   **Full Changelog**: https://github.com/LlmKira/Openaibot/compare/nolib0.26.3_1...nolib0.26.3_2 
```

### 2023-11-02T13:00:36Z [**MetaCubeX/ClashMetaForAndroid**](https://github.com/MetaCubeX/ClashMetaForAndroid)

```
**Full Changelog**: https://github.com/MetaCubeX/ClashMetaForAndroid/compare/v2.8.9...v2.9.0 
```

### 2023-11-01T07:26:04Z [**IrineSistiana/mosdns**](https://github.com/IrineSistiana/mosdns)

```
- forward 插件: 优化 pipeline 和 quic 连接利用。会自动控制连接数量。因此forward 插件的 maxconn 参数不再生效。 - 新 ecs_handler 插件 (实验性): 可控制 edns0 client subnet。支持转发客户端的 ecs。支持发送 ecs。 - 新 forward_edns0opt 插件 (实验性): 可以控制转发哪些类型的 edns0 option。 - tcp 和 http 服务端支持 unix abstract domain socket。监听地址以"@"开头即可。 - prefer_ipv4/6: 新增缓存。会缓存域名双栈测试的结果，避免每次请求都需要测试。目前缓存时间默认为 1小时。暂不支持自定义。  ---  Breaking changes  - mosdns 默认不会转发，也不会发送，任何 EDNS0 Option 。EDNS0 option 需由插件处理和控制，决定是否转发/发送。 - rate_limit 插件 (实验性): 现在是匹配插件。详见 wiki。 
```

### 2023-11-01T05:57:35Z [**hpcaitech/ColossalAI**](https://github.com/hpcaitech/ColossalAI)

```
## What's Changed   ### Release  - [release] update version (#4995) by [Hongxin Liu](https://api.github.com/users/ver217)  ### Pipeline inference  - [Pipeline Inference] Merge pp with tp (#4993) by [Bin Jia](https://api.github.com/users/FoolPlayer) - [Pipeline inference] Combine kvcache with pipeline inference (#4938) by [Bin Jia](https://api.github.com/users/FoolPlayer) - [Pipeline Inference] Sync pipeline inference branch to main  (#4820) by [Bin Jia](https://api.github.com/users/FoolPlayer)  ### Doc  - [doc] add supported feature diagram for hybrid parallel plugin (#4996) by [ppt0011](https://api.github.com/users/ppt0011) - [doc]Update doc for colossal-inference (#4989) by [Cuiqing Li (李崔卿)](https://api.github.com/users/tiandiao123) - Merge pull request #4889 from ppt0011/main by [ppt0011](https://api.github.com/users/ppt0011) - [doc] add reminder for issue encountered with hybrid adam by [ppt0011](https://api.github.com/users/ppt0011) - [doc] update advanced tutorials, training gpt with hybrid parallelism (#4866) by [flybird11111](https://api.github.com/users/flybird11111) - Merge pull request #4858 from Shawlleyw/main by [ppt0011](https://api.github.com/users/ppt0011) - [doc] update slack link (#4823) by [binmakeswell](https://api.github.com/users/binmakeswell) - [doc] add lazy init docs (#4808) by [Hongxin Liu](https://api.github.com/users/ver217) - Merge pull request #4805 from TongLi3701/docs/fix by [Desperado-Jia](https://api.github.com/users/Desperado-Jia) - [doc] polish shardformer doc (#4779) by [Baizhou Zhang](https://api.github.com/users/Fridge003) - [doc] add llama2 domain-specific solution news (#4789) by [binmakeswell](https://api.github.com/users/binmakeswell)  ### Hotfix  - [hotfix] fix the bug of repeatedly storing param group (#4951) by [Baizhou Zhang](https://api.github.com/users/Fridge003) - [hotfix] Fix the bug where process groups were not being properly released. (#4940) by [littsk](https://api.github.com/users/littsk) - [hotfix] fix torch 2.0 compatibility (#4936) by [Hongxin Liu](https://api.github.com/users/ver217) - [hotfix] fix lr scheduler bug in torch 2.0 (#4864) by [Baizhou Zhang](https://api.github.com/users/Fridge003) - [hotfix] fix bug in sequence parallel test (#4887) by [littsk](https://api.github.com/users/littsk) - [hotfix] Correct several erroneous code comments (#4794) by [littsk](https://api.github.com/users/littsk) - [hotfix] fix norm type error in zero optimizer (#4795) by [littsk](https://api.github.com/users/littsk) - [hotfix] change llama2 Colossal-LLaMA-2 script filename (#4800) by [Chandler-Bing](https://api.github.com/users/Chandler-Bing)  ### Kernels  - [Kernels]Updated Triton kernels into 2.1.0 and adding flash-decoding for llama token attention  (#4965) by [Cuiqing Li](https://api.github.com/users/tiandiao123)  ### Inference  - [Inference] Dynamic Batching Inference, online and offline (#4953) by [Jianghai](https://api.github.com/users/CjhHa1) - [Inference]ADD Bench Chatglm2 script (#4963) by [Jianghai](https://api.github.com/users/CjhHa1) - [inference] add reference and fix some bugs (#4937) by [Xu Kai](https://api.github.com/users/Xu-Kai) - [inference] Add smmoothquant for llama (#4904) by [Xu Kai](https://api.github.com/users/Xu-Kai) - [inference] add llama2 support (#4898) by [Xu Kai](https://api.github.com/users/Xu-Kai) - [inference]fix import bug and delete down useless init (#4830) by [Jianghai](https://api.github.com/users/CjhHa1)  ### Test  - [test] merge old components to test to model zoo (#4945) by [Hongxin Liu](https://api.github.com/users/ver217) - [test] add no master test for low level zero plugin (#4934) by [Zhongkai Zhao](https://api.github.com/users/KKZ20) - Merge pull request #4856 from KKZ20/test/model_support_for_low_level_zero by [ppt0011](https://api.github.com/users/ppt0011) - [test] modify model supporting part of low_level_zero plugin (including correspoding docs) by Zhongkai Zhao  ### Refactor  - [Refactor] Integrated some lightllm kernels into token-attention  (#4946) by [Cuiqing Li](https://api.github.com/users/tiandiao123)  ### Nfc  - [nfc] fix some typo with colossalai/ docs/ etc. (#4920) by [digger yu](https://api.github.com/users/digger-yu) - [nfc] fix minor typo in README (#4846) by [Blagoy Simandoff](https://api.github.com/users/blagoySimandov) - [NFC] polish code style (#4799) by [Camille Zhong](https://api.github.com/users/Camille7777) - [NFC] polish colossalai/inference/quant/gptq/cai_gptq/__init__.py code style (#4792) by [Michelle](https://api.github.com/users/MichelleMa8)  ### Format  - [format] applied code formatting on changed files in pull request 4820 (#4886) by [github-actions[bot]](https://api.github.com/users/github-actions%5Bbot%5D) - [format] applied code formatting on changed files in pull request 4908 (#4918) by [github-actions[bot]](https://api.github.com/users/github-actions%5Bbot%5D) - [format] applied code formatting on changed files in pull request 4595 (#4602) by [github-actions[bot]](https://api.github.com/users/github-actions%5Bbot%5D)  ### Gemini  - [gemini] support gradient accumulation (#4869) by [Baizhou Zhang](https://api.github.com/users/Fridge003) - [gemini] support amp o3 for gemini (#4872) by [Hongxin Liu](https://api.github.com/users/ver217)  ### Kernel  - [kernel] support pure fp16 for cpu adam and update gemini optim tests (#4921) by [Hongxin Liu](https://api.github.com/users/ver217)  ### Feature  - [feature] support no master weights option for low level zero plugin (#4816) by [Zhongkai Zhao](https://api.github.com/users/KKZ20) - [feature] Add clip_grad_norm for hybrid_parallel_plugin (#4837) by [littsk](https://api.github.com/users/littsk) - [feature] ColossalEval: Evaluation Pipeline for LLMs (#4786) by [Yuanchen](https://api.github.com/users/chengeharrison)  ### Checkpointio  - [checkpointio] hotfix torch 2.0 compatibility (#4824) by [Hongxin Liu](https://api.github.com/users/ver217) - [checkpointio] support unsharded checkpointIO for hybrid parallel (#4774) by [Baizhou Zhang](https://api.github.com/users/Fridge003)  ### Infer  - [infer] fix test bug (#4838) by [Xu Kai](https://api.github.com/users/Xu-Kai) - [Infer] Serving example w/ ray-serve (multiple GPU case) (#4841) by [Yuanheng Zhao](https://api.github.com/users/yuanheng-zhao) - [Infer] Colossal-Inference serving example w/ TorchServe (single GPU case) (#4771) by [Yuanheng Zhao](https://api.github.com/users/yuanheng-zhao)  ### Chat  - [chat] fix gemini strategy (#4698) by [flybird11111](https://api.github.com/users/flybird11111)  ### Misc  - [misc] add last_epoch in CosineAnnealingWarmupLR (#4778) by [Yan haixu](https://api.github.com/users/hova88)  ### Lazy  - [lazy] support from_pretrained (#4801) by [Hongxin Liu](https://api.github.com/users/ver217)  ### Fix  - [fix] fix weekly runing example (#4787) by [flybird11111](https://api.github.com/users/flybird11111)  **Full Changelog**: https://github.com/hpcaitech/ColossalAI/compare/v0.3.4...v0.3.3 
```

### 2023-11-01T11:21:50Z [**osfans/trime**](https://github.com/osfans/trime)

```
**Change log since v3.2.14:** - 31894f63 fix: update opencc asset - e236272d chore: format code with ktlint 1.0.1 - e66cd6f6 chore: upgrade ktlint to 1.0.1 - 6dc39ad3 Add librime-predict update OpenCC and librime-lua - 3501cc92 fix: timing sync crash above Android 12 - ac654e3f chore: upgrade rime to 1.9.0 - cbe811a1 chore: bump version to 3.2.15 
```

### 2023-11-01T22:04:26Z [**benbusby/whoogle-search**](https://github.com/benbusby/whoogle-search)

```
## Updates * Site favicons are now fetched and displayed for each search result * Audio tags are now interpreted correctly   * Primarily found in word definition cards in the results view * `POST` requests now redirected as encrypted `GET` requests   * This allows navigating back from a result website to the Whoogle search result page without having to confirm form resubmission   * The "GET-only searches" config is still available for anyone who still prefers it * URLs in element and window endpoints are now validated   * Fixes a potential vulnerability where an element or window endpoint could retrieve file contents from a service hosted on another port * Valid HTML in result text content is now sanitized to prevent parsing issues  ## Community Contributions * fix: whoogle can be deployed using the fly.io free allowances by @suzaku in https://github.com/benbusby/whoogle-search/pull/1058 * fix for #1062 by @Moist-Cat in https://github.com/benbusby/whoogle-search/pull/1064 * Helm chart fix: Provide auth in probes if it is set by @mironov in https://github.com/benbusby/whoogle-search/pull/1065 * Bump cryptography from 3.3.2 to 41.0.4 by @dependabot in https://github.com/benbusby/whoogle-search/pull/1067 * Update README.md by @AlekseiKondrashov in https://github.com/benbusby/whoogle-search/pull/1069 * Remove a public instance. by @AlekseiKondrashov in https://github.com/benbusby/whoogle-search/pull/1074 * Bump urllib3 from 1.26.14 to 1.26.17 by @dependabot in https://github.com/benbusby/whoogle-search/pull/1073 * fix: correctly handle skip_prefix logic for site_alts by @kageiit in https://github.com/benbusby/whoogle-search/pull/1092 * fix: add missing dependency `validators` to setup.cfg by @zydou in https://github.com/benbusby/whoogle-search/pull/1087 * Bump urllib3 from 1.26.17 to 1.26.18 by @dependabot in https://github.com/benbusby/whoogle-search/pull/1085 * Bump werkzeug from 2.3.3 to 3.0.1 by @dependabot in https://github.com/benbusby/whoogle-search/pull/1093  ## New Contributors * @mironov made their first contribution in https://github.com/benbusby/whoogle-search/pull/1065 * @AlekseiKondrashov made their first contribution in https://github.com/benbusby/whoogle-search/pull/1069 * @kageiit made their first contribution in https://github.com/benbusby/whoogle-search/pull/1092 * @zydou made their first contribution in https://github.com/benbusby/whoogle-search/pull/1087  **Full Changelog**: https://github.com/benbusby/whoogle-search/compare/v0.8.3...v0.8.4 
```

### 2023-11-04T14:14:03Z [**be5invis/Sarasa-Gothic**](https://github.com/be5invis/Sarasa-Gothic)

```
Release version: 0.42.5 
```

### 2023-10-29T03:46:31Z [**drogonframework/drogon**](https://github.com/drogonframework/drogon)

```
### API changes list  - Added isTopicEmpty function;  ### Changed  - Update the ubuntu Dockerfile;  - Add optional Criteria && || operator support;  - Bump actions/checkout from 3 to 4;  - Make & and * directly adjacent to variable names;  - Use wss://echo.websocket.events/.ws in WebSocket client example;  - Change logs in the AccessLogger plugin to TRACE level;  ### Fixed  - Fix an error in the secureRandomString function;  - FIX int mapping to int64_t instead of uint64_t; 
```

### 2023-10-29T10:35:57Z [**MrMissx/Telegram_Forwarder**](https://github.com/MrMissx/Telegram_Forwarder)

```
## What's Changed * support for topic as source in https://github.com/MrMissx/Telegram_Forwarder/pull/85  ## Fixes * misc: handle topic context for `/id` in https://github.com/MrMissx/Telegram_Forwarder/pull/84  **Full Changelog**: https://github.com/MrMissx/Telegram_Forwarder/compare/2.1.1...2.2.0 
```

### 2023-10-30T18:54:13Z [**FreshRSS/FreshRSS**](https://github.com/FreshRSS/FreshRSS)

```
* [Milestone](https://github.com/FreshRSS/FreshRSS/milestones/1.22.1)  This release contains mostly some bug fixes for the recent [1.22.0](https://github.com/FreshRSS/FreshRSS/releases/tag/1.22.0). This version 1.22.x is also the last to support PHP 7.2 before requiring PHP 7.4+.  A few highlights ✨:  * Fix regression in extensions translations (i18n) * Better identification of proxied client IP * Better support of environment variables in K8s setups * And more!  This release has been made by several contributors: @Alkarex, @Frenzie, @MHketbi, @XtremeOwnageDotCom, @math-GH, @mossroy  Full [changelog](https://github.com/FreshRSS/FreshRSS/blob/1.22.1/CHANGELOG.md):  * Bug fixing 	* Fix regression in i18n English fallback for extensions [#5752](https://github.com/FreshRSS/FreshRSS/pull/5752) 	* Fix identification of thumbnails [#5750](https://github.com/FreshRSS/FreshRSS/pull/5750) 	* OpenID Connect compatibility with colon `:` in `OIDC_SCOPES` [#5753](https://github.com/FreshRSS/FreshRSS/pull/5753), [#5764](https://github.com/FreshRSS/FreshRSS/pull/5764) 	* Avoid a warning on non-numeric `TRUSTED_PROXY` environment variable [#5733](https://github.com/FreshRSS/FreshRSS/pull/5733) 	* Better identification of proxied client IP with `RemoteIPInternalProxy` in Apache [#5740](https://github.com/FreshRSS/FreshRSS/pull/5740) * Deployment 	* Export all environment variables to cron (to allow custom environment variables such as for Kubernetes) [#5772](https://github.com/FreshRSS/FreshRSS/pull/5772) 	* Docker: Upgraded Alpine dev image `freshrss/freshrss:newest` to PHP 8.3 [#5764](https://github.com/FreshRSS/FreshRSS/pull/5764) * Compatibility 	* Test compatibility with PHP 8.3 [#5764](https://github.com/FreshRSS/FreshRSS/pull/5764) * UI 	* Improve *Origine* theme (dark mode) [#5745](https://github.com/FreshRSS/FreshRSS/pull/5745) 	* Improve *Nord* theme [#5754](https://github.com/FreshRSS/FreshRSS/pull/5754) 	* Various UI and style improvements [#5737](https://github.com/FreshRSS/FreshRSS/pull/5737), [#5765](https://github.com/FreshRSS/FreshRSS/pull/5765), 		[#5773](https://github.com/FreshRSS/FreshRSS/pull/5773), [#5774](https://github.com/FreshRSS/FreshRSS/pull/5774) * i18n 	* Better i18n string for feed submenu for mark as read [#5762](https://github.com/FreshRSS/FreshRSS/pull/5762) 	* Improve Dutch [#5759](https://github.com/FreshRSS/FreshRSS/pull/5759) * Misc. 	* Move to GitHub Actions for our GitHub Pages [#5681](https://github.com/FreshRSS/FreshRSS/pull/5681) 	* Update dev dependencies and use `stylelint-stylistic` [#5766](https://github.com/FreshRSS/FreshRSS/pull/5766) 
```

### 2023-11-04T11:25:33Z [**sissbruecker/linkding**](https://github.com/sissbruecker/linkding)

```
## What's Changed * Fix RSS feed not handling None values  by @vitormarcal in https://github.com/sissbruecker/linkding/pull/569 * Bump django from 4.1.10 to 4.1.13 by @dependabot in https://github.com/sissbruecker/linkding/pull/567  ## New Contributors * @vitormarcal made their first contribution in https://github.com/sissbruecker/linkding/pull/569  **Full Changelog**: https://github.com/sissbruecker/linkding/compare/v1.22.2...v1.22.3 
```

### 2023-11-03T03:16:28Z [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/4267/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/4267/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### 2023-11-04T14:20:35Z [**Anankke/SSPanel-Uim**](https://github.com/Anankke/SSPanel-Uim)

```
配套数据库版本 2023102200  ### What's Changed * 现在订阅中的节点会正常根据节点等级-节点名的顺序进行排序 * 简化了默认 Clash 配置中的分流设置，去除了重复的项目并进行了排序 * WebAPI 增加了对 Hostname 的检测，当 Hostname 与 webAPIUrl 配置不符时将会拒绝该请求 * 修正了管理员后台修改时间/流量包时因为存在空值而报错的问题 * 简化了当前面板中的 Telegram Bot 实现，为添加新的 Bot 做准备 * 重构了站点数据分析服务，移除了前端模板文件中的 function call 与数值计算，为更换 Twig 模板引擎做准备 * 现在无效用户的登录尝试也会被记录于登录日志中 * 重构了管理员后台的数据库化配置页面，减少了代码重复度，提高了可维护性 * 修正了订阅系统中 Trojan 协议的传输配置，现在订阅可以正常下发除 gRPC 以外的传输插件配置 * 移除 WebAPI 中计划于 2023.6 版本淘汰的数值 * 修正了 Stripe 网关的实现，移除了不必要的参数 * 使用 GuzzleHttp 取代原生 Curl 实现，简化配置方式，减少功能所需的代码量 * 现在 Cookie 会使用 SHA3-256 作为默认的加密方式，在有指令集加速支持的现代硬件上，SHA3-256 远远快于 SHA256 * 使用 Htmx 取代绝大部分用户面板中的 jQuery ajax 代码，精简前端模板尺寸 * 修正了由上游前端库更新所导致的系统页面检查更新按钮颜色错误的问题 * 使用 C 实现的 PHP yaml 扩展取代 symfony/yaml 作为 Yaml 格式的导出工具，改善在数据量巨大情况下的 Clash 通用订阅接口性能 * 修正了一个在特定情况下可能导致管理员后台节点管理页面报错的问题 * 在 Slim Router 中添加了更多的路径合法性检查，避免无效路由数据被发送至后端 * 现在所有 Model 都有了完整的数值名称以及其类型 hint，PHPStrom 等 IDE 将可以正确检测 Model 中的数据与其类型 * 新增了 HTTPUpgrade 传输协议的支持，sing-box 与 Clash.Meta(R.I.P) 内核在最新的测试版中均已支持该传输协议  ### What's New * 通用订阅（Universal Subscription）新增 sing-box 订阅下发支持 * 客户端下载功能新增 SFA 与 SFM 客户端 * 新增 TUIC 与 Shadowsocks2022 节点类型 * 配置文件中新增了 jsDelivr Endpoint 的相关设置项 * 流量与订阅日志的相关设置现在可以通过数据库化配置系统进行管理 * 全新的用户登录日志的开关 * 全新的当用户使用新的IP订阅或登录站点时发送通知信息的功能 * 全新的整合汇率服务 * 新增了 SHA3-256 作为用户密码加密的选项 * 现在使用文档中可以插入图片 * 新增了用户注册默认语言设置，为 i18n 集成做准备 * 全新的动态倍率服务 * 新增了 PHP 8.1 与 PHP 8.3 的单元测试，为 PHP 8.3 正式版做准备 * Cookie 验证中新增了全新的验证设备选项，如开启则会验证用户是否使用与登陆时所使用的相同设备访问站点  **Full Changelog**: https://github.com/Anankke/SSPanel-Uim/compare/2023.5...2023.6 
```

