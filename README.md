# Clash

自用的 Clash / Mihomo 资源仓库：分流规则与图标素材。

## 目录

| 目录 | 内容 |
| --- | --- |
| `rules/` | mihomo / OpenClash 分流规则（`.list`） |
| `icons/airport/` | 机场图标（A 序号连续排列）及图标订阅清单 `A000-icons.json` |
| `icons/app/` | 应用 / 面板图标 |
| `icons/emby/` | Emby 服务图标 |
| `configs/` | 配置与转换模板（预留） |
| `docs/` | 说明文档（预留） |

## 引用示例

```text
# 规则集（rule-providers）
https://raw.githubusercontent.com/ccyin/Clash/main/rules/emby-01.list

# 策略组图标
https://raw.githubusercontent.com/ccyin/Clash/main/icons/airport/A001-HongXing.png

# 机场图标订阅清单
https://raw.githubusercontent.com/ccyin/Clash/main/icons/airport/A000-icons.json
```

> 需要 CDN 加速时，把 `raw.githubusercontent.com/ccyin/Clash/main` 换成
> `cdn.jsdelivr.net/gh/ccyin/Clash@main` 即可，路径不变。

## 免责声明

1. 本仓库内容仅供个人学习、技术研究与自用配置参考，不得用于任何商业用途，亦不得用于违反使用者所在地法律法规的用途。
2. 本仓库仅收录公开可获取的域名清单与图标素材，不提供、不推广、不销售任何网络代理、VPN 或网络接入服务；对任何第三方服务的可用性、合法性、安全性不作任何明示或默示的保证。
3. 本仓库内容按「现状」提供，不附带任何担保。因使用或无法使用本仓库内容所造成的任何直接或间接损失——包括但不限于数据丢失、设备或系统损坏、服务中断、账号受限、法律纠纷——本仓库维护者均不承担任何责任。
4. 使用者应自行判断并承担使用本仓库内容的全部风险与法律责任；因违反所在地法律法规而产生的一切后果，由使用者自行承担，与本仓库维护者无关。
5. 如权利人认为本仓库内容侵犯其合法权益，请通过 Issue 联系，核实后将及时删除相关内容。

## 更新记录

- 2026-11-11 重建目录结构，规则与图标重新归档。
