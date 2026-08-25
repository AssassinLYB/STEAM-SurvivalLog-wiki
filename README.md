# 🏕️生存日志  Survival Log 物品百科（玩家自制资料站）

单个 HTML 文件、零依赖、无需联网——**下载 `生存日志图鉴.html` 双击即可使用。（请下载最新版本）**

## 功能

- **物品图鉴**：2872 种物品按分类浏览，五维属性（饱食/心态/精力/健康/生命）、品质对比（完美/优良/普通/失败）、保鲜与变质链
- **配方图鉴**：496 道烹饪配方（含标签组合菜谱）+ 148 条制作配方，设施/等级反查
- **家具图鉴**：1249 件家具（功能按钮、电气参数、对应包裹物品互链）
- **Buff / 天赋图鉴**：758 条 Buff（含过期惩罚反查）、454 个天赋逐级效果
- **搜索**：支持拼音与首字母（如输入 `ftq` 搜"佛跳墙"）
- **实用工具**：列表排序筛选、食材标签过滤、⭐收藏与属性对比表、深浅双主题、字体大小调节
- **配方进度记录（v1.1.0）**：手动标记已解锁的配方——配方列表/详情页/物品列表行 🔒 均可一键标记；「✅ 已解锁」页按原本分类分组查看（烹饪按菜品子类、制作按产物类别），支持一键清空（带确认）
- **物品解锁进度（v1.3.0）**：任意物品（食材/即食食物/菜品/材料…）都能标记"已解锁"——列表行 🔒/🔓 一键切换、详情页可标记，分类列表支持"已解锁在前"排序，「✅ 已解锁」页汇总查看（与配方标记相互独立）
- **全端适配**：电脑和手机浏览器打开自动切换布局（手机端侧栏变为抽屉式，无需安装任何 App）

## 版本记录

- **v1.3.0**（2026-08-25）
  - 物品级解锁标记：所有物品（不只菜品）都能标记"已解锁"——食材、即食食物、材料等列表行都带 🔒/🔓，物品详情页也可标记
  - 分类列表新增"解锁状态"排序：可按 已解锁在前 / 未解锁在前 排列
  - 「✅ 已解锁」页新增"已解锁物品"分组（按原分类），一键清空同时清掉配方与物品
- **v1.2.0**（2026-08-24）
  - 配方列表分区：专属菜谱（指定食材）排在前面，通用菜谱（食材组合/自由组合）排在后面，两组各有小节标题
  - 修正食材类别标签：物品详情"作为食材"的组合菜谱、食物列表"按食材类别过滤"现在按真正的食材类别（肉/蔬菜/菌菇/主食…）匹配
- **v1.1.0**（2026-08-24）
  - 新增「✅ 已解锁」页：手动标记已解锁配方，侧栏入口带实时计数；按原本分类分组展示；一键清空（带确认弹窗）
  - 物品列表行新增 🔒/🔓 按钮：收藏星标旁一键标记"产出该物品的配方"为已解锁，无需点进详情页
  - 解锁进度保存在你本地的浏览器中（localStorage），不同浏览器/设备之间不共享
- **v1.0.0**：物品图鉴、配方图鉴、家具图鉴、Buff/天赋图鉴、拼音搜索、收藏与属性对比、深浅双主题、字体调节、手机端适配

## 地址

- GitHub Pages：[Release v1 · AssassinLYB/STEAM-SurvivalLog-wiki](https://github.com/AssassinLYB/STEAM-SurvivalLog-wiki/releases/tag/V1)
- bilibili：https://www.bilibili.com/video/BV1Gz8t6LEyP/

## 数据来源与声明

数据提取自游戏配置表（游戏版本 1.0.14911），页面不包含任何游戏美术资源。非官方资料站，仅供参考；数据如与游戏内不符，以游戏为准。

# 🏕️ Survival Log Wiki (Player-Made Game Database)

A single self-contained HTML file with zero dependencies, works fully offline. **Just download `生存日志图鉴.html` and open it in any browser.**

- GitHub Pages：[Release v1 · AssassinLYB/STEAM-SurvivalLog-wiki](https://github.com/AssassinLYB/STEAM-SurvivalLog-wiki/releases/tag/V1)
- bilibili：https://www.bilibili.com/video/BV1Gz8t6LEyP/

## Features

- **Items**: 2,872 items browsable by category — five stat dimensions (Satiety / Morale / Energy / Health / Life), quality comparison (Perfect / Good / Normal / Fail), freshness & spoilage chains
- **Recipes**: 496 cooking recipes (incl. tag-combination recipes) + 148 crafting recipes, with facility & level lookups
- **Furniture**: 1,249 furniture pieces — interaction buttons, electrical stats, cross-links between packages and placed furniture
- **Buffs & Talents**: 758 buffs (incl. reverse lookup of spoiled-food debuffs) and 454 talents with per-level effects
- **Search**: pinyin & initials supported (e.g. type `ftq` to find 佛跳墙, "Buddha Jumps Over the Wall")
- **Utilities**: list sorting & filtering, ingredient-tag filters, ⭐ favorites with a stat-comparison table, light/dark themes, adjustable font size
- **Recipe progress tracker (v1.1.0)**: mark recipes as unlocked — from recipe lists, detail pages, or the 🔒 button right on item rows; browse them grouped by original category on the "✅ Unlocked" page (cooking by dish sub-type, crafting by product category); clear all with a confirmation
- **Item unlock progress (v1.3.0)**: mark any item (ingredients / ready-to-eat food / dishes / materials, …) as "unlocked" — one-click 🔒/🔓 on list rows and the detail page, "unlocked-first" sorting in category lists, and a summary on the "✅ Unlocked" page (independent from recipe marks)
- **Responsive**: the layout switches automatically between desktop and mobile browsers (drawer sidebar on phones, no app required)

## Changelog

- **v1.3.0** (2026-08-25)
  - Item-level unlock flag: every item (not just dishes) can now be marked "unlocked" — raw ingredients, ready-to-eat food, materials, etc. all show a 🔒/🔓 toggle on list rows, and the item detail page has one too
  - Category lists: new "unlock status" sort — order by unlocked-first / locked-first
  - "✅ Unlocked" page: new "unlocked items" section (grouped by category); clear-all now clears both recipes and items
- **v1.2.0** (2026-08-24)
  - Recipe list sections: specific recipes (fixed ingredients) come first, generic recipes (ingredient combinations / free combination) after, each with its own heading
  - Fixed ingredient-category tags: the item detail "used in recipes" combo list and the food-list category filter now match by the real ingredient category (meat / vegetable / mushroom / staple, …), so the related generic recipes are correct
- **v1.1.0** (2026-08-24)
  - New "✅ Unlocked" page: manually track unlocked recipes — sidebar entry with live count, grouped by original category, clear-all with confirmation
  - Item lists: new 🔒/🔓 button next to the favorite star marks the recipes that produce that item in one click, no need to open the detail page
  - Unlock progress is stored in your local browser (localStorage) and is not shared across browsers or devices
- **v1.0.0**: item codex, recipe codex, furniture codex, buff/talent codex, pinyin search, favorites & stat comparison, light/dark themes, font-size control, mobile support

## Data Source & Disclaimer

All data is extracted from the game's config tables (game version 1.0.14911). This page contains no game art assets. This is an unofficial fan project for reference only — when data differs from the game, the game is always right.
