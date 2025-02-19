# Repositories with Latest Commits within 7 days

### 2025-02-18T07:07:50Z [**sub-store-org/Sub-Store**](https://github.com/sub-store-org/Sub-Store)

```
## <small>2.16.47 (2025-02-18)</small>  * feat: Egern 支持 Shadow TLS ([0825f15](https://github.com/sub-store-org/Sub-Store/commit/0825f15)) 
```

### 2025-02-17T15:07:37Z [**usememos/telegram-integration**](https://github.com/usememos/telegram-integration)

```
## Changelog * 3a600a458461527fd096acaeb776f8940be56e33 fix: media group mutex  
```

### 2025-02-18T05:30:59Z [**TermoraDev/termora**](https://github.com/TermoraDev/termora)

```
### New features/Updates  - known_hosts (#206) - Floating Toolbar (#231) - SFTP command (#234) - Support system fonts (#260) - HostTree shows more information (#203) - SFTP support for editing files (#209) - Support password-less connections to SSH servers (#211) - Support open SFTP directly to the current SSH server (#216) - Support for opening with SFTP (#217) - Export configuration file support encryption (#221) - AppImage format support for Linux (#222) - Clear terminal screen key shortcut (#239) - Removed the shortcut key for double-clicking Shift to open FindEverywhere (#249)  ### Bug fixes  - Fix windows high cpu usage (#197) - Fix auto wrap mode (#215) - Fix dialog edge detection (#240) - Fix the issue of hotkeys being assigned even when there is a pop-up window (#250)  ----  ### 新功能/更新  - known_hosts (#206) - 悬浮工具栏 (#231) - 支持 SFTP 终端 (#234) - 支持系统本地字体 (#260) - 主机树显示更多信息 (#203) - SFTP 支持编辑文件 (#209) - 支持无密码连接 SSH 服务器 (#211) - 支持直接打开当前选中 SSH 标签的 SFTP (#216) - 支持使用 SFTP 打开服务器 (#217) - 导出配置文件支持加密 (#221) - 支持 Linux 的 AppImage 格式 (#222) - 清除终端屏幕快捷键 (#239) - 移除双击 Shift 打开 FindEverywhere 快捷键 (#249)   ### 问题修复  - 修复 Windows 过高 CPU 占用 (#197) - 修复自动换行问题 (#215) - 修复窗口边缘问题 (#240) - 修复快捷键在弹出窗口时依然派发的问题 (#250) 
```

### 2025-02-15T04:50:00Z [**DrewThomasson/ebook2audiobook**](https://github.com/DrewThomasson/ebook2audiobook)

```
CHANGELOG  version 25.2.0:  * version structure is now based on YEAR.MONTH.PATCH_NUMBER * Now no need to have admin privileges on Windows to install ebook2audiobook packages (replaced chocolatey by scoop) * added MPS processor * added custom models dropdown list * added voices dropdown list and play button to listen each of them * added voice extractor for upload voices (separate vocals from background and music) * added delete button for voices, custom models and audiobooks list * added builtin voices to the voices list and can be used for all TTS models * added "--output_dir" for custom output folder in headless mode * added directory options for ebook upload batch files in gradio/gui mode * added new output audio format ['m4b', 'm4a', 'mp4', 'webm', 'mov', 'mp3', 'flac', 'wav', 'ogg', 'aac'].    More can be added on demand. * added running conversion cancellation via the ebook upload gradio component (when the "X" is clicked) * new global config settings: 	tmp_expire = for inactive session before cleanup, in days 	max_custom_model: max custom model on list (by session id) 	max_custom_voices: max custom voice on list (by session id) 	tts_default_settings: fine tuned XTTS default parameters 	(refer to ./lib/conf.py for all new configuration settings) * gradio GUI settings are now saved and restored on refresh and browser exit * resume conversion in headless and gradio GUI mode, when client page/connection lost or reloaded    (however the user should restart the process manually with the same session id) * Math symbols and numbers to phonemes are now on all TTS engines    (non covered languages are pronounced with the default_language_code set in ./lib/conf.py.    PR are welcome to fix missing translations) * audio filtering, normalization and improvement of all upload voices and final audiobook   to have the best sound presence and clarity. * fixed custom model upload * fixed missing pages in conversion * fixed modules and libraries missing during the installation (regex, mecab etc..) * various gradio design improvements * optimized multi language sentence splitting to minimize hallucinations and unnatural pauses * now numbers and maths symbols are said for fairseq and XTTSv2 * the TTS model is now loaded once in the script and for all users using the same model * added coqui-tts built-in voices for all TTS engines and as standard in all languages * added new modal alerts for info, error, exception and warnings * removed docker_utils which was a docker with ffmpeg and calibre only  * Many more fixes and new features, but don't remember all.... see by yourself ;)  ### Currently in development: * added Terminal output console to gradio/gui * implement more TTS engines (list not decided yet) * apprise notification * implement chapter summarizing to create background music and sounds * implement indices in the metadata for each sentence in the final file     to eventually improve the pronounciation and replace it with the new sentence. * add built-in voice list of xttsv2 * add czhech, croatian and others with cv/vits * add music interlude between chapters * adding chapters name (if chapters well detected) in place of number in the final metadata * split the output in multiple file if > 12hours #  chapters as final * installation of the right torch and cuda version if GPU available so deepspeed can be used * automatic user crash bug report by email via a URL request * create a legends.py file for all gradio/gui legends to manage multilanguage * mark each sentence number in the metadata with the timecode so   the user would be able to re*convert one sentence before to export the audiobook   (it requires to not delete the ebook temp folder) * use "websocat" in "cmd.exe" and "bash/zsh" script to connect in headless mode via gradio and avoid tts load at each command 
```

### 2025-02-18T19:14:47Z [**zarunbal/LogExpert**](https://github.com/zarunbal/LogExpert)

```
Patch for following Issues: https://github.com/zarunbal/LogExpert/issues/314 https://github.com/zarunbal/LogExpert/issues/313 https://github.com/zarunbal/LogExpert/issues/311  **Full Changelog**: https://github.com/zarunbal/LogExpert/compare/v.1.11.0...v.1.11.1 
```

### 2025-02-14T09:25:34Z [**liriliri/aya**](https://github.com/liriliri/aya)

