# Repositories with Latest Commits within 7 days

### 2024-05-15T06:10:45Z [**TabbyML/tabby**](https://github.com/TabbyML/tabby)

```
For release notes of the v0.11 minor version, please refer to [v0.11.0](https://github.com/TabbyML/tabby/releases/tag/v0.11.0).  ### 🧰 Fixes and Improvements  * Fixed the display of files with special characters in their paths. ([#2081](https://github.com/TabbyML/tabby/issues/2081)) * Resolved the issue where non-admin users were unable to see the repository in the Code Browser. ([#2110](https://github.com/TabbyML/tabby/discussions/2110)) 
```

### 2024-05-18T09:07:42Z [**dreamhunter2333/cloudflare_temp_email**](https://github.com/dreamhunter2333/cloudflare_temp_email)

```
## [Join Discord](https://discord.gg/dQEwTWhA6Q) ## [Join Telegram](https://t.me/cloudflare_temp_email)  ## What's Changed  ### Breaking Changes  worker toml 配置文件 `main = "src/worker.js"` 改为 `main = "src/worker.ts"`  ### Changes  - `telegram bot`  白名单配置 - `ENABLE_WEBHOOK` 添加 webhook - UI: admin 页面使用双层 tab - UI: 登录后可直接主页切换地址 - UI: 发件箱也采用左右分栏显示(类似收件箱) - `SMTP IMAP Proxy` 添加发件箱查看  * feat: telegram bot TelegramSettings && webhook by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/244 * fix build by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/245 * feat: UI changes by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/247 * feat: SMTP IMAP Proxy: add sendbox && UI: sendbox use split view by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/248   **Full Changelog**: https://github.com/dreamhunter2333/cloudflare_temp_email/compare/v0.4.2...v0.4.3 
```

### 2024-05-14T16:30:41Z [**xtrime-ru/TelegramApiServer**](https://github.com/xtrime-ru/TelegramApiServer)

```
Features:   - Add Password protection for API: https://github.com/xtrime-ru/TelegramApiServer?tab=readme-ov-file#security  - Latest madelineProto version  Fixes:  - Docker 26 DNS issue: https://github.com/xtrime-ru/TelegramApiServer/issues/155, https://github.com/amphp/dns/pull/118 
```

### 2024-05-16T16:17:27Z [**casibase/casibase**](https://github.com/casibase/casibase)

```
# [1.87.0](https://github.com/casibase/casibase/compare/v1.86.0...v1.87.0) (2024-05-16)   ### Features  * use vision models for question with image ([#811](https://github.com/casibase/casibase/issues/811)) ([cf8275c](https://github.com/casibase/casibase/commit/cf8275c369d0f016dc67b833fffb95d8106cba6e)) 
```

### 2024-05-13T05:39:54Z [**labring/FastGPT**](https://github.com/labring/FastGPT)

