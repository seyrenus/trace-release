# Repositories with Latest Commits within 7 days

### 2024-04-16T03:35:54Z [**huangyz0918/termax**](https://github.com/huangyz0918/termax)

```
 
```

### 2024-04-15T20:49:53Z [**dunst-project/dunst**](https://github.com/dunst-project/dunst)

```
This release hopefully marks the start of a new period of active development and contributions and a shift away from the previous lower maintenance mode.  For users:  This is the perfect time to engage with the project and other dunst users. Some of the features and changes to include in the v2 release are starting to be proposed or implemented. Everyone's opinion is important, so feel free to participate in the issues proposing new features (or redesigns of the old ones).  This version mainly contains bug fixes and QoL improvements, and can be considered a preparatory release for the various things that will come in the future (overhaul of the rule syntax, multiple windows support, aesthetic and customization options, refactor of the drawing system, etc).  For maintainers:  X11 support is now optional and can be disabled in build by setting the `X11` make flag to 0. This means that you can offer Wayland-only builds.  Shell completions are now considered official and can be installed/uninstalled from the Makefile. By default they are installed and can be disabled by setting the `COMPLETIONS` flag to 0.  Take a look at the changelog for all the bug fixes and improvements. ### Added - Add `corners`, `progress_bar_corners` and `icon_corners` options to control which corners to round (#1268) - Support GTK/CSS cursor names on Wayland (#1276) - Make dunst more portable (#1288) - Print detected monitors names (X11) (#1332)  ### Changed - Make X11 optional in build (this allows wayland-only dunst) (#1290) - Shell completions are now official and can be installed from the Makefile (#1262, #1263) - Don't search for icon path if icons are disabled (#1301) - Eagerly parse and cache colors (#1306) - Update dunstctl manpage (#1298) - Update documentation (#1315, #1334)  ### Fixed - Fix settings initialization (this prevented --print and --startup\_notification from working) (#1299) - Rework timer logic and fix error about Glib source ID for good (#1308, #1196) - Prevent memory corruption in XrmSetDatabase (#1256, #1291) - Don't try to print NULL strings (#1323) - Do not resolve icon paths twice (#1307, #1314) - Don't crash the test suite if librsvg is not present (#1329) - Fix memory leak in DBus RuleEnable (#1328) - Fix dunstctl rule (#1281) - Remove newlines from icon logging (#1296) - Prevent make from failing if git tags are not found (#1287) - Fix some typos (#1324, #1325, #1279)  **Full Changelog**: https://github.com/dunst-project/dunst/compare/v1.10.0...v1.11.0  **New maintainers:** - [Bjoern Hiller](https://github.com/zappolowski) <bjoern.hiller@gmail.com> - [Federico Angelilli](https://github.com/bynect) <fedeangemail@gmail.com> - [Friso Smit](https://github.com/fwsmit) <fw.smit01@gmail.com> 
```

### 2024-04-15T06:19:45Z [**dreamhunter2333/cloudflare_temp_email**](https://github.com/dreamhunter2333/cloudflare_temp_email)

```
## What's Changed  - 添加用户界面安装文档 - 支持邮件 DKIM - 限流配置 /api/new_address  * feat: add docs for ui install by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/127 * fix: docs depoly by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/128 * feat: support DKIM by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/129 * feat: add /api/new_address ratelimit by @dreamhunter2333 in https://github.com/dreamhunter2333/cloudflare_temp_email/pull/130   **Full Changelog**: https://github.com/dreamhunter2333/cloudflare_temp_email/compare/v0.2.6...v0.2.7 
```

### 2024-04-19T05:59:18Z [**KaringX/karing**](https://github.com/KaringX/karing)

```
1. android: Fixed the problem that the timeout callback did not take effect, causing the application to freeze when using certain wg protocols and initializing DNS resolution under android. 2. Adjust the configuration expiration reminder from 30 days to 14 days 3. Add additional http proxy to vpn option in mobile selection 4. Other improvements and fixes  ----------------------------------------------------------------------------  1. android: 修复超时回调未生效导致android下使用某些wg协议,初始化解析dns造成应用卡死的问题 2. 配置过期提醒由30天调整为14天 3. 移动选新增附加http proxy到vpn选项 4. 其他改进及修复 
```

### 2024-04-17T16:26:57Z [**xiaopanglian/icefox**](https://github.com/xiaopanglian/icefox)

```
新增顶部友情链接 新增点击文章头像旁用户名跳转到详情页链接 优化点击备份通知显示问题 优化浏览器不支持cookie时显示问题 优化评论回复后显示问题 优化夜间模式线条颜色搭配 调整部分svg素材 统一页内顶部悬浮框 
```

### 2024-04-18T13:42:48Z [**postalserver/postal**](https://github.com/postalserver/postal)

```
## [3.3.3](https://github.com/postalserver/postal/compare/3.3.2...3.3.3) (2024-04-18)   ### Bug Fixes  * **legacy-api:** allow _expansions to be provided as true to return all expansions ([39f704c](https://github.com/postalserver/postal/commit/39f704c256fc3e71a1dc009acc77796a1efffead)), closes [#2932](https://github.com/postalserver/postal/issues/2932) 
```

### 2024-04-20T04:47:24Z [**babalae/better-genshin-impact**](https://github.com/babalae/better-genshin-impact)

