---
api_specs:
- filename: appsmax-rest-api-v1-access-api-openapi.yml
  format: yaml
  label: AppsMax Access API
  slug: appsmax-rest-api-v1-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-access-api-openapi.yml
- filename: appsmax-rest-api-v1-applications-api-openapi.yml
  format: yaml
  label: AppsMax Applications API
  slug: appsmax-rest-api-v1-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-applications-api-openapi.yml
- filename: appsmax-rest-api-v1-bots-api-openapi.yml
  format: yaml
  label: AppsMax Bots API
  slug: appsmax-rest-api-v1-bots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-bots-api-openapi.yml
- filename: appsmax-rest-api-v1-campaigns-api-openapi.yml
  format: yaml
  label: AppsMax Campaigns API
  slug: appsmax-rest-api-v1-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-campaigns-api-openapi.yml
- filename: appsmax-rest-api-v1-funnels-api-openapi.yml
  format: yaml
  label: AppsMax Funnels API
  slug: appsmax-rest-api-v1-funnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-funnels-api-openapi.yml
- filename: appsmax-rest-api-v1-interactive-menu-api-openapi.yml
  format: yaml
  label: AppsMax Interactive menu API
  slug: appsmax-rest-api-v1-interactive-menu-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-interactive-menu-api-openapi.yml
- filename: appsmax-rest-api-v1-miniapps-api-openapi.yml
  format: yaml
  label: AppsMax Miniapps API
  slug: appsmax-rest-api-v1-miniapps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-miniapps-api-openapi.yml
- filename: appsmax-rest-api-v1-organizations-api-openapi.yml
  format: yaml
  label: AppsMax Organizations API
  slug: appsmax-rest-api-v1-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-organizations-api-openapi.yml