```
* fix: application empty list if storage stats not available * perf: logcat improve performance 
```

### 2025-02-18T00:41:42Z [**langfuse/langfuse**](https://github.com/langfuse/langfuse)

```
## What's Changed * security: upgrade jsonpath plus v2 by @maxdeichmann in https://github.com/langfuse/langfuse/pull/5595  **Full Changelog**: https://github.com/langfuse/langfuse/compare/2.95.2...v2.95.3 
```

### 2025-02-12T06:04:25Z [**modstart-lib/aigcpanel**](https://github.com/modstart-lib/aigcpanel)

```
 - 新增：时间戳获取方法  - 新增：OSX 视频合成支持  - 新增：cosyvoice 和 musetalk 模型支持升级  - 新增：模型导入增加系统要求和版本要求  - 优化：系统未捕获异常日志记录  - 优化：工单提交日志收集完善更多信息，方便排查问题  - 优化：toast 和 loading 显示位置优化  - 优化：Linux 平台获取 UUID 方法优化  - 优化：路择路径检测非英文和空格提示  - 修复：版本号对比检测异常问题修复  - 优化：文件追加方法缓存优化  - 优化：模型启动检测间隔 
```

### 2025-02-16T10:08:10Z [**alebeck/boring**](https://github.com/alebeck/boring)

```
* Improved reconnection timing * Improved logging 
```

### 2025-02-17T03:02:12Z [**lejianwen/rustdesk-api**](https://github.com/lejianwen/rustdesk-api)

```
### &nbsp;&nbsp;&nbsp;🚨 Breaking Changes  - **config**: Token expire time &nbsp;-&nbsp; by @lejianwen in https://github.com/lejianwen/rustdesk-api/issues/145 [<samp>(49cf9)</samp>](https://github.com/lejianwen/rustdesk-api/commit/49cf954)  ##### &nbsp;&nbsp;&nbsp;&nbsp;[View changes on GitHub](https://github.com/lejianwen/rustdesk-api/compare/v2.6.10...v2.6.11) 
```

### 2025-02-14T07:07:43Z [**certd/certd**](https://github.com/certd/certd)

```
## [1.30.5](https://github.com/certd/certd/compare/v1.30.4...v1.30.5) (2025-02-14)  **Note:** Version bump only for package root 
```

### 2025-02-17T20:49:10Z [**go-acme/lego**](https://github.com/go-acme/lego)

```
## Changelog * 584d3747146193ddc2b7ee37f503e2f101d1fae1 acme-dns: use new registred account (#2445) 
```

### 2025-02-12T03:57:51Z [**TyCoding/langchat**](https://github.com/TyCoding/langchat)

```
- 修复若干问题 - 适配DeekSeek-R1模型 
```

### 2025-02-14T14:32:57Z [**ente-io/ente**](https://github.com/ente-io/ente)

```
## What's Changed * Cluster trigger by @laurenspriem in https://github.com/ente-io/ente/pull/4750 * [mob][photos] Sort merge persons by @laurenspriem in https://github.com/ente-io/ente/pull/4761 * [mobile] New translations by @github-actions in https://github.com/ente-io/ente/pull/4781 * [mob] Lower Mem & increase ops limit for key derivation by @ua741 in https://github.com/ente-io/ente/pull/4771 * [mob] Bump version by @ua741 in https://github.com/ente-io/ente/pull/4801 * [mob] Opt of out flutter default deeplink by @ua741 in https://github.com/ente-io/ente/pull/4825 * [mob] Use different bundle for iOS debug variant by @ua741 in https://github.com/ente-io/ente/pull/4840 * [Mob][Photos] People-contact linking by @ashilkn in https://github.com/ente-io/ente/pull/4845 * [mobile] New translations by @github-actions in https://github.com/ente-io/ente/pull/4860 * [mob][photos] Use face when available for user avatar by @ashilkn in https://github.com/ente-io/ente/pull/4879 * [mob][photos] Fix clipping issue of people in all people screen by @ashilkn in https://github.com/ente-io/ente/pull/4880 * [mob] Handle 401/404 failure during individual multipart upload by @ua741 in https://github.com/ente-io/ente/pull/4890 * Person issue logs by @laurenspriem in https://github.com/ente-io/ente/pull/4894 * [mob][photos] Bump by @laurenspriem in https://github.com/ente-io/ente/pull/4895 * [mob][photos] Bump for internal release again by @laurenspriem in https://github.com/ente-io/ente/pull/4896 * [mob] Interface for ML DB + refactor by @ua741 in https://github.com/ente-io/ente/pull/4898 * [mob] Fix bad translation by @ua741 in https://github.com/ente-io/ente/pull/4911 * [mob] Reduce noise from logs by @ua741 in https://github.com/ente-io/ente/pull/4914 * [mob][photos] Bug fixes for contact-person linking feature by @ashilkn in https://github.com/ente-io/ente/pull/4931 * [mob][photos] Ask "open public album link in app" permission once by @AmanRajSinghMourya in https://github.com/ente-io/ente/pull/4922 * [mob][photos] Time based memories (internal users) by @laurenspriem in https://github.com/ente-io/ente/pull/4926 * [mobile] New translations by @github-actions in https://github.com/ente-io/ente/pull/4938 * Revert "[mobile] New translations (#4938)" by @ua741 in https://github.com/ente-io/ente/pull/4943 * [mob] Store remote ml data before scheduling processing by @ua741 in https://github.com/ente-io/ente/pull/4942 * [mob] Fix personAvatar when low score face is manually assigned by @ua741 in https://github.com/ente-io/ente/pull/4950 * [mob][photos] Contact person linking final fixes by @ashilkn in https://github.com/ente-io/ente/pull/4951 * [mob][photos] Fix freezing app + improvements to contacts-faces linking by @ashilkn in https://github.com/ente-io/ente/pull/4957 * [mob] Fix bad state error by @ua741 in https://github.com/ente-io/ente/pull/4963 * [mob][photos] Memories fix by @laurenspriem in https://github.com/ente-io/ente/pull/4964 * [mob][preview] add support for video streaming by @prateekmedia in https://github.com/ente-io/ente/pull/4253 * [mob][photos] Change log for release by @ashilkn in https://github.com/ente-io/ente/pull/4965 * [mob][photos] Use first letter person avatar if no person is linked to contact in contacts section, all contacts screen and contact search results by @ashilkn in https://github.com/ente-io/ente/pull/4975 * [mob][photos] Extract strings by @ashilkn in https://github.com/ente-io/ente/pull/4976 * [mob][photos] fix: Value out of range by @AmanRajSinghMourya in https://github.com/ente-io/ente/pull/4979 * [mob][photos] Use leading debouncer for better UX by @ashilkn in https://github.com/ente-io/ente/pull/4988 * fix(mob): streaming changes by @prateekmedia in https://github.com/ente-io/ente/pull/4992  **Full Changelog**: https://github.com/ente-io/ente/compare/photos-v0.9.81...photos-v0.9.98 
```