```
久等了的一次更新，最近社畜有点忙  ![ed9149f3db5048ae7702416009fd7b08](https://github.com/babalae/better-genshin-impact/assets/15783049/1217905c-ef66-454a-9576-2f29a99d4601)   ## 新功能 * **新增通知模块** @Mr-Quin   ## 操控辅助 * **一键战斗宏，按下后会识别当前出战角色，并根据配置执行对应的宏，比如：皇女滑步弓、胡桃A重跳**     * 暂不支持联机环境，切人cd时识别率会很差     * 有兴趣可以在交流群联系我贡献更多的宏 https://docs.qq.com/sheet/DTGZqVVhkZk5SWEtn?tab=000001 * 一键进出尘歌壶 #340 @Mr-Quin  * 一键确认/取消 #170   ## 自动战斗/秘境 * **大幅优化在自动战斗/秘境中队伍角色的识别成功率，在头像未处于半透明情况下识别率非常高（使用新训练的分类器替代原有的OCR方案）** * 自动战斗/秘境支持自动选择合适的策略，无需手动切换策略  ## 自动剧情 * 自动交付物品支持多物品 * 添加更多NPC的对话选项排除（暂停选择） #350 @snouker * 添加不自动选择选项的功能选项 #350   ## UI/UX优化 * 在遮盖窗口中添加状态指示 #319 #67 @Mr-Quin  ![image](https://github.com/babalae/better-genshin-impact/assets/15783049/d27d5ce5-a9fd-4138-9b2e-8e7ba174c732) * 启动软件时自动获取焦点 #325 @Mr-Quin  * 通用设置里增加“退出时最小化到托盘”选项 #324 @Mr-Quin   ## 其他优化 * Yap 自动拾取模型更新 * 修复原神启动时，'config.ini' 不生效的问题（用了官B切换工具，但使用BetterGI启动时永远是官服） * 优化了内部模板匹配方法，使之支持所有模板匹配算法 * 内部代码结构优化 @Lightczx  
```

### 2024-04-18T13:47:02Z [**casibase/casibase**](https://github.com/casibase/casibase)

```
# [1.73.0](https://github.com/casibase/casibase/compare/v1.72.0...v1.73.0) (2024-04-18)   ### Features  * improve exportText() ([bc90b2f](https://github.com/casibase/casibase/commit/bc90b2fb3fa7f98c7c2b7ecaba2a3889426b8490)) * support Claude3 model provider ([#785](https://github.com/casibase/casibase/issues/785)) ([cca3874](https://github.com/casibase/casibase/commit/cca3874756bb353d631ac3b9ce71b55bf9196efd)) 
```

### 2024-04-18T04:07:42Z [**labring/FastGPT**](https://github.com/labring/FastGPT)

```
修复语音输入在高级编排中无法选择。 
```

### 2024-04-18T05:05:46Z [**Calcium-Ion/new-api**](https://github.com/Calcium-Ion/new-api)

```
**Full Changelog**: https://github.com/Calcium-Ion/new-api/compare/v0.2.1.0-alpha.35...v0.2.1.1  ## What's Changed * Update README.md by @h1xy in https://github.com/Calcium-Ion/new-api/pull/98 * fix: layout issues by @xyspg in https://github.com/Calcium-Ion/new-api/pull/113 * feat: support midjourney-proxy-plus by @Calcium-Ion in https://github.com/Calcium-Ion/new-api/pull/114 * fix: openai_organization not working by @wozulong in https://github.com/Calcium-Ion/new-api/pull/125 * feat: 敏感词过滤 by @Calcium-Ion in https://github.com/Calcium-Ion/new-api/pull/131 * feat: support 01.AI by @MapleEve in https://github.com/Calcium-Ion/new-api/pull/137 * feat: vite by @Calcium-Ion in https://github.com/Calcium-Ion/new-api/pull/141 * fix(global): error in console under dev mode by @QuentinHsu in https://github.com/Calcium-Ion/new-api/pull/145 * fix: 支持 /mj-{mode} 路径 by @xyfacai in https://github.com/Calcium-Ion/new-api/pull/165 * 增加MJ上游构图失败判断 by @weikecloud in https://github.com/Calcium-Ion/new-api/pull/167 * Support Claude TopK by @MapleEve in https://github.com/Calcium-Ion/new-api/pull/172 * Rename .prettierrc.mjs  to .prettierrc.mjs by @AI-ASS in https://github.com/Calcium-Ion/new-api/pull/174 * refactor(helpers): renderGroup function by @QuentinHsu in https://github.com/Calcium-Ion/new-api/pull/176 * 修改了用户注册使用临时邮箱验证的问题 by @ye4293 in https://github.com/Calcium-Ion/new-api/pull/175 * perf(Setting): setting tab navigation by @QuentinHsu in https://github.com/Calcium-Ion/new-api/pull/171 * fix: 修复渠道一次性添加很多model失败 by @xyfacai in https://github.com/Calcium-Ion/new-api/pull/188 * Fix: CompletionRatio is not working for openrouter.ai by @h1xy in https://github.com/Calcium-Ion/new-api/pull/185 * 清除mj prompt里的--mode by @iszcz in https://github.com/Calcium-Ion/new-api/pull/183 * Update model-ratio.go by @xqx333 in https://github.com/Calcium-Ion/new-api/pull/197 * fix: Gemini new model name error and Support both v1 and v1beta models by @MapleEve in https://github.com/Calcium-Ion/new-api/pull/205 * feat: 新增渠道复制功能 by @iszcz in https://github.com/Calcium-Ion/new-api/pull/194 * fix: the dark mode does not work for the `OperationSetting` and `SystemSetting` panels by @kahosan in https://github.com/Calcium-Ion/new-api/pull/208  ## New Contributors * @h1xy made their first contribution in https://github.com/Calcium-Ion/new-api/pull/98 * @xyspg made their first contribution in https://github.com/Calcium-Ion/new-api/pull/113 * @wozulong made their first contribution in https://github.com/Calcium-Ion/new-api/pull/125 * @MapleEve made their first contribution in https://github.com/Calcium-Ion/new-api/pull/137 * @weikecloud made their first contribution in https://github.com/Calcium-Ion/new-api/pull/167 * @ye4293 made their first contribution in https://github.com/Calcium-Ion/new-api/pull/175 * @iszcz made their first contribution in https://github.com/Calcium-Ion/new-api/pull/183 * @xqx333 made their first contribution in https://github.com/Calcium-Ion/new-api/pull/197 * @kahosan made their first contribution in https://github.com/Calcium-Ion/new-api/pull/208  **Full Changelog**: https://github.com/Calcium-Ion/new-api/compare/v0.2.0.2...v0.2.1.1 
```