```
## 更新内容  FastGPT workflow V2上线，支持更加简洁的工作流模式。  **由于工作流差异较大，需要手动重新构建。**  为了兼容旧的工作流，我们给应用和插件增加了 version 的字段，用于标识是旧工作流还是新工作流。 当你更新 4.8 后，旧工作流不会立即无效，当你打开旧版工作流会有一个重置的弹窗提示，直到你手动保存它，才会更新。  1. 重构 - 工作流  2. 新增 - 判断器。支持 if elseIf else 判断。 @newfish-cmyk  （preview版本的if else节点需要删除重建） @newfish-cmyk  3. 新增 - 变量更新节点。支持更新运行中工作流输出变量，或更新全局变量。@newfish-cmyk  4. 新增 - 工作流自动保存和版本管理。 @c121914yu  5. 新增 - 工作流 Debug 模式，可以调试单个节点或者逐步调试工作流。 @c121914yu  6. 新增 - 定时执行应用。可轻松实现定时任务。 @c121914yu  7. 新增 - 插件自定义输入优化，可以渲染输入组件。 @newfish-cmyk  8. 新增 - 分享链接发送对话前 hook https://github.com/labring/FastGPT/pull/1252 @gaord  9. 优化 - 工作流连线，可以四向连接，方便构建循环工作流。 @c121914yu @newfish-cmyk  10. 优化 - 工作流上下文传递，性能🚀。 @c121914yu  11. 优化 - 简易模式，更新配置后自动更新调试框内容，无需保存。 @c121914yu  12. 优化 - worker进程管理，并将计算 Token 任务分配给 worker 进程。 @c121914yu  13. 优化 - 工具调用支持指定字段数据类型（string, boolean, number） https://github.com/labring/FastGPT/issues/1236 @newfish-cmyk  14. 优化 - completions接口size限制 https://github.com/labring/FastGPT/issues/1241 @c121914yu  15. 优化 - Node api 中间件。优化 api 端代码。@c121914yu  16. 优化 - 对话记录保持为偶数进行截取，避免部分模型不支持奇数的历史记录，最大长度增加到50轮。  @c121914yu https://github.com/labring/FastGPT/issues/1384 17. 优化 - HTTP节点错误后终止进程 https://github.com/labring/FastGPT/issues/1290 @c121914yu  18.  优化 - ctrl和alt+enter换行，换行符位置不正确。 @c121914yu  19.  优化 - 图片上传过程中禁止直接发送消息 @c121914yu  20. 优化 - 向量检索sql @c121914yu  21. 修复 - 工具调用时候，name不能是数字开头（随机数有概率数字开头）@c121914yu  22. 修复 - 分享链接， query 全局变量会被缓存。  @c121914yu  23. 修复 - 工具调用字段兼容。 https://github.com/labring/FastGPT/issues/1253 24. 修复 - HTTP 模块url光标问题 https://github.com/labring/FastGPT/issues/1334 @maquannene  25. 修复 - PPTx读取，使用 utf-8兜底编码 @newfish-cmyk  26. 修复 - HTTP插件兼容数字和bool https://github.com/labring/FastGPT/issues/1310 @newfish-cmyk  27. 文档 - dump迁移mongo数据库 https://github.com/labring/FastGPT/pull/1426 @samqin123   ## 镜像 tag  v4.8 
```

### 2024-05-18T06:22:11Z [**Calcium-Ion/new-api**](https://github.com/Calcium-Ion/new-api)

```
## What's Changed * 用户管理页-新增分组查询 by @iszcz in https://github.com/Calcium-Ion/new-api/pull/213 * feat: add midjourney task used time by @kakingone in https://github.com/Calcium-Ion/new-api/pull/232 * feat: 批量添加自定义模型 by @iszcz in https://github.com/Calcium-Ion/new-api/pull/242 * feat: add pricing page by @Calcium-Ion in https://github.com/Calcium-Ion/new-api/pull/245 * Support Gpt4o by @MapleEve in https://github.com/Calcium-Ion/new-api/pull/247 * Refactor settings operation by @QuentinHsu in https://github.com/Calcium-Ion/new-api/pull/248 * Update constant.go by @congyijiu in https://github.com/Calcium-Ion/new-api/pull/251 * feat: support gemini-1.5-flash-latest by @utopeadia in https://github.com/Calcium-Ion/new-api/pull/252 * Add Baidu Default Behavior and Updating Baidu&360 Models & Prices by @jimmyshjj in https://github.com/Calcium-Ion/new-api/pull/259 * 修复渠道测试时，没有走模型映射 by @p3psi-boo in https://github.com/Calcium-Ion/new-api/pull/257 * Update Perplexity and 01AI models by @jimmyshjj in https://github.com/Calcium-Ion/new-api/pull/265  ## New Contributors * @kakingone made their first contribution in https://github.com/Calcium-Ion/new-api/pull/232 * @congyijiu made their first contribution in https://github.com/Calcium-Ion/new-api/pull/251 * @utopeadia made their first contribution in https://github.com/Calcium-Ion/new-api/pull/252 * @jimmyshjj made their first contribution in https://github.com/Calcium-Ion/new-api/pull/259 * @p3psi-boo made their first contribution in https://github.com/Calcium-Ion/new-api/pull/257  **Full Changelog**: https://github.com/Calcium-Ion/new-api/compare/v0.2.1.1...v0.2.2.1 
```

### 2024-05-18T14:41:35Z [**dockur/windows**](https://github.com/dockur/windows)

```
## What's Changed * fix yaml format by @qclaogui in https://github.com/dockur/windows/pull/506 * feat: Support multiple languages by @xsy420 in https://github.com/dockur/windows/pull/504 * fix: Revert policies for Windows 7 and 2008 R2 by @kroese in https://github.com/dockur/windows/pull/510 * feat: Multi-language support by @kroese in https://github.com/dockur/windows/pull/514  ## New Contributors * @qclaogui made their first contribution in https://github.com/dockur/windows/pull/506 * @xsy420 made their first contribution in https://github.com/dockur/windows/pull/504  **Full Changelog**: https://github.com/dockur/windows/compare/v3.06...v3.07 
```

