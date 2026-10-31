# 轻量工作台 1.1.4（114）

- 会员授权页新增“授权数量”，紧接设备 ID 显示可授权数量和已授权数量；数值来自服务器已验签的授权状态，不使用固定范例。未获取时保留未知值，合法离线授权继续有效。
- 合并原来的两行设备数量，查询失败说明统一放入底部提示信息区；新行沿用皮肤字体和字号，内容可自动换行。
- 以简体中文为准同步其余八种语言，补齐授权数量、开机启动、自定义模板和备份恢复相关文字；更新已有的备份恢复说明。
- 保留直装版启动自动检查、Gitee / GitHub 双源和旧 QLLaunch 升级入口。两个渠道均通过 Releases 分发安装包，新版验证成功后保留最新版与上一版。
- 支持 Apple Silicon 与 Intel，包含九种语言，要求 macOS 14 或更新版本。

正式 1.1.0（106）及更新版本可在软件内升级；0.x 请下载完整安装包手动安装。旧版如没有自动检查，请手动检查并升级一次。

## English

- Membership settings now show the device license limit and active count directly below the device ID. Counts come from verified server-signed status. Unavailable counts remain unknown, and valid offline licenses remain usable.
- The two device-count rows are combined. Query guidance appears in the information section. The new row follows the selected appearance font and wraps when needed.
- Updated all nine languages, including device counts, launch at login, custom templates and backup restoration.
- Keeps startup update checks, Gitee / GitHub sources and legacy QLLaunch update feeds. Both sources distribute installers through Releases and retain the latest and previous versions after verification.
- Universal Apple Silicon / Intel app with nine languages. Requires macOS 14 or later.

Official version 1.1.0 (106) and later support in-app updates. Versions 0.x require the full installer. If an older version does not check automatically, check manually and upgrade once.
