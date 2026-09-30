# Handoff: GGR252 Assignment 1 — CF Toronto Eaton Centre 地图（现状交接）

**更新时间：** 2026-09-30 下午（第二次 session 结束）
**接手 session 的任务：** 陪潇予写报告、审稿、核对脚注。**地图已经完成并导出，不要再动地图。**
**本轮已定的决定：不再做工作日中午的复测。** 见第 3 节。

截止：**周五 2026-10-02 23:59**，Quercus Assignment 1 dropbox 提交。

---

## 1. 现状一句话

ArcGIS Pro 工程 `GGR252_EatonCentre` 已建好，所有图层由潇予自己数字化，布局已导出 `GGR252_EatonCentre_map.png`（300 dpi，Letter 横向）。工程文件夹已压缩上传 OneDrive。剩下的全部是**写作**：900–1200 词报告、5 张照片、参考文献。

## 2. 地图里有什么（写正文时直接指着用）

| 图层（图例名） | 内容 | 对应论点 |
|---|---|---|
| Study area | Bay–Dundas–Victoria–Queen，南延到 Richmond（Bay–Yonge）。面积 ≈ 157,400 m²（UTM 17N 量得） | 研究区定义 |
| Line 1 subway | TTC 官方线路 shapefile | 特征 1 |
| Stations / observation points | 两个点，分级符号（`alighted`）：TMU 381、Queen 47；标注 "TMU (formerly Dundas) — 89% into mall" / "Queen — 83% into mall" | 特征 1 |
| Mall entrances | 4 个点：2 个 concourse（白方块，压在站点上）、2 个 street（Yonge & Dundas 主入口、Trinity Square 西入口，空心圆） | 特征 3 |
| Interior pedestrian street | 商场南北中轴一条线（橙） | 特征 2 |
| Vacated anchors | 两个斜线填充面：Former Nordstrom (vacated 2023) – Simons / Uniqlo / Winners / H&M；Former Hudson's Bay / Saks (closed 2025)，176 Yonge（Yonge & Queen **西南角**） | 特征 2 |
| Surface transit stops | 4 个点，按 `route` 分色：501 Queen（红，Richmond & Yonge WB、Adelaide & Yonge EB）、97 Yonge（灰，Queen 站附近南北各一），标注含 service："97 Yonge (weekday peak only)" / "501 Queen (all day)" | 周日零地面接驳 |
| Photo locations | 1–6 号红黑方块，标注编号 | 照片图注 |
| Building Outlines | 城市建筑轮廓，淡色底 | 底图 |
| 插图 | 多伦多 1:400,000，红框 extent indicator | 题面要求的 context |

图廓：标题、图例、比例尺（0–100–200 m）、指北针、来源行、Esri credits。

**砍掉的图层（gdb 里还留着空要素类，不要再画）：** 501 pre-2023 线路、PATH 线、Public squares 面、Ontario Line 工地面。原因：评分表里地图只占 Evidence 5 分 + Communication 5 分的一部分，图例超过 7 项反而扣印象分。这些内容改为正文一句话或不提。

## 3. 决定：不做工作日复测

交接文档第一版里写着"weekday-noon repeat count is still pending"。**本轮决定放弃**，理由：

- 评分权重：Geographical Analysis 10 分是大头，地图和证据合计最多 10 分。剩下两天投在写作上收益更高。
- 周三下午潇予还有三篇 essay 要写，时间不够。
- 作业只要求 45–60 分钟一次现场观察，已满足。

**写作上的处理：** 在 Section 3 "Priorities for Further Analysis" 里把它写成第一个问题的一部分——单次周日下午的样本无法区分 TMU ≫ Queen 是周日特有还是常态；工作日高峰 97 Yonge 有车、办公人流出现时，Queen 站的进商场比例可能变化。这正好对应 Lecture 2 的 temporal barriers / friction of distance (uncertainty)。**这是诚实的写法，不是补救。** 不要在正文里假装做过复测。

## 4. 报告结构与字数（来自作业 PDF，已核对）