### 2025-02-13T17:46:23Z [**massgravel/Microsoft-Activation-Scripts**](https://github.com/massgravel/Microsoft-Activation-Scripts)

```
## Changelog: 3.0  #### TSforge:  - A new activation method named TSforge is added to MAS.   - For details about the method, see our [documentation](https://massgrave.dev/tsforge) and our [blogpost](https://massgrave.dev/blog).   - [Thanks](https://massgrave.dev/credits) to @WitherOrNot @asdcorp @abbodi1406 and @thecatontheceiling from the MASSGRAVE R&D team for TSforge.  #### HWID  - Fixed an issue in checking the licensing server status.  #### Ohook / Online KMS  - Some obscure Office products are added. - Scripts will skip the check for permanently activated Office products.  #### Check Activation Status  - Updated CAS by @abbodi1406 is added.  #### All  - Various other minor fixes and improvements.  ----  ## Download / How to use it?  https://github.com/massgravel/Microsoft-Activation-Scripts?tab=readme-ov-file#download--how-to-use-it  ## Don't download from the below Source code (zip) link. Check the above link for the info. 
```

### 2025-02-15T12:42:12Z [**0x2E/fusion**](https://github.com/0x2E/fusion)

```
## Changelog * de322417966a6b830a11e7b0c05bcb07d20bced5: fix: redirect to page 1 when use changes feeds (@dev-shetty) * ba3f61b4a0b61c260bbc3f71bd10d1b9050e8c01: Merge pull request #57 from dev-shetty/fix-incorrect-pagination-redirect (@0x2E) * e19c9dc5b3e27342bc7c49764f80695c618a7625: fix: improve pagination button responsiveness (@dev-shetty) * b4283e8ff64059c95518ae145224b8d0ebdb848c: fix: reduce breakpoint to sm (@dev-shetty) * 7f33caf701e3e7154c69ea4003289ff13ed1f0f4: Merge pull request #58 from dev-shetty/fix-mobile-pagination (@0x2E)  
```

### 2025-02-15T05:57:51Z [**ast-grep/ast-grep**](https://github.com/ast-grep/ast-grep)

