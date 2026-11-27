---
api_specs:
- filename: astroway-info-v1-openapi.json
  format: json
  label: AstroWay Calculation API V1 API
  slug: astroway-calculation-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astroway-info/openapi/_original/astroway-info-v1-openapi.json
- filename: astroway-info-openapi-openapi.json
  format: json
  label: astroway-info Openapi API
  slug: astroway-info-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astroway-info/openapi/_original/astroway-info-openapi-openapi.json
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: ім’я та прізвище; електронна адреса
  - category: contact
    text: контактний телефон (якщо ви вказали); адреса доставки
  - category: financial
    text: Платіжна інформація (номер картки, CVV, експірація) обробляється безпосередньо платіжними сервісами (Monobank Acquiring, LiqPay) і ніколи не зберігається на серверах Astro Way.
  - category: behavioral
    text: сторінки, які ви переглядали, тривалість сесії, дії на сайті
  - category: device
    text: User-Agent браузера, тип пристрою, ОС, мовна налаштувань
  - category: demographic
    text: дату, точний час та місце народження
  - category: other
    text: IP-адреса (псевдонімізована для аналітики GA4)
  deletion:
    route: Запит на видалення на info@astroway.info
    text: Щоб скористатися будь-яким із цих прав, надішліть запит на info@astroway.info . Ми відповімо протягом 30 днів.
  dpa:
    available: true
    text: Копії відповідних DPA та SCC доступні на запит — пишіть на info@astroway.info .
    url: null
  purposes:
  - purpose: Надання астрологічних послуг
    text: 'Для надання астрологічних, нумерологічних і таро послуг ми обробляємо: дату, точний час та місце народження'
  - purpose: Облік замовлень і платежів
    text: Виконання договору, виставлення рахунків, повернення коштів
  - purpose: Аналітика та безпека
    text: Безпека, аналітика, оптимізація
  - purpose: Маркетингові листи
    text: Маркетингові листи, акції, новини (тільки після підписки)
  retention:
  - period: Поки активний обліковий запис + 24 місяці після останньої активності
    scope: Облікový запис
    text: Поки активний обліковий запис + 24 місяці після останньої активності
  - period: 3 (три) роки після закриття замовлення
    scope: Замовлення, рахунки, бухгалтерські документи
    text: 3 (три) роки після закриття замовлення
  - period: 90 днів детально + 24 місяці агрегованих метрик
    scope: Журнал API-викликів
    text: 90 днів детально + 24 місяці агрегованих метрик
  - period: 30 днів
    scope: Логи nginx, error logs
    text: Логи nginx, error logs 30 днів
  rights:
  - right: Доступ
    text: Право на доступ (ст. 15 GDPR) — запросити копію всіх ваших персональних даних, які ми обробляємо.
  - right: Виправлення
    text: Право на виправлення (ст. 16 GDPR) — вимагати виправлення неточних або застарілих даних.
  - right: Видалення
    text: Право на видалення / «право бути забутим» (ст. 17 GDPR) — вимагати видалення даних з урахуванням законних строків зберігання.
  - right: Обмеження обробки
    text: Право на обмеження обробки (ст. 18 GDPR).
  - right: Переносимість
    text: Право на переносимість даних (ст. 20 GDPR) — отримати свої дані у структурованому, машиночитному форматі.
  - right: Заперечення
    text: Право заперечувати проти обробки (ст. 21 GDPR) — зокрема, проти прямого маркетингу.
  - right: Відкликання згоди
    text: Право відкликати згоду в будь-який момент, коли обробка ґрунтується на згоді.
  role:
    text: Розпорядником персональних даних, що обробляються на цьому Сайті, є фізична особа-підприємець Бурхан Лілія Олексіївна
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: '5. З ким ми ділимося даними — субпроцесори Для надання послуг ми передаємо обмежені обсяги персональних даних таким субпроцесорам:'
    url: null
  transfers:
  - mechanism: SCC
    text: Передача персональних даних до США та інших країн поза межами ЄС/ЄЕЗ здійснюється на підставі Стандартних договірних положень ЄС (Імплементаційне рішення Комісії (ЄС) 2021/914)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: astroway-info