| 节 | 词数 | 内容 |
|---|---|---|
| 1. Retail Environment and Context | 150–200 | 研究区定义、地理位置、目的 |
| 2. Geographical Assessment | 600–700 | 三个特征，每个：观察 → 空间证据（指图/照片）→ 概念 → 为什么重要 |
| 3. Priorities for Further Analysis | 200–300 | **两个**问题：还需要知道什么、为什么、用什么证据/分析 |
| 4. References | 不计字数 | APA，单倍行距，悬挂缩进，**至少一篇指定阅读** |

总计 900–1200 词封顶（不含参考文献）。11 pt 以上字体，1 英寸边距，页码，页眉信息（标题、姓名、学号、课程、教师、日期）。照片 3–5 张，每张必须服务一个论点并在正文里被引用。

评分（30 分）：Observation & Evidence 5 / Concepts 5 / **Analysis 10** / Interpretation 5 / Communication 5。

## 5. 三个特征（已定，不要重开）

1. **Transit accessibility as the cause of everything else.** Line 1 两站（TMU 北、Queen 南）各自单一大厅直通商场；周日 89% / 83% 的下车乘客直接进商场。概念：accessibility（network connections, mode, frequency, temporal barriers），proximity ≠ accessibility，transit nodes channel flows。
2. **Internal activity gradient and anchor reorganisation.** 北端人流占绝对优势；Nordstrom 旧址（2023 空置）被分割成 Simons / Uniqlo / Winners / H&M——agglomeration 取代单一 anchor；南端 Bay/Saks（176 Yonge，2025 关闭）空置、招牌仍在。概念：agglomeration economies，concentration/dispersion。
3. **Site vs situation.** 同一栋楼两面：Yonge/Dundas 面有地铁、广场、街面零售；Trinity Square（Bay St 侧）面是教堂 + 餐厅露台，穿行流量近零。

进一步分析的两个问题：(a) dwell time / trade area——地铁下车者是购物者还是穿行者？需要 mobile-location 数据或 gravity model；(b) Ontario Line Queen 站（目标 2031）会让南端成为换乘站，南北梯度会不会翻转？

## 6. 现场数据（2026-09-27 周日）

在 TTC 收费亭内、经工作人员同意计数，视野覆盖全部闸机和大厅分流。方法：一班到站列车 = 一个 wave，每个下车乘客归为 "entered mall directly" 或 "did not"。

| 站 | 时间 | 下车 | 进商场 | 未进 | % |
|---|---|---|---|---|---|
| Queen | 14:50 | 26 | 20 | 6 | 77 |
| Queen | 14:59 | 21 | 19 | 2 | 90 |
| **Queen 合计** | | **47** | **39** | **8** | **83** |
| TMU | 15:11 | 151 | 140 | 11 | 93 |
| TMU | 15:17 | 230 | 200 | 30 | 87 |
| **TMU 合计** | | **381** | **340** | **41** | **89** |

周日 Line 1 间隔约 5–6 分钟。

照片（全部 2026-09-27）：
1. 14:52 Queen 站大厅——闸机、"Access to Street" 标志、商场通道
2. 15:20 Yonge & Dundas 东南角向西北看——TTC 标志、商场入口、Uniqlo/Simons/H&M 招牌、路边摊
3. 15:22 Dundas 中庭——Nordstrom 旧址里的 Simons/Uniqlo/Winners/H&M
4. 15:31 Queen St 天桥 + Metrolinx Ontario Line 围挡
5. 15:33 Yonge & Queen 向北看——Saks 招牌仍在、176 Yonge、道路开挖、"TTC vehicles excepted"
6. 15:39 Trinity Square 西入口——空巷、教堂、Trattoria 露台

提交 6 张里的 5 张，1 或 4 可能被舍弃。

## 7. 事实核对清单（脚注要用的日期）

