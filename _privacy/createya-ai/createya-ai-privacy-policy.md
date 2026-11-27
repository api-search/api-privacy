---
api_specs:
- filename: createya-ai-balance-api-openapi.yml
  format: yaml
  label: Createya Balance API
  slug: createya-ai-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-balance-api-openapi.yml
- filename: createya-ai-healthz-api-openapi.yml
  format: yaml
  label: Createya Healthz API
  slug: createya-ai-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-healthz-api-openapi.yml
- filename: createya-ai-mcp-api-openapi.yml
  format: yaml
  label: Createya MCP API
  slug: createya-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-mcp-api-openapi.yml
- filename: createya-ai-models-api-openapi.yml
  format: yaml
  label: Createya Models API
  slug: createya-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-models-api-openapi.yml
- filename: createya-ai-run-api-openapi.yml
  format: yaml
  label: Createya Run API
  slug: createya-ai-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-run-api-openapi.yml
- filename: createya-ai-runs-api-openapi.yml
  format: yaml
  label: Createya Runs API
  slug: createya-ai-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-runs-api-openapi.yml
- filename: createya-ai-uploads-api-openapi.yml
  format: yaml
  label: Createya Uploads API
  slug: createya-ai-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/createya-ai/openapi/createya-ai-uploads-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: адрес электронной почты (email); имя (необязательно, заполняется по желанию Пользователя)
  - category: financial
    text: записи о транзакциях (суммы, даты, статусы платежей)
  - category: device
    text: IP-адрес; информация о браузере (user-agent); файлы cookie и аналогичные технологии; информация об устройстве (тип, операционная система, разрешение экрана)
  - category: behavioral
    text: аналитические метрики (частота использования, предпочтения функциональности)
  - category: other
    text: текстовые запросы (промпты) для генерации контента; загруженные Пользователем файлы (изображения, видео, аудио)
  deletion:
    route: account deletion by the user
    text: 'Право на удаление учётной записи: полное удаление учётной записи и связанных с ней персональных данных (за исключением данных, хранение которых обусловлено требованиями законодательства).'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision
    text: предоставление доступа к функциям генерации контента с использованием технологий искусственного интеллекта
  - purpose: billing
    text: начисление и списание кредитов, обработка оплаты подписок и пополнений баланса
  - purpose: marketing
    text: направление информационных и рекламных сообщений (только при наличии отдельного согласия Пользователя; Пользователь вправе отказаться от получения таких сообщений в любое время)
  - purpose: analytics
    text: анализ поведения Пользователей для повышения качества Сервиса
  residency:
  - region: Russian Federation
    text: Все персональные данные Пользователей хранятся на серверах, расположенных на территории Российской Федерации
  retention:
  - period: 3 (трёх) лет
    scope: financial records
    text: Финансовые записи (данные о транзакциях, чеки) хранятся в течение 3 (трёх) лет после совершения операции
  - period: до момента удаления учётной записи Пользователем либо до отзыва согласия
    scope: personal data
    text: Персональные данные хранятся до момента удаления учётной записи Пользователем либо до отзыва согласия на обработку.
  - period: 1 (одного) года
    scope: persistent cookies
    text: постоянные cookie хранятся не более 1 (одного) года с момента последнего обновления
  rights:
  - right: access
    text: 'Право на доступ: получение информации об обрабатываемых персональных данных'
  - right: rectification
    text: 'Право на исправление: уточнение, обновление или исправление неточных или неполных персональных данных.'
  - right: erasure or blocking
    text: 'Право на блокирование и удаление: требование блокирования или уничтожения персональных данных'
  - right: withdraw consent
    text: 'Право на отзыв согласия: отзыв ранее данного согласия на обработку персональных данных в любое время.'
  - right: object to automated processing
    text: Пользователь имеет право возражать против автоматизированной обработки своих персональных данных
  role:
    text: 'осуществляемой Индивидуальным предпринимателем Оганесян Артур Патваканович, ИНН 770372906310, ОГРНИП 318774600215091, зарегистрированным по адресу: 641611, обл. Курганская, р-н. Макушинский, с. Обутковское, ул. Береговая, д. 9, кв. 3 (далее — «Оператор»).'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'AI-провайдеры, используемые Сервисом: fal.ai (США), OpenRouter (США), ElevenLabs (США), Suno (США).'
    url: null
  transfers:
  - mechanism: other
    text: Передача данных AI-провайдерам, расположенным за пределами Российской Федерации, осуществляется на основании согласия Пользователя, выраженного при акцепте Оферты.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Createya
