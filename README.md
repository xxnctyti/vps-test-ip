# v.ps测试ip：11个机房完整测试地址，购买前必看的网络选择指南

想搞清楚 v.ps 各机房到你本地的延迟和速度，最直接的办法就是用官方提供的测试 IP 和 Looking Glass 工具跑一遍。v.ps 目前在全球运营 11 个数据中心（新加坡、东京、大阪、香港、悉尼、阿姆斯特丹、法兰克福、伦敦、杜塞尔多夫、塔林、圣何塞），每个位置都有独立的测试资源，但不同机房走的线路差别很大——有的是 CN2 GIA 优化线路，有的是普通国际带宽，直接影响晚高峰能不能用。

大多数 VPS 测评只给一个通用测试 IP，但 v.ps 的关键在于：同一个城市可能有多条网络（比如新加坡分 Premium 和 Edge，东京分 Premium 和 Softbank），你买的套餐属于哪个产品线，实际走的就是哪条线路。测错网络，延迟数据就没参考价值。

> **快速选购建议**
> 如果你在国内且预算有限，推荐日本大阪 Cloud Starter 套餐（2核/1GB/20GB NVMe/1TB 流量，€6.95/月），电信联通走 IIJ，移动走 CMI，延迟稳定且价格合理。👉 [查看大阪机房当前套餐](https://vps.hosting/?affid=1666)

## v.ps 全套餐价格与配置对比（2026年）

v.ps 根据机房和硬件配置划分了多个产品线，同样的套餐名称在不同机房价格不同。以下整理了主要套餐的配置、价格范围和购买链接（价格截至 2026 年 10 月，实际以官网为准）。

### 主力套餐对比

| 套餐名称 | CPU | 内存 | 存储 | 流量 | 带宽 | 月付价格 | 适用机房 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Nano | 1核 | 1GB | 15GB SSD | 1TB | 1Gbps | 年付 €9.95（月均 €0.83） | 阿姆斯特丹、法兰克福 | [立即选购](https://vps.hosting/?affid=1666) |
| Nano Pro | 1核 | 2GB | 30GB SSD | 2TB | 1Gbps | 年付 €22.34（月均 €1.86） | 德国 | [立即选购](https://vps.hosting/?affid=1666) |
| Mini | 1核 | 1GB | 15GB SSD | 无限 | - | 年付 €44.72（月均 €3.73） | 日本 | [立即选购](https://vps.hosting/?affid=1666) |
| Mini Pro | 1核 | 1GB | 15GB NVMe | 600GB | 500Mbps | 年付 €55.91（月均 €4.66） | 德国 | [立即选购](https://vps.hosting/?affid=1666) |
| Cloud Starter | 2核 | 1GB | 20GB NVMe | 1TB | 1Gbps | €6.95 | 多数机房 | [立即选购](https://vps.hosting/?affid=1666) |
| Cloud Essential | 2核 | 2GB | 30GB NVMe | 1TB | 1Gbps | €7.95 | 多数机房 | [立即选购](https://vps.hosting/?affid=1666) |
| Cloud Pro | 4核 | 4GB | 40GB NVMe | 1TB | 1Gbps | €9.95 | 多数机房 | [立即选购](https://vps.hosting/?affid=1666) |
| Cloud Premium | 8核 | 8GB | 80GB NVMe | 1TB | 1Gbps | €19.95 | 多数机房 | [立即选购](https://vps.hosting/?affid=1666) |

**重要说明**：
- Nano 系列只能年付，是 v.ps 最便宜的入门选择，但只在德国和阿姆斯特丹提供
- Cloud 系列是主力产品，支持月付，但 Cloud Starter 在不同机房价格不同（香港 €11.95/月，圣何塞 €8.95/月，大阪/东京/欧洲三大优化节点 €6.95/月）
- Mini 系列只在日本提供，流量标注为"无限"但实际受公平使用政策限制

### 亚太高配套餐

| 套餐名称 | CPU | 内存 | 存储 | 流量 | 带宽 | 月付价格 | 可选机房 | 购买 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Edge Green | 1核 | 2GB | 20GB NVMe | 1TB | 1Gbps | €8.95 | 日本、新加坡 | [立即选购](https://vps.hosting/?affid=1666) |
| Edge Blue | 2核 | 4GB | 40GB NVMe | 2TB | 1Gbps | €17.95 | 日本、新加坡 | [立即选购](https://vps.hosting/?affid=1666) |
| Edge Yellow | 4核 | 8GB | 80GB NVMe | 4TB | 1Gbps | €35.95 | 日本、新加坡 | [立即选购](https://vps.hosting/?affid=1666) |
| Edge Orange | 8核 | 16GB | 160GB NVMe | 8TB | 1Gbps | €65.95 | 日本、新加坡 | [立即选购](https://vps.hosting/?affid=1666) |
| EPYC Flash Gen 2 | 2核 | 4GB | 30GB NVMe | 1TB | 1Gbps | €49.95 | 日本 | [立即选购](https://vps.hosting/?affid=1666) |
| EPYC Flow Gen 2 | 2核 | 8GB | 60GB NVMe | 2TB | 1.25Gbps | €95.95 | 日本 | [立即选购](https://vps.hosting/?affid=1666) |
| EPYC Fleet Gen 2 | 4核 | 16GB | 120GB NVMe | 4TB | 2Gbps | €191.95 | 日本 | [立即选购](https://vps.hosting/?affid=1666) |
| EPYC Formula Gen 2 | 8核 | 32GB | 240GB NVMe | 8TB | 2.5Gbps | €383.95 | 日本 | [立即选购](https://vps.hosting/?affid=1666) |

Edge 系列只在日本和新加坡提供，流量配额比 Cloud 系列更大。Performance EPYC 系列使用 AMD EPYC 7763 处理器，带宽从 1Gbps 起步最高可达 2.5Gbps，目前只在日本提供。

## v.ps 全部机房测试 IP 与 Looking Glass 地址

v.ps 为每个机房配备了独立的 Looking Glass 页面，可以直接在线运行 ping、traceroute、DNS 查询和速度测试。需要注意的是，同一个城市可能有多个网络，选错网络测出来的结果完全不一样。

### 亚太机房

**新加坡**
- Premium 网络（Performance KVM VPS）：https://sin-premium.lg.xtom.com/
- Edge 网络（Edge KVM VPS）：https://sin-edge.lg.xtom.com/
- 线路特点：CN2 GIA，适合国内电信用户

**日本东京**
- Premium 网络（Performance KVM VPS）：https://tok-premium.lg.xtom.com/
- Softbank 网络（Cloud KVM VPS、Mini KVM VPS）：https://tok-sb.lg.xtom.com/
- 测试文件示例：https://tok-sb.lg.v.ps/100MB.test
- 历史测试 IP：103.201.131.131
- 线路特点：Softbank 线路或 CN2 GIA，晚高峰表现稳定

**日本大阪**
- IIJ 网络（Edge KVM VPS、Cloud KVM VPS）：https://kix-iij.lg.xtom.com/
- 历史测试 IP：45.14.106.106
- 线路特点：电信联通走 IIJ，移动走 CMI，综合性价比高

**中国香港**
- Cloud KVM VPS 网络：https://hkg.lg.xtom.com/
- 测试文件示例：https://hkg.lg.v.ps/100MB.test
- 历史测试 IP：157.119.101.101
- 线路特点：CMI 线路，但无直连，购买前务必自测延迟

**澳大利亚悉尼**
- Cloud KVM VPS、Mini KVM VPS 网络：https://syd.lg.xtom.com/
- 测试文件示例：https://syd.lg.v.ps/100MB.test
- 历史测试 IP：103.136.146.146
- 线路特点：AS9929，联通用户友好

### 欧洲机房

**荷兰阿姆斯特丹**
- Premium 网络（Cloud KVM VPS）：https://ams-premium.lg.xtom.com/
- 标准网络（Storage KVM VPS、Nano KVM VPS）：https://ams.lg.xtom.com/
- 测试文件示例：https://ams.lg.v.ps/100MB.test
- 历史测试 IP：78.142.195.195
- 线路特点：CN2 GIA + AS9929 + CMIN2 三网优化

**德国法兰克福**
- Premium 网络（Performance KVM VPS、Cloud KVM VPS、Mini KVM VPS）：https://fra-premium.lg.xtom.com/
- 标准网络（Nano KVM VPS）：https://fra.lg.xtom.com/
- 历史测试 IP：45.80.188.188
- 线路特点：与阿姆斯特丹同样的三网优化

**德国杜塞尔多夫**
- Cloud KVM VPS 网络：https://dus.lg.xtom.com/
- 历史测试 IP：185.254.74.74
- 线路特点：普通国际线路，主要面向欧洲用户

**英国伦敦**
- Premium 网络（Cloud KVM VPS）：https://lon-premium.lg.xtom.com/
- 历史测试 IP：185.248.86.86
- 线路特点：CN2 GIA + AS9929 + CMIN2

**爱沙尼亚塔林**
- Cloud KVM VPS 网络：https://tll.lg.xtom.com/
- 历史测试 IP：185.194.53.53
- 线路特点：普通国际线路，价格相对便宜

### 北美机房

**美国圣何塞**
- Premium 网络（Cloud KVM VPS、Mini KVM VPS）：https://sjc-premium.lg.xtom.com/
- 历史测试 IP：104.245.12.12
- 测试文件示例：https://sjc-premium.lg.v.ps/100MB.test
- 线路特点：三网高级线路（电信 CN2 GIA、联通 AS9929、移动 CMIN2），是 v.ps 在美国的王牌机房

**关于西雅图和纽约机房**：v.ps 在 2021-2023 年间提供过西雅图（历史测试 IP：23.145.48.48）和纽约（历史测试 IP：23.159.160.160）机房，但 2026 年的官方机房列表中不再包含这两个位置。需要美国节点的用户建议选择圣何塞。

## 如何用测试 IP 判断机房是否适合你

拿到测试 IP 或 Looking Glass 地址后，别只看 ping 值，至少要确认三件事：

**1. 本地到机房的路由跳数和延迟波动**
直接在 Looking Glass 页面运行 traceroute，看中间经过哪些节点。如果路由绕了大半个地球，或者中间某一跳延迟突然飙升，晚高峰大概率会炸。

**2. 下载测速文件的实际速度**
每个 Looking Glass 对应的测试文件下载链接格式通常是 `https://机房代码.lg.v.ps/100MB.test`（例如大阪是 https://kix-iij.lg.v.ps/100MB.test），用你常用的网络环境测一下实际下载速度。理论带宽是 1Gbps，但能跑满的情况很少见。

**3. 不同时段的稳定性**
晚上 8-11 点是国际线路的重灾区，有条件的话在高峰时段再测一次，确认延迟和丢包是否能接受。v.ps 提供的线路质量差异很大，优化线路和普通线路在晚高峰的表现天差地别。

## 不同运营商用户该怎么选机房

v.ps 的机房虽然都是自有硬件和 IP，但不同位置接入的上游运营商和优化线路差别很大。如果你在国内，选错机房可能导致延迟翻倍或晚高峰直接断线。

**中国电信用户**
优先选择标注 CN2 GIA 的机房：美国圣何塞、新加坡、日本东京、德国法兰克福、荷兰阿姆斯特丹、英国伦敦。这些机房的回程路由走 CN2 GIA 专线，晚高峰延迟稳定。日本大阪走 IIJ 线路，电信用户同样友好。

**中国联通用户**
AS9929 是联通的优化线路，覆盖圣何塞、悉尼、法兰克福、阿姆斯特丹、伦敦。如果你主要用联通宽带，这些机房的表现会明显好于普通国际线路。日本大阪的 IIJ 线路对联通也很友好。

**中国移动用户**
CMIN2 或 CMI 线路是移动的优化选项，圣何塞三网都优化，香港和日本大阪走 CMI。但移动用户普遍反映国际线路不如电信联通稳定，有条件的话建议同时测试多个机房。

**其他地区或国际用户**
如果你不在国内，或者主要访问欧美服务，直接选地理位置最近的机房就行。杜塞尔多夫和塔林是普通国际线路，年付 €69.95 起步，适合预算有限且不在意中国大陆访问速度的用户。

👉 [根据你的运营商选择合适机房](https://vps.hosting/?affid=1666)

## v.ps 购买前需要确认的 5 个限制

大多数测评文章只讲配置和价格，但 v.ps 有几个容易踩坑的限制，买之前必须知道。

**1. 不支持跨机房迁移**
v.ps 明确说明不支持跨位置迁移，如果你买了香港机房后发现延迟不行，想换到日本，只能重新订购并手动迁移数据。部分促销折扣产品连同城转移都不支持，下单前一定要先测好网络。

**2. 超流量后的限速幅度很大**
v.ps 的标准套餐配 1TB 月流量，上行下行都计入。超流量后，Nano、Storage 和 Performance 系列会被限速到 1-10Mbps，其他产品直接暂停到月底。如果你的应用流量不可控，建议选流量更大的 Edge 或 Performance 系列，或者提前在客户区购买额外流量。

**3. 端口 25 默认封禁**
所有 VPS 的出站端口 25（邮件）默认被封，需要发邮件只能联系客服申请解封或使用第三方邮件服务。这对个人博客影响不大，但如果你要自建邮件服务器，得提前确认能否解封。

**4. 月付可能需要额外设置费**
根据 v.ps 在部分产品（如荷兰存储型 VPS）的定价政策，月付用户可能需要额外支付 10 欧元设置费，年付及以上周期则免除。Nano 系列只能年付，如果你需要月付灵活性，最低选 Cloud Starter（€6.95/月起），但要留意是否适用设置费。

**5. 14 天退款保证但有例外**
v.ps 提供 14 天退款保证，但域名注册、转移和恢复不可退款。如果你是第一次购买，建议先选月付套餐测试网络，确认满意后再考虑年付或更长周期以获得更好的价格。

## 常见问题

**v.ps 的测试 IP 能不能直接 ping？**
可以。历史测试 IP（如香港 157.119.101.101、东京 103.201.131.131）仍然可以 ping 通，但官方推荐直接用 Looking Glass 页面，因为不同产品线可能走不同网络，单纯 ping IP 测不出实际购买后的线路。

**为什么同一个城市有多个 Looking Glass 地址？**
v.ps 在部分城市提供多条线路，比如新加坡分 Premium 和 Edge，东京分 Premium 和 Softbank。你买的套餐属于哪个产品线，就用对应的 Looking Glass 测试，否则测出来的结果和实际不符。

**Nano 套餐为什么只能年付？**
Nano 系列是 v.ps 最便宜的入门套餐，年付 €9.95 相当于月均不到 1 欧元，官方不提供月付选项。如果你需要月付灵活性，最低选 Cloud Starter（€6.95/月），但部分产品月付可能需要额外支付 10 欧元设置费。

**v.ps 有没有促销或优惠码？**
v.ps 在 2023 年 5 月的 2 周年促销中提供过最高 40% 的循环折扣码（如 3 年付使用 AMAJJG894VGB5），但截至 2026 年这些促销码是否仍然有效未确认。官方偶尔会针对特定机房或套餐推出限时折扣，建议直接访问官网查看当前活动。

**日本大阪和东京该选哪个？**
大阪走 IIJ/CMI，价格便宜（Cloud Starter €6.95/月），适合预算有限且对延迟要求不是极端苛刻的用户。东京分 Softbank 和 Premium 两条线路，Softbank 价格和大阪一样，Premium 则贵一倍以上但带宽和流量更大。如果你只是建站或轻量使用，大阪性价比更高。

选 v.ps 的机房，核心就是先用 Looking Glass 测好网络，再根据实际需求和预算选套餐。别光看价格便宜就下单，路由不对晚高峰炸了钱就白花了。👉 [立即测试并选购合适套餐](https://vps.hosting/?affid=1666)
