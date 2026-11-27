---
api_specs:
- filename: apihubs-ru-default-api-openapi.yml
  format: yaml
  label: apihubs-ru Агент API
  slug: apihubs-ru-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihubs-ru/openapi/apihubs-ru-default-api-openapi.yml
- filename: apihubs-ru-llm-api-openapi.yml
  format: yaml
  label: apihubs-ru LLM API
  slug: apihubs-ru-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apihubs-ru/openapi/apihubs-ru-llm-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: адрес электронной почты, имя или отображаемое имя
  - category: device
    text: IP-адрес, сведения о браузере и устройстве (user-agent), файлы cookie и аналогичные идентификаторы
  - category: financial
    text: состояние Баланса, история начислений и списаний, сумма, валюта, статус и идентификаторы платежа
  - category: behavioral
    text: дата, время и параметры обращений к Сервису, коды ответов
  - category: other
    text: содержание Задания — текстовый запрос, входные файлы и полученный результат
  deletion:
    route: автоматическое удаление входных файлов и результатов; запрос на адрес support@apihubs.ru
    text: Входные файлы Заданий и результаты генерации хранятся не более 3 (трех) суток с момента загрузки или готовности и удаляются автоматически.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: обеспечение работы сайта и Сервиса
    text: обеспечение работы сайта и Сервиса
  - purpose: регистрация, авторизация и защита аккаунта
    text: регистрация, авторизация и защита аккаунта
  - purpose: прием, выполнение и выдача результата Заданий
    text: прием, выполнение и выдача результата Заданий
  - purpose: проведение расчетов и формирование кассовых чеков
    text: проведение расчетов, ведение Баланса и формирование кассовых чеков
  - purpose: предотвращение мошенничества и злоупотреблений
    text: предотвращение мошенничества, злоупотреблений и атак
  residency:
  - region: Российская Федерация
    text: Запись, систематизация, накопление, хранение, уточнение и извлечение персональных данных граждан Российской Федерации осуществляются с использованием баз данных, находящихся на территории Российской Федерации
  retention:
  - period: 3 (трех) суток
    scope: входные файлы Заданий и результаты генерации
    text: Входные файлы Заданий и результаты генерации хранятся не более 3 (трех) суток с момента загрузки или готовности и удаляются автоматически.
  - period: 1 (одного) года
    scope: технические журналы и события безопасности
    text: но не более 1 (одного) года, если более длительный срок не требуется для расследования инцидента или рассмотрения спора
  - period: не менее 3 (трех) лет
    scope: сведения об операциях, связанных с приемом платежей
    text: Сведения об операциях, связанных с приемом платежей, хранятся не менее 3 (трех) лет
  rights:
  - right: получение сведений об обработке
    text: Субъект вправе получать сведения, касающиеся обработки его персональных данных
  - right: уточнение, блокирование или уничтожение данных
    text: требовать уточнения, блокирования или уничтожения данных
  - right: отзыв согласия
    text: отозвать согласие на обработку
  - right: обжалование
    text: обжаловать действия или бездействие Оператора в уполномоченный орган или в судебном порядке
  role:
    text: 'Оператор персональных данных: Индивидуальный предприниматель Иванов Сергей Юрьевич'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Выполнение Заданий связано с передачей содержания Задания и параметров генерации поставщикам моделей, находящимся на территории иностранных государств.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: apihubs-ru
provenance_date: '2026-11-09'
provider_name: apihubs-ru
provider_slug: apihubs-ru
slug: apihubs-ru-privacy-policy
source_date: '2026-11-09'
source_filename: apihubs-ru-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://apihubs.ru/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: apihubs-ru\naid: apihubs-ru\nurl: https://apihubs.ru/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Оператор персональных данных: Индивидуальный предприниматель Иванов Сергей Юрьевич'\ndata_categories:\n- category: identifying\n  text: адрес электронной почты, имя или отображаемое имя\n- category: device\n  text: IP-адрес, сведения о браузере и устройстве (user-agent), файлы cookie и аналогичные идентификаторы\n- category: financial\n  text: состояние Баланса, история начислений и списаний, сумма, валюта, статус и идентификаторы платежа\n- category: behavioral\n  text: дата, время\
  \ и параметры обращений к Сервису, коды ответов\n- category: other\n  text: содержание Задания — текстовый запрос, входные файлы и полученный результат\npurposes:\n- purpose: обеспечение работы сайта и Сервиса\n  text: обеспечение работы сайта и Сервиса\n- purpose: регистрация, авторизация и защита аккаунта\n  text: регистрация, авторизация и защита аккаунта\n- purpose: прием, выполнение и выдача результата Заданий\n  text: прием, выполнение и выдача результата Заданий\n- purpose: проведение расчетов и формирование кассовых чеков\n  text: проведение расчетов, ведение Баланса и формирование кассовых чеков\n- purpose: предотвращение мошенничества и злоупотреблений\n  text: предотвращение мошенничества, злоупотреблений и атак\nretention:\n- scope: входные файлы Заданий и результаты генерации\n  period: 3 (трех) суток\n  text: Входные файлы Заданий и результаты генерации хранятся не более 3 (трех) суток с момента загрузки или готовности\n    и удаляются автоматически.\n- scope: технические\
  \ журналы и события безопасности\n  period: 1 (одного) года\n  text: но не более 1 (одного) года, если более длительный срок не требуется для расследования инцидента или рассмотрения\n    спора\n- scope: сведения об операциях, связанных с приемом платежей\n  period: не менее 3 (трех) лет\n  text: Сведения об операциях, связанных с приемом платежей, хранятся не менее 3 (трех) лет\nresidency:\n- region: Российская Федерация\n  text: Запись, систематизация, накопление, хранение, уточнение и извлечение персональных данных граждан Российской\n    Федерации осуществляются с использованием баз данных, находящихся на территории Российской Федерации\ntransfers:\n- mechanism: other\n  text: Выполнение Заданий связано с передачей содержания Задания и параметров генерации поставщикам моделей, находящимся\n    на территории иностранных государств.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: автоматическое удаление входных файлов\
  \ и результатов; запрос на адрес support@apihubs.ru\n  text: Входные файлы Заданий и результаты генерации хранятся не более 3 (трех) суток с момента загрузки или готовности\n    и удаляются автоматически.\nrights:\n- right: получение сведений об обработке\n  text: Субъект вправе получать сведения, касающиеся обработки его персональных данных\n- right: уточнение, блокирование или уничтожение данных\n  text: требовать уточнения, блокирования или уничтожения данных\n- right: отзыв согласия\n  text: отозвать согласие на обработку\n- right: обжалование\n  text: обжаловать действия или бездействие Оператора в уполномоченный орган или в судебном порядке\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/apihubs-ru/privacy/apihubs-ru-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 21 quoted statements, read from apihubs-ru's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Russian
- Software-as-a-Service
---