provenance_date: '2026-11-09'
provider_name: Createya
provider_slug: createya-ai
slug: createya-ai-privacy-policy
source_date: '2026-11-09'
source_filename: createya-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://createya.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Createya\naid: createya-ai\nurl: https://createya.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'осуществляемой Индивидуальным предпринимателем Оганесян Артур Патваканович, ИНН 770372906310, ОГРНИП 318774600215091,\n    зарегистрированным по адресу: 641611, обл. Курганская, р-н. Макушинский, с. Обутковское, ул. Береговая, д. 9,\n    кв. 3 (далее — «Оператор»).'\ndata_categories:\n- category: contact\n  text: адрес электронной почты (email); имя (необязательно, заполняется по желанию Пользователя)\n- category: financial\n  text: записи о транзакциях (суммы, даты, статусы платежей)\n\
  - category: device\n  text: IP-адрес; информация о браузере (user-agent); файлы cookie и аналогичные технологии; информация об устройстве\n    (тип, операционная система, разрешение экрана)\n- category: behavioral\n  text: аналитические метрики (частота использования, предпочтения функциональности)\n- category: other\n  text: текстовые запросы (промпты) для генерации контента; загруженные Пользователем файлы (изображения, видео,\n    аудио)\npurposes:\n- purpose: service provision\n  text: предоставление доступа к функциям генерации контента с использованием технологий искусственного интеллекта\n- purpose: billing\n  text: начисление и списание кредитов, обработка оплаты подписок и пополнений баланса\n- purpose: marketing\n  text: направление информационных и рекламных сообщений (только при наличии отдельного согласия Пользователя; Пользователь\n    вправе отказаться от получения таких сообщений в любое время)\n- purpose: analytics\n  text: анализ поведения Пользователей для повышения\
  \ качества Сервиса\nretention:\n- scope: financial records\n  period: 3 (трёх) лет\n  text: Финансовые записи (данные о транзакциях, чеки) хранятся в течение 3 (трёх) лет после совершения операции\n- scope: personal data\n  period: до момента удаления учётной записи Пользователем либо до отзыва согласия\n  text: Персональные данные хранятся до момента удаления учётной записи Пользователем либо до отзыва согласия на\n    обработку.\n- scope: persistent cookies\n  period: 1 (одного) года\n  text: постоянные cookie хранятся не более 1 (одного) года с момента последнего обновления\nresidency:\n- region: Russian Federation\n  text: Все персональные данные Пользователей хранятся на серверах, расположенных на территории Российской Федерации\ntransfers:\n- mechanism: other\n  text: Передача данных AI-провайдерам, расположенным за пределами Российской Федерации, осуществляется на основании\n    согласия Пользователя, выраженного при акцепте Оферты.\nsubprocessors:\n  url: null\n  text: 'AI-провайдеры,\
  \ используемые Сервисом: fal.ai (США), OpenRouter (США), ElevenLabs (США), Suno (США).'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: account deletion by the user\n  text: 'Право на удаление учётной записи: полное удаление учётной записи и связанных с ней персональных данных\n    (за исключением данных, хранение которых обусловлено требованиями законодательства).'\nrights:\n- right: access\n  text: 'Право на доступ: получение информации об обрабатываемых персональных данных'\n- right: rectification\n  text: 'Право на исправление: уточнение, обновление или исправление неточных или неполных персональных данных.'\n- right: erasure or blocking\n  text: 'Право на блокирование и удаление: требование блокирования или уничтожения персональных данных'\n- right: withdraw consent\n  text: 'Право на отзыв согласия: отзыв ранее данного согласия на обработку персональных данных в любое время.'\n- right: object to automated processing\n  text: Пользователь имеет право возражать\
  \ против автоматизированной обработки своих персональных данных\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/createya-ai/privacy/createya-ai-privacy-policy.yml
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
summary_line: 22 quoted statements, read from Createya's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Generative AI
- Image Generation
- Video Generation
- Audio Generation
- Model Aggregator
- MCP
---
