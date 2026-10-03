# 🏕️生存日志 Survival Log 物品百科（玩家自制资料站）

单个 HTML 文件、零依赖、无需联网——**下载 `生存日志图鉴.html` 双击即可使用。**

> 🎯 **当前版本：v1.9.1**（2026-10-03）· 游戏配置已同步至 **1.1.18293（10.2 热修补丁）** · 详见下方[版本记录](#版本记录)

## 功能

- **物品图鉴**：3857 种物品，五维属性、品质对比（完美/优良/普通/失败）、保鲜与变质链、使用后返还材料
- **配方图鉴**：524 道烹饪配方 + 820 条制作配方，设施/等级反查
- **家具图鉴**：1556 件家具，功能按钮真实数值、电气参数、包裹互链
- **Buff / 天赋图鉴**：864 条 Buff（已合并重复条目）、545 个天赋逐级效果，Buff 支持按饱腹/心态/精力/健康/生命五维筛选
- **主线任务与事件图鉴**：974 条事件（22 条主线）触发条件、前置门槛、选项与奖励全解，剧情物件 239 条
- **⏱ 按天数时间线**：主线 + 事件从第 1 天依次排到第 100 天（无天数限制的条目末尾单独成组），卡片标注「最早可达天数」与依据
- **搜索**：拼音/首字母（`ftq`=佛跳墙）+ `re:` 正则 + `*`/`?` 通配符
- **实用工具**：排序筛选、食材标签过滤、收藏与属性对比、深浅主题、字体调节、手机适配
- **进度记录**：配方/物品/天赋「已解锁」标记（本机保存）、「✅ 已解锁」汇总页、存档导入
- **配方计算器**：勾选已有食材列出可做菜谱，支持「只看未制作」+ 结果内筛选
- **使用次数**：食材「被 N 道菜谱使用 / 可用×N 次」、成品「可吃×N 次」
- **结局条件**：9 种结局一览 + 五路线总览 + 各结局前置事件提示 + 相关成就
- **地图开启**：30 个地点解锁条件解码，按区域/开放状态筛选

## 版本记录

- **v1.9.1**（2026-10-03）数据同步 **1.1.18293**（10.2 热修补丁）
  - 新增陷阱规划卡（嗉中藏种 / 储物仓加层 / 储物仓拓宽 / 饵仓扩容）· 角色选择界面可回看已达成结局 · 修复无尽模式科技公司解锁 / 幸存者纪念品获取 / 幸存者来信 / 营地结局
  - 配置数据：店铺 loot 池重构（新增 17 个图级池/专用池包裹 + 15 个随机组）、家具「维修设施」→「加油泵」改名、天赋「老主顾」图标修正；核心计数（物品/事件/配方/家具/天赋）不变
- **v1.9.0**（2026-10-02）测试版（t0.0.4~t0.0.6）转正 + 数据同步 **1.1.18254**（大版本更新）
  - 主线按「当前版本」口径去重（39 → 22 条）；非主线「版本并存」去重；事件天数第三轮修正（事件激活链 / 短信日程 / 条件触发 / 同名取齐）
  - 角色变体合并补漏：激活事件 ID 重映射 + 二次合并，悬空「触发后续事件」引用 22 → 3
  - 推不出天数的前置条件条目不再谎报「第 1 天」，如实标注「🎲 条件触发（无固定天数）」
  - 试玩版 / 旧版遗留内容从构建期剔除（页面上不再有任何开关入口）
  - 游戏秋季更新内容（已与官方更新公告逐条核对）：🤖 **安全屋自动化**——HK 整理 / GR 种植 / FX 维修三型机器人（充电座 + 模块升级）、无人机中控台、材料架、自定义储物规则 · 🏁 **各角色新挑战结局路线**（一区之盾 / 如约而至 / 营地灯火 / 末世灯塔 / 末日绿洲 / 越冬之种 / 物资枢纽）· 🏢 新探索地点「**科技公司**」· ♾️ **无尽模式扩展**（5 天 3 波 · 难度至 T40 · 营地共生 · 从灾变重来）· 🎨 装修与染色（墙纸 / 地板 / 八色染料 · 装修图鉴）· 🪤 自动诱捕笼 · 三级堆肥箱 · 新猎物与十余道新料理 · 进阶材料
  - 物品 2877 → 3857 · 事件 731 → 974 · 家具 1249 → 1556 · Buff 734 → 864 · 天赋 454 → 545 · 烹饪配方 493 → 524 · 制作配方 148 → 820
- **v1.8.1**（2026-09-12）测试版（t0.0.1~t0.0.3）转正 + 数据同步 **1.0.16363**
  - 新增「📜 主线任务与事件图鉴」「⏱ 按天数时间线」（主线+事件从第 1 天依次往后，无天数收尾）
  - 角色徽章显著化 + 重复角色事件合并（原始 1121 条 → 731 条）；物品详情显示「使用后返还材料」
  - Buff 五维分类筛选 + 重复条目合并（759 → 734）
  - 游戏新内容：大学生第二台无人机支线「学校里的无人机 / 修好它」、腐肉条·块·排可堆肥转化为基础肥料、太阳能板发电说明、天赋「冷藏有方」图标修正
- **v1.7.1**（2026-09-10）新增结局条件页、地图开启页；首页横幅收敛为「已同步最新版本」；数据同步 1.0.15955
- **v1.6.3**（2026-09-10）正则/通配符搜索 · 后退保留滚动 · 食材/成品使用次数 · 计算器「只看未制作」
- **v1.6.2**（2026-09-10）数据同步 1.0.15511→1.0.15955（110 表重解析）；咖啡因 Buff、无人机、单曲循环等新内容；移除 3 道胡萝卜菜谱
- **v1.6.1**（2026-09-03）数据更新 1.0.14911→1.0.15511；专属天赋、天赋触发时间、只看未解锁、图纸解锁
- **v1.5.5**（2026-08-27）物品格子大小可视化
- **v1.5.4**（2026-08-27）家具交互时间显示
- **v1.5.3**（2026-08-26）配方计算器 · 搜索历史/最近浏览 · 食材类别筛选 · 存档导入
- **v1.4.1**（2026-08-26）「用于配方」专属/通用分区 · 专用设备警示 · 可烹饪措辞
- **v1.4.0**（2026-08-25）床睡眠回复效率 · 家具功能真实数值
- **v1.3.0**（2026-08-25）物品级解锁标记 · 解锁状态排序 · 已解锁物品分组
- **v1.2.0**（2026-08-24）配方列表分区 · 食材类别标签修正
- **v1.1.0**（2026-08-24）「✅ 已解锁」页 · 列表行一键标记
- **v1.0.0** 物品/配方/家具/Buff/天赋图鉴 · 拼音搜索 · 收藏对比 · 主题/字体 · 手机适配

## 地址

- GitHub Pages：[Release v1 · AssassinLYB/STEAM-SurvivalLog-wiki](https://github.com/AssassinLYB/STEAM-SurvivalLog-wiki/releases/tag/V1)
- bilibili：https://www.bilibili.com/video/BV1Gz8t6LEyP/

## 数据来源与声明

数据提取自游戏配置表（游戏版本 1.1.18293），页面不含任何游戏美术资源。非官方资料站，仅供参考；数据如与游戏内不符，以游戏为准。

---

# 🏕️ Survival Log Wiki (Player-Made Game Database)

A single self-contained HTML file with zero dependencies, fully offline. **Just download `生存日志图鉴.html` and open it.**

> 🎯 **Latest version: v1.9.1** (2026-10-03) · game config synced to **1.1.18293 (10.2 hotfix)** · see [Changelog](#changelog) below

## Features

- **Items**: 3,857 items — five stats, quality tiers (Perfect/Good/Normal/Fail), freshness & spoilage, materials returned on use
- **Recipes**: 524 cooking + 820 crafting recipes, facility & level lookups
- **Furniture**: 1,556 pieces — real function values, electrical stats, package links
- **Buffs & Talents**: 864 buffs (duplicates merged), 545 talents with per-level effects, buffs filterable by five stats
- **Quests & Events**: 974 events (22 main-quest) with triggers, prerequisites, choices and rewards; 239 story objects
- **⏱ Day-by-day timeline**: main quests + events ordered from Day 1 up to Day 100, undated entries grouped at the end
- **Search**: pinyin/initials (`ftq` = 佛跳墙) + `re:` regex + `*`/`?` wildcards
- **Utilities**: sorting/filtering, ingredient-tag filters, favorites & comparison, themes, font size, mobile
- **Progress tracking**: mark recipes/items/talents unlocked (saved locally), "✅ Unlocked" page, save-file import
- **Recipe calculator**: pick ingredients to list cookable recipes, with "not-yet-made only" + in-result filter
- **Usage counts**: ingredients "used in N recipes / usable ×N times", dishes "eatable ×N times"
- **Ending conditions**: all 9 endings, five-route overview, per-ending prerequisite hints, related achievements
- **Map unlocks**: 30 map points with decoded unlock conditions, filter by area / open state

## Changelog

- **v1.9.1** (2026-10-03) data synced to **1.1.18293** (10.2 hotfix)
  - new trap planning cards (seed-in-crop / storage add-row / storage add-col / bait expansion) · ending recap on the character-select screen · fixes for tech-company unlock in endless mode / survivor keepsake acquisition / survivor messages / camp ending
  - config data: shop loot-pool refactor (17 new tier/dedicated pool packages + 15 random groups), furniture "Repair Facility" → "Fuel Pump" renames, "Regular" talent icon fix; core counts (items/events/recipes/furniture/talents) unchanged
- **v1.9.0** (2026-10-02) test builds (t0.0.4–t0.0.6) promoted to stable + data synced to **1.1.18254** (major update)
  - main quests deduped to the current-version set (39 → 22); non-main "parallel versions" deduped; third round of day corrections (activation chain / SMS schedule / conditional triggers / same-name alignment)
  - role-variant merge completed: activation-event ID remap + re-merge; dangling "next event" refs 22 → 3
  - entries whose day cannot be derived no longer claim "Day 1" — they are marked "🎲 conditional (no fixed day)"
  - demo/legacy content removed at build time (no toggle on the page)
  - new content (autumn update, cross-checked against the official patch notes): 🤖 **shelter automation** — HK tidy / GR planting / FX repair robots (charging docks + module upgrades), drone control console, material rack, custom storage rules · 🏁 **new challenge ending routes per character** (District Shield / As Promised / Camp Lights / Wasteland Lighthouse / Doomsday Oasis / Overwintering Seed / Supply Hub) · 🏢 new exploration map "**Tech Company**" · ♾️ **endless mode expansion** (3 waves per 5 days · up to T40 · camp symbiosis · restart from the outbreak) · 🎨 renovation & dyeing (wallpaper / flooring / 8 dyes · renovation codex) · 🪤 auto trap cage · 3-tier compost bin · new prey & a dozen new dishes · advanced materials
  - items 2,877 → 3,857 · events 731 → 974 · furniture 1,249 → 1,556 · buffs 734 → 864 · talents 454 → 545 · cooking recipes 493 → 524 · crafting recipes 148 → 820
- **v1.8.1** (2026-09-12) test builds (t0.0.1–t0.0.3) promoted to stable + data synced to **1.0.16363**
  - new Quest & Event codex and ⏱ day-by-day timeline (main quests + events from Day 1, undated last)
  - role badges highlighted, duplicate role-variant events merged (1,121 → 731); "materials returned on use" on item pages
  - buffs split by five stats and duplicate buffs merged (759 → 734)
  - game content: college student's second-drone side quest, rotten meat compostable into basic fertilizer, solar panel output notes, "Keep It Chilled" talent icon fix
- **v1.7.1** (2026-09-10) new Ending-conditions page & Map-unlock page; home banner condensed to "synced to latest version"; data synced to 1.0.15955
- **v1.6.3** (2026-09-10) regex/wildcard search · back preserves scroll · ingredient/dish usage counts · calculator "not-yet-made only"
- **v1.6.2** (2026-09-10) data sync 1.0.15511→1.0.15955 (all 110 tables re-parsed); Caffeine buff, drone, single-loop & more; 3 carrot recipes removed
- **v1.6.1** (2026-09-03) data update 1.0.14911→1.0.15511; exclusive talents, trigger times, unlocked-only filter, blueprint locks
- **v1.5.5** (2026-08-27) item size cells visualization
- **v1.5.4** (2026-08-27) furniture interaction duration
- **v1.5.3** (2026-08-26) recipe calculator · search history/recent · ingredient-category filter · save import
- **v1.4.1** (2026-08-26) "used in recipes" sections · appliance warnings · wording fix
- **v1.4.0** (2026-08-25) bed sleep-recovery efficiency · real furniture function values
- **v1.3.0** (2026-08-25) item-level unlock flag · unlock-status sort · unlocked-items section
- **v1.2.0** (2026-08-24) recipe list sections · ingredient-category tag fixes
- **v1.1.0** (2026-08-24) "✅ Unlocked" page · one-click marking on list rows
- **v1.0.0** item/recipe/furniture/buff/talent codexes · pinyin search · favorites & comparison · themes/font/mobile

## Links

- GitHub Pages: [Release v1 · AssassinLYB/STEAM-SurvivalLog-wiki](https://github.com/AssassinLYB/STEAM-SurvivalLog-wiki/releases/tag/V1)
- bilibili: https://www.bilibili.com/video/BV1Gz8t6LEyP/

## Data Source & Disclaimer

All data is extracted from the game's config tables (game version 1.1.18293). This page contains no game art assets. This is an unofficial fan project for reference only — when data differs from the game, the game is always right.