```
- fix: ensure SerializableStopBy serialization matches deserialization [`#1802`](https://github.com/ast-grep/ast-grep/pull/1802) - fix: ensure SerializableStopBy serialization matches deserialization (#1802) [`#1802`](https://github.com/ast-grep/ast-grep/issues/1802) - feat: allow ERROR node in pattern to match everything [`#1791`](https://github.com/ast-grep/ast-grep/issues/1791) - **Breaking change:** feat: use php-only-language for php [`#900`](https://github.com/ast-grep/ast-grep/issues/900) - **Breaking change:** refactor: better apis [`d91b5c5`](https://github.com/ast-grep/ast-grep/commit/d91b5c5f2ce6b8e379a9a260d325bda6b22f4322) - chore(deps): update dependency @ast-grep/napi to v0.34.4 [`a7ca599`](https://github.com/ast-grep/ast-grep/commit/a7ca599a78c3d2e6699ac8b5a132e4873edc34ed) - fix(deps): update dependency @babel/core to v7.26.8 [`bf5b3a4`](https://github.com/ast-grep/ast-grep/commit/bf5b3a4af7c50328afb217d88a17d8a92961f489) 
```

### 2025-02-15T06:44:32Z [**hatoo/oha**](https://github.com/hatoo/oha)

```
## What's Changed * Preload tls config by @hatoo in https://github.com/hatoo/oha/pull/686 * Support mtls by @hatoo in https://github.com/hatoo/oha/pull/687 * Proxy headers by @hatoo in https://github.com/hatoo/oha/pull/688 * test ci by @hatoo in https://github.com/hatoo/oha/pull/689 * Randomize --connect-to if multiple matching options by @thomasgl-orange in https://github.com/hatoo/oha/pull/695 * maybe fix ci 2 by @hatoo in https://github.com/hatoo/oha/pull/697 * Update README by @hatoo in https://github.com/hatoo/oha/pull/698  ## New Contributors * @thomasgl-orange made their first contribution in https://github.com/hatoo/oha/pull/695  **Full Changelog**: https://github.com/hatoo/oha/compare/v1.7.0...v1.8.0 
```

### 2025-02-15T07:11:32Z [**mudkipme/MoeMemosAndroid**](https://github.com/mudkipme/MoeMemosAndroid)

```
## What's Changed - Added support for Memos 0.24.0. Due to breaking API changes, Memos versions 0.22.0–0.23.1 are no longer supported. You can still use Memos 0.21.0 or upgrade to 0.24.0. - Removed username and password login.  This is the last version of Moe Memos that supports Memos API-breaking changes. Future versions will maintain compatibility with Memos 0.21.0 and 0.24.0. If future Memos releases introduce breaking API changes, a server-side compatibility layer will be provided to convert them to the Memos 0.21.0 API.  **Full Changelog**: https://github.com/mudkipme/MoeMemosAndroid/compare/0.8.4...0.8.5 
```

### 2025-02-18T12:59:52Z [**dreamhunter2333/cloudflare_temp_email**](https://github.com/dreamhunter2333/cloudflare_temp_email)

```
## What's Changed  [文档 - 使用 SMTP 发送邮件](https://temp-mail-docs.awsl.uk/zh/guide/config-send-mail.html#%E4%BD%BF%E7%94%A8-smtp-%E5%8F%91%E9%80%81%E9%82%AE%E4%BB%B6)  - fix: |UI| 修复移动设备日期显示问题 - feat: |Worker| 支持通过 `SMTP` 发送邮件, 使用 [zou-yu/worker-mailer](https://github.com/zou-yu/worker-mailer/blob/main/README_zh-CN.md) @zou-yu  ### [更新或者部署网页不生效请如图勾选清理缓存](https://github.com/dreamhunter2333/cloudflare_temp_email/discussions/487)  ![image](https://github.com/user-attachments/assets/b6ec233d-ae77-4dfb-8124-2f9f98d4a110)  ### PRs  * fix: |UI| date parse error at mobile devices by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/575 * feat: |Worker| support send mail by SMTP by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/580 * feat: update dependencies by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/581   **Full Changelog**: https://github.com/dreamhunter2333/cloudflare_temp_email/compare/v0.8.6...v0.8.7 
```

### 2025-02-14T05:24:53Z [**Hk-Gosuto/ChatGPT-Next-Web-LangChain**](https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain)

```
## What's Changed * Feat realtime by @Hk-Gosuto in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/328 * PDF plugin improvement by @michaelGuo1204 in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/330 * feat: remote model by @Hk-Gosuto in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/333 * Modify ArxivAPIWrapper by @michaelGuo1204 in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/334 * feat: sync deepseek r1 thinking code by @Hk-Gosuto in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/338 * Feat google model update by @Hk-Gosuto in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/341  ## New Contributors * @michaelGuo1204 made their first contribution in https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/pull/330  **Full Changelog**: https://github.com/Hk-Gosuto/ChatGPT-Next-Web-LangChain/compare/v2.13.2...v2.13.3 
```

### 2025-02-12T01:29:25Z [**veops/oneterm**](https://github.com/veops/oneterm)

```
## [Version v25.2.1] - 2025-02-12  ### Features - Work station - update layout and style - Add userPanel component - Login page - update background image  ### Documentation - Add CODE_OF_CONDUCT - Add SECURITY - Update README    ### Bug Fixes - Fix menu permission - Fix create table 
```

### 2025-02-12T16:52:20Z [**babalae/better-genshin-impact**](https://github.com/babalae/better-genshin-impact)

```
* **修复 5.4 版本地图UI变动导致传送失效的问题** @Scarlet1ssimo  * TP时扩展右上角的不可点击区域，适配新地图UI * **修复启动调度器时完全卡死的问题（只会在独占全屏时出现）** * **修复通知导致的截图失败报错提示** * 使 JS脚本 中的 keyDown(), keyUp(), keyPress() 方法 和 战斗策略脚本 中的 keydown(), keyup(), keypress() 方法 可以直接使用 虚拟键代码 来执行 鼠标操作 #1124 @2696791698 * 5.4 七圣召唤卡牌元数据更新 @haokaiyang 
```

### 2025-02-18T14:21:36Z [**casibase/casibase**](https://github.com/casibase/casibase)

```
# [1.209.0](https://github.com/casibase/casibase/compare/v1.208.0...v1.209.0) (2025-02-18)   ### Features  * use Ant Design X for chat UI ([#1009](https://github.com/casibase/casibase/issues/1009)) ([b3fed5d](https://github.com/casibase/casibase/commit/b3fed5df9661506c9da36afb0ae6e80437654591)) 
```

### 2025-02-14T03:44:02Z [**labring/FastGPT**](https://github.com/labring/FastGPT)

```
## 变更总结 1. 修复 - 系统未配置模型时候，会循环检测，导致一直出现警告，同时修复该文案i18n提示。   **Full Changelog**: https://github.com/labring/FastGPT/compare/v4.8.21...v4.8.21-fix 
```

### 2025-02-17T10:16:34Z [**Calcium-Ion/new-api**](https://github.com/Calcium-Ion/new-api)

```
**Full Changelog**: https://github.com/Calcium-Ion/new-api/compare/v0.4.7.3.2...v0.4.7.3.3 
```

### 2025-02-14T02:58:08Z [**HeyPuter/puter**](https://github.com/HeyPuter/puter)

```
This changelog was generated by GitHub. We've also generated [our own changelog](https://github.com/HeyPuter/puter/blob/0cb1ca7989000ddd3b37c2bad344a26a38706e52/CHANGELOG.md) which might be easier to follow.  ## What's Changed * networking API beginnings by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1085 * Add Feature Flags to Disable Temporary Users and User Signup by @Raiu in https://github.com/HeyPuter/puter/pull/1086 * add close to psocket by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1088 * TLS Support through rustls-wasm by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1090 * add 0x01 and 0x03 wisp messages by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1091 * move try-catch outside of loop in TLS readstream by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1092 * more socket fixes by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1094 * Complete the Norwegian Bokmål (Norsk Bokmål) translation of Puter by @AryanTavish in https://github.com/HeyPuter/puter/pull/1093 * Update fr.js by @Zac0511 in https://github.com/HeyPuter/puter/pull/1100 * Create TRADEMARK.md by @jelveh in https://github.com/HeyPuter/puter/pull/1037 * new API puter.net.generateWispV1URL() by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1104 * TLS Socket fix: only close TLS socket once by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1105 * PDE command provider by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1110 * Added Browser IDEs by @mojafa in https://github.com/HeyPuter/puter/pull/1109 * Revert "Added Browser IDEs" by @jelveh in https://github.com/HeyPuter/puter/pull/1111 * Added tab completion to PDEs by @ProgrammerIn-wonderland in https://github.com/HeyPuter/puter/pull/1113  ## New Contributors * @Raiu made their first contribution in https://github.com/HeyPuter/puter/pull/1086 * @AryanTavish made their first contribution in https://github.com/HeyPuter/puter/pull/1093 * @mojafa made their first contribution in https://github.com/HeyPuter/puter/pull/1109  **Full Changelog**: https://github.com/HeyPuter/puter/compare/v2.5.0...v2.5.1 
```

### 2025-02-15T03:50:37Z [**dockur/windows**](https://github.com/dockur/windows)

```
## What's Changed * docs: Add restart policy by @kroese in https://github.com/dockur/windows/pull/1028 * fix: Download links by @kroese in https://github.com/dockur/windows/pull/1035   **Full Changelog**: https://github.com/dockur/windows/compare/v4.10...v4.11 
```

### 2025-02-18T05:48:51Z [**open-webui/open-webui**](https://github.com/open-webui/open-webui)

```
## [0.5.14] - 2025-02-17  ### Fixed  - **🔧 Critical Import Error Resolved**: Fixed a circular import issue preventing 'override_static' from being correctly imported in 'open_webui.config', ensuring smooth system initialization and stability. 
```

### 2025-02-13T22:25:30Z [**ImranR98/Obtainium**](https://github.com/ImranR98/Obtainium)

```
## What's Changed * By @ImranR98 in https://github.com/ImranR98/Obtainium/pull/2112   * GitLab URL parsing bugfix (#2106)   * Tencent store bugfix (#2108)   * Allow for MarkDown inside "about" app field (#2109) * RuStore support by @PadowYT2 in https://github.com/ImranR98/Obtainium/pull/2081 (for #1593) * Fix RuStore characterset issue + support RuStore app  changelogs by @ImranR98 in https://github.com/ImranR98/Obtainium/pull/2113  ## New Contributors * @PadowYT2 made their first contribution in https://github.com/ImranR98/Obtainium/pull/2081  **Full Changelog**: https://github.com/ImranR98/Obtainium/compare/v1.1.40...v1.1.41 
```

### 2025-02-17T01:04:25Z [**jlesage/docker-firefox**](https://github.com/jlesage/docker-firefox)

```
Changes in this release:   - Updated Firefox to version 135.0-r0. 
```

### 2025-02-18T17:46:38Z [**msgbyte/tianji**](https://github.com/msgbyte/tianji)

```
## [1.18.10](https://github.com/msgbyte/tianji/compare/v1.18.7...v1.18.10) (2025-02-18)  ### Features  * migrate ai survey task from promise to MQ ([e79ad8f](https://github.com/msgbyte/tianji/commit/e79ad8fe4b966d69956fea01c3474fe6b347ba52))  ### Bug Fixes  * fix a not accept language problem(some ts issue before) ([b38310e](https://github.com/msgbyte/tianji/commit/b38310eb1c2b9811c93567989aa15fcc7acb9afd)) * hotfix some header not have language header issue ([8959ddc](https://github.com/msgbyte/tianji/commit/8959ddcc4bb70bb8d921bc27a5db3810d2daeecc))  ### Others  * release v1.18.8 ([b838c4d](https://github.com/msgbyte/tianji/commit/b838c4dc055cd2109ee08476f1afec5bc94d38e3)) * release v1.18.9 ([ab90204](https://github.com/msgbyte/tianji/commit/ab90204344f4336c14669e856c37267a94164bed)) * update survey date picker logic ([a235289](https://github.com/msgbyte/tianji/commit/a2352896dc1806ce6e208b27ca150a3f3758dcf7)) * use or to filter suggestion category ([c0995bc](https://github.com/msgbyte/tianji/commit/c0995bcb313d72429bc5fe1a7eeea6fde6ef5764)) 
```

### 2025-02-17T16:16:18Z [**reqable/reqable-app**](https://github.com/reqable/reqable-app)

```
### windows-macos-linux-android-ios - ❗ [IMP] Data structure upgrade, please do not downgrade to the old version after upgrading. - 🚀 [NEW] API collection supports folder-level configuration like authorization and scripting. - 💪 [OPT] Redesign the UI/UX of HTTP custom method management. - 💪 [OPT] JSON tree view supports node single-click. - 💪 [OPT] File naming rules for traffic list data export. - 🐞 [FIX] A bug that the API tab fails to be automatically closed when deleting an API from the collection. - 🐞 [FIX] A bug that the API header name uses environment variables to prompt an illegal name. ### windows-macos-linux-android - 🐞 [FIX] A bug that the Android network stack information is not saved in the history. ### windows-macos-linux - 🚀 [NEW] The traffic list supports exporting data according to the file structure. - 🚀 [NEW] `Gateway`, `Rewrite`, `Breakpoint` and `Script` matching rules support specifying the HTTP method. - 🚀 [NEW] Applications and domain names in explorer support copying. - 💪 [OPT] The API collection distinguishes between root directories and subdirectories, and cannot be changed by dragging and dropping. - 💪 [OPT] The variable value can be copied in the environment variable mouse hover prompt view. - 💪 [OPT] The environment variable name supports the `-` symbol. - 💪 [OPT] Fully support user custom HTTP methods. - 💪 [OPT] Adjust the display order of `Mirror` and `Gateway`. - 💪 [OPT] The `Breakpoint` executor window can directly open the hit breakpoint rule window. - 🐞 [FIX] The API collection data may be imported with an error. - 🐞 [FIX] The bug that the global environment variable data is written to the user environment after the script is executed. - 🐞 [FIX] A bug that the tab does not have a modification mark when editing an API script. - 🐞 [FIX] A bug that the environment variables are not parsed when copying URLs and cURL in the collection list. - 🐞 [FIX] A bug that ADB may not be able to discover Android devices. ### android-ios - 🐞 [FIX] A bug that the collaborative QR code displays no valid IP address. ### android - 💪 [OPT] The description of the user certificate installation guide is more accurate. - 🐞 [FIX] A bug that the Android official document link is misspelled in English. - 🐞 [FIX] A bug that a crash may occur when opening the application list. - 🐞 [FIX] A bug that the API collection page does not return to the parent directory but returns to the homepage after pressing the back key. 
```

### 2025-02-15T15:09:08Z [**jianchang512/pyvideotrans**](https://github.com/jianchang512/pyvideotrans)

```
> 预打包版仅适用于Windows10/11，MacOS和Linux请源码部署 > MacOS/Linux升级：重新拉取源码覆盖，然后执行 >  `pip3 install --upgrade openai-whisper elevenlabs`  >  `pip3 install --no-deps  --force-reinstall "faster-whisper @ https://github.com/SYSTRAN/faster-whisper/archive/refs/heads/master.tar.gz"`  ## Change  - Fix: openai 语音识别接口兼容第三方 - Feat: 高级选项中增加`保留每条字幕音频`选项，选中后将在目标文件夹内生成每条字幕对应的配音mp3 #731    ## Win v3.53 完整包下载  > 如果未安装过旧版本，请在此下载完整版，如需cuda加速，需有英伟达显卡并且安装cuda12.x及cudnn9  百度网盘下载地址(含tiny/medium模型):  https://pan.baidu.com/s/1JVM5SDyg7sMlcSyEfM9-Zw?pwd=bxtm  GitHub地址: https://github.com/jianchang512/pyvideotrans/releases/download/v3.53/win-videotrans-v3.53-tiny.7z     ## v3.53 补丁包190MB  > 如果已安装过3.x版本，可下载补丁包后解压在sp.exe所在目录，覆盖已有sp.exe和文件夹  百度网盘下载地址: https://pan.baidu.com/s/1U0MBXUwRTMU-scTwPDIjZw?pwd=ejkt  GitHub地址: https://github.com/jianchang512/pyvideotrans/releases/download/v3.53/win-PatchUpdate-3.53.7z   > 若补丁覆盖后打开提示`需下载完整包`，请升级显卡驱动、升级cuda到12.x、升级cudnn到cudnn9，并重新下载完整包   ----  ### 所有模型下载地址  为避免压缩包体积过大，预打包版只内置最小模型 tiny，识别效果不佳，效果更好的模型请点击下载 ，建议至少使用medium模型，推荐large-v2  https://github.com/jianchang512/stt/releases/tag/0.0  
```

### 2025-02-17T21:09:58Z [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
## [4.32.0](https://github.com/AstroNvim/AstroNvim/compare/v4.31.1...v4.32.0) (2025-02-17)   ### Features  * **astrolsp:** add LSP based file operations and neo-tree integration ([71853c9](https://github.com/AstroNvim/AstroNvim/commit/71853c97440ac479a70c2dab507be6e029b4df9d)) * **autopairs:** only enable auto pairs in actual file editing buffers ([7e633c9](https://github.com/AstroNvim/AstroNvim/commit/7e633c9adc387b67452b971270422a29c0d36f0a)) * **mappings:** add `&lt;Leader&gt;R` to rename the current file ([415adc9](https://github.com/AstroNvim/AstroNvim/commit/415adc944ccf01e5df46a7705865abe2ed5161b2))   ### Bug Fixes  * **astrolsp:** disable LSP file operations by default until v5 ([ac15557](https://github.com/AstroNvim/AstroNvim/commit/ac1555797980dc2791a391e9e40224ee5349d96b)) 
```

