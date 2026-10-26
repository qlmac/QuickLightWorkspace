# 轻量工作台 1.1.3（113）

- 增加直装版启动后的静默更新检查；发现新版本时显示升级窗口，没有更新或网络失败时不弹窗。
- 默认开启自动检查，常驻运行每 24 小时检查；保留用户此前关闭自动检查的选择。可在应用菜单中开启或关闭“自动检查更新”。
- 自动检查只读取升级清单，不自动下载或安装；下载和安装重启均由用户确认。
- 在主界面就绪后显式启动升级控制器，改善启动时机，并保留升级完成后的来源与“重新检查”动作。
- 继续使用 Gitee / GitHub 的 QuickLightWorkspace 升级源，旧 QLLaunch 入口仍可升级。
- 保留九种语言和 Apple Silicon / Intel 通用支持，要求 macOS 14 或更新版本。

旧版如未启用自动检查，请手动检查并升级一次，或下载完整安装包安装。正式 1.1.0（106）及更新版本支持软件内升级，0.x 版本需手动安装。

## English

- The direct edition now checks for updates quietly at startup and every 24 hours while running. An update window appears only when an update is available.
- Automatic checks are enabled by default. Previous opt-out choices are respected; use the application menu to turn automatic checks on or off.
- Checking does not download or install updates automatically. Downloading and restarting to install require confirmation.
- Starts the updater explicitly after the main interface is ready and preserves the update source and recheck action after installation.
- Continues to use the QuickLightWorkspace feeds on Gitee and GitHub. The legacy QLLaunch feeds remain available.
- Universal Apple Silicon / Intel app with nine languages. Requires macOS 14 or later.

If automatic checks are disabled in an older version, check manually and upgrade once, or install the full package. Official version 1.1.0 (106) and later support in-app updates; 0.x versions require manual installation.