### 2024-05-17T02:12:28Z [**jason5ng32/MyIP**](https://github.com/jason5ng32/MyIP)

```
## What's Changed * Remove unnecessary codes * Simplify some functions 
```

### 2024-05-18T02:46:41Z [**ImranR98/Obtainium**](https://github.com/ImranR98/Obtainium)

```
## What's Changed * Update fa.json by @mxhdee in https://github.com/ImranR98/Obtainium/pull/1620 * By @ImranR98 in https://github.com/ImranR98/Obtainium/pull/1631   * Don't use partial downloads for BG tasks (more reliable)   *  More accurate error reports for Huawei AppGallery fails   * Various bugfixes   * Update Flutter (Material UI colour is now slightly less saturated)  **Full Changelog**: https://github.com/ImranR98/Obtainium/compare/v1.1.8...v1.1.9 
```

### 2024-05-17T06:09:11Z [**yzqzy/wechat-assistant**](https://github.com/yzqzy/wechat-assistant)

```
Release on v1.0.10  * 支持导出群成员列表头像 
```

### 2024-05-15T08:27:08Z [**GreyDGL/PentestGPT**](https://github.com/GreyDGL/PentestGPT)

```
## What's Changed * Openai compatability by @GreyDGL in https://github.com/GreyDGL/PentestGPT/pull/231 * Support gpt4o by @GreyDGL in https://github.com/GreyDGL/PentestGPT/pull/233   **Full Changelog**: https://github.com/GreyDGL/PentestGPT/compare/v0.13.0...v0.14.0 
```

### 2024-05-16T07:40:04Z [**lizongying/my-tv**](https://github.com/lizongying/my-tv)

```
* 解决卡顿问题 * 解决网格样式时，点击空白处不退出的问题 * 解决频道列表样式切换可能不生效的问题 
```

### 2024-05-15T16:11:07Z [**msgbyte/tianji**](https://github.com/msgbyte/tianji)

```
## [1.10.0](https://github.com/msgbyte/tianji/compare/v1.9.4...v1.10.0) (2024-05-15)   ### Features  * [#62](https://github.com/msgbyte/tianji/issues/62) add title section in website ([d5895dc](https://github.com/msgbyte/tianji/commit/d5895dc4a9d9d161fd17ebeb7d55b0304101b3aa)) * add survey backend endpoint ([2764262](https://github.com/msgbyte/tianji/commit/27642625ac9612ceeb1329d0aa3db8004af87844)) * add survey command panel ([c9bf016](https://github.com/msgbyte/tianji/commit/c9bf016fbf0c7216aa944118efda6b6f0acde350)) * add survey delete action ([12cd54e](https://github.com/msgbyte/tianji/commit/12cd54eafe63446471b0366d18cdaaea4ac95532)) * add survey download feature ([eebf00f](https://github.com/msgbyte/tianji/commit/eebf00f882cd8906aff2316936da9b2496018a53)) * add survey usage button ([2b75a8e](https://github.com/msgbyte/tianji/commit/2b75a8edad4285c524846438c79acfae7b013923)) * add tianji event for pricing page ([6606b25](https://github.com/msgbyte/tianji/commit/6606b253d84da09e1d821c00bd97bd7b2abf7452)) * add tianji-client-react package and useTianjiSurvey hooks which can easy to get survey info ([0fc112f](https://github.com/msgbyte/tianji/commit/0fc112fc329f0364914044f6f2727765307023ef)) * add website pricing page ([6674c19](https://github.com/msgbyte/tianji/commit/6674c19e87d3a628a2a305f9d5db48e365189b0c)) * survey basic fe framework and add new form ([010fd00](https://github.com/msgbyte/tianji/commit/010fd00be348cb5de0207cf1aea58fb43117130a)) * survey detail and edit ([a596011](https://github.com/msgbyte/tianji/commit/a596011960db230a8241e4f59bac5d33597cdc9a)) * survey sdk and openapi client ([f7f191a](https://github.com/msgbyte/tianji/commit/f7f191a53da03334b8b08844c7c51b19727828d1))   ### Document  * Add one-click deploy on sealos ([#64](https://github.com/msgbyte/tianji/issues/64)) ([fc79c57](https://github.com/msgbyte/tianji/commit/fc79c5758817d95b1058e4c0093c88b262973d52)) * clear email input when submit success in price page ([3d16d8e](https://github.com/msgbyte/tianji/commit/3d16d8edd8c89fd3d553ad461a5ae383862b80fb)) * reduce homepage image size to improve user network ([6865a7c](https://github.com/msgbyte/tianji/commit/6865a7ca0bae30f017837a5e54a171be8ce6d85a)) * update custom script document ([7d370b4](https://github.com/msgbyte/tianji/commit/7d370b4fc51a52ee91b2d94afcc9d2367fcc5fbb)) * update qrcode ([ebb6c51](https://github.com/msgbyte/tianji/commit/ebb6c51f81d75b2736213403772f5418e778224e))   ### Others  * add tooltip and time display on table ([9d3c034](https://github.com/msgbyte/tianji/commit/9d3c0344eee7b4309fad2e7ab827090136541d51)) * change weight of commit list search ([cc0bd73](https://github.com/msgbyte/tianji/commit/cc0bd73ed1c48c1fed0da95fcfc2890d1cd73012)) * change word: Countries -> Country or Region ([1ad9aa9](https://github.com/msgbyte/tianji/commit/1ad9aa95f9886342a6771cd6501d448f7801916e)) * common list add loading state ([9780aff](https://github.com/msgbyte/tianji/commit/9780affebca31f709d4f8f20e6c8f2593f1b198a)) * define survey model ([9143cc4](https://github.com/msgbyte/tianji/commit/9143cc468cd15d83b5419521adc9834576488b56)) * improve mobile display ([b2fb183](https://github.com/msgbyte/tianji/commit/b2fb1832e1a2573c7e5ad8abc38a937e4e63d1a1)) * improve mobile layout navbar display if have much features ([fd9108e](https://github.com/msgbyte/tianji/commit/fd9108e77fd8c0f4db5840512f1f0e9a73bce4d3)) * remove unused code ([342c076](https://github.com/msgbyte/tianji/commit/342c076966dcd2ede5341067a069743c09b967d1)) * update jwt secret generator more safe for user ([6e8c280](https://github.com/msgbyte/tianji/commit/6e8c28026e890774ce3edb49febde1f606aa0aee)) 
```

