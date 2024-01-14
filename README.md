# Repositories with Latest Commits within 7 days

### 2024-01-12T07:13:52Z [**0xjiayu/go_parser**](https://github.com/0xjiayu/go_parser)

```
- Fix bug of go_root parsing - Fix bug about funcID parsing - Fix UTF-8 decoding exception - Fix infinite loop bug caused by error calclating of type addrs for 64-bit binaries 
```

### 2024-01-10T08:35:38Z [**msgbyte/tianji**](https://github.com/msgbyte/tianji)

```
## [1.3.1](https://github.com/msgbyte/tianji/compare/v1.3.0...v1.3.1) (2024-01-10)   ### Bug Fixes  * fix manual start monitor will not loop run bug [#15](https://github.com/msgbyte/tianji/issues/15) ([bcfaab6](https://github.com/msgbyte/tianji/commit/bcfaab6959f56a5c8890937761ce909953d193aa)) 
```

### 2024-01-07T09:30:57Z [**scoful/N-Tab**](https://github.com/scoful/N-Tab)

```
1. 改名N-Tab 2. 修复，锁定组的情况下，开启“打开标签并将其从标签列表中删除”会被删除的情况，锁定了就不能删了，除非解锁 3. 新增2个小功能，发送左侧所有标签，发送右侧所有标签 4. 修改readme，增加使用场景模拟 
```

### 2024-01-12T05:49:51Z [**reqable/reqable-app**](https://github.com/reqable/reqable-app)

```
### windows-macos-linux-android-ios - 🚀 [New] Introduce a new secondary proxy feature. - 🐞 [FIX] The bug that the generated cURL does not merge cookies. - 🐞 [FIX] The bug that the `Referer` header cannot be sent in API requests. - 🐞 [FIX] The bug of missing `application/x-www-form-urlencoded` header in code snippet. - 🐞 [FIX] A bug that may crash when exporting P12 format certificate. ### windows-macos-linux - 🚀 [New] Supports drag sorting of working tabs. - 🚀 [New] You can select or unselect a search condition for traffic list. - 💪 [OPT] The time threshold for triggering drag is reduced from 500ms to 150ms. - 🐞 [FIX] A bug that may jump abnormally when selecting a debug list. ### windows-linux - 💪 [OPT] Supports mouse wheel to control horizontal layout scrolling. ### ios-android - 🚀 [New] Supports double-clicking the title to open the search bar. - 🐞 [FIX] The bug where the proxy port number display is inconsistent with the actual one. - 🐞 [FIX] The bug that the remote device may not be able to coordinate after the address is changed. ### ios - 🚀 [New] Supports opening the browser to download the CA certificate description file. - 🐞 [FIX] The bug that the network will get stuck when entering the background. ### linux - 🐞 [FIX] A bug that may have some exceptions when the certificate is not installed. 
```

### 2024-01-11T06:54:25Z [**clash-verge-rev/clash-verge-rev**](https://github.com/clash-verge-rev/clash-verge-rev)

```
### Features  - Windows 便携版禁用应用内更新 - 支持代理组 Hidden 选项 - 支持 URL Scheme(MacOS & Linux) 
```

### 2024-01-09T07:26:41Z [**shenghui0779/api-tpl-rs**](https://github.com/shenghui0779/api-tpl-rs)

```
因 `OnceCell` 和 `OnceLock` 在 `1.70` 版本中已稳定，故该版本由 `Axum State` 改用 `OnceLock` ，从而减少以 配置、数据库、缓存 等作为函数参数 
```

### 2024-01-13T05:19:04Z [**Yanyutin753/PandoraNext-TokensTool**](https://github.com/Yanyutin753/PandoraNext-TokensTool)

```
## PandoraNext-tokensTool v 0.6.6版本 1. tokensTool新增**copilot接口**,实现**接入fastGPT知识库** > * /cocopilot/v1/embeddings > * /v1/embeddings  2. 接口**使用多线程**，提高**并发能力** 3. **优化失效之后自动关闭分享，恢复之后自动打开分享** 4. 修复历史问题bug,优化代码，优化前端 > * 修复修改Pool传递到oneapi无法更改默认的URl 5. 新增详细[部署使用文档](https://[apifox.com/apidoc/shared-40345b46-9c9c-45cc-b494-6a6a387a978f](https://apifox.com/apidoc/shared-40345b46-9c9c-45cc-b494-6a6a387a978f))，小白迅速上手部署自己的**API站**  > [!important] > >一键部署的可以通过下面代码一键更新 > >cd /tokenTools-sh && sudo sh update.sh > 
```

### 2024-01-07T14:23:07Z [**aristocratos/btop**](https://github.com/aristocratos/btop)

