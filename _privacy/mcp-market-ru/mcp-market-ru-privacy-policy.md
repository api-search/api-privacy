---
claim_count: 17
description: ''
doc:
  data_categories:
  - category: identifying
    text: e-mail при регистрации
  - category: device
    text: IP-адрес и User-Agent при API-запросах (для антиабузного лимитирования)
  - category: behavioral
    text: содержимое запросов к MCP-эндпоинту (для кеширования и аналитики)
  - category: financial
    text: сведения об оплате через платёжный шлюз партнёра
  - category: contact
    text: имя, телефон, email и комментарий
  deletion:
    route: e-mail запрос на info@mcp-market.ru
    text: Вы можете в любой момент запросить доступ к своим данным, их исправление, удаление или отзыв согласия, написав на info@mcp-market.ru .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: связь и восстановление доступа
    text: E-mail — для связи, восстановления доступа, уведомлений о лидах (request_quote).
  - purpose: защита от DDoS и rate-limit
    text: IP + User-Agent — для защиты от DDoS и rate-limit.
  - purpose: диагностика и улучшение качества ответов
    text: Логи API — для диагностики инцидентов и улучшения качества ответов инструментам AI-агентов.
  residency:
  - region: Российская Федерация
    text: Все данные хранятся на серверах, физически расположенных на территории Российской Федерации.
  retention:
  - period: 90 дней
    scope: логи API
    text: Логи API хранятся 90 дней и затем анонимизируются.
  rights:
  - right: доступ
    text: запросить доступ к своим данным
  - right: исправление
    text: их исправление
  - right: удаление
    text: удаление
  - right: отзыв согласия
    text: отзыв согласия
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Мы не продаём ваши персональные данные рекламодателям и брокерам данных.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: указанные вами имя, телефон, email и комментарий передаются оператору MCP Market уведомлением в мессенджер Telegram (Telegram Messenger Inc.), серверы которого расположены за пределами РФ.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mcp-market-ru
provenance_date: '2026-11-10'
provider_name: mcp-market-ru
provider_slug: mcp-market-ru
slug: mcp-market-ru-privacy-policy
source_date: '2026-11-10'
source_filename: mcp-market-ru-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mcp-market.ru/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mcp-market-ru\naid: mcp-market-ru\nurl: https://mcp-market.ru/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: e-mail при регистрации\n- category: device\n  text: IP-адрес и User-Agent при API-запросах (для антиабузного лимитирования)\n- category: behavioral\n  text: содержимое запросов к MCP-эндпоинту (для кеширования и аналитики)\n- category: financial\n  text: сведения об оплате через платёжный шлюз партнёра\n- category: contact\n  text: имя, телефон, email и комментарий\npurposes:\n- purpose: связь и восстановление доступа\n\
  \  text: E-mail — для связи, восстановления доступа, уведомлений о лидах (request_quote).\n- purpose: защита от DDoS и rate-limit\n  text: IP + User-Agent — для защиты от DDoS и rate-limit.\n- purpose: диагностика и улучшение качества ответов\n  text: Логи API — для диагностики инцидентов и улучшения качества ответов инструментам AI-агентов.\nretention:\n- scope: логи API\n  period: 90 дней\n  text: Логи API хранятся 90 дней и затем анонимизируются.\nresidency:\n- region: Российская Федерация\n  text: Все данные хранятся на серверах, физически расположенных на территории Российской Федерации.\ntransfers:\n- mechanism: other\n  text: указанные вами имя, телефон, email и комментарий передаются оператору MCP Market уведомлением в мессенджер\n    Telegram (Telegram Messenger Inc.), серверы которого расположены за пределами РФ.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: e-mail запрос на info@mcp-market.ru\n  text: Вы можете\
  \ в любой момент запросить доступ к своим данным, их исправление, удаление или отзыв согласия, написав\n    на info@mcp-market.ru .\nrights:\n- right: доступ\n  text: запросить доступ к своим данным\n- right: исправление\n  text: их исправление\n- right: удаление\n  text: удаление\n- right: отзыв согласия\n  text: отзыв согласия\nsale_or_sharing:\n  stance: prohibited\n  text: Мы не продаём ваши персональные данные рекламодателям и брокерам данных.\n"
source_yaml_url: https://artifacts.apis.io/mcp-market-ru/privacy/mcp-market-ru-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from mcp-market-ru's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- E-Commerce
- Russia
---
