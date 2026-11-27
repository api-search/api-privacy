---
api_specs:
- filename: srezai-ru-openapi-generated.yml
  format: yaml
  label: srezai-ru API
  slug: srezai-ru-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/srezai-ru/openapi/_ae-authored/srezai-ru-openapi-generated.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Адрес электронной почты, имя или логин, идентификатор пользователя в системе авторизации, дата регистрации и дата последнего входа.
  - category: financial
    text: Сумма и дата пополнения Баланса, текущий остаток, история списаний за оказанные Услуги, тарифный план.
  - category: behavioral
    text: Текст запроса, тип Услуги (веб-поиск, изображения, чтение страницы, скриншот страницы, извлечение по схеме, DeepResearch)
  - category: device
    text: IP-адрес обращения, префикс использованного API-ключа и время запроса.
  - category: location
    text: примерный регион
  - category: communication
    text: Тема и текст сообщения, адрес электронной почты и имя автора, содержание переписки с поддержкой.
  deletion:
    route: support request and in-account history clearing
    text: вы можете в любой момент очистить локальную историю запросов в личном кабинете и запросить удаление серверного журнала, обратившись в поддержку.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service provision
    text: Предоставление Услуг - создание учётной записи, выпуск и проверка API-ключей, выполнение запросов.
  - purpose: billing
    text: Расчёты и биллинг - приём платежей, учёт списаний, возвраты.
  - purpose: security and abuse prevention
    text: Безопасность и защита от злоупотреблений - ограничение частоты запросов, выявление обхода лимитов и автоматизированного перебора.
  - purpose: product analytics
    text: Улучшение продукта и аналитика - обезличенные агрегированные метрики использования.
  - purpose: marketing mailings
    text: Рекламные рассылки отправляются только с отдельного согласия и всегда содержат ссылку на отказ.
  residency:
  - region: Russia
    text: Базы данных, серверы приложения и объектное хранилище Сервиса размещены на территории Российской Федерации.
  retention:
  - period: пока учётная запись существует, и до 1 года после её удаления
    scope: account data
    text: Данные учётной записи - пока учётная запись существует, и до 1 года после её удаления (для разрешения возможных споров).
  - period: 5 лет
    scope: billing and payment records
    text: Расчётные и платёжные записи - 5 лет, как требует законодательство о бухгалтерском учёте.
  - period: до 12 месяцев
    scope: request log
    text: Журнал запросов - до 12 месяцев, затем удаляется или обезличивается до агрегированной статистики.
  - period: 3 года с момента закрытия обращения
    scope: support requests
    text: Обращения в поддержку - 3 года с момента закрытия обращения.
  - period: минуты и часы
    scope: rate-limit counters
    text: Счётчики лимитов - минуты и часы, удаляются автоматически.
  rights:
  - right: access
    text: получить сведения об обработке ваших персональных данных
  - right: rectification, blocking or deletion
    text: потребовать уточнения, блокирования или удаления данных, если они неполны, устарели, неточны или обрабатываются неправомерно
  - right: withdraw consent
    text: отозвать согласие на обработку данных
  - right: opt out of mailings and analytics cookies
    text: отказаться от рассылок и от аналитических cookie
  - right: portability
    text: получить копию ваших данных в машиночитаемом виде
  - right: complaint
    text: обжаловать наши действия в Роскомнадзоре или в суде
  role:
    text: Оператор ИП Болгар Виталий Юрьевич ИНН 780537116634
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Мы не продаём и не передаём ваши данные третьим лицам для их собственных целей.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Часть подрядчиков (в частности, поставщики языковых моделей и Google Analytics) находится за пределами Российской Федерации, поэтому при выполнении отдельных запросов и при веб-аналитике возможна трансграничная передача данных.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: srezai-ru
provenance_date: '2026-11-10'
provider_name: srezai-ru
provider_slug: srezai-ru
slug: srezai-ru-privacy-policy
source_date: '2026-11-10'
source_filename: srezai-ru-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://srezai.ru/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: srezai-ru\naid: srezai-ru\nurl: https://srezai.ru/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Оператор ИП Болгар Виталий Юрьевич ИНН 780537116634\ndata_categories:\n- category: contact\n  text: Адрес электронной почты, имя или логин, идентификатор пользователя в системе авторизации, дата регистрации\n    и дата последнего входа.\n- category: financial\n  text: Сумма и дата пополнения Баланса, текущий остаток, история списаний за оказанные Услуги, тарифный план.\n- category: behavioral\n  text: Текст запроса, тип Услуги (веб-поиск, изображения, чтение страницы, скриншот страницы,\
  \ извлечение по схеме,\n    DeepResearch)\n- category: device\n  text: IP-адрес обращения, префикс использованного API-ключа и время запроса.\n- category: location\n  text: примерный регион\n- category: communication\n  text: Тема и текст сообщения, адрес электронной почты и имя автора, содержание переписки с поддержкой.\npurposes:\n- purpose: service provision\n  text: Предоставление Услуг - создание учётной записи, выпуск и проверка API-ключей, выполнение запросов.\n- purpose: billing\n  text: Расчёты и биллинг - приём платежей, учёт списаний, возвраты.\n- purpose: security and abuse prevention\n  text: Безопасность и защита от злоупотреблений - ограничение частоты запросов, выявление обхода лимитов и автоматизированного\n    перебора.\n- purpose: product analytics\n  text: Улучшение продукта и аналитика - обезличенные агрегированные метрики использования.\n- purpose: marketing mailings\n  text: Рекламные рассылки отправляются только с отдельного согласия и всегда содержат ссылку на\
  \ отказ.\nretention:\n- scope: account data\n  period: пока учётная запись существует, и до 1 года после её удаления\n  text: Данные учётной записи - пока учётная запись существует, и до 1 года после её удаления (для разрешения возможных\n    споров).\n- scope: billing and payment records\n  period: 5 лет\n  text: Расчётные и платёжные записи - 5 лет, как требует законодательство о бухгалтерском учёте.\n- scope: request log\n  period: до 12 месяцев\n  text: Журнал запросов - до 12 месяцев, затем удаляется или обезличивается до агрегированной статистики.\n- scope: support requests\n  period: 3 года с момента закрытия обращения\n  text: Обращения в поддержку - 3 года с момента закрытия обращения.\n- scope: rate-limit counters\n  period: минуты и часы\n  text: Счётчики лимитов - минуты и часы, удаляются автоматически.\nresidency:\n- region: Russia\n  text: Базы данных, серверы приложения и объектное хранилище Сервиса размещены на территории Российской Федерации.\ntransfers:\n- mechanism:\
  \ other\n  text: Часть подрядчиков (в частности, поставщики языковых моделей и Google Analytics) находится за пределами Российской\n    Федерации, поэтому при выполнении отдельных запросов и при веб-аналитике возможна трансграничная передача данных.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: support request and in-account history clearing\n  text: вы можете в любой момент очистить локальную историю запросов в личном кабинете и запросить удаление серверного\n    журнала, обратившись в поддержку.\nrights:\n- right: access\n  text: получить сведения об обработке ваших персональных данных\n- right: rectification, blocking or deletion\n  text: потребовать уточнения, блокирования или удаления данных, если они неполны, устарели, неточны или обрабатываются\n    неправомерно\n- right: withdraw consent\n  text: отозвать согласие на обработку данных\n- right: opt out of mailings and analytics cookies\n  text: отказаться от рассылок\
  \ и от аналитических cookie\n- right: portability\n  text: получить копию ваших данных в машиночитаемом виде\n- right: complaint\n  text: обжаловать наши действия в Роскомнадзоре или в суде\nsale_or_sharing:\n  stance: prohibited\n  text: Мы не продаём и не передаём ваши данные третьим лицам для их собственных целей.\n"
source_yaml_url: https://artifacts.apis.io/srezai-ru/privacy/srezai-ru-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from srezai-ru's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Search
- Artificial Intelligence
- Russia
---