```
## Changelog v1.3.0  * Added Gpu Support Linux | @romner-set | PR #529 * Added platform support for OpenBSD | @joske | PR #607 * Enable macos clang | @muneebmahmed | PR #666 * Fix Apple Silicon CPUs misprinted | @masiboss | PR #679 * Cmake support for MacOS | @imwints | PR #675 * Elementarish theme: color update according to Elementary palette | @stradicat | PR #660 * Add alternative key codes for Delete, Insert, Home, End | @ivanp7 | PR #659 * Fix scrollbar not clearing sometimes. | @DecklynKern | PR #643 * Add keybind for toggling memory display mode in PROC box | @rahulaggarwal965 | PR #623 * Minor string initialization improvement | @imwints | PR #636 * Made disks statvfs logic asynchronous. | @crestfallnatwork | PR #633 * Fix signal list on non-linux/weird linux platforms | @lvxnull | PR #630 * Add option to accumulate a child's resources in parent in tree-view | @imwints | PR #618 * Add CMake support for Linux | @imwints | PR #589 * Horizon theme | @SidVeld | PR #610 * Fix short conversion of 1000-1023 *iB | @scorpion-26 | #609 * Fix integer overflows in btop_collect.cpp | @dorrellmw | #546 * Support compiling with LLVM | @imwints | #510 * Fix getting zfs pool name with '.' char in freebsd | @jfouquart | #602 * [macos/freebsd] support gcc13 | @joske | #600 * FreeBSD swap info | @rrveex | #560 * Create adwaita.theme | @flipflop133 | #485 * Try get terminal size of "/dev/tty" if stdout fails | @imwints | PR #627 * Refresh rate program argument | @imwints | PR #640 * Improved error handling when determining the config directory | @imwints | #652 * Use native POSIX polling syscalls to read input | @lvxnull | #624 * Conditional compile on Big Sur and up | @joske | PR #690 * + Various fixes by @imwints, @simplepad, @joske, @gwena, @cpalv, @iambeingtracked, @mattico, @NexAdn  **For additional binaries see the [Continuous Builds](https://github.com/aristocratos/btop/actions).**  **Linux binaries for each architecture are statically linked with musl and works on kernel 2.6.39 and newer.**  **No Macos and FreeBSD binaries provided for the moment.**  **Notice! None of the binaries have GPU support, compile yourself or wait for distribution packages for GPU monitoring support!**  **Notice! Use x86_64 for 64-bit x86 systems, i486 and i686 are 32-bit!** 
```

### 2024-01-11T16:02:23Z [**tiny-craft/tiny-rdm**](https://github.com/tiny-craft/tiny-rdm)

```
### Fixes * Compatible with server that has "memory" command disabled or unsupported. * Unable to copy binary key name.  ### Optimizations  * Optimized the mouse click for the tree view.  ---  ### 问题修复  * 服务端不支持memory命令导致无法显示内容 * 二进制键名无法复制  ### 功能优化  * 优化树形列表鼠标点击逻辑  --- > If you can not launch on macOS after drop app into `/Application` floder, try to run the command below on terminal >  > 安装完成后如果在macOS下无法运行，请尝试在终端执行以下命令 >  > shell > sudo xattr -d com.apple.quarantine /Applications/Tiny\ RDM.app >  ---  ### 此外本人正式开通微信公众号，不定期更新独立开发以及产品相关内容，欢迎扫码关注  <img alt="微信公众号" src="https://github.com/tiny-craft/tiny-rdm/assets/137850705/d831664a-d24a-42aa-82a4-45208485c80d" style="width: 200px; height: auto;"  /> 
```

### 2024-01-11T08:10:24Z [**gngpp/ninja**](https://github.com/gngpp/ninja)

```
## What's Changed * feat(auth): Dynamically adjust the preauth cookie life cycle by @gngpp in https://github.com/gngpp/ninja/pull/418 * feat(arkose): Restore arkose endpoint usage by @gngpp in https://github.com/gngpp/ninja/pull/419 * deps(reqwest-impersonate): bump version to v0.11.47 by @gngpp in https://github.com/gngpp/ninja/pull/420 * feat(auth): Optimize login prompt by @gngpp in https://github.com/gngpp/ninja/pull/426 * deps(reqwest-impersonate): bump version to v0.11.48 by @gngpp in https://github.com/gngpp/ninja/pull/427 * feat(serve): Support obtaining billing usage by @gngpp in https://github.com/gngpp/ninja/pull/428 * fix(frontend): Fix account status refresh by @gngpp in https://github.com/gngpp/ninja/pull/430 * feat(auth): Return original error message by @gngpp in https://github.com/gngpp/ninja/pull/431 * fix(client): Close request client connection pool and fix tcp keepalive by @gngpp in https://github.com/gngpp/ninja/pull/432   **Full Changelog**: https://github.com/gngpp/ninja/compare/v0.9.8...v0.9.9 
```

### 2024-01-09T15:47:11Z [**heqingpan/rnacos**](https://github.com/heqingpan/rnacos)

```
更新版本到v0.4.2,修复控制台前端时间转化成字符串格式取值错误的问题。  **Full Changelog**: https://github.com/heqingpan/rnacos/compare/v0.4.1...v0.4.2 
```