### 2025-02-16T08:56:48Z [**knadh/tg-archive**](https://github.com/knadh/tg-archive)

```
## What's Changed * Fix ModuleNotFoundError during setup. Closes #127 by @PiN73 in https://github.com/knadh/tg-archive/pull/143  ## New Contributors * @PiN73 made their first contribution in https://github.com/knadh/tg-archive/pull/143  **Full Changelog**: https://github.com/knadh/tg-archive/compare/v1.2.1...v1.2.2 
```

### 2025-02-15T22:51:53Z [**LazyVim/LazyVim**](https://github.com/LazyVim/LazyVim)

```
## [14.14.0](https://github.com/LazyVim/LazyVim/compare/v14.13.0...v14.14.0) (2025-02-15)   ### Features  * **extras:** setup neogen and mini.snippets integration ([#5594](https://github.com/LazyVim/LazyVim/issues/5594)) ([5788b9d](https://github.com/LazyVim/LazyVim/commit/5788b9d1e06dfb5f99f92354dc550c9f2c5a6710)) * **keymaps:** enable toggling in quickfix list and location list ([#5608](https://github.com/LazyVim/LazyVim/issues/5608)) ([32e575a](https://github.com/LazyVim/LazyVim/commit/32e575aa75792c63f710f0bdc3e2fb5aa8ea75ad)) * **snacks.picker:** added support for Project shortcuts in other dashboards ([#5607](https://github.com/LazyVim/LazyVim/issues/5607)) ([401ef48](https://github.com/LazyVim/LazyVim/commit/401ef48fcd617534b017ef471309bb1bd6465131)) * **snacks.picker:** move trouble keymap from `ctrl+t` -&gt; `alt+t` ([4aff006](https://github.com/LazyVim/LazyVim/commit/4aff0063a42bbc499cfa03feb6e58d4339c0950d))   ### Bug Fixes  * **blink:** `blink` released new version, remove previous hack ([#5616](https://github.com/LazyVim/LazyVim/issues/5616)) ([b35015a](https://github.com/LazyVim/LazyVim/commit/b35015ac59f0c630b2efe18ccf10d693397d0ca4)) * **blink:** `cmdline` is now top-level on main branch ([#5615](https://github.com/LazyVim/LazyVim/issues/5615)) ([0458e46](https://github.com/LazyVim/LazyVim/commit/0458e46dcca49cc404062e04a9054a8bd058dcd3)) * **blink:** enable Neovim native mapping with `&lt;Tab&gt;` ([#5617](https://github.com/LazyVim/LazyVim/issues/5617)) ([e7f8e4f](https://github.com/LazyVim/LazyVim/commit/e7f8e4faba0c6d397526238923f1aeff1740d09c)) 
```

