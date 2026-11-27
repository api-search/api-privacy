---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 邮箱地址 ：通过 Google OAuth 或邮箱密码方式注册 / 登录。
  - category: financial
    text: 持仓数据 ：你手动录入的股票 / 期权（ticker、合约、张数、入场价）。
  - category: behavioral
    text: 登录 / 推荐 / 早安简报 / 复盘 等动作的时间戳和聚合 metadata（ticker、策略类型、是否报错）
  - category: device
    text: 限流命中 记录：触发频率限制时记 IP 的 哈希前 12 位 （不存原始 IP）+ user agent 头 120 字符 + 触发的端点。
  deletion:
    route: 'Account settings: 右上角头像菜单选「删除账号」，30 天宽限期后自动硬删除；立即硬删可发邮件至 hi@baozugong.app'
    text: 30 天后 ：自动硬删除——所有 user_data 行 + auth.users 记录 + usage_events（级联删除）从数据库永久清除。这是不可逆操作。
  dpa:
    available: null
    text: 这些公司都签了数据处理协议或受其服务条款约束。
    url: null
  purposes:
  - purpose: 提供产品功能
    text: 提供产品功能 ：推荐引擎、风险评估、Greeks 计算、早安简报、复盘报告。
  - purpose: 多设备同步
    text: 多设备同步 ：登录后你的持仓 / 偏好在所有设备实时同步。
  - purpose: 反滥用 / 反爬虫
    text: 反滥用 / 反爬虫 ：限流、阻挡自动化 scraping。
  - purpose: 错误排查
    text: 错误排查 ：Sentry 报警 → 我们修 bug → 你下次少踩坑。
  residency:
  - region: US
    text: 数据库 ：Supabase（位于美国 AWS）
  retention:
  - period: null
    scope: 账号在用的持仓/偏好/笔记
    text: 账号在用 ：持仓 / 偏好 / 笔记保留到你删除为止。
  - period: 24 个月
    scope: 行为日志聚合统计
    text: 行为日志 ：聚合统计保留 24 个月，之后只保聚合的 metric 不保单条记录。
  - period: 90 天
    scope: 错误日志
    text: 错误日志 ：Sentry 默认 90 天滚动删除。
  - period: 7 天
    scope: 备份
    text: 备份 ：Supabase 自动每日备份，保留 7 天，到期自动覆盖。
  rights:
  - right: 访问 / 导出
    text: 可下载你全部的持仓 + 偏好 + 笔记，JSON 格式
  - right: 修正
    text: 你可以在 App 里随时直接改你的持仓 / 笔记 / 偏好。改完会实时同步。
  - right: 反对处理 / 撤回同意
    text: 登出 = 立即停止收集新数据。
  - right: 投诉
    text: 如果你在欧盟，可以向你所在国的 Data Protection Authority 投诉。
  role:
    text: 包租公（"我们"）是一个让散户用 Covered Call / Cash-Secured Put / Wheel 策略可视化"出租"美股的分析工具。
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: 不卖、不出租、不分享数据给广告商。
  subprocessors:
    text: 第三方分包商（Sub-processors） 为了让产品跑起来，下面这些第三方会处理你的部分数据。
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: 包租公
provenance_date: '2026-11-09'
provider_name: 包租公
provider_slug: baozugong-app
slug: baozugong-app-privacy-policy
source_date: '2026-11-09'
source_filename: baozugong-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://baozugong.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: 包租公\naid: baozugong-app\nurl: https://baozugong.app/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 包租公（\"我们\"）是一个让散户用 Covered Call / Cash-Secured Put / Wheel 策略可视化\"出租\"美股的分析工具。\ndata_categories:\n- category: identifying\n  text: 邮箱地址 ：通过 Google OAuth 或邮箱密码方式注册 / 登录。\n- category: financial\n  text: 持仓数据 ：你手动录入的股票 / 期权（ticker、合约、张数、入场价）。\n- category: behavioral\n  text: 登录 / 推荐 / 早安简报 / 复盘 等动作的时间戳和聚合 metadata（ticker、策略类型、是否报错）\n- category: device\n  text: 限流命中 记录：触发频率限制时记 IP 的 哈希前 12 位 （不存原始 IP）+ user agent 头 120 字符 + 触发的端点。\npurposes:\n- purpose: 提供产品功能\n  text: 提供产品功能 ：推荐引擎、风险评估、Greeks\
  \ 计算、早安简报、复盘报告。\n- purpose: 多设备同步\n  text: 多设备同步 ：登录后你的持仓 / 偏好在所有设备实时同步。\n- purpose: 反滥用 / 反爬虫\n  text: 反滥用 / 反爬虫 ：限流、阻挡自动化 scraping。\n- purpose: 错误排查\n  text: 错误排查 ：Sentry 报警 → 我们修 bug → 你下次少踩坑。\nretention:\n- scope: 账号在用的持仓/偏好/笔记\n  period: null\n  text: 账号在用 ：持仓 / 偏好 / 笔记保留到你删除为止。\n- scope: 行为日志聚合统计\n  period: 24 个月\n  text: 行为日志 ：聚合统计保留 24 个月，之后只保聚合的 metric 不保单条记录。\n- scope: 错误日志\n  period: 90 天\n  text: 错误日志 ：Sentry 默认 90 天滚动删除。\n- scope: 备份\n  period: 7 天\n  text: 备份 ：Supabase 自动每日备份，保留 7 天，到期自动覆盖。\nresidency:\n- region: US\n  text: 数据库 ：Supabase（位于美国 AWS）\ntransfers: []\nsubprocessors:\n  url: null\n  text: 第三方分包商（Sub-processors） 为了让产品跑起来，下面这些第三方会处理你的部分数据。\ndpa:\n  available: null\n  url: null\n  text: 这些公司都签了数据处理协议或受其服务条款约束。\ndeletion:\n  route: 'Account settings: 右上角头像菜单选「删除账号」，30 天宽限期后自动硬删除；立即硬删可发邮件至 hi@baozugong.app'\n  text: 30 天后 ：自动硬删除——所有 user_data 行 + auth.users 记录 + usage_events（级联删除）从数据库永久清除。这是不可逆操作。\nrights:\n- right: 访问 / 导出\n  text: 可下载你全部的持仓 + 偏好 + 笔记，JSON 格式\n- right:\
  \ 修正\n  text: 你可以在 App 里随时直接改你的持仓 / 笔记 / 偏好。改完会实时同步。\n- right: 反对处理 / 撤回同意\n  text: 登出 = 立即停止收集新数据。\n- right: 投诉\n  text: 如果你在欧盟，可以向你所在国的 Data Protection Authority 投诉。\nsale_or_sharing:\n  stance: prohibited\n  text: 不卖、不出租、不分享数据给广告商。\n"
source_yaml_url: https://artifacts.apis.io/baozugong-app/privacy/baozugong-app-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from 包租公's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Investing
- Artificial Intelligence
- Options
- US-Stocks
---