### 2024-01-13T23:36:39Z [**AstroNvim/AstroNvim**](https://github.com/AstroNvim/AstroNvim)

```
  ### Bug Fixes  * **mappings:** gdu executable for mac is `gdu-go` ([39f5e4a](https://github.com/AstroNvim/AstroNvim/commit/39f5e4af81cffd457f0a5f603d2fd70044e5549c))  **Full Changelog**: https://github.com/AstroNvim/AstroNvim/compare/v3.41.0...v3.41.1 
```

### 2024-01-12T12:32:22Z [**Ajaxy/telegram-tt**](https://github.com/Ajaxy/telegram-tt)

```
null 
```

### 2024-01-07T15:02:00Z [**pot-app/pot-desktop**](https://github.com/pot-app/pot-desktop)

```
## 2.7.4 (2024-01-07)  ### New feature:  -   Support Backup with Aliyun Drive([`f509dc1`](https://github.com/pot-app/pot-desktop/commit/f509dc16f67233f88e8f685b33012963e8773f79)) (by @Pylogmon) -   Add animations for translation card([`c9af0e1`](https://github.com/pot-app/pot-desktop/commit/c9af0e1d16e0298b0cdcec89b4e0c968e9ba0d5a)) (by @spyeic)  ### Bugs fixed:  -   Blank window edge (#653)([`2350eb3`](https://github.com/pot-app/pot-desktop/commit/2350eb37e6d7c09765b04a0587c14ba673945e62)) (by @950288) -   Improve Error Message([`47ef579`](https://github.com/pot-app/pot-desktop/commit/47ef5794f72c43f4302951f366a4b5a2b531f555)) (by @Pylogmon) -   CSP Error([`6daea9e`](https://github.com/pot-app/pot-desktop/commit/6daea9ee4f615277e0651f7b53a844c664823066)) (by @Pylogmon) -   I18n Fallback Language([`d9ecebb`](https://github.com/pot-app/pot-desktop/commit/d9ecebbfab12b305ba6b2231338be32e17886a8c)) (by @Pylogmon) 
```

### 2024-01-11T09:21:36Z [**1Panel-dev/1Panel**](https://github.com/1Panel-dev/1Panel)