### 2025-02-18T22:40:11Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2025-02-18T12:04:53Z [**sigoden/aichat**](https://github.com/sigoden/aichat)

```
## New Features  - display reasoning tokens ([#1139](https://github.com/sigoden/aichat/pull/1139)) - webui support `think` tag ([#1140](https://github.com/sigoden/aichat/pull/1140)) - strip reasoning contents ([#1141](https://github.com/sigoden/aichat/pull/1141)) - support model alias ([#1150](https://github.com/sigoden/aichat/pull/1150)) - enhance `.file` for loading resources from diverse sources ([#1155](https://github.com/sigoden/aichat/pull/1155)) - supports selecting LLM during configuration initialization ([#1158](https://github.com/sigoden/aichat/pull/1158)) - supports fetching models during configuration initialization ([#1161](https://github.com/sigoden/aichat/pull/1161)) - new model field `system_prompt_prefix` ([#1163](https://github.com/sigoden/aichat/pull/1163)) - remove predefined models for ollama ([#1165](https://github.com/sigoden/aichat/pull/1165)) - add model field `patch` ([#1169](https://github.com/sigoden/aichat/pull/1169)) - add patch `max_tokens: null` to openai/github o* serial models ([#1174](https://github.com/sigoden/aichat/pull/1174)) - remove supports for hyperbolic and novita ([#1176](https://github.com/sigoden/aichat/pull/1176)) - remove supports for fireworks/siliconflow/together ([#1181](https://github.com/sigoden/aichat/pull/1181)) - openai/github providers add `o3-mini-high` model ([#1182](https://github.com/sigoden/aichat/pull/1182))  ## Bug Fixes  - messages with tool_calls have not been saved to messages.md ([#1156](https://github.com/sigoden/aichat/pull/1156)) - webui sessions do not persist system prompt ([#1162](https://github.com/sigoden/aichat/pull/1162)) - webui settings do not work ([#1175](https://github.com/sigoden/aichat/pull/1175)) - better handle OpenAI-Compatible streaming responses ([#1184](https://github.com/sigoden/aichat/pull/1184))  ## New Contributors * @mtul0729 made their first contribution in https://github.com/sigoden/aichat/pull/1138 * @wwsheng009 made their first contribution in https://github.com/sigoden/aichat/pull/1184  **Full Changelog**: https://github.com/sigoden/aichat/compare/v0.27.0...v0.28.0 
```

