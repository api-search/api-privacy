---
api_specs:
- filename: aifra-ru-analytics-api-openapi.yml
  format: yaml
  label: AIfra Analytics API
  slug: aifra-ru-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-analytics-api-openapi.yml
- filename: aifra-ru-health-api-openapi.yml
  format: yaml
  label: AIfra Health API
  slug: aifra-ru-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-health-api-openapi.yml
- filename: aifra-ru-mcp-api-openapi.yml
  format: yaml
  label: AIfra MCP API
  slug: aifra-ru-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-mcp-api-openapi.yml
- filename: aifra-ru-previews-api-openapi.yml
  format: yaml
  label: AIfra Previews API
  slug: aifra-ru-previews-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-previews-api-openapi.yml
- filename: aifra-ru-ready-api-openapi.yml
  format: yaml
  label: AIfra Ready API
  slug: aifra-ru-ready-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-ready-api-openapi.yml
- filename: aifra-ru-remote-api-openapi.yml
  format: yaml
  label: AIfra Remote API
  slug: aifra-ru-remote-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aifra-ru/openapi/aifra-ru-remote-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: device
    text: Для доставки страницы и защиты соединения технически обрабатываются сетевой адрес и параметры HTTP-запроса.
  - category: behavioral
    text: браузер отправляет название действия, путь текущей страницы из закрытого списка, категорию источника перехода и способ определения этой категории
  - category: contact
    text: При обращении по email обрабатываются адрес отправителя, сообщённое имя, содержание и необходимые вложения.
  - category: identifying
    text: Обрабатываются source IP, preview ID, hash management token, даты создания и удаления
  - category: device
    text: Локальный CLI передаёт случайный installation ID, заявленный источник, имя и версию клиента.
  deletion:
    route: preview deletion with management token
    text: удалите preview по своему токену
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery and security
    text: Их обработка ограничивается обслуживанием запроса и безопасностью
  - purpose: anonymized site statistics
    text: Основной сайт AIfra может собирать обезличенную статистику открытий своих публичных страниц
  - purpose: providing the requested preview function
    text: Это нужно для предоставления запрошенной функции и применения ограничений
  - purpose: replies and handling requests
    text: Цели — ответ, устранение нарушения и исполнение обязанностей оператора
  residency:
  - region: Russia
    text: События хранятся в базе сервиса в РФ не более 30 дней
  - region: Moscow
    text: Основной сервер и база сервиса размещены у Selectel в Москве
  retention:
  - period: 30 дней
    scope: site analytics events
    text: События хранятся в базе сервиса в РФ не более 30 дней с последующим автоматическим удалением существующим обработчиком.
  - period: 30 дней
    scope: daily preview totals
    text: Суточные итоги хранятся до 30 дней и доступны только владельцу сервиса.
  - period: 48-часовой срок
    scope: preview files
    text: Файлы preview имеют отдельный 48-часовой срок
  - period: 2 часа
    scope: unconfirmed uploaded files (remote MCP)
    text: Неподтверждённые файлы удаляются через 2 часа
  rights:
  - right: access and correction information requests
    text: Вы вправе запросить сведения об обработке, уточнение, блокирование или уничтожение данных при наличии оснований
  - right: withdraw consent
    text: а также отозвать отдельно предоставленное согласие
  - right: appeal
    text: Действия оператора можно обжаловать в Роскомнадзор или суд.
  role:
    text: Оператор — физическое лицо Башарин Николай Игоревич, сервис AIfra.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: произвольная продажа персональных данных не предусмотрена
  subprocessors:
    text: Основной сервер и база сервиса размещены у Selectel в Москве; почтовый провайдер — Timeweb.
    url: null
  transfers:
  - mechanism: other
    text: Трансграничная передача не включается как функция сервиса
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIfra
provenance_date: '2026-11-09'
provider_name: AIfra
provider_slug: aifra-ru
slug: aifra-ru-privacy-policy
source_date: '2026-11-09'
source_filename: aifra-ru-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aifra.ru/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIfra\naid: aifra-ru\nurl: https://aifra.ru/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Оператор — физическое лицо Башарин Николай Игоревич, сервис AIfra.\ndata_categories:\n- category: device\n  text: Для доставки страницы и защиты соединения технически обрабатываются сетевой адрес и параметры HTTP-запроса.\n- category: behavioral\n  text: браузер отправляет название действия, путь текущей страницы из закрытого списка, категорию источника перехода\n    и способ определения этой категории\n- category: contact\n  text: При обращении по email обрабатываются адрес отправителя,\
  \ сообщённое имя, содержание и необходимые вложения.\n- category: identifying\n  text: Обрабатываются source IP, preview ID, hash management token, даты создания и удаления\n- category: device\n  text: Локальный CLI передаёт случайный installation ID, заявленный источник, имя и версию клиента.\npurposes:\n- purpose: service delivery and security\n  text: Их обработка ограничивается обслуживанием запроса и безопасностью\n- purpose: anonymized site statistics\n  text: Основной сайт AIfra может собирать обезличенную статистику открытий своих публичных страниц\n- purpose: providing the requested preview function\n  text: Это нужно для предоставления запрошенной функции и применения ограничений\n- purpose: replies and handling requests\n  text: Цели — ответ, устранение нарушения и исполнение обязанностей оператора\nretention:\n- scope: site analytics events\n  period: 30 дней\n  text: События хранятся в базе сервиса в РФ не более 30 дней с последующим автоматическим удалением существующим\n\
  \    обработчиком.\n- scope: daily preview totals\n  period: 30 дней\n  text: Суточные итоги хранятся до 30 дней и доступны только владельцу сервиса.\n- scope: preview files\n  period: 48-часовой срок\n  text: Файлы preview имеют отдельный 48-часовой срок\n- scope: unconfirmed uploaded files (remote MCP)\n  period: 2 часа\n  text: Неподтверждённые файлы удаляются через 2 часа\nresidency:\n- region: Russia\n  text: События хранятся в базе сервиса в РФ не более 30 дней\n- region: Moscow\n  text: Основной сервер и база сервиса размещены у Selectel в Москве\ntransfers:\n- mechanism: other\n  text: Трансграничная передача не включается как функция сервиса\nsubprocessors:\n  url: null\n  text: Основной сервер и база сервиса размещены у Selectel в Москве; почтовый провайдер — Timeweb.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: preview deletion with management token\n  text: удалите preview по своему токену\nrights:\n- right: access and correction information requests\n\
  \  text: Вы вправе запросить сведения об обработке, уточнение, блокирование или уничтожение данных при наличии оснований\n- right: withdraw consent\n  text: а также отозвать отдельно предоставленное согласие\n- right: appeal\n  text: Действия оператора можно обжаловать в Роскомнадзор или суд.\nsale_or_sharing:\n  stance: prohibited\n  text: произвольная продажа персональных данных не предусмотрена\n"
source_yaml_url: https://artifacts.apis.io/aifra-ru/privacy/aifra-ru-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 23 quoted statements, read from AIfra's own page on 2026-11-09.
synthetic: false
tags:
- Software-as-a-Service
- Static-Previews
- Artificial Intelligence
- CLI
- REST
---