### 2024-04-18T21:19:54Z [**srcrs/rss-reader**](https://github.com/srcrs/rss-reader)

```
1.ws关闭页面自动刷新 2.移动端页面取消自动刷新 
```

### 2024-04-19T23:58:09Z [**dockur/windows**](https://github.com/dockur/windows)

```
## What's Changed * fix: Disable secure boot by default by @kroese in https://github.com/dockur/windows/pull/399 * feat: Print system info to log by @kroese in https://github.com/dockur/windows/pull/400   **Full Changelog**: https://github.com/dockur/windows/compare/v2.13...v2.14 
```

### 2024-04-16T00:22:44Z [**jason5ng32/MyIP**](https://github.com/jason5ng32/MyIP)

```
## What's Changed  1. Added DNS resolution feature. 2. Added Advanced features panel; home page optimized. 3. SpeedTest now allows users to choose download/upload file sizes, and can be paused during testing. 4. Improved usability by optimizing the way environment variables are checked.  ## Bug Fixes  1. Fixed some UI bugs. 2. Optimized some program logic. 
```

### 2024-04-16T22:13:05Z [**open-webui/open-webui**](https://github.com/open-webui/open-webui)

```
## [0.1.119] - 2024-04-16  ### Added  - **🌟 Enhanced RAG Embedding Support**: Ollama, and OpenAI models can now be used for RAG embedding model. - **🔄 Seamless Integration**: Copy 'ollama run <model name>' directly from Ollama page to easily select and pull models. - **🏷️ Tagging Feature**: Add tags to chats directly via the sidebar chat menu. - **📱 Mobile Accessibility**: Swipe left and right on mobile to effortlessly open and close the sidebar. - **🔍 Improved Navigation**: Admin panel now supports pagination for user list. - **🌍 Additional Language Support**: Added Polish language support.  ### Fixed  - **🌍 Language Enhancements**: Vietnamese and Spanish translations have been improved. - **🔧 Helm Fixes**: Resolved issues with Helm trailing slash and manifest.json.  ### Changed  - **🐳 Docker Optimization**: Updated docker image build process to utilize 'uv' for significantly faster builds compared to 'pip3'.  👏 Massive thanks to our incredible contributors for their hard work and dedication to making this release possible: @pkrolkgp, @djismgaming, @cheahjs, @JanSolo1, @lainedfles, @dariothornhill, @que-nguyen, @justinh-rahb, @7a6ac0, @Fusseldieb  🚀 We'd like to extend a heartfelt thank you to our amazing sponsors for their generous support (Note: We've excluded private sponsors from this list. If you'd like to get featured here, feel free to reach out to us!): @MorrisLu-Taipei, @rfernandez760, @tbendien, @GenieDev101 
```

### 2024-04-14T14:37:32Z [**datawhalechina/llm-universe**](https://github.com/datawhalechina/llm-universe)

```
LLM Universe（动手学大模型应用开发）教程 PDF V1 版本发布！ 
```

### 2024-04-20T23:55:21Z [**ImranR98/Obtainium**](https://github.com/ImranR98/Obtainium)

```
## What's Changed * Native and UI improvements by @re7gog in https://github.com/ImranR98/Obtainium/pull/1548   **Full Changelog**: https://github.com/ImranR98/Obtainium/compare/v1.1.4...v1.1.5 
```

### 2024-04-16T04:12:22Z [**mingzhixian/Easycontrol**](https://github.com/mingzhixian/Easycontrol)

```
更新V1.5.2  V1.5.x将是V1版本最后的版本，不再进行功能性更新，只修复Bug  - 修复崩溃问题 - 缩放UI，便于使用 - 提高稳定性 - 优化连接问题 - 支持分开记忆横竖屏小窗大小和位置 
```

### 2024-04-15T14:08:29Z [**KRTirtho/spotube**](https://github.com/KRTirtho/spotube)