### 2024-05-17T13:27:01Z [**reqable/reqable-app**](https://github.com/reqable/reqable-app)

```
### windows-macos-linux-android-ios - 🚀 [NEW] WebSocket supports list display mode. - 🚀 [NEW] Request parameter supports whether to omit `=` for empty value. - 💪 [OPT] Creating API requests from the traffic list no longer checks non-ASCII characters. - 💪 [OPT] The default display of WebSocket is changed from chat mode to list mode. - 💪 [OPT] WebSocket chat mode performance. - 🐞 [FIX] The bug where WebSocket filtering does not reset type and code filters. ### windows-macos-linux - 💪 [OPT] Reset md5 result when input was changed. - 🐞 [FIX] The bug that tooltip does not disappear automatically. - 🐞 [FIX] The bug that some column widths will be automatically restored after some operations. ### android - 🚀 [NEW] Supports quick selection of target applications from the home page. - 💪 [OPT] Hide system applications by default in target app selection. - 💪 [OPT] Applications will be sorted by update time in target app selection. - 💪 [OPT] Improve the application list loading time. 
```

### 2024-05-14T02:52:38Z [**kingmo888/rustdesk-api-server**](https://github.com/kingmo888/rustdesk-api-server)

```
Windows version, synchronize to the latest version windows版本，同步到最新版本 
```

### 2024-05-18T15:32:02Z [**MetaCubeX/mihomo**](https://github.com/MetaCubeX/mihomo)