```
## 新增功能  * 【网站】PHP 运行环境页面增加扩展模版。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3502 * 【网站】OpenResty 状态栏增加清除反向代理缓存功能。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3471 * 【数据库】新增 PostgreSQL 数据库管理功能。 by @qwenode in https://github.com/1Panel-dev/1Panel/pull/3447 * 【容器】列表增加与容器相关联的网站和应用资源。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3465  ## 功能优化   * 【网站】创建网站时支持输入中文域名。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3472 * 【应用商店】支持根据应用名称和描述信息进行搜索。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3473 * 【应用商店】Halo、Gitea 支持选择 PostgreSQL 数据库。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3504 * 【应用商店】phpMyAdmin 隐藏部分系统数据库。 by @hhun in https://github.com/1Panel-dev/appstore/pull/766 * 【数据库】同步服务器数据库信息时不再创建关联用户。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3442 * 【容器】支持用户选择是否展示应用商店容器。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3469 * 【容器】优化容器监控请求频率。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3563 * 【主机】自动清理压缩失败的 ZIP 文件。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3459 * 【工具箱】适配 Fail2ban v0.10.2 版本。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3503 * 【计划任务】支持备份 PostgreSQL 数据库。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3520 * 【系统】优化部分校验的提示信息。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3554 * 【系统】更新系统中所使用的 IP 地址库。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3561 * 【系统】添加类型转换安全检查。 by @lostmaniac in https://github.com/1Panel-dev/1Panel/pull/3543  ## 问题修复  * 【网站】修复了证书申请界面复制按钮在复制内容时出现的错误。 by @Anyexyz in https://github.com/1Panel-dev/1Panel/pull/3422 * 【网站】修复了因网站文件层级过多而导致的授权超时问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3451 * 【网站】修复了反向代理网站在开启 HTTPS 后 HSTS 配置失效的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3483 * 【网站】修复了部分场景下申请证书超时的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3540 * 【数据库】修复了 MySQL root 密码输入框在部分场景下出现换行问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3479 * 【容器】修复了镜像清理仅显示当前页中未使用镜像的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3558 * 【主机】修复了文件列表跳转每页条数限制不生效的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3570 * 【工具箱】修复了工具箱中 hosts 解析没有忽略 # 注释的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3501 * 【计划任务】修复了网站日志正在写入时可能会导致日志切割失败的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3481 * 【日志审计】修复了网站日志页面在网站为空时报错的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3452 * 【日志审计】修复了部分场景下网站日志清理日志按钮无法点击的问题。 by @zhengkunwang223 in https://github.com/1Panel-dev/1Panel/pull/3562 * 【面板设置】修复了部分场景下创建和恢复快照提示 .db-wal 等事务文件被删除的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3500 * 【面板设置】修复了关闭面板 SSL 异常的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3443 * 【系统】修复了部分页面因右侧抽屉内容过多而导致显示不完整的问题。 by @ssongliu in https://github.com/1Panel-dev/1Panel/pull/3547  ## 应用商店  * 新增 One API。 by @igophper in https://github.com/1Panel-dev/appstore/pull/751 * 新增 Dockge。 by @TScci in https://github.com/1Panel-dev/appstore/pull/753 * 添加 Twikoo。 by @clover1420 in https://github.com/1Panel-dev/appstore/pull/732 * DataEase 版本升级至 v2.2.0。 by @wanghe-fit2cloud in https://github.com/1Panel-dev/appstore/commit/475a080f47e04f08c48ac8580b76e8506f031d0d * Alist 版本升级至 v3.30.0。 by @renovate in https://github.com/1Panel-dev/appstore/pull/780 * uuWAF 版本升级至 v2.7.0。 by @renovate in https://github.com/1Panel-dev/appstore/pull/779 * IT-Tools 版本升级至 2023.12.21。 by @xiongsp in https://github.com/1Panel-dev/appstore/pull/774 * ddns-go 版本升级至 v5.7.1。 by @renovate in https://github.com/1Panel-dev/appstore/pull/786 * Redis 版本升级至 v7.2.4。 by @renovate in https://github.com/1Panel-dev/appstore/pull/793 * Jenkins 版本升级至 v2.440。 by @renovate in https://github.com/1Panel-dev/appstore/pull/795 * MinIO 版本升级至 2024-01-05。 by @wanghe-fit2cloud in https://github.com/1Panel-dev/appstore/commit/b1c57e11f16d3ac83fe151647891bc5756dfa822 * Flarum 版本升级至 v1.8.3。 by @renovate in https://github.com/1Panel-dev/appstore/pull/770 * Audiobookshelf 版本升级至 v2.7.1。 by @renovate in https://github.com/1Panel-dev/appstore/pull/771 * OpenLiteSpeed 版本升级至 v1.7.19。 by @renovate in https://github.com/1Panel-dev/appstore/pull/772 * File Browser 版本升级至 v2.27.0。 by @renovate in https://github.com/1Panel-dev/appstore/pull/773 * Memos 版本升级至 v0.18.2。 by @renovate in https://github.com/1Panel-dev/appstore/pull/777 * Mailserver 版本升级至 v13.2.0。 by @renovate in https://github.com/1Panel-dev/appstore/pull/778 * ClickHouse 版本升级至 v23.12.2。 by @renovate in https://github.com/1Panel-dev/appstore/pull/781 * EMQX 版本升级至 v5.4.1。 by @renovate in https://github.com/1Panel-dev/appstore/pull/782 * Draw.io 版本升级至 v22.1.18。 by @renovate in https://github.com/1Panel-dev/appstore/pull/792 * Nexus Repository 版本升级至 v3.64.0。 by @renovate in https://github.com/1Panel-dev/appstore/pull/794 * Metabase 版本升级至 v0.48.2。 by @renovate in https://github.com/1Panel-dev/appstore/pull/784 * RabbitMQ 版本升级至 v3.12.12。 by @renovate in https://github.com/1Panel-dev/appstore/pull/785 * MongoDB 版本升级至 v7.0.5。 by @renovate in https://github.com/1Panel-dev/appstore/pull/791 
```

### 2024-01-12T09:13:27Z [**nova-video-player/aos-AVP**](https://github.com/nova-video-player/aos-AVP)

```
- libyuv upstep aligned on chromium master - Stability enhancements 
```

### 2024-01-13T22:37:11Z [**Loyalsoldier/clash-rules**](https://github.com/Loyalsoldier/clash-rules)

```
 
```

### 2024-01-13T19:34:13Z [**krahets/hello-algo**](https://github.com/krahets/hello-algo)