provenance_date: '2026-11-09'
provider_name: astroway-info
provider_slug: astroway-info
slug: astroway-info-privacy-policy
source_date: '2026-11-09'
source_filename: astroway-info-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astroway.info/politika-konfidentsialnosti/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: astroway-info\naid: astroway-info\nurl: https://astroway.info/politika-konfidentsialnosti/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Розпорядником персональних даних, що обробляються на цьому Сайті, є фізична особа-підприємець Бурхан Лілія\n    Олексіївна\ndata_categories:\n- category: identifying\n  text: ім’я та прізвище; електронна адреса\n- category: contact\n  text: контактний телефон (якщо ви вказали); адреса доставки\n- category: financial\n  text: Платіжна інформація (номер картки, CVV, експірація) обробляється безпосередньо платіжними сервісами (Monobank\n    Acquiring, LiqPay)\
  \ і ніколи не зберігається на серверах Astro Way.\n- category: behavioral\n  text: сторінки, які ви переглядали, тривалість сесії, дії на сайті\n- category: device\n  text: User-Agent браузера, тип пристрою, ОС, мовна налаштувань\n- category: demographic\n  text: дату, точний час та місце народження\n- category: other\n  text: IP-адреса (псевдонімізована для аналітики GA4)\npurposes:\n- purpose: Надання астрологічних послуг\n  text: 'Для надання астрологічних, нумерологічних і таро послуг ми обробляємо: дату, точний час та місце народження'\n- purpose: Облік замовлень і платежів\n  text: Виконання договору, виставлення рахунків, повернення коштів\n- purpose: Аналітика та безпека\n  text: Безпека, аналітика, оптимізація\n- purpose: Маркетингові листи\n  text: Маркетингові листи, акції, новини (тільки після підписки)\nretention:\n- scope: Облікový запис\n  period: Поки активний обліковий запис + 24 місяці після останньої активності\n  text: Поки активний обліковий запис + 24 місяці після\
  \ останньої активності\n- scope: Замовлення, рахунки, бухгалтерські документи\n  period: 3 (три) роки після закриття замовлення\n  text: 3 (три) роки після закриття замовлення\n- scope: Журнал API-викликів\n  period: 90 днів детально + 24 місяці агрегованих метрик\n  text: 90 днів детально + 24 місяці агрегованих метрик\n- scope: Логи nginx, error logs\n  period: 30 днів\n  text: Логи nginx, error logs 30 днів\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Передача персональних даних до США та інших країн поза межами ЄС/ЄЕЗ здійснюється на підставі Стандартних\n    договірних положень ЄС (Імплементаційне рішення Комісії (ЄС) 2021/914)\nsubprocessors:\n  url: null\n  text: '5. З ким ми ділимося даними — субпроцесори Для надання послуг ми передаємо обмежені обсяги персональних\n    даних таким субпроцесорам:'\ndpa:\n  available: true\n  url: null\n  text: Копії відповідних DPA та SCC доступні на запит — пишіть на info@astroway.info .\ndeletion:\n  route: Запит на видалення на info@astroway.info\n\
  \  text: Щоб скористатися будь-яким із цих прав, надішліть запит на info@astroway.info . Ми відповімо протягом 30\n    днів.\nrights:\n- right: Доступ\n  text: Право на доступ (ст. 15 GDPR) — запросити копію всіх ваших персональних даних, які ми обробляємо.\n- right: Виправлення\n  text: Право на виправлення (ст. 16 GDPR) — вимагати виправлення неточних або застарілих даних.\n- right: Видалення\n  text: Право на видалення / «право бути забутим» (ст. 17 GDPR) — вимагати видалення даних з урахуванням законних\n    строків зберігання.\n- right: Обмеження обробки\n  text: Право на обмеження обробки (ст. 18 GDPR).\n- right: Переносимість\n  text: Право на переносимість даних (ст. 20 GDPR) — отримати свої дані у структурованому, машиночитному форматі.\n- right: Заперечення\n  text: Право заперечувати проти обробки (ст. 21 GDPR) — зокрема, проти прямого маркетингу.\n- right: Відкликання згоди\n  text: Право відкликати згоду в будь-який момент, коли обробка ґрунтується на згоді.\nsale_or_sharing:\n\
  \  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/astroway-info/privacy/astroway-info-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- dpa
- deletion
- rights
summary_line: 27 quoted statements, read from astroway-info's own page on 2026-11-09.
synthetic: false
tags:
- Astrology
- Horoscope
- Natal Chart
- Ukrainian
- OnlinePortal
---