### 2025-02-17T09:00:58Z [**WPeace-HcH/WPeChatGPT**](https://github.com/WPeace-HcH/WPeChatGPT)

```
# Version 2.6 - Add support for DeepSeek, see **Update History** in README for details on how to use it. 
```

### 2025-02-18T10:18:14Z [**WerWolv/ImHex**](https://github.com/WerWolv/ImHex)

```
![image](https://github.com/user-attachments/assets/52f8c250-f3a1-447c-969b-1cf11b9b9e4a) ![image](https://github.com/user-attachments/assets/3a6aacb7-259e-4a71-bf03-d1355bafcdd7) ![image](https://github.com/user-attachments/assets/4d527d9f-fe59-4954-8c04-2d5f1451ec07)  ## Bug Fixes - Fixed large memory allocations when printing error messages in some cases - Fixed an issue that caused the pattern editor to shift to the left when clicking evaluate - Fixed a crash when a custom disassembler returned no bytes - Fixed incorrect native scaling value when using fractional scaling on Wayland - Moving the ImHex window between two screens with different DPI on Windows works better now - Fixed a crash when loading a project with a saved process memory provider - Fixed closing one Selection View causing all other Selection Views to become unusable - Fixed a crash when selecting an invalid font - Fixed the pattern editor losing focus when auto evaluate is on  # Previous Version  ## Features  - **ImHex now properly supports HiDPI scaling on Windows, macOS and Linux!** - **ImHex now uses the native menu bar on macOS** -  **You can now set separate fonts for the main UI, the Hex Editor and the Pattern Editor** -  Added a new ARM64 AppImage release as well as a WebAssembly release to self-host ImHexWeb -  ImHex can now be fully compiled using MSVC and ClangCL on Windows! Huge thanks to @mrexodia     - The main releases are still built with MinGW but this should hopefully make it easier to contribute to ImHex! -  We now provide build attestation for each build generated through our CI so you can verify exactly from which run an artifact has been built -  Added initial support for custom disassemblers     - This lets you define disassemblers for custom instruction sets using a simple [JSON format](https://github.com/WerWolv/ImHex-Patterns/tree/master/disassemblers) -  **Added messaging support for macOS and Linux**     - This allows you to use ImHex as a command line tool on macOS and Linux to control the currently open ImHex instance     - For example `imhex --open "SomeFile.bin" --select 0x100 0x200` will open the SomeFile.bin file in the current instance and then select addresses 0x100 to 0x200 -  Added Russian translation! Huge thanks to @Lemon4ksan  -  Added a title bar backdrop color gradients and accent colors -  Added utf16 and utf32 string and char types -  Added option to randomize window title     - In case some stupid anti-cheat is trying to detect ImHex in the future :) -  Added new --select, --pattern and --debug-mode subcommands -  Added support for OpenGL post processing shaders     - This lets you load custom shaders now by placing a `shader.vert` and `shader.frag` file in one of the ImHex resource folders.     - These shaders can apply any post processing to the rendered image -  Added New File option to the GNOME launcher and a --new cli option -  Added support for scanning binaries for UTF-8 strings -  Added visibility toggle to hide bookmark highlighting -  Added option to fit hex columns to screen width -  Added setting to disable hex editor highlights entirely -  Added a preview to the Edit -> Copy as options -  Added "Jump to address" option to data inspector row context menu -  Added option to change radix of numbers in hex editor view -  Added context menu and next/previous buttons to the data inspector -  Added option to move selection back to hex editor footer -  Added option to copy data as escaped string -  Added shortcut for Copy as -> Custom Encoding  ## Improvements  -  **Replaced the Windows and Linux app icon with the one from the Papyrus Icon Project!** -  The DMG on macOS now looks a lot nicer than before -  Revamped the frame rate limiting system to make ImHex feel much less laggy by default and make it use less CPU resources -  ImHex now uses Jetbrains Mono as its default font instead of the ImGui default font -  The settings window can now be resized -  The ImHex window is now hidden on macOS when close button is pressed -  Allowed all highlights to overlap each other -  Allowed the favorite column in the pattern data view to be hidden -  Allowed command palette to be closed by clicking on the menu bar -  All installed content store items are now force updated after an ImHex update  ## Bug Fixes  -  Fixed various issues with the auto updater -  RGBA8 data processor node not working correctly -  Very slow processing of large pattern console outputs -  Windows forwarder application not working when piping output -  Writing not working correctly through a provider view -  Crash on Linux if XDG_SESSION_TYPE is not set -  Crash when closing ImHex with one or more view providers open -  Uninitialized buffers in resize operation -  Exception being thrown while loading projects -  Crash when certain pattern language exceptions were thrown -  Pattern Editor shortcuts not working correctly on different languages (#2085) -  Pattern Editor Find and Replace history (#2064) -  Crash in 3D Visualizer, improved error messages (#2062) -  Disable bogus Keypad to function key conversions on macOS -  Empty regions in Intel Hex and Motorola SREC files not being displayed correctly -  Make sure provider switch buttons and close button don't overlap -  Hang when filtering for a large number of items in the pattern data view -  Off-by-one when calculating hashes of selected regions -  ImHex freezing on AMD GPUs when resizing -  Rendering issues with text editor in bookmark view -  Ctrl sometimes getting stuck when pressing ALT GR and other keys at the same time -  Missing endian setting in ARM64 disassembler -  Clicking past end of line in text editor putting cursor before last character  ## Pattern Language  - **The evaluator now tries to keep as many patterns as it possibly can when an error occurs** -  Added cursor positions to the error stack traces -  Exported global variables are now displayed in the output -  Added support for rvalue assignments inside of structs -  Fixed various issues when importing patterns as types -  Make decompress functions return number of read bytes -  Allow #pragma magic to index from the end of the data with negative addresses -  Fixed error spam when encountering an error in the Lexer   <p align="center">If you like my work, please consider supporting me on GitHub Sponsors, Patreon or PayPal. Thanks a lot!</p> <p align="center"> <a href="https://github.com/sponsors/WerWolv"><img src="https://werwolv.net/assets/github_banner.png" alt="GitHub donate button" /> </a> <a href="https://www.patreon.com/werwolv"><img src="https://c5.patreon.com/external/logo/become_a_patron_button.png" alt="Patreon donate button" /> </a> <a href="https://werwolv.net/donate"><img src="https://werwolv.net/assets/paypal_banner.png" alt="PayPal donate button" /> </a> </p 
```

