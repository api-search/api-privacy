---
api_specs:
- filename: egrul-org-openapi-generated.yml
  format: yaml
  label: egrul-org API
  slug: egrul-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/egrul-org/openapi/_ae-authored/egrul-org-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: адрес электронной почты подписчика — используется исключительно как логин для доступа в личный кабинет
  - category: behavioral
    text: история запросов к API — используется только для учёта лимитов тарифа
  - category: device
    text: счётчик Яндекс.Метрики собирает агрегированные технические показатели (переходы, просмотры страниц, тип устройства) для целей статистики
  - category: financial
    text: Платёжные данные обрабатываются платёжным провайдером/банком напрямую — Сайт не хранит номера банковских карт.
  deletion:
    route: запрос на адрес, указанный в разделе «Контакты»
    text: потребовать их удаление, направив запрос на адрес, указанный в разделе «Контакты»
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: statistics
    text: для целей статистики
  - purpose: subscription contract
    text: используется исключительно для исполнения договора подписки
  - purpose: API tariff limits
    text: используется только для учёта лимитов тарифа
  - purpose: service notifications
    text: для направления уведомлений, связанных с оказанием услуги
  residency:
  - region: Российская Федерация
    text: Технические и учётные данные хранятся на серверах, расположенных на территории Российской Федерации
  retention:
  - period: до 12 месяцев после её окончания
    scope: subscriber account data (email, request history)
    text: данные учётной записи подписчика (email, история запросов) хранятся на всё время действия подписки и до 12 месяцев после её окончания
  - period: null
    scope: Yandex.Metrica statistics
    text: Обезличенная статистика посещаемости (Яндекс.Метрика) хранится в соответствии со сроками, установленными самим сервисом Яндекс.Метрика.
  rights:
  - right: access to account data
    text: Пользователь вправе запросить сведения о своём адресе электронной почты и истории запросов в рамках личного кабинета
  - right: erasure
    text: а также потребовать их удаление
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Технические и учётные данные не продаются и не передаются третьим лицам, за исключением случаев, необходимых для работы Сервиса
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: egrul-org
provenance_date: '2026-11-09'
provider_name: egrul-org
provider_slug: egrul-org
slug: egrul-org-privacy-policy
source_date: '2026-11-09'
source_filename: egrul-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://egrul.org/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: egrul-org\naid: egrul-org\nurl: https://egrul.org/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: адрес электронной почты подписчика — используется исключительно как логин для доступа в личный кабинет\n- category: behavioral\n  text: история запросов к API — используется только для учёта лимитов тарифа\n- category: device\n  text: счётчик Яндекс.Метрики собирает агрегированные технические показатели (переходы, просмотры страниц, тип\n    устройства) для целей статистики\n- category: financial\n  text: Платёжные данные обрабатываются\
  \ платёжным провайдером/банком напрямую — Сайт не хранит номера банковских\n    карт.\npurposes:\n- purpose: statistics\n  text: для целей статистики\n- purpose: subscription contract\n  text: используется исключительно для исполнения договора подписки\n- purpose: API tariff limits\n  text: используется только для учёта лимитов тарифа\n- purpose: service notifications\n  text: для направления уведомлений, связанных с оказанием услуги\nretention:\n- scope: subscriber account data (email, request history)\n  period: до 12 месяцев после её окончания\n  text: данные учётной записи подписчика (email, история запросов) хранятся на всё время действия подписки и до\n    12 месяцев после её окончания\n- scope: Yandex.Metrica statistics\n  period: null\n  text: Обезличенная статистика посещаемости (Яндекс.Метрика) хранится в соответствии со сроками, установленными\n    самим сервисом Яндекс.Метрика.\nresidency:\n- region: Российская Федерация\n  text: Технические и учётные данные хранятся на серверах,\
  \ расположенных на территории Российской Федерации\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: запрос на адрес, указанный в разделе «Контакты»\n  text: потребовать их удаление, направив запрос на адрес, указанный в разделе «Контакты»\nrights:\n- right: access to account data\n  text: Пользователь вправе запросить сведения о своём адресе электронной почты и истории запросов в рамках личного\n    кабинета\n- right: erasure\n  text: а также потребовать их удаление\nsale_or_sharing:\n  stance: conditional\n  text: Технические и учётные данные не продаются и не передаются третьим лицам, за исключением случаев, необходимых\n    для работы Сервиса\n"
source_yaml_url: https://artifacts.apis.io/egrul-org/privacy/egrul-org-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from egrul-org's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Government
- Data
- Russia
---