- **176 Yonge（前 Bay/Saks）在 Yonge & Queen 西南角**，不是东南。
- **501 Queen** 自 2023 年 5 月起因 Ontario Line 施工改线：西行 Church → Richmond → York，东行 York → Adelaide → Church。最近站 Richmond & Yonge (WB)、Adelaide & Yonge (EB)，TTC 标注 2 分钟步行。来源：TTC 501 route map，retrieved 28 Sept 2026（有截图）。
- **97 Yonge：** 现场标牌和 501 路线图写 97C；TTC 97 路线说明页（retrieved 28 Sept 2026）只列 97A/97B/97F。**地图上统一写 "97 Yonge"，编号出入放脚注。** 无论哪个分支都只在工作日高峰运营，周日下午 Queen 站没有地面接驳。
- ICSC 2025：Eaton Centre 每平方英尺销售额 $1,642，加拿大第二，比 2024 高 $139，比 2019 的 $1,592 高（Retail Insider，2026 年 4 月）。
- Ontario Line Queen 站开通目标：2031。
- **不要引用** torontotourism.org 的指南，它还把 Bay 和 Nordstrom 列为在营主力店。
- **PATH 数据集已从 open.toronto.ca 下架**（2026-09-30 用 CKAN API 查过全目录，只有 "Pedestrian Network" 是人行道网）。地图上没画 PATH，正文提一句即可；若要引用，用市政府官方 PATH 地图 PDF（已存 Evidence 文件夹）。

数据来源与日期（来源行已写在图上）：
- City of Toronto Open Data — Topographic Mapping – Building Outlines，last refreshed **2026-04-05**
- City of Toronto Open Data — TTC Subway Shapefiles，last refreshed **2019-07-23**（只有线路，站点是潇予按检票口位置自己打的点）
- City of Toronto Open Data — Toronto Centreline (TCL)，last refreshed **2026-09-29**（已下载，图上关闭未用）
- Esri World Topographic Map 底图
- 投影：NAD 1983 UTM Zone 17N（EPSG 26917）
- 手工数字化精度约 ±10–20 m；Building Outlines 官方精度 ±30 cm

## 8. 文件位置

机房账号 `ICW044-CAF` 的 Documents 会被清盘。**唯一可靠副本在 OneDrive** 上的 zip：
```
GGR252_EatonCentre/
  GGR252_EatonCentre.aprx
  GGR252_EatonCentre.gdb/        # 所有数字化图层
  Data/                          # 三个 open.toronto.ca 下载解压后的 shapefile
  Evidence/                      # 照片原件、TTC 截图、PATH 地图 PDF
  GGR252_EatonCentre_map.png     # 最终地图，300 dpi
```

## 9. 还没做的事（按顺序）

1. 在 Quercus 找一篇**指定阅读**，定下来引用哪一篇（Lecture 2 slides 不算 reading）。
2. Word 模板：11 pt，1 英寸边距，页码，页眉信息，APA。
3. 写四节正文。地图和照片图注承担证据展示，正文只做解释，控制在 1200 词内。
4. 脚注：数据日期、97B/97C 出入、现场计数方法（地点、时间、工作人员同意、自己的判断标准）。
5. 提交前对照第 4 节的清单过一遍。

## 10. 和潇予合作的方式（沿用）

- 每条回复至少一个颜文字，轮换用，别重复同一个。
- 不要表演式退让（"let me gently push back" 之类）。给证据，她会自己核对，没依据的话会被指出来。
- 她挑战某个说法时，先查再答。她已经纠正过这个项目三次（Bay 大楼位置、TMU 大厅结构、PATH 数据集不存在），三次都对。
- 提醒说一次就够，不要唠叨。不评论 session 长度，不建议休息。
- 代码注释英文，正文可中文。
- 她曾被误指为 AI 写作（ISP100）并在 Tribunal 胜诉。报告脚注要读起来明确是第一手：具体地点、时间、页码、检索日期、她自己的判断。原始证据（照片 EXIF、带时间戳截图）留在 Evidence 文件夹。
- 她会主动砍范围（这轮她问"地图有必要这么复杂吗"，答案是没必要，砍掉了 5 层）。尊重这个判断，别为了完整而堆功能。

## 11. 本轮用时（供下次估算）

约 3 小时 20 分钟：建工程和数据 30 min，数字化 95 min（含 20 min 建了后来砍掉的要素类），符号化 30 min，标注 20 min，布局导出 25 min。下次同类作业先定图层清单再开建。