```
## Highlights  - Spotify Connect support a.k.a LAN Control   Users can now control Spotube playback and select local   output devices from other devices on the same network.  - Alternative LRCLIB lyrics provider - Caching improvment making experience smoother  ### Features  * add Spotify homepage personalized recommendations ([#1402](https://github.com/krtirtho/spotube/issues/1402)) ([9e25c74](https://github.com/krtirtho/spotube/commit/9e25c742d4e43e4e10d2b48afb8e6d90288ffa11)) * add user profile page ([39e97ee](https://github.com/krtirtho/spotube/commit/39e97eef34d87348a264843e145f31f82832d12e)) * **android:** Filter Device To Force High Frame Rate ([#880](https://github.com/krtirtho/spotube/issues/880)) ([6e41b10](https://github.com/krtirtho/spotube/commit/6e41b106fa989adee393d3ce2535e75446ad3eea)) * improved caching based on riverpod ([#1343](https://github.com/krtirtho/spotube/issues/1343)) ([6673e5a](https://github.com/krtirtho/spotube/commit/6673e5a8a86b9667cf9dbff9bb7c40ea6b7de771)) * LAN connect a.k.a control remote Spotube playback and local output device selection ([#1355](https://github.com/krtirtho/spotube/issues/1355)) ([68374ef](https://github.com/krtirtho/spotube/commit/68374efd3ec556f31b937e5b96920787b54eec78)) * **lyrics:** add LRCLIB lyrics provider as fallback ([5afe823](https://github.com/krtirtho/spotube/commit/5afe823abdb198340b55d138d8173d886a811632)) * search history support [#1236](https://github.com/krtirtho/spotube/issues/1236) ([82b1cfa](https://github.com/krtirtho/spotube/commit/82b1cfa0d775e3958c666280943a893c9113d468)) * **translations:** Add Czech translation ([#1401](https://github.com/krtirtho/spotube/issues/1401)) ([5a6b800](https://github.com/krtirtho/spotube/commit/5a6b80091259359bc38c4b91cd8cb496c4270fa4)) * **translations:** add Thai Language ([#1319](https://github.com/krtirtho/spotube/issues/1319)) ([b70f250](https://github.com/krtirtho/spotube/commit/b70f250e8d5137fd990787ec9e3d058126cf14f3)), closes [#1310](https://github.com/krtirtho/spotube/issues/1310) [#1311](https://github.com/krtirtho/spotube/issues/1311)   ### Bug Fixes  * instance of Artist bug [#1362](https://github.com/krtirtho/spotube/issues/1362) ([c8dd802](https://github.com/krtirtho/spotube/commit/c8dd8025ec96bd78ed77cae35f1429aa48c16fde)) * **playback:** sponsor block skips and stutters in same position ([0d080b7](https://github.com/krtirtho/spotube/commit/0d080b77b72529c0be5ebc27ace1c52307511f73))  ## What's Changed * Fix broken link in README.md by @MerkomassDev in https://github.com/KRTirtho/spotube/pull/1311 * feat : added Thai Language by @watchakorn-18k in https://github.com/KRTirtho/spotube/pull/1319 * Update app_tr.arb by @mikropsoft in https://github.com/KRTirtho/spotube/pull/1307 * Updating Readme according to #1082 by @ksaadDE in https://github.com/KRTirtho/spotube/pull/1171 * Android: Filter Device To Force High Frame Rate by @brianabdl in https://github.com/KRTirtho/spotube/pull/880 * Add Czech translation by @Tutislav in https://github.com/KRTirtho/spotube/pull/1401  ## New Contributors * @watchakorn-18k made their first contribution in https://github.com/KRTirtho/spotube/pull/1319 * @mikropsoft made their first contribution in https://github.com/KRTirtho/spotube/pull/1307 * @ksaadDE made their first contribution in https://github.com/KRTirtho/spotube/pull/1171 * @brianabdl made their first contribution in https://github.com/KRTirtho/spotube/pull/880 * @Tutislav made their first contribution in https://github.com/KRTirtho/spotube/pull/1401  **Full Changelog**: https://github.com/KRTirtho/spotube/compare/v3.5.0...v3.6.0 
```

### 2024-04-19T12:17:55Z [**lizongying/my-tv**](https://github.com/lizongying/my-tv)

```
* 修复返回键无法退出问题 * 设置中增加退出按钮 * 修改非电视上的样式 * 修复低版本闪退问题 
```

### 2024-04-16T16:23:13Z [**msgbyte/tianji**](https://github.com/msgbyte/tianji)