```
此版本为《Hello 算法》1.0.0 正式版，主要内容包括：  - 复杂度分析：数据结构和算法的评价维度与方法。时间复杂度和空间复杂度的推算方法、常见类型、示例等。 - 数据结构：基本数据类型和数据结构的分类方法。数组、链表、栈、队列、哈希表、树、堆、图等数据结构的定义、优缺点、常用操作、常见类型、典型应用、实现方法等。 - 算法：搜索、排序、分治、回溯、动态规划、贪心等算法的定义、优缺点、效率、应用场景、解题步骤和示例问题等。  **现已支持 Python, C++, Java, C#, Go, Swift, JavaScript, TypeScript, Dart, Rust, C 等多种编程语言的 PDF 电子书下载**。  ## 主要改动  1. 添加小节：术语表。 2. 引入 pythontutor 代码可视化运行模块。 3. 启动中译英工作流，已完成翻译前三章。 4. 完成整书文字、图片和代码的修订工作。 5. 更新项目 logo、主页图、封面图等素材。 6. 修复各类已知问题。  ## 致谢  一年多来，《Hello 算法》经历了数个版本的迭代，在开源社区 130 多位贡献者的共同努力下不断完善。感谢本书的所有贡献者，包括：@krahets、@codingonion、@Gonglja、@nuomi1、@Reanon、@justin-tse、@hpstory、@danielsss、@S-N-O-R-L-A-X、@night-cruise、@msk397、@gvenusleo、@RiverTwilight、@gyt95、@zhuoqinyue、@Zuoxun、@mingXta、@Xia-Sang、@FangYuan33、@GN-Yu、@IsChristina、@xBLACKICEx、@guowei-gong、@Cathay-Chen、@mgisr、@JoseHung、@qualifier1024、@pengchzn、@Guanngxu、@L-Super、@longsizhuo、@WSL0809、@Slone123c、@lhxsm、@yuan0221、@what-is-me、@K3v123、@longranger2、@theNefelibatas、@yuelinxin、@xiongsp、@JeffersonHuang、@Wonderdch、@malone6、@gaofer、@a16su、@hongyun-robot、@MolDuM、@Nigh、@huawuque404、@iron-irax、@yd-j、@XiaChuerwu、@XC-Zero、@QiLOL、@reeswell、@NI-SW、@Horbin-Magician、@xjr7670、@DullSword、@luluxia、@lucaswangdev、@liuxjerry、@lwbaptx、@lclc6、@kilikilikid、@keshida、@wenjianmin、@jiaxianhua、@iStig、@boloboloda、@hts0000、@gledfish、@fbigm、@szu17dmy、@dshlstarr、@coderlef、@czruby、@xb534、@ElaBosak233、@baagod、@zhouLion、@yishangzhang、@yi427、@yabo083、@weibk、@wangwang105、@th1nk3r-ing、@tao363、@4yDX3906、@syd168、@siqyka、@selear、@noobcodemaker、@chadyi、@lyl625760、@0130w、@shanghai-Jerry、@JackYang-hellobobo、@Javesun99、@lipusheng、@ShiMaRing、@FreddieLi、@FloranceYeh、@Transmigration-zhou、@fanchenggang、@gltianwen、@YangXuanyi、@curly210102、@youshaoXG、@bubble9um、@52coder、@foursevenlove、@KorsChen、@beintentional、@ZongYangL、@hezhizhen、@linzeyan、@ZJKung、@GaochaoZhu、@Evilrabbit520、@Turing-1024-Lee、@Suremotoo、@Richard-Zhang1019、@qingpeng9802、@Phoenix0415、@1ch0、@MwumLi、@ZnYang2018、@logan-qiu、@psychelzh 和 @Keynman 。  ### 代码审阅  本书提供十余种编程语言的实现，代码审阅工作由 @codingonion、@Gonglja、@gvenusleo、@hpstory、@justin-tse、@krahets、@night-cruise、@nuomi1 和 @Reanon 完成。  在本书更新过程中，他们持续为本项目提供代码示例、审阅 PR 、修复 bug 、构建自动化工作流。感谢他们付出的时间，正是他们确保了各语言代码的规范与统一，使得本书覆盖到更多有需要的读者。  ### 中译英  本项目在成长过程中，逐渐吸引了全球读者的关注。因此，我们组建了一个由计算机专业、笔译专业和英语母语者组成的翻译小组，成员包括：@yuelinxin、@K3v123、@yanedie、@Phoenix0415、@QiLOL、@SamJin98、@thomasq0、@YangXuanyi 和 @longsizhuo 。感谢各位投入的精力，正因他们的积极参与，这本书才有机会触及更广泛的读者群体。  我们采用三段式的翻译工作流（机器翻译 > 人工优化 > 审阅）和交叉审查机制，确保翻译内容的准确性和流畅度。翻译工作正在进行中，期待你的加入，详情请见 #914 。  ### 评论区  我们致力于构建一个互助学习的环境。感谢 @hpstory 积极回答读者的问题，@longsizhuo 总结具有启发性的讨论内容，也期待更多贡献者在评论区中回答问题和分享见解。  ## 致读者  > "Knowledge isn't free. You have to pay attention." — Richard P. Feynman > “知识并不免费，你必须付出注意力。” — 理查德 · P · 费曼。  正如费曼教授所言，虽然这本开源书是免费的，但知识并不“免费”。感谢每一位为本书付出宝贵注意力的读者。  希望这本书能够帮助到你！ 
```

### 2024-01-09T11:37:48Z [**fork-maintainers/iceraven-browser**](https://github.com/fork-maintainers/iceraven-browser)

```
## Release info   Iceraven: 2.14.2 Fenix: 121.1.0   ## News  ## Change log  [iceraven-2.14.1...iceraven-2.14.2](https://github.com/fork-maintainers/iceraven-browser/compare/iceraven-2.14.1...iceraven-2.14.2) 
```

### 2024-01-07T20:11:44Z [**TGX-Android/Telegram-X**](https://github.com/TGX-Android/Telegram-X)

