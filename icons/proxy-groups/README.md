# 策略组图标 · proxy-groups

32 张，全部 108×108 PNG。命名直接对应 mihomo `proxy-groups` 里的组名。

| 策略组 | 文件 |
| --- | --- |
| 默认代理 | `global.png` |
| 自动选择 | `auto-select.png` |
| 手动选择 | `local-nodes.png` |
| Ai | `ai.png` |
| Telegram | `telegram.png` |
| YouTube | `youtube.png` |
| Google | `google.png` |
| X | `x.png` |
| GitHub | `github.png` |
| Emby | `emby.png` |
| Video | `infuse.png` |
| Social | `facebook.png` |
| Microsoft | `microsoft.png` |
| Apple | `apple.png` |
| Steam | `steam.png` |
| Game | `game-platforms.png` |
| GameDownload | `game-download.png` |
| 漏网之鱼 | `final.png` |
| 香港智能 | `hongkong.png` |
| 日本智能 | `japan.png` |
| 美国智能 | `usa.png` |
| 新加坡智能 | `singapore.png` |
| 韩国智能 | `korea.png` |
| 英国智能 | `united-kingdom.png` |
| 台湾智能 | `taiwan.png` |
| 香港-稳定IP | `hongkong-lock.png` |
| 日本-稳定IP | `japan-lock.png` |
| 美国-稳定IP | `usa-lock.png` |
| 新加坡-稳定IP | `singapore-lock.png` |
| 韩国-稳定IP | `korea-lock.png` |
| 英国-稳定IP | `united-kingdom-lock.png` |
| 台湾-稳定IP | `taiwan-lock.png` |

## 地区旗为什么分两套

14 个地区组只覆盖 7 个国家，客户端里图标只显示 32px、组名又长，光看旗子分不清
「智能」还是「稳定IP」。所以：

- **智能组** = 纯方角国旗
- **稳定IP组** = 同一面旗 + 右下角一枚锁角标（黑锁 + 白描边，无圆底）

锁角标按旗面真实 alpha bbox 高度的 34% 生成、贴右下角内缩 2%，8× 超采样绘制。

## 来源与许可

| 部分 | 来源 | 许可 |
| --- | --- | --- |
| 18 个服务/入口组 | [zwjtano/icons](https://github.com/zwjtano/icons) | MIT |
| 7 张方角国旗 | [Semporia/Hand-Painted-icon](https://github.com/Semporia/Hand-Painted-icon) | 见原仓库 |
| `game-download.png` | zwjtano `game-platforms.png` + 从 `final.png` 抠出的箭头，本地合成 | 同上 |
| `*-lock.png` 的锁角标 | 本仓库自绘（该图标库无锁类图标） | 随本仓库 |

## 引用

```text
https://raw.githubusercontent.com/ccyin/Clash/main/icons/proxy-groups/ai.png
https://cdn.jsdelivr.net/gh/ccyin/Clash@main/icons/proxy-groups/ai.png
```