```
## [1.8.2](https://github.com/msgbyte/tianji/compare/v1.8.1...v1.8.2) (2024-04-16)   ### Features  * add telemetry event count ([8a3c93f](https://github.com/msgbyte/tianji/commit/8a3c93fff71a42a48041af1008f701e9868982c7)) * add track function ([6349931](https://github.com/msgbyte/tianji/commit/6349931714063edb9d17cb45b1a200bb04d48d25)) * Adding Portuguese (pt-PT) Translation ([#52](https://github.com/msgbyte/tianji/issues/52)) ([49fa50c](https://github.com/msgbyte/tianji/commit/49fa50c3cd12a693738aa4b6a7ef3fbdd9fc1da6)) @ChobPT  * telemetry add force to improve url fetch logic ([ac7b44e](https://github.com/msgbyte/tianji/commit/ac7b44e86276819be34ed91eea0b108747fa2c66)) * add github package @KingPin    ### Document  * update openapi ([1db0832](https://github.com/msgbyte/tianji/commit/1db0832d989123a05f034a128d9717da0091f1b7)) * update README ([8acbbb5](https://github.com/msgbyte/tianji/commit/8acbbb56f5401e62e183e73606feb82a3d2890b4))   ### Others  * add title for status page and update UI style for it. ([d3ce409](https://github.com/msgbyte/tianji/commit/d3ce4090022841fa1a7f5624cd958d0ba2dc4e6c)) * fix ci problem ([932d78b](https://github.com/msgbyte/tianji/commit/932d78b172feb4a49a2fd8079180ce9c1f38147f)) * init client sdk ([699aedc](https://github.com/msgbyte/tianji/commit/699aedc272b4ba614280d2cfd92020734303a707)) * remove cache for monitor badge ([10d9438](https://github.com/msgbyte/tianji/commit/10d943854143dff66810793f965d3b0992c569dd)) * rename and add init tracker function ([cdcd6e2](https://github.com/msgbyte/tianji/commit/cdcd6e228467780f87ebab1e2af3f9e22d849196)) * update docker registry name ([48210d2](https://github.com/msgbyte/tianji/commit/48210d29acf50e9fd1d42d23afb22ab431012f2b)) * update translation ([9ce882b](https://github.com/msgbyte/tianji/commit/9ce882ba39b131ad5be89071bd33ff599edeaf4e)) * upgrade i18next-toolkit and ant design icons, and update translation ([1dec411](https://github.com/msgbyte/tianji/commit/1dec411dd342ca2001d8a276bd4076d1b89a59fe)) 
```

### 2024-04-19T10:23:57Z [**reqable/reqable-app**](https://github.com/reqable/reqable-app)

```
### windows-macos-linux-android-ios - 🐞 [FIX] The bug of API request global setting not taking effect in some cases. - 🐞 [FIX] The bug that the API request domain name cannot be associated with cookies when using environment variables. - 🐞 [FIX] The bug that `=` and `&` in API request query entry are not automatically encoded. - 🐞 [FIX] A bug that some exceptions caused by automatic decoding of API query when created from the traffic list. - 🐞 [FIX] The bug that the table mode input autocomplte list will be display incomplete near the bottom of the application. - 🐞 [FIX] A bug that may cause crash when importing p12 certificate. ### windows-macos-linux - 🐞 [FIX] The bug that dragging selection in the editor cannot automatically request focus. - 🐞 [FIX] A bug where directly importing cURL into the API request input box would cause the app to freeze. - 💪 [OPT] The focus of the input field is still maintained after selecting auto-complete content in table mode. ### windows - 🐞 [FIX] Fix the bug where the app information cannot be dumped in some cases. - 🐞 [FIX] Fix the bug where some chinese fonts are displayed abnormally. 
```

### 2024-04-16T19:17:53Z [**OwO-Network/DeepLX**](https://github.com/OwO-Network/DeepLX)

```
**Full Changelog**: https://github.com/OwO-Network/DeepLX/compare/v0.9.2...v0.9.3 
```

### 2024-04-15T15:34:46Z [**jianchang512/pyvideotrans**](https://github.com/jianchang512/pyvideotrans)

```
  # 更新记录  0. 增加 Google Speech 语音识别接口 1. 增加 Azure AI TTS 配音渠道，菜单-设置-Azure AI TTS 中配置 region key 2. 内置免费ChatGPT API，由 https://apiskey.top 赞助 3. 优化报错提示  ##  Window预打包版/解压后双击 sp.exe  不支持win7系统  **v1.54升级包补丁**： https://github.com/jianchang512/pyvideotrans/releases/download/v1.51/win-PatchUpdate-1.54.zip  v1.51完整包github下载：https://github.com/jianchang512/pyvideotrans/releases/download/v1.51/win-videotrans-v1.51.7z  v1.51完整包百度网盘：https://pan.baidu.com/s/1VD1XQeR__Ifhibid4oW3hA?pwd=vdis       ## MacOS预打包版/解压后双击 start.app  v1.51完整包github下载：https://github.com/jianchang512/pyvideotrans/releases/download/v1.51/mac-videotrans-v1.51.zip  v1.51完整包百度网盘：https://pan.baidu.com/s/1Kg0-N5_zRmMLoHFHKvFClQ?pwd=aynu  **如果Mac上双击start.app无法打开，请尝试在start.app所属的文件夹上右键->服务->新建位于文件夹位置的终端窗口，然后在终端中执行如下2条命令** ![136f1832fdbd93bdcecbf9ed9c5f7ced](https://github.com/jianchang512/pyvideotrans/assets/3378335/fd53811b-1c69-42df-88c7-5945f6fb9712)  - 命令1 `chmod +x ./do` - 命令2 `./do`   ---- ---- ----  # ChangeLog  0. Add Azure AI TTS 1. Built-in free ChatGPT API, sponsored by https://apiskey.top 2. Fixed subtitle bug  ## Windows Pre-Packaged Version  **v1.54 upgrade package patch**: https://github.com/jianchang512/pyvideotrans/releases/download/v1.51/win-PatchUpdate-1.54.zip  v1.51 full package GitHub download: https://github.com/jianchang512/pyvideotrans/releases/download/v1.51/win-videotrans-v1.51.7z     ## MacOS Pre-Packaged Version  v1.51 full package GitHub download: https://github.com/jianchang512/pyvideotrans/releases/download/v1.51/mac-videotrans-v1.51.zip  
```

### 2024-04-18T02:08:52Z [**fishjar/kiss-translator**](https://github.com/fishjar/kiss-translator)

