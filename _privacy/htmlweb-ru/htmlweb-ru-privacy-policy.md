---
api_specs:
- filename: htmlweb-ru-json-api-openapi.yml
  format: yaml
  label: htmlweb-ru JSON API
  slug: htmlweb-ru-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/htmlweb-ru/openapi/htmlweb-ru-json-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Базовые данные: идентификатор пользователя; email; номер телефона (при наличии)'
  - category: device
    text: технические данные (IP, user-agent, cookie, дата/время действий, журналы событий)
  - category: financial
    text: платежные служебные атрибуты (без хранения полных реквизитов банковских карт)
  - category: behavioral
    text: URL посещенных страниц, дата/время посещения, источник перехода и технические события
  - category: communication
    text: команды и сообщения пользователя боту
  deletion:
    route: support@htmlweb.ru
    text: 'Для реализации прав пользователь направляет обращение на: support@htmlweb.ru'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: registration and authentication
    text: Регистрация, идентификация и аутентификация пользователя.
  - purpose: analytics and site improvement
    text: Аналитика посещаемости сайта, выявление технических ошибок и улучшение интерфейсов с использованием cookie и Яндекс.Метрики.
  - purpose: anti-fraud and security
    text: Поддержка пользователей, антифрод, обеспечение безопасности и стабильности сервисов.
  - purpose: subscriptions and recurring payments
    text: Исполнение обязательств по оферте, включая подписки и рекуррентные списания.
  - purpose: spam moderation in chats
    text: 'Цель: автоматическая и ручная модерация спама, защита чатов, настройка правил антиспама и информирование администраторов.'
  retention:
  - period: 10 суток
    scope: phone_email_checks uploaded and verified data
    text: загруженные и проверенные данные хранятся не более 10 суток, если пользователь не удалил их раньше
  - period: 3 суток
    scope: user_ban messages
    text: сообщения - 3 суток
  - period: 30 суток
    scope: user_ban messages with a ban
    text: сообщения, по которым выполнен бан, - до 30 суток
  - period: 3 месяцев
    scope: smsgate SMS and call history in personal cabinet
    text: история входящих/исходящих SMS и звонков в личном кабинете хранится до 3 месяцев, после чего удаляется
  - period: null
    scope: main site account data
    text: в течение срока действия аккаунта и далее в пределах сроков, необходимых для бухгалтерского учета, исполнения обязательств, рассмотрения обращений, безопасности и требований закона
  rights:
  - right: access to information about processing
    text: получать сведения об обработке своих персональных данных
  - right: correction, blocking or deletion
    text: требовать уточнения, блокирования или удаления данных
  - right: withdraw consent
    text: отозвать согласие на обработку персональных данных
  - right: appeal
    text: обжаловать действия Оператора в уполномоченный орган или в судебном порядке
  role:
    text: 'Оператор: ИП Колесников Дмитрий Геннадьевич, ИНН: 616301431999'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Оператор не продает персональные данные пользователей.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Для сервисов user_ban и postman возможна трансграничная передача технических и учетных данных в рамках инфраструктуры Telegram и связанных провайдеров.
  - mechanism: other
    text: Для сервисов max_ban и max_gift трансграничная передача не применяется, если иное прямо не указано в документации конкретного сервиса.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: htmlweb-ru
provenance_date: '2026-11-09'
provider_name: htmlweb-ru
provider_slug: htmlweb-ru
slug: htmlweb-ru-privacy-policy
source_date: '2026-11-09'
source_filename: htmlweb-ru-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://htmlweb.ru/user/privacy_policy_new.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: htmlweb-ru\naid: htmlweb-ru\nurl: https://htmlweb.ru/user/privacy_policy_new.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Оператор: ИП Колесников Дмитрий Геннадьевич, ИНН: 616301431999'\ndata_categories:\n- category: identifying\n  text: 'Базовые данные: идентификатор пользователя; email; номер телефона (при наличии)'\n- category: device\n  text: технические данные (IP, user-agent, cookie, дата/время действий, журналы событий)\n- category: financial\n  text: платежные служебные атрибуты (без хранения полных реквизитов банковских карт)\n- category: behavioral\n  text: URL посещенных\
  \ страниц, дата/время посещения, источник перехода и технические события\n- category: communication\n  text: команды и сообщения пользователя боту\npurposes:\n- purpose: registration and authentication\n  text: Регистрация, идентификация и аутентификация пользователя.\n- purpose: analytics and site improvement\n  text: Аналитика посещаемости сайта, выявление технических ошибок и улучшение интерфейсов с использованием cookie\n    и Яндекс.Метрики.\n- purpose: anti-fraud and security\n  text: Поддержка пользователей, антифрод, обеспечение безопасности и стабильности сервисов.\n- purpose: subscriptions and recurring payments\n  text: Исполнение обязательств по оферте, включая подписки и рекуррентные списания.\n- purpose: spam moderation in chats\n  text: 'Цель: автоматическая и ручная модерация спама, защита чатов, настройка правил антиспама и информирование\n    администраторов.'\nretention:\n- scope: phone_email_checks uploaded and verified data\n  period: 10 суток\n  text: загруженные\
  \ и проверенные данные хранятся не более 10 суток, если пользователь не удалил их раньше\n- scope: user_ban messages\n  period: 3 суток\n  text: сообщения - 3 суток\n- scope: user_ban messages with a ban\n  period: 30 суток\n  text: сообщения, по которым выполнен бан, - до 30 суток\n- scope: smsgate SMS and call history in personal cabinet\n  period: 3 месяцев\n  text: история входящих/исходящих SMS и звонков в личном кабинете хранится до 3 месяцев, после чего удаляется\n- scope: main site account data\n  period: null\n  text: в течение срока действия аккаунта и далее в пределах сроков, необходимых для бухгалтерского учета, исполнения\n    обязательств, рассмотрения обращений, безопасности и требований закона\nresidency: []\ntransfers:\n- mechanism: other\n  text: Для сервисов user_ban и postman возможна трансграничная передача технических и учетных данных в рамках инфраструктуры\n    Telegram и связанных провайдеров.\n- mechanism: other\n  text: Для сервисов max_ban и max_gift трансграничная\
  \ передача не применяется, если иное прямо не указано в документации\n    конкретного сервиса.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: support@htmlweb.ru\n  text: 'Для реализации прав пользователь направляет обращение на: support@htmlweb.ru'\nrights:\n- right: access to information about processing\n  text: получать сведения об обработке своих персональных данных\n- right: correction, blocking or deletion\n  text: требовать уточнения, блокирования или удаления данных\n- right: withdraw consent\n  text: отозвать согласие на обработку персональных данных\n- right: appeal\n  text: обжаловать действия Оператора в уполномоченный орган или в судебном порядке\nsale_or_sharing:\n  stance: prohibited\n  text: Оператор не продает персональные данные пользователей.\n"
source_yaml_url: https://artifacts.apis.io/htmlweb-ru/privacy/htmlweb-ru-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from htmlweb-ru's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Web
- Russia
- Data
- Utilities
---