```
## What's Changed * 107e3e76 feat: Allow upgrade to latest release (#1235) by @Pylogmon * 1bc3c16b feat: add `PROCESS-NAME-REGEX` and `PROCESS-PATH-REGEX` by @wwqgtxx  ## BUG & Fix * 314c0bb3 fix: hy2 udp incompatible with quic-go 0.43.0 by @wwqgtxx * 5c3a9b1d fix: geo auto update #1261 by @Larvan2 * 6d1c62bb fix: shadowsocks uot not work with dialer-proxy by @wwqgtxx * 7df1c269 fix: fingerprint passing by @wwqgtxx * 87877d1b fix: don't ignore http.NewRequest's error by @wwqgtxx * b840eae4 fix: x509 error in windows7/8 by @wwqgtxx * fc82a32a fix: `system` tun stack not working in win7 by @wwqgtxx  ## Maintenance * 00e361c5 chore: stop using go:linkname for http.registerOnHitEOF, http.requestBodyRemains (#1275) by @hunshcn * 2b52809d chore: update quic-go to 0.43.1 by @wwqgtxx * 30a913aa chore: stop using go:linkname for net.lookupStaticHost by @wwqgtxx * 3ae4014b chore: disable tfo when lower than Windows 10.0.14393 by @wwqgtxx * 5dd883e7 chore: Add use-system-hosts option by @xishang0128 * 8861eaf9 chore: hysteria2 will only change remote port in hopLoop by @wwqgtxx * 89a097fa chore: update quic-go to 0.43.0 by @wwqgtxx * a50339bd chore: swtich `RtlGetNtVersionNumbers` to `RtlGetVersion` https://go-review.googlesource.com/c/go/+/571015 by @wwqgtxx * bfb6caee chore: stop using go:linkname for x/sys/windows by @wwqgtxx * fd7ecc00 chore: Add filter for include-all-proxies by @xishang0128 * fe88f0e4 chore: Ensure that some expressions take effect by @xishang0128  **Full Changelog**: https://github.com/MetaCubeX/mihomo/compare/v1.18.4...v1.18.5 
```

### 2024-05-18T08:57:29Z [**shenghui0779/api-tpl-rs**](https://github.com/shenghui0779/api-tpl-rs)

```
**Full Changelog**: https://github.com/shenghui0779/api-tpl-rs/compare/v1.2.3...v1.2.4 
```

### 2024-05-14T14:19:21Z [**jianchang512/pyvideotrans**](https://github.com/jianchang512/pyvideotrans)

```
# 更新记录  > 预打包版仅支持win10/win11系统, 其他系统请源码部署 > **基于源码使用pyinstaller打包，某些系统和软件可能报毒，请添加信任。介意勿下或源码部署**  - 修复几处bug - 原始视频同目录下若有同名srt字幕文件，将直接使用不再识别，如1.mp4同目录下有1.srt，将直接使用1.srt，而不再识别 - 修复字幕嵌入视频时报错  - 增加字幕字体设置、字体尺寸、字体颜色支持 videotrans/set.ini中  搜索 `fontname=`看注释   ----  #  Window预打包版  ## v1.76完整包下载  从huggingface下载(需科学上网)：https://huggingface.co/spaces/mortimerme/s4/resolve/main/win-videotrans-1.76.7z?download=true  从123网盘下载:   https://www.123pan.com/s/03Sxjv-Gi6B3.html  从百度网盘下载: https://pan.baidu.com/s/1jpXSGPmIzTe83eO4F0cdDw?pwd=i32g   ## v1.78升级补丁包/覆盖后如果无法打开，请下载完整包  补丁包下载地址 :  https://github.com/jianchang512/pyvideotrans/releases/download/v1.78/win-PatchUpdate-1.78.7z   ---- ---- ----  ## v1.76  Windows Pre-Packaged Version   From huggingface download:  https://huggingface.co/spaces/mortimerme/s4/resolve/main/win-videotrans-1.76.7z?download=true  ### Download v1.78 patch  (if don't open sp.exe,download full package):    https://github.com/jianchang512/pyvideotrans/releases/download/v1.78/win-PatchUpdate-1.78.7z 
```

### 2024-05-17T02:31:12Z [**fishjar/kiss-translator**](https://github.com/fishjar/kiss-translator)

```
更新内容：  - 优化自定义接口设置，增加hook功能，以适应更广泛的接口 - 优化gemini接口设置，展示完整url，以便更灵活的填写 - 支持下载和上传配置的json文件了 - 可以在规则设置中编写翻译文本时的hook函数，以实现某些特殊功能 
```