- filename: appsmax-rest-api-v1-subscribers-api-openapi.yml
  format: yaml
  label: AppsMax Subscribers API
  slug: appsmax-rest-api-v1-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appsmax-rest-api-v1/openapi/appsmax-rest-api-v1-subscribers-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: behavioral
    text: IP-адрес, user-agent, URL и время запроса, технические cookies, выбор согласия, идентификаторы Яндекс Метрики, события просмотра и взаимодействия, UTM-метки и yclid.
  - category: identifying
    text: имя, логин, email, хеш пароля и параметры входа, роли и настройки
  - category: financial
    text: идентификаторы платежей, суммы, статусы, сведения для чека
  - category: communication
    text: переписка поддержки и история согласий
  - category: other
    text: Специальные категории и биометрические данные не запрашиваются для обычной работы AppsMax.
  deletion:
    route: email request to info@appsmax.ru
    text: Для запроса направьте письмо на info@appsmax.ru с темой «Персональные данные».
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: site operation and security
    text: работа сайта, безопасность, запоминание выбора cookies, базовый учёт первого просмотра и, после согласия, расширенная аналитика
  - purpose: handling requests and partner applications
    text: ответ на обращение, подготовка предложения, рассмотрение партнёрской заявки и защита от злоупотреблений
  - purpose: registration, contract and billing
    text: регистрация, идентификация, исполнение договора, предоставление функций, биллинг, чеки, поддержка, безопасность и обязательный учёт
  residency:
  - region: Russian Federation
    text: Базы данных, в которых первично собираются данные граждан РФ, размещаются в Российской Федерации.
  - region: Russian Federation
    text: Beget — хостинг сайта и VPS продукта, базы данных, файлы, журналы и резервные копии в РФ
  retention:
  - period: до 12 месяцев
    scope: site request
    text: заявки сайта — до 12 месяцев после последнего содержательного контакта
  - period: до 30 дней
    scope: account and user content
    text: аккаунт и пользовательский контент — срок договора и до 30 дней после прекращения для восстановления
  - period: до 30 дней
    scope: application logs
    text: основные application logs — до 30 дней
  - period: обычно 5 лет
    scope: payments and accounting documents
    text: платежи, чеки и обязательные учётные документы — не менее срока, установленного законом, обычно 5 лет после отчётного года
  rights:
  - right: access to information about processing
    text: Субъект вправе получить сведения об обработке
  - right: correction, blocking or deletion
    text: потребовать уточнения, блокирования или удаления незаконно обрабатываемых данных
  - right: withdraw consent
    text: отозвать согласие
  - right: opt out of advertising
    text: отказаться от рекламы
  - right: appeal
    text: обжаловать действия Оператора в Роскомнадзор или суд
  role:
    text: AppsMax может быть самостоятельным оператором данных посетителей, заявителей и пользователей, а при обработке данных конечных пользователей бизнес-клиента — лицом, действующим по поручению такого клиента.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Beget — хостинг сайта и VPS продукта, базы данных, файлы, журналы и резервные копии в РФ; ЮKassa — приём платежей, статусы и кассовые чеки
    url: null
  transfers:
  - mechanism: other
    text: Если выбранная пользователем интеграция предполагает трансграничную передачу, она проводится только после выполнения применимых требований
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AppsMax
provenance_date: '2026-11-09'
provider_name: AppsMax
provider_slug: appsmax-rest-api-v1
slug: appsmax-rest-api-v1-privacy-policy
source_date: '2026-11-09'
source_filename: appsmax-rest-api-v1-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://appsmax.ru/documents/politika-obrabotki-personalnyh-dannyh/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AppsMax\naid: appsmax-rest-api-v1\nurl: https://appsmax.ru/documents/politika-obrabotki-personalnyh-dannyh/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: AppsMax может быть самостоятельным оператором данных посетителей, заявителей и пользователей, а при обработке\n    данных конечных пользователей бизнес-клиента — лицом, действующим по поручению такого клиента.\ndata_categories:\n- category: behavioral\n  text: IP-адрес, user-agent, URL и время запроса, технические cookies, выбор согласия, идентификаторы Яндекс Метрики,\n    события просмотра и взаимодействия, UTM-метки и yclid.\n- category: identifying\n\
  \  text: имя, логин, email, хеш пароля и параметры входа, роли и настройки\n- category: financial\n  text: идентификаторы платежей, суммы, статусы, сведения для чека\n- category: communication\n  text: переписка поддержки и история согласий\n- category: other\n  text: Специальные категории и биометрические данные не запрашиваются для обычной работы AppsMax.\npurposes:\n- purpose: site operation and security\n  text: работа сайта, безопасность, запоминание выбора cookies, базовый учёт первого просмотра и, после согласия,\n    расширенная аналитика\n- purpose: handling requests and partner applications\n  text: ответ на обращение, подготовка предложения, рассмотрение партнёрской заявки и защита от злоупотреблений\n- purpose: registration, contract and billing\n  text: регистрация, идентификация, исполнение договора, предоставление функций, биллинг, чеки, поддержка, безопасность\n    и обязательный учёт\nretention:\n- scope: site request\n  period: до 12 месяцев\n  text: заявки сайта — до\
  \ 12 месяцев после последнего содержательного контакта\n- scope: account and user content\n  period: до 30 дней\n  text: аккаунт и пользовательский контент — срок договора и до 30 дней после прекращения для восстановления\n- scope: application logs\n  period: до 30 дней\n  text: основные application logs — до 30 дней\n- scope: payments and accounting documents\n  period: обычно 5 лет\n  text: платежи, чеки и обязательные учётные документы — не менее срока, установленного законом, обычно 5 лет после\n    отчётного года\nresidency:\n- region: Russian Federation\n  text: Базы данных, в которых первично собираются данные граждан РФ, размещаются в Российской Федерации.\n- region: Russian Federation\n  text: Beget — хостинг сайта и VPS продукта, базы данных, файлы, журналы и резервные копии в РФ\ntransfers:\n- mechanism: other\n  text: Если выбранная пользователем интеграция предполагает трансграничную передачу, она проводится только после\n    выполнения применимых требований\nsubprocessors:\n\
  \  url: null\n  text: Beget — хостинг сайта и VPS продукта, базы данных, файлы, журналы и резервные копии в РФ; ЮKassa — приём\n    платежей, статусы и кассовые чеки\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to info@appsmax.ru\n  text: Для запроса направьте письмо на info@appsmax.ru с темой «Персональные данные».\nrights:\n- right: access to information about processing\n  text: Субъект вправе получить сведения об обработке\n- right: correction, blocking or deletion\n  text: потребовать уточнения, блокирования или удаления незаконно обрабатываемых данных\n- right: withdraw consent\n  text: отозвать согласие\n- right: opt out of advertising\n  text: отказаться от рекламы\n- right: appeal\n  text: обжаловать действия Оператора в Роскомнадзор или суд\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/appsmax-rest-api-v1/privacy/appsmax-rest-api-v1-privacy-policy.yml
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
summary_line: 23 quoted statements, read from AppsMax's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Software-as-a-Service
- Messaging
- Business Automation
- Chatbots
- Mini Apps
- Customer Requests
- Workflow Automation
- MAX
- Telegram
- Russian Language
---