### 2025-02-12T15:29:04Z [**ventoy/Ventoy**](https://github.com/ventoy/Ventoy)

```
 1. Fix the `Unsupported vtoy type unknown` error when boot a VDI file created by VBox7. [Issue 48](https://github.com/ventoy/vtoyboot/issues/48) 2. vtoyboot-1.0.36 release. [https://github.com/ventoy/vtoyboot/releases](https://github.com/ventoy/vtoyboot/releases)   **Wana boot and install OS through network (PXE)? Welcome to my new project iVentoy.**  **About iVentoy [https://www.iventoy.com](https://www.iventoy.com)** iVentoy is an enhanced version of the PXE server.  Extremely easy to use Many advanced features x86 Legacy BIOS, IA32 UEFI, x86_64 UEFI and ARM64 UEFI mode supported 110+ common types of OS supported (Windows/WinPE/Linux/VMware) ......    **SHA-256**  0b47aeba910dd9a9d5faad26988c45bef5238c4eb19e3bf510545698ac5caece  ventoy-1.1.02-linux.tar.gz 65dcdfc57d79988f7d7841cbed7b81a4a03fff65b91fdfd70316ca6dd140027e  ventoy-1.1.02-livecd.iso f992fb0569a2f9ec057c7d97800a13ead7acc57a758953800d8d958d0ae471dc  ventoy-1.1.02-windows.zip    [![Download Ventoy](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/ventoy/files/v1.1.02/) 
```

### 2025-02-18T07:40:01Z [**Aloxaf/fzf-tab**](https://github.com/Aloxaf/fzf-tab)

```
## What's Changed * fix: prefix completion in quoted string by @Aloxaf in https://github.com/Aloxaf/fzf-tab/pull/448 * docs: add info about completions by @LuisUrrutia in https://github.com/Aloxaf/fzf-tab/pull/454 * fix: unable to build binary module on some new systems by @Aloxaf in https://github.com/Aloxaf/fzf-tab/pull/472 * Add `use-fzf-default-opts` by @PrayagS in https://github.com/Aloxaf/fzf-tab/pull/479 * Remove text-coloring that interferes with fzf theming by @peterldowns in https://github.com/Aloxaf/fzf-tab/pull/484  ## New Contributors * @LuisUrrutia made their first contribution in https://github.com/Aloxaf/fzf-tab/pull/454 * @PrayagS made their first contribution in https://github.com/Aloxaf/fzf-tab/pull/479 * @peterldowns made their first contribution in https://github.com/Aloxaf/fzf-tab/pull/484  **Full Changelog**: https://github.com/Aloxaf/fzf-tab/compare/v1.1.2...v1.2.0 
```

### 2025-02-18T06:56:05Z [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/5935/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/5935/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### 2025-02-18T18:34:13Z [**ccxt/ccxt**](https://github.com/ccxt/ccxt)

```
## What's Changed * test(ticker) - fix precisions PHP by @ttodua in https://github.com/ccxt/ccxt/pull/25295 * fix(gate): remove subscriptions for watch symbols by @sc0Vu in https://github.com/ccxt/ccxt/pull/25301 * test(currency) - leveraged tokens tests ^ by @ttodua in https://github.com/ccxt/ccxt/pull/25298 * fix(gate) - trade timestamps by @ttodua in https://github.com/ccxt/ccxt/pull/25299 * fix(go): signSecp256k1 available in all envs by @carlosmiei in https://github.com/ccxt/ccxt/pull/25303 * fix(go): signSecp256k1 available in all envs by @carlosmiei in https://github.com/ccxt/ccxt/pull/25305 * fix(phemex) - perpetual pilot by @ttodua in https://github.com/ccxt/ccxt/pull/25304 * gate - networks list unification ^ by @ttodua in https://github.com/ccxt/ccxt/pull/18487   **Full Changelog**: https://github.com/ccxt/ccxt/compare/go/v4.4.60...go/v4.4.61 
```

### 2025-02-18T07:29:07Z [**dromara/hutool**](https://github.com/dromara/hutool)

```
# 5.8.36(2025-02-18)  ### 🐣新特性 * 【crypto 】      增加BCUtil.decodeECPrivateKey方法（issue#3829@Github） * 【core   】      增加HtmlUtil.cleanEmptyTag方法（pr#3838@Github） * 【db     】      GlobalDbSetting优化默认配置读取规则，优先读取文件而非jar中的文件（issue#900@Github） * 【dfa    】      删除StopChar类中存在重复字符（pr#3841@Github） * 【http   】      支持鸿蒙设备 UA 解析（pr#1301@Gitee）  ### 🐞Bug修复 * 【aop    】      修复ProxyUtil可能的空指针问题（issue#IBF20Z@Gitee） * 【core   】      修复XmlUtil转义调用方法错误问题，修复XmlEscape未转义单引号问题（pr#3837@Github） * 【core   】      修复FileUtil.isAbsolutePath没有判断smb路径问题（pr#1299@Gitee） * 【core   】      修复AbstractFilter没有检查参数长度问题（issue#3854@Github） 
```