### 2024-05-18T18:44:40Z [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
## [4.7.3](https://github.com/AstroNvim/AstroNvim/compare/v4.7.2...v4.7.3) (2024-05-18)   ### Bug Fixes  * **mappings:** add back next/previous diagnostic mappings to neovim 0.10 ([f0c9a3f](https://github.com/AstroNvim/AstroNvim/commit/f0c9a3fff7f6cab815dd6b38d120cdb291cd393b)) * **mappings:** add missing default diagnostic mapping backport ([b853b01](https://github.com/AstroNvim/AstroNvim/commit/b853b0154d8b8daae78668e55469973f2d5a927f)) 
```

### 2024-05-12T16:57:06Z [**linyimin0812/spring-startup-analyzer**](https://github.com/linyimin0812/spring-startup-analyzer)

```
feat: use gson istead of fastjson #138 #148 
```

### 2024-05-13T16:12:08Z [**TodePond/DreamBerd**](https://github.com/TodePond/DreamBerd)

```
In this week's weekly update, we have a very exciting update for you. Let's just say, we're... **rich** to the brim with excitement (ha ha ha ha).  ## DreamBerd now supports rich text  Have you guessed it yet? Yes, you guessed it! DreamBerd now supports rich text.  <pre> const const <b>name</b> = "Lu"! const const <i>name</i> = "Luke"!  print(<b>name</b>)! // Lu print(<i>name</i>)! // Luke </pre>  Rich text can be helpful when making your website. Use it to add links!  <pre> &lt;p>Click <a href="https://dreamberd.computer">here</a>&lt;/p> </pre>  ## Bounty update  Here's an update on our affluent and highly successful [bounty program](https://github.com/TodePond/DreamBerd/tree/main/docs/investment/bounty). GitHub user [mgrkan](https://github.com/mgrkan) successfully completed the `£99 to a charity of your choice if you comment below saying "I miss when dreamberd was just about the programming and not any of this woke rubbish"` bounty, and so £99 has been donated to [UNICEF](https://www.unicef.org/) as requested by them. UNICEF is providing [life-saving support to children in Gaza](https://www.unicef.org/emergencies/children-gaza-need-lifesaving-support).  See you next week.  <img width="1087" alt="Screenshot 2024-05-13 at 17 03 30" src="https://github.com/TodePond/DreamBerd/assets/15892272/b3e55982-666e-4075-a739-655e96343b97"> 
```

### 2024-05-17T14:02:50Z [**Ajaxy/telegram-tt**](https://github.com/Ajaxy/telegram-tt)

```
null 
```

### 2024-05-13T19:09:18Z [**klzgrad/naiveproxy**](https://github.com/klzgrad/naiveproxy)

```
Rebased to 125.0.6422.35. 
```

### 2024-05-12T14:10:28Z [**tw93/Pake**](https://github.com/tw93/Pake)

```
## 更新日志  🆕 支持设置唤起快捷键、窗口置顶、禁用 Web 快捷键等新功能，详细可看 Cli 文档 😏 本地文件打包 iterCopyFile 修改成 useLocalFile，沉浸式头部从 transparent 修改成 hideTitleBar 🚀 提升国内用户打包的速度、把不常用的打包配置隐藏掉、升级底层到最新、简化了不少代码 🦖 支持配置菜单栏图标，同时不虚化显示、修复 Mac 下点击关闭展示的交互和原生一致  ## Update Log 🆕 Support setting activation shortcut, always on top, disable web shortcuts and other new features, see Cli documentation for details. 😏 Local file packaging iterCopyFile changed to useLocalFile, immersive header changed from transparent to hideTitleBar. 🚀 Improve the speed of packaging for domestic users, hide unused packaging configurations, upgrade the base layer to the latest, and simplify a lot of code. 🦖 Support configure menu bar icon, and do not show it as a dummy, fix the interaction of clicking to close the display on Mac to be consistent with the native one. 
```

### 2024-05-14T09:37:41Z [**ChatGPTNextWeb/ChatGPT-Next-Web**](https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web)

```
## What's Changed * feat: fix 1)the property named 'role' of the first message must be 'u… by @Dean-YZG in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4625 * feat: googleApiKey & anthropicApiKey support setting multi-key by @Dean-YZG in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4626 * Fix Sync Issue with Upstash by @rooben-me in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4610 * Fix typo for "OpenAI Endpoint" in the en locale by @DmitrySandalov in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4670 * chore(deps): bump next from 13.4.9 to 14.1.1 by @dependabot in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4647 * support gpt-4o by @leo4life2 in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4674 * feat: bump version by @fred-bf in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4684  ## New Contributors * @rooben-me made their first contribution in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4610 * @DmitrySandalov made their first contribution in https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/pull/4670  **Full Changelog**: https://github.com/ChatGPTNextWeb/ChatGPT-Next-Web/compare/v2.12.2...v2.12.3 
```

### 2024-05-18T21:56:59Z [**LazyVim/LazyVim**](https://github.com/LazyVim/LazyVim)

```
## [11.3.1](https://github.com/LazyVim/LazyVim/compare/v11.3.0...v11.3.1) (2024-05-18)   ### Bug Fixes  * **util:** fixup ([3a4672d](https://github.com/LazyVim/LazyVim/commit/3a4672de3f8b6410de9fbd5b7134d5108d86f46c)) 
```

### 2024-05-16T15:09:15Z [**josStorer/chatGPTBox**](https://github.com/josStorer/chatGPTBox)

```
# Changes  ## Upgrades - add the latest GPT-4o Web and API (#701, #702, #705, #706)  ## Fixes - fix https://github.com/josStorer/chatGPTBox/issues/661#issuecomment-2016704211 - fix handling of empty choices array in Azure OpenAI API integration  ## Chores - update enforcement rule 
```

### 2024-05-12T15:05:47Z [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- Revert from jupnp to cling because of errors seen on sentry 
```

### 2024-05-18T22:37:46Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2024-05-13T22:43:39Z [**sigoden/aichat**](https://github.com/sigoden/aichat)

```
## Break Changing  - always use stream unless set `--no-stream` explicitly (#415) - vertexai config changed: replace `api_base` with `project_id`/`location`  ## Self-Hosted Server  AIChat comes with a built-in lightweight web server:  - Provide access to all LLMs using OpenAI format API - Host LLM playground/arena web applications   $ aichat --serve Chat Completions API: http://127.0.0.1:8000/v1/chat/completions LLM Playground:       http://127.0.0.1:8000/playground LLM ARENA:            http://127.0.0.1:8000/arena   ## New Clients  bedrock, vertex-claude, cloudflare, groq, perplexity, replicate, deepseek, zhipuai, anyscale, deepinfra, fireworks, openrouter, octoai, together  ## New REPL Command   .prompt                  Create a temporary role using a prompt .set max_output_tokens    > .prompt your are a js console  %%> Date.now() 1658333431437  .set max_output_tokens 4096   ## New CLI Options   --serve [<ADDRESS>]    Serve the LLM API and WebAPP --prompt <PROMPT>      Use the system prompt   ## New Configuration Fields  yaml # Set default top-p parameter top_p: null # Command that will be used to edit the current line buffer with ctrl+o # if unset fallback to $EDITOR and $VISUAL buffer_editor: null   ## New Features  - add completion scripts ([#411](https://github.com/sigoden/aichat/pull/411)) - shell commands support revision - add `.prompt` repl command ([#420](https://github.com/sigoden/aichat/pull/420)) - customize model's max_output_tokens ([#428](https://github.com/sigoden/aichat/pull/428)) - builtin models can be overwritten by models config ([#429](https://github.com/sigoden/aichat/pull/429)) - serve all LLMs as OpenAI-compatible API ([#431](https://github.com/sigoden/aichat/pull/431)) - support customizing `top_p` parameter ([#434](https://github.com/sigoden/aichat/pull/434)) - run without config file by set `AICHAT_CLIENT` ([#452](https://github.com/sigoden/aichat/pull/452)) - add `--prompt` option ([#454](https://github.com/sigoden/aichat/pull/454)) - non-streaming returns tokens usage ([#458](https://github.com/sigoden/aichat/pull/458)) - `.model` repl completions show max tokens and price ([#462](https://github.com/sigoden/aichat/pull/462)) 
```

### 2024-05-16T01:26:07Z [**the1812/Bilibili-Evolved**](https://github.com/the1812/Bilibili-Evolved)

```
- 修复 `评论区IP属地显示` 的回复显示了相同地区. (#4745) 
```

### 2024-05-12T21:53:51Z [**be5invis/Sarasa-Gothic**](https://github.com/be5invis/Sarasa-Gothic)

```
### Everything Package  | Package | 7z | zip | |---------|----|-----| | SuperTTC |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-SuperTTC-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-SuperTTC-Unhinted-1.0.12.7z)) | [📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-SuperTTC-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-SuperTTC-Unhinted-1.0.12.zip))| | TTC |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-TTC-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-TTC-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-TTC-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-TTC-Unhinted-1.0.12.zip))| | TTF |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/Sarasa-TTF-Unhinted-1.0.12.7z))| (File too large for GitHub release artifact) | ### Single Family TTF Package  | Package | 7z | zip | |---------|----|-----| | Gothic |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothic-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothic-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothic-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothic-TTF-Unhinted-1.0.12.zip))| | Ui |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUi-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUi-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUi-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUi-TTF-Unhinted-1.0.12.zip))| | Mono |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMono-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMono-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMono-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMono-TTF-Unhinted-1.0.12.zip))| | MonoSlab |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlab-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlab-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlab-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlab-TTF-Unhinted-1.0.12.zip))| | Term |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTerm-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTerm-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTerm-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTerm-TTF-Unhinted-1.0.12.zip))| | TermSlab |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlab-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlab-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlab-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlab-TTF-Unhinted-1.0.12.zip))| | Fixed |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixed-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixed-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixed-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixed-TTF-Unhinted-1.0.12.zip))| | FixedSlab |[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlab-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlab-TTF-Unhinted-1.0.12.7z))|[📦 Download](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlab-TTF-1.0.12.zip) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlab-TTF-Unhinted-1.0.12.zip))|  ### Single Family & Language TTF Package  <details>  | Locale | Gothic | Ui | Mono | MonoSlab | Term | TermSlab | Fixed | FixedSlab | |---|---|---|---|---|---|---|---|---| | CL | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedCL-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabCL-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabCL-TTF-Unhinted-1.0.12.7z)) | | SC | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabSC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabSC-TTF-Unhinted-1.0.12.7z)) | | TC | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedTC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabTC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabTC-TTF-Unhinted-1.0.12.7z)) | | HC | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedHC-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabHC-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabHC-TTF-Unhinted-1.0.12.7z)) | | J | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedJ-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabJ-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabJ-TTF-Unhinted-1.0.12.7z)) | | K | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaGothicK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaUiK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaMonoSlabK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaTermSlabK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedK-TTF-Unhinted-1.0.12.7z)) | [7z](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabK-TTF-1.0.12.7z) ([Unhinted](https://github.com/be5invis/Sarasa-Gothic/releases/download/v1.0.12/SarasaFixedSlabK-TTF-Unhinted-1.0.12.7z)) | </details> 
```

### 2024-05-14T20:48:27Z [**iiordanov/remote-desktop-clients**](https://github.com/iiordanov/remote-desktop-clients)

```
RELEASE-v5.4.8 
```

### 2024-05-18T06:38:15Z [**MrMissx/Telegram_Forwarder**](https://github.com/MrMissx/Telegram_Forwarder)

```
## Added * add word filters and blacklist by in https://github.com/MrMissx/Telegram_Forwarder/pull/98   **Full Changelog**: https://github.com/MrMissx/Telegram_Forwarder/compare/2.2.1...2.3.0 
```

### 2024-05-16T12:07:30Z [**plutobell/teelebot**](https://github.com/plutobell/teelebot)

```
* 消息发送类型方法新增参数 run_in_thread * 消息发送类型方法新增参数 del_msg_after * 修复bug 
```

### 2024-05-18T18:48:29Z [**floccusaddon/floccus**](https://github.com/floccusaddon/floccus)

```
### Fixed  - [native] fix: set largeHeap to true on android + fix git settings - fix: Improve locking logic - fix(NextcloudBookmarks#getExistingBookmarks): Don't use search-by-url for javascript links - fix: Make Diff#inspect() output more readable - fix: Limit concurrency for reorderings - fix: Improve bulkImport performance by chunking - fix: Unhandled error "Receiving end does not exist" 
```

### 2024-05-16T04:10:57Z [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/5077/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/5077/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### 2024-05-18T11:12:03Z [**ccxt/ccxt**](https://github.com/ccxt/ccxt)

```
## What's Changed * build: [ci deploy] [skip-tests] by @carlosmiei in https://github.com/ccxt/ccxt/pull/22545   **Full Changelog**: https://github.com/ccxt/ccxt/compare/4.3.25...4.3.27 
```

### 2024-05-15T12:21:16Z [**shuzijun/leetcode-editor**](https://github.com/shuzijun/leetcode-editor)

```
### Added - Code Type: Pandas & PostgreSQL enhancement [#709](https://github.com/shuzijun/leetcode-editor/issues/709) - 希望点击搜索按钮时可以自动聚焦到搜索框 [#713](https://github.com/shuzijun/leetcode-editor/issues/713)  ### Changed  ### Deprecated  ### Fixed - fix [#708](https://github.com/shuzijun/leetcode-editor/issues/708) - fix [#712](https://github.com/shuzijun/leetcode-editor/issues/712)  ### Removed 
```