```
**Telegram X** `0.26.3.1674` has been released. You can review all changes in the source code [here](https://github.com/TGX-Android/Telegram-X/compare/fa99a84f...8b30d0fe).  ## Changes  * Custom emoji and reactions * Archive settings * Select and adjust link preview * Media-only groups support * In-app avatar picker * Improved notifications reliability * Notifications on Android Auto * Other features and bugfixes.  Read more: https://telegra.ph/Telegram-X-2023-12-31  ## Download * **[Google Play](https://play.google.com/store/apps/details?id=org.thunderdog.challegram)** ([subscribe to beta](https://play.google.com/apps/testing/org.thunderdog.challegram)) * **[Huawei AppGallery](https://appgallery.huawei.com/app/C101754199)** * **[GitHub Releases](https://github.com/TGX-Android/Telegram-X/releases)** * **[Telegram X APKs & Build Info](https://t.me/tgx_log)**  ## Checksums  You can always check if checksum of an APK you downloaded corresponds to any official Telegram X build via [@tgx_bot](https://t.me/tgx_bot).  <details> <summary>Checksums for <code>0.26.3.1674</code>. Tap to expand</summary>  ---  **universal**  MD5: [31718b37fda0c2f90b03cd207cf7528b](https://t.me/tgx_bot?start=31718b37fda0c2f90b03cd207cf7528b) SHA-1: [76bda0a27944da1edd58ba83a234b15ddd14539f](https://t.me/tgx_bot?start=76bda0a27944da1edd58ba83a234b15ddd14539f) SHA-256: [bb0f0d381c1a411db9c7b28806a261cf39b1ea94020b5db4a8ce8a1d6aeb1913](https://t.me/tgx_bot?start=bb0f0d381c1a411db9c7b28806a261cf39b1ea94020b5db4a8ce8a1d6aeb1913)  ---  **arm64-v8a**  MD5: [8d6a3b9f19e45f951d79aeb1535693c5](https://t.me/tgx_bot?start=8d6a3b9f19e45f951d79aeb1535693c5) SHA-1: [cf5694a8ccee7bf53f0be96ff2d0b87be969b986](https://t.me/tgx_bot?start=cf5694a8ccee7bf53f0be96ff2d0b87be969b986) SHA-256: [386a9e1b75dac833017dc2271f00023c3250d6c64791fdc9fdbdcf997562308b](https://t.me/tgx_bot?start=386a9e1b75dac833017dc2271f00023c3250d6c64791fdc9fdbdcf997562308b)  ---  **armeabi-v7a**  MD5: [417188063f40cc9b761edcdfad302289](https://t.me/tgx_bot?start=417188063f40cc9b761edcdfad302289) SHA-1: [a1fda6852e445479011a29f477b85887f76a5620](https://t.me/tgx_bot?start=a1fda6852e445479011a29f477b85887f76a5620) SHA-256: [91df27b546afa41ab19afcde9bb1a0dcc86a5c75fab70944d9d30ff8ab481e37](https://t.me/tgx_bot?start=91df27b546afa41ab19afcde9bb1a0dcc86a5c75fab70944d9d30ff8ab481e37)  ---  **x64**  MD5: [bf1dd9fa44a7020f04a478b8705ad145](https://t.me/tgx_bot?start=bf1dd9fa44a7020f04a478b8705ad145) SHA-1: [6f50703346206fb13f0f3cc400fc29b7a75f2504](https://t.me/tgx_bot?start=6f50703346206fb13f0f3cc400fc29b7a75f2504) SHA-256: [7a8d46122a82ea0b789cddda6b766b6dd8d90eced1cf52f6ab4b56f1e306659b](https://t.me/tgx_bot?start=7a8d46122a82ea0b789cddda6b766b6dd8d90eced1cf52f6ab4b56f1e306659b)  </details> 
```

### 2024-01-11T08:58:23Z [**sigoden/dufs**](https://github.com/sigoden/dufs)

```
### Bug Fixes  - Upload more than 100 files in directory ([#317](https://github.com/sigoden/dufs/issues/317)) - Auth precedence ([#325](https://github.com/sigoden/dufs/issues/325)) - Serve files with names containing newline char ([#328](https://github.com/sigoden/dufs/issues/328)) - Corrupted zip when downloading large folders ([#337](https://github.com/sigoden/dufs/issues/337))  ### Features  - Empty search `?q=` list all paths ([#311](https://github.com/sigoden/dufs/issues/311)) - Add `--compress` option ([#319](https://github.com/sigoden/dufs/issues/319)) - Upgrade to hyper 1.0 ([#321](https://github.com/sigoden/dufs/issues/321)) - Auth supports forbidden permissions ([#329](https://github.com/sigoden/dufs/issues/329)) - Supports resumable uploads ([#343](https://github.com/sigoden/dufs/issues/343))  ### Refactor  - Change the format of www-authenticate ([#312](https://github.com/sigoden/dufs/issues/312)) - Change the value name of `--config` ([#313](https://github.com/sigoden/dufs/issues/313)) - Optimize http range parsing and handling ([#323](https://github.com/sigoden/dufs/issues/323)) - Propfind with auth no need to list all ([#344](https://github.com/sigoden/dufs/issues/344)) 
```