```
更新内容：  - 修复划词翻译按钮点击页面不消失的问题 - 优化划词翻译框   - 增加简洁UI界面，支持快捷切换，也可设置默认启用   - 触发方式支持点击、鼠标悬停、选中立即触发三种   - 支持附加样式代码，自定义翻译框样式   - 支持复制词典翻译的内容 - 自定义接口增加`自定义选项`功能   - 借此能够自定义请求的`method`、`body`、`headers`等 - 其他一些小改动或优化 
```

### 2024-04-19T16:41:49Z [**r-nacos/r-nacos**](https://github.com/r-nacos/r-nacos)

```
**Full Changelog**: https://github.com/r-nacos/r-nacos/compare/v0.5.5...v0.5.6  1. 重构控制台接口，把控制台接口独立出来不依赖openapi。这样控制台接口能灵活的支持控制台功能，同时也方便系统对nacos openapi后续的持续兼容。 #58 2. 配置中心，配置信息内容增加配置格式和配置描述两个字段。 #55 #57 3. 控制台页面，配置中心配置编辑器换成代码编辑器，支持高亮显示配置内容，对编辑配置内容操作更友好。 #55 #57 4. 修复重启后配置中心历史记录id从1计数的问题。(配置历史记录id只用于控制台显示，不影响使用) 
```

