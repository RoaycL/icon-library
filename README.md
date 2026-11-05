# Personal Icon Library

个人图标库，供 Surge、Loon、Egern 等工具使用。

## 目录结构

- `data/icons-all.json`：图标目录（1,630 项）
- `icons/`：镜像图标文件；JSON 中的全部图标均托管于本仓库
- `icons/personal/`：个人自用图标（CloudCone、VMISS、DigitalOcean、PaopaoDog、Skylumo、顶级机场）

原始图标资源来自 [fmz200/wool_scripts](https://github.com/fmz200/wool_scripts)，根据其 GPL-3.0 许可证复制并镜像至本仓库；本仓库同样采用 GPL-3.0。

## Claude / Anthropic 图标

- `icons/apps/Claude_03.png`：以 [Claude 官方 iOS App Store 图标](https://apps.apple.com/us/app/claude-by-anthropic/id6473753684)为来源，替换旧版带阴影图案，并处理为透明圆角。
- `icons/apps/Claude_04.png`：Anthropic 标志，保留原配色与字样，处理为透明圆角。
- 原名称 `Claude_01`、`Claude_02` 及文件保留原版图标。圆角版本以 `Claude_03`、`Claude_04` 新增到目录，使用不同文件链接；更新订阅后请选择编号 `03`、`04` 的新版本。圆角已包含在 PNG 的透明通道中，不依赖客户端裁切。

圆角蒙版使用图像编辑工具生成并清理透明通道，两个图标使用同一蒙版；标志内容来自原始图像，未采用生成工具重绘的内容。Claude / Anthropic 标志归相应权利人所有。

## 新增图标与命名规则

新增图标保留旧版，名称及文件名使用该图标现有最大编号加一，编号至少两位。例如已有 `Google_03`，下一张使用 `Google_04`；无编号的基础名称视为首版，下一张使用 `_02`。不使用字面的 `+1` 后缀。添加前同时检查目录条目和文件，避免覆盖已有编号。

- `Google_04`：[Google iOS](https://apps.apple.com/us/app/id284815942)
- `YouTube_07`：[YouTube iOS](https://apps.apple.com/us/app/id544007664)
- `Telegram_07`：[Telegram iOS](https://apps.apple.com/us/app/id686449807)
- `Twitter_05`：基于库内 `Twitter_03` 经典蓝鸟图案，添加白底圆角图标框。
- `Apple_Home_02`：[Apple 家庭 iOS](https://apps.apple.com/us/app/id1110145103)

新增图标均为 144×144 PNG，沿用相同的透明圆角蒙版。标志归相应权利人所有。

- `github_19`：[GitHub 官方 iOS](https://apps.apple.com/us/app/github/id1477376905)，在现有 `github_18` 基础上递增。
- `steam_02`：[Steam Mobile 官方 iOS](https://apps.apple.com/us/app/steam-mobile/id495369748)，接续现有 `steam`、`steam(1)` 版本。
- `X_02`：[X 官方 iOS](https://apps.apple.com/us/app/x/id333903271)，在现有 `X` 基础上递增；与经典 Twitter 蓝鸟图标分别保留。

## 视觉协调版本

保留官方图案及配色，分别调整留白与主体占比；较小的白底图案放大，Claude、X、Steam 整体收小至 92%，统一在 144×144 透明画布中。旧版均保留。

- `Apple_Home_03`：基于 `Apple_Home_02`，缩放至 120%。
- `Telegram_08`：基于 `Telegram_07`，缩放至 112%。
- `Claude_05`：基于 `Claude_03`，缩放至 92%。
- `X_03`：基于 `X_02`，缩放至 92%。
- `Google_05`：基于 `Google_04`，缩放至 114%。
- `YouTube_08`：基于 `YouTube_07`，缩放至 118%。
- `steam_03`：基于 `steam_02`，缩放至 92%。
- `github_20`：基于 `github_19`，缩放至 110%。