### 2024-01-13T17:15:30Z [**ayrat555/el_monitorro**](https://github.com/ayrat555/el_monitorro)

```
## What's Changed * Docker compose  by @pxp9 in https://github.com/ayrat555/el_monitorro/pull/352 * update rust and deps by @ayrat555 in https://github.com/ayrat555/el_monitorro/pull/353 * fix: handle invalid publication dates by @ayrat555 in https://github.com/ayrat555/el_monitorro/pull/354 * update frankenstein to 0.29.2 by @ayrat555 in https://github.com/ayrat555/el_monitorro/pull/355 * Frankenstein 0.30.0 by @ayrat555 in https://github.com/ayrat555/el_monitorro/pull/356   **Full Changelog**: https://github.com/ayrat555/el_monitorro/compare/0.12.1...0.14.0 
```

### 2024-01-12T19:15:33Z [**Ashinch/ReadYou**](https://github.com/Ashinch/ReadYou)

```
## 0.9.11  1. Remember scroll position on feed pages (#519) (@aeghn)  2. Favicon fetching and handling fixes (#511) (@Ashinch, @kid1412621)  3. Fix "Swipe to Mark Read" gesture marking multiple items as read (#515) (@kid1412621, @mbestavros)  4. Add workaround for "Row too big to fit into CursorWindow" bug (#312) (@mbestavros)  5. Translations updates (thanks to everyone who helped out!)  ### Notes  It's been quite a week for Read You! This release fixes up most of the rest of the major bugs from release 0.9.9, plus one that's been around for a long while.  My hope is that this will be a solid longer-term build, and we can take a break from releases for a bit while we wait for new improvements to cook from our wonderful community. As always, if you encounter a bug, please report it on Github!  Since some of you may have missed the big changes in 0.9.9, I'll include them again below.  ## 0.9.9  1. Fever API now properly syncs read/starred metadata across devices (#401) (#406) (@mbestavros)  2. Add prompt for notification permission when relevant (#422) (@RafhaanShah)  3. New feature: Swipe to mark read (#455) (@boun, @nvllz)  4. New option: External link handling (#428) (@S-H-Y-A)  5. Fetch favicons for feed items (#471) (@Ashinch, @kid1412621)  6. Various internal refactorings and improvements (@Ashinch)  7. Translations updates: Hungarian, Turkish, Serbian, German, Indonesian, Persian, and many others (thanks to everyone who helped out!) 
```

### 2024-01-10T20:00:29Z [**LemmyNet/lemmy**](https://github.com/LemmyNet/lemmy)

```
[Release Notes](https://join-lemmy.org/news/2024-01-10_-_Lemmy_Release_v0.19.2_-_More_Federation_Fixes)  **Full Changelog**: https://github.com/LemmyNet/lemmy/compare/0.19.1...0.19.2 
```

### 2024-01-09T18:43:56Z [**Rongronggg9/RSS-to-Telegram-Bot**](https://github.com/Rongronggg9/RSS-to-Telegram-Bot)

```
### Addition  - **Set niceness for subprocesses/threads**: (Unix only) Nice subprocesses and/or threads to improve the responsiveness of the main process. This is tunable via the environment variable `EXECUTOR_NICENESS_INCREMENT`.  ### Enhancements  - **HTML list support improvement**: Now `<menu>` and `<dir>` are treated the same as `<ul>` (unordered list). In addition, orphan `<li>` (list item) without a valid list parent tag are no longer ignored but treated as an item in an single unordered list.  ### Bug fixes  - **Stay in topic group even when the "General" topic is closed**: Now that topic groups are not fully supported, the bot can only send messages in the "General" topic. Previously, the bot would only send an error message to the bot manager if the "General" topic is closed. Now the bot will leave the topic group, without disturbing the bot manager, if the "General" topic is closed. This is a temporary limitation before topic groups are fully supported. - **v2.4.1 not released to PyPI**: Due to a previous mistake, v2.4.1 could not be released to PyPI. v2.5.0 fixes the mistake and is released to PyPI.   <hr>  ## v2.5.0: 响应性优化、小的增强和修复  ### 新增功能  - **为子进程/线程设置 nice 值**: (仅限 Unix) 为子进程和/或线程提升 nice 值以改进主进程的响应性。这可通过环境变量 `EXECUTOR_NICENESS_INCREMENT` 调节。  ### 增强  - **改进了对 HTML 列表的支持**: 现在，`<menu>` 和 `<dir>` 被视为 `<ul>` (无序列表)。此外，没有有效列表父标签的孤立 `<li>` (列表项) 不再被忽略，而是被视为单个无序列表中的一个项目。  ### Bug 修复  - **即使 “General” 话题已关闭，也留在话题群组中**: 由于话题群组尚未被完全支持，bot 只能在 “General” 话题中发送消息。先前，如果 “General” 话题被关闭，bot 只会向 bot 管理员发送错误消息。现在，如果 “General” 话题被关闭，bot 将离开话题群组，而不再打扰 bot 管理员。这是在话题群组完全受支持之前的一个临时限制。 - **v2.4.1 未被发布到 PyPI**: 由于一个先前的失误，v2.4.1 无法被发布到 PyPI。v2.5.0 修正了这一失误，并被发布到 PyPI。 
```