### 2024-04-18T17:24:46Z [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
## [4.2.0](https://github.com/AstroNvim/AstroNvim/compare/v4.1.12...v4.2.0) (2024-04-18)   ### Features  * add notification to recommend running `:Lazy update` again after AstroNvim updates ([3c81105](https://github.com/AstroNvim/AstroNvim/commit/3c811058edc4094a276e637e1763ca14a6135acc)) 
```

### 2024-04-15T12:07:28Z [**oldratlee/useful-scripts**](https://github.com/oldratlee/useful-scripts)

```
<a href="#dummy"><img src="https://github.com/oldratlee/useful-scripts/assets/1063891/82f2d184-ca16-4c37-b053-07f21fd8aef1" alt="repo-icon" width="20%" align="right" /></a>  > [!IMPORTANT] > This is a WIP/cleanup release for upgrading version to `3.x`  - remove `legacy bin` 🚮 - rename dir `test-cases` to `test` 🆙   > #### It's time to say goodbye, <a href="#"><img src="https://img.shields.io/badge/legacy-bin-red?logo=Pastebin&amp;logoColor=white" alt="legacy bin"></a> my friend > It's been a long day without you my friend > And I'll tell you all about it when I see you again > We've come a long way from where we began > Oh I'll tell you all about it when I see you again  -----  Have Fun! 💕 2024-04-15 
```

### 2024-04-14T07:50:49Z [**pot-app/pot-desktop**](https://github.com/pot-app/pot-desktop)

```
## 2.7.10 (2024-04-14)  ### Break Change:  -   如果更新后遇到闪退问题请重新安装所有插件的最新版本  ### Bugs fixed:  -   Check whether the directory is not empty before uninstall([`e88f2db`](https://github.com/pot-app/pot-desktop/commit/e88f2dbe0846ea61e4a48c290faa7dbc0dd2d549)) (by @Pylogmon) -   repair openai translation prompt description (#731)([`780c499`](https://github.com/pot-app/pot-desktop/commit/780c499d494002ef2e76175ae5fa27c883b6ec3c)) (by @zggsong) 
```

### 2024-04-19T11:11:09Z [**1Panel-dev/1Panel**](https://github.com/1Panel-dev/1Panel)

```
## 功能优化  * 【面板设置】优化面板安全入口长度限制。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/4594  ## 问题修复  * 【网站】修复了网站开启防盗链失败的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/4591 * 【容器】修复了容器日志文件被删除但进程未结束的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/4588 * 【系统】修复了许可证接口可以未授权访问的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/4593 * 【X-Pack】修复了多显卡编号显示异常的问题。 * 【X-Pack】修复了未授权域名访问功能返回 500 错误的问题。 
```

### 2024-04-19T16:41:28Z [**songquanpeng/one-api**](https://github.com/songquanpeng/one-api)

```
## What's Changed * fix: update model-ratio.go 修正文心计费模型名称 by @manjieqi in https://github.com/songquanpeng/one-api/pull/1241 * feat: add embedding-2 support for zhipu by @cdredfox in https://github.com/songquanpeng/one-api/pull/1273 * feat: update baidu model name & ratio by @manjieqi in https://github.com/songquanpeng/one-api/pull/1253 * feat: update baidu model name & ratio by @manjieqi in https://github.com/songquanpeng/one-api/pull/1277 * feat: support Ali stable-diffusion-xl and wanx-v1 model by @mo2g in https://github.com/songquanpeng/one-api/pull/1240 * fix:  fix Lark icon button style by @AI-ASS in https://github.com/songquanpeng/one-api/pull/1279 * feat: berry theme update & bug fix by @MartialBE in https://github.com/songquanpeng/one-api/pull/1282 * chore: resolve the issue of onclick event scope for custom Lark button by @AI-ASS in https://github.com/songquanpeng/one-api/pull/1281 * feat: support function call for ali (close #1242) * feat: support top_k for claude (close #1239) * feat: initial function call support for xunfei * feat: able to set model limitation for token (close #178) * feat: /v1/models now only return available models * feat: add subnet validation (#1275) * feat: support feishu login now * fix: do not detect quota field in error message (close #1276) * feat: show token info when quota is not enough (close #1274) * feat: able to change gemini version (close #1211) * feat: add gpt-4-turbo support (close #1304)  ## New Contributors * @manjieqi made their first contribution in https://github.com/songquanpeng/one-api/pull/1241 * @cdredfox made their first contribution in https://github.com/songquanpeng/one-api/pull/1273 * @mo2g made their first contribution in https://github.com/songquanpeng/one-api/pull/1240  **Full Changelog**: https://github.com/songquanpeng/one-api/compare/v0.6.4...v0.6.5 
```

### 2024-04-17T09:59:47Z [**gnehs/subtitle-translator-electron**](https://github.com/gnehs/subtitle-translator-electron)

```
![SCR-20240417-qdyu](https://github.com/gnehs/subtitle-translator-electron/assets/16719720/779a63b9-eef2-45eb-b05d-8034baaa9d15) - Add compatibility mode   This allows you to use services like LM Studio to perform translations. - Add temperature option - Fixed cost calculate #110  ### Download - [Windows](https://github.com/gnehs/subtitle-translator-electron/releases/download/1.5.0/subtitle-translator_1.5.0.exe) - [macOS](https://github.com/gnehs/subtitle-translator-electron/releases/download/1.5.0/subtitle-translator_1.5.0.dmg) - [Linux](https://github.com/gnehs/subtitle-translator-electron/releases/download/1.5.0/subtitle-translator_1.5.0.AppImage)  <details><summary>Compatibility mode details</summary>  Tested on: - M3 Pro with 36GB RAM - [LM Studio](https://lmstudio.ai/) 0.2.19   - CORS: `on`   - Model: [Qwen/Qwen1.5-32B-Chat-GGUF](https://huggingface.co/Qwen/Qwen1.5-32B-Chat-GGUF/tree/main) (qwen1_5-32b-chat-q4_k_m.gguf) - Subtitle Translator 1.5.0   - API Host: `http://localhost:1234/v1`   - Model name: `Qwen/Qwen1.5-32B-Chat-GGUF`   - Compatibility Mode: `Enable`   - Prompt:  // You are a professional subtitle translator. // You will only receive subtitles and are only required to translate, no need for any replies. // Note: {{additional}} // Do not merge sentences, translate them individually. // 1. Parse the input subtitles // 2. Translate the input subtitles into {{lang}} // 3. Convert names into {{lang}} // 4. Paraphrase the translated subtitles into more fluent sentences // 5. Output the translated subtitles as string[]   </details> 
```

### 2024-04-19T18:27:04Z [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- Fix poster download on old Android versions where system CA are outdated 
```

### 2024-04-20T22:37:04Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2024-04-14T17:49:16Z [**krahets/hello-algo**](https://github.com/krahets/hello-algo)

```
《Hello 算法》1.1.0 版本的 PDF 电子书请见附件，支持 Python、C++、Java、C#、Go、Swift、JavaScript、TypeScript、Dart、Rust、C 和 Kotlin 等语言。  ## 主要改动  - 新增小节：纸质书、序，重写小节：术语表。 - 新增繁体中文版（由 @Shyam-Chen、@Dr-XYZ 审阅）。 - 新增 Kotlin 语言（由 @curtishd 审阅），修订 Swift 代码（@nuomi1）。 - 新增中译英指南、翻译图文等（由 @K3v123、@yuelinxin、@RafaelCaso、@thomasq0、@QiLOL、@pengchzn 审阅）。 - 重新设计网页版主页、优化术语标注、PDF callouts 等。 - 修复各类已知问题。  ## 贡献者  感谢 @Allen-Scai, @CuB3y0nd, @Dr-XYZ, @Gonglja, @K3v123, @KeiichiKasai, @Phoenix0415, @QiLOL, @Reanon, @SamJin98, @YangXuanyi, @bluebean-cloud, @curtishd, @cy-by-side, @echo1937, @fanenr, @hpstory, @hugtyftg, @khoaxuantu, @krahets, @longsizhuo, @nanlei, @nidhoggfgg, @night-cruise, @nuomi1, @primexiao, @qq909244296, @rongyi, @sdshaoda, @yang-le 对该版本的贡献！  > [!tip] >  纸质书已发行，详情请见[此链接](https://www.hello-algo.com/chapter_paperbook/)。 
```

### 2024-04-18T17:27:21Z [**louislam/uptime-kuma**](https://github.com/louislam/uptime-kuma)

```
> [!WARNING] > The i18n detection mehanism which matches your languages and our languages introduced in #4244 was too basic (depending on your setup you might or might not be affected) > See #4692 for further details.  > [!WARNING] > If you use proxys, please use `1.23.11` instead, as the more reliable events from #4630 don't take this part into consideration. > If you want to prevent such breakages in the future, we would be very happy with increasing the test-coverage in general ^^  ### 💇‍♀️ Improvements - #4477 Improved helptext of how to send mail via the systems mail subsystem (Thanks @apio-sys) - #4630 Feat: Use keylog event to obtain TLS certificate for better reliability [1.23.X] (Thanks @chakflying)  ### 🐞 Bug Fixes - #4326 Fix `encodeBase64` for empty password or user in HTTP Basic Authentication (Thanks @Saibamen) - #4244 made sure that the i18n does use `navigator.languages` instead of  `navigator.language` for automatic language detection (Thanks @CommanderStorm) - #3598 fix(notification-dingding): throw error when failed (Thanks @AnnAngela) - #4417 Fix: Make sure browser is connected before returning (Thanks @chakflying) - #4425 Fix: [JSON-Query] Prevent parsing string-only JSON (Thanks @chakflying) - #4631 Fix: Add missing FK for monitor-tls-info table [1.23.X] (Thanks @chakflying)  ### ⬆️ Security Fixes - GHSA-23q2-5gf8-gjpp - #4653 fix: Update nodemailer to fix GHSA-9h6g-pr28-7cqp [1.23.X] (Thanks @Saibamen) - #4652 fix: Update `axios`, `@actions/github` and `dompurify`  [1.23.X] (Thanks @Saibamen) - Update all dependencies  ### 🦎 Translation Contributions  ### Others - #4633 Fix: Fix CI on Windows Runner [1.23.X] (Thanks @chakflying) - Other small changes, code refactoring and comment/doc updates in this repo: 
```

### 2024-04-20T10:25:17Z [**LlmKira/Openaibot**](https://github.com/LlmKira/Openaibot)

```
A more complete conversation experience, and the problem of repeated searches has been fixed.  ## What's Changed * Logic Mock In Recursive function snapshot process by @sudoskys in https://github.com/LlmKira/Openaibot/pull/403   **Full Changelog**: https://github.com/LlmKira/Openaibot/compare/pypi_1.0.3...app_4.0.4 
```

### 2024-04-18T06:41:53Z [**nxtrace/NTrace-core**](https://github.com/nxtrace/NTrace-core)

```
- 修正在ECMP网络下的表现 - [修改一些显示问题，对于FASTTRACE/TESTFILE功能应用NO_COLOR属性，对于TESTFILE应用IP隐匿功能。](https://github.com/nxtrace/NTrace-V1/commit/cbc511f0975421fa3fb395998db6b63adf79d0ba) - [修复ft时个别地方未应用色彩参数的问题](https://github.com/nxtrace/NTrace-V1/commit/c6eb9bbd2ea27fcd516dfc946165f50afb2967af) - 一些依赖更新   **Full Changelog**: https://github.com/nxtrace/NTrace-core/compare/v1.2.9...v1.3.0 
```

### 2024-04-14T01:51:17Z [**plutobell/teelebot**](https://github.com/plutobell/teelebot)

```
* 修复bug 
```

### 2024-04-19T07:13:45Z [**TophantTechnology/ARL**](https://github.com/TophantTechnology/ARL)

```
1. 添加 wih 结果导出、删除功能。#715 2. 任务管理添加站点、域名、WIH结果数量字段筛选 #659 3. 文档优化 docker-compose 替换为 docker compose #737 4. 升级 Rabitmq 版本 3.13.1 #732 5. 策略配置添加排除端口 #735 6. 测试通知失败问题修复 #700 #699 7. fofa 数据源添加最大页数和每页数量配置 #701 8. nuclei 结果批量删除。 #739 9. 升级nuclei 版本为 v3.2.4 10. 优化任务进程被KILL状态一直不变问题 #669 #654    更新参考：[更新文档](https://tophanttechnology.github.io/ARL-doc/faq/#5-docker-arl) 
```

### 2024-04-17T03:51:36Z [**go-rod/rod**](https://github.com/go-rod/rod)

```
There's a breaking change, now if you want the same behavior before, you have to manually call the `Launcher.AlwaysOpenPDFExternally`.  **Full Changelog**: https://github.com/go-rod/rod/compare/v0.114.8...v0.115.0 
```

### 2024-04-20T12:23:23Z [**sissbruecker/linkding**](https://github.com/sissbruecker/linkding)

```
## What's Changed * Add reader mode by @sissbruecker in https://github.com/sissbruecker/linkding/pull/703 * Allow uploading custom files for bookmarks by @sissbruecker in https://github.com/sissbruecker/linkding/pull/713 * Add option for marking bookmarks as unread by default by @ab623 in https://github.com/sissbruecker/linkding/pull/706 * Make blocking cookie banners more reliable by @sissbruecker in https://github.com/sissbruecker/linkding/pull/699 * Close bookmark details with escape by @sissbruecker in https://github.com/sissbruecker/linkding/pull/702 * Show proper name for bookmark assets in admin by @ab623 in https://github.com/sissbruecker/linkding/pull/708 * Bump sqlparse from 0.4.4 to 0.5.0 by @dependabot in https://github.com/sissbruecker/linkding/pull/704  ## New Contributors * @ab623 made their first contribution in https://github.com/sissbruecker/linkding/pull/706  **Full Changelog**: https://github.com/sissbruecker/linkding/compare/v1.29.0...v1.30.0 
```

### 2024-04-15T15:04:30Z [**python-telegram-bot/python-telegram-bot**](https://github.com/python-telegram-bot/python-telegram-bot)

```
# Version 21.1.1 *Released 2024-04-15*  This is the technical changelog for version 21.1.1. More elaborate release notes can be found in the news channel [@pythontelegrambotchannel](https://t.me/pythontelegrambotchannel).  ## Bug Fixes - Fix Bug With Parameter `message_thread_id` of `Message.reply_*` (#4207 closes #4205)  ## Minor Changes - Remove Deprecation Warning in `JobQueue.run_daily` (#4206 by [@Konano](https://github.com/Konano)) - Fix Annotation of `EncryptedCredentials.decrypted_secret` (#4199 by [@marinelay](https://github.com/marinelay) closes #4198) 
```