### 2024-01-08T15:51:24Z [**floccusaddon/floccus**](https://github.com/floccusaddon/floccus)

```
### Fixed  * [chrome] fix(background sync): Apply hack to keep service worker alive  (See v5.0.0 announcement: https://github.com/floccusaddon/floccus/discussions/1449 ) 
```

### 2024-01-10T04:19:21Z [**stefansundin/rssbox**](https://github.com/stefansundin/rssbox)

```
Deploy 139bd28  Diff: https://github.com/stefansundin/rssbox/compare/fly/v21...fly/v22 - [Update gems.](https://github.com/stefansundin/rssbox/commit/a158ec1ba293ec1eec1fb9e1a51504c901bb1570) - [Add `CSRF_PROTECTION` environment variable where you can turn off the robots protection (by setting the variable to `off`). It is enabled by default.](https://github.com/stefansundin/rssbox/commit/c4f9a6d9dc80b20baf3002abb5b570379ac008ec) - [Comment out `env_file` as it does not exist by default.](https://github.com/stefansundin/rssbox/commit/4da9acfdba361da55f431128edbc942f0ba2f001) - [Fix docker signal issues.](https://github.com/stefansundin/rssbox/commit/139bd28a366ead762f96cd76fbccc82f9e3ee61e) 
```

### 2024-01-10T12:43:30Z [**theonedev/onedev**](https://github.com/theonedev/onedev)

```
## Installation Guide  https://docs.onedev.io/category/installation-guide  ## Change Log  https://code.onedev.io/onedev/server/~builds/4496/fixed-issues?query=%22State%22+is+%22Released%22+order+by+%22Type%22+asc+and+%22Priority%22+desc  ## Incompatibilities  https://code.onedev.io/onedev/server/~builds/4496/markdown/Incompatibilities/server-product/system/incompatibilities/incompatibilities.md 
```

### 2024-01-08T03:12:33Z [**pingcap/tidb**](https://github.com/pingcap/tidb)

```
For new features, improvements, and bug fixes released in 6.5.7 for tidb-server, see [TiDB 6.5.7 release notes](https://docs.pingcap.com/tidb/v6.5/release-6.5.7/). See the difference from the issue perspective: <details>  - pingcap/tidb#48808 - pingcap/tidb#49096 - pingcap/tidb#42739 - pingcap/tidb#48741 - pingcap/tidb#48983 - pingcap/tidb#49273 - pingcap/tidb#36004, close pingcap/tidb#38189 - pingcap/tidb#43385 - pingcap/tidb#47071 - pingcap/tidb#47071 - pingcap/tidb#49033 - pingcap/tidb#48164 - pingcap/tidb#49308 - pingcap/tidb#49526 - pingcap/tidb#49631 - pingcap/tidb#49369 - pingcap/tidb#46522 - pingcap/tidb#42337 - pingcap/tidb#49616 - pingcap/tidb#47634 - pingcap/tidb#49377 - pingcap/tidb#49285 - pingcap/tidb#49487 - pingcap/tidb#42931 - pingcap/tidb#44830 - pingcap/tidb#49414 - pingcap/tidb#48969 - pingcap/tidb#49498 - pingcap/tidb#48301 - pingcap/tidb#49801  </details> 
```

### 2024-01-11T04:47:35Z [**dromara/hutool**](https://github.com/dromara/hutool)

```
# 5.8.25(2024-01-11)  ### 🐣新特性 * 【core  】      WatchServer新增通过Path获取WatchKey方法（pr#1145@Gitee） * 【core  】      CopyOptions中增加setAutoTransCamelCase方法（issue#3452@Github） * 【captcha】     验证码生成器增加构造方法，可自定义随机数字符集（pr#1147@Gitee）  ### 🐞Bug修复 * 【core  】      修复StrJoin当append内容后调用length()会出现空指针问题（issue#3444@Github） * 【core  】      修复PostgreSQL、H2使用upsert字段大小写问题（issue#I8PB4X@Gitee） * 【core  】      修复RandomUtil.randomInt,RandomUtil.randomLong边界问题（pr#3450@Github） * 【db    】      修复Druid连接池无法设置部分属性问题（issue#I8STFC@Gitee） * 【core  】      修复金额转换为英文时缺少 trillion 单位问题（pr#3454@Github） * 【json  】      增加ParseConfig，通过增加maxNestingDepth参数避免StackOverflowError问题，修复CVE-2022-45688漏洞（issue#2748@Github） * 【system】      修复UserInfo中用户名加/问题（pr#3458@Github） * 【core  】      修复NumberUtil.toBigDecimal方法报StackOverflowError(CVE-2023-51080)（issue#3423@Github） 
```

