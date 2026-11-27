---
api_specs:
- filename: prro-cloud-billing-api-openapi.yml
  format: yaml
  label: prro-cloud Billing API
  slug: prro-cloud-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prro-cloud/openapi/prro-cloud-billing-api-openapi.yml
- filename: prro-cloud-fiscal-api-openapi.yml
  format: yaml
  label: prro-cloud Fiscal API
  slug: prro-cloud-fiscal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prro-cloud/openapi/prro-cloud-fiscal-api-openapi.yml
- filename: prro-cloud-system-api-openapi.yml
  format: yaml
  label: prro-cloud System API
  slug: prro-cloud-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prro-cloud/openapi/prro-cloud-system-api-openapi.yml
- filename: prro-cloud-webhooks-api-openapi.yml
  format: yaml
  label: prro-cloud Webhooks API
  slug: prro-cloud-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prro-cloud/openapi/prro-cloud-webhooks-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Дані облікового запису: адреса електронної пошти, найменування суб''єкта господарювання, код ЄДРПОУ / РНОКПП, контактні дані, зазначені під час реєстрації.'
  - category: financial
    text: 'Фіскальні дані: зміст чеків (найменування товарів і послуг, ціни, суми), фіскальні номери ПРРО та чеків, дані змін і Z-звітів'
  - category: other
    text: 'Дані КЕП: кваліфіковані сертифікати (публічна частина) та зашифровані контейнери ключів, завантажені користувачем для підписання фіскальних документів.'
  - category: device
    text: 'Технічні дані: IP-адреса, дата й час запитів, ідентифікатори API-ключів, журнали технічних подій.'
  - category: communication
    text: 'Дані звернень: вміст листів, надісланих на нашу адресу електронної пошти, та контактні дані відправника.'
  deletion:
    route: Email info@prro.cloud
    text: Для реалізації цих прав звертайтеся на info@prro.cloud .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Fiscalization services
    text: надання послуг фіскалізації відповідно до договору
  - purpose: Legal compliance
    text: виконання вимог законодавства (зокрема податкового)
  - purpose: Security and stability
    text: забезпечення безпеки та стабільності Сервісу
  - purpose: Communication and support
    text: комунікації з користувачами та підтримки
  - purpose: Billing
    text: виставлення рахунків і обліку розрахунків
  retention:
  - period: протягом дії договору
    scope: Account data
    text: Дані облікового запису зберігаються протягом дії договору та видаляються або знеособлюються після його припинення
  - period: null
    scope: Fiscal data
    text: Фіскальні дані зберігаються не менше строків, установлених податковим законодавством України для первинних документів.
  - period: 12 місяців
    scope: Technical logs
    text: Технічні журнали зберігаються не довше 12 місяців, якщо інше не потрібне для розслідування інцидентів безпеки.
  rights:
  - right: Access
    text: отримувати доступ до своїх персональних даних та інформацію про їх обробку
  - right: Rectification
    text: вимагати виправлення неточних даних
  - right: Erasure
    text: вимагати видалення даних, якщо вони обробляються неправомірно
  - right: Object and withdraw consent
    text: заперечувати проти обробки та відкликати згоду на обробку, якщо обробка ґрунтується на згоді
  - right: Complaint
    text: звертатися зі скаргою до Уповноваженого Верховної Ради України з прав людини або до суду
  role:
    text: Володільцем персональних даних є суб'єкт господарювання, реквізити якого зазначено в розділі 16 Договору публічної оферти
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Ми не продаємо персональні дані та не передаємо їх третім особам у маркетингових цілях.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: prro-cloud
provenance_date: '2026-11-10'
provider_name: prro-cloud
provider_slug: prro-cloud
slug: prro-cloud-privacy-policy
source_date: '2026-11-10'
source_filename: prro-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://prro.cloud/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: prro-cloud\naid: prro-cloud\nurl: https://prro.cloud/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Володільцем персональних даних є суб'єкт господарювання, реквізити якого зазначено в розділі 16 Договору\n    публічної оферти\ndata_categories:\n- category: identifying\n  text: 'Дані облікового запису: адреса електронної пошти, найменування суб''єкта господарювання, код ЄДРПОУ / РНОКПП,\n    контактні дані, зазначені під час реєстрації.'\n- category: financial\n  text: 'Фіскальні дані: зміст чеків (найменування товарів і послуг, ціни, суми), фіскальні номери ПРРО та чеків,\n    дані\
  \ змін і Z-звітів'\n- category: other\n  text: 'Дані КЕП: кваліфіковані сертифікати (публічна частина) та зашифровані контейнери ключів, завантажені користувачем\n    для підписання фіскальних документів.'\n- category: device\n  text: 'Технічні дані: IP-адреса, дата й час запитів, ідентифікатори API-ключів, журнали технічних подій.'\n- category: communication\n  text: 'Дані звернень: вміст листів, надісланих на нашу адресу електронної пошти, та контактні дані відправника.'\npurposes:\n- purpose: Fiscalization services\n  text: надання послуг фіскалізації відповідно до договору\n- purpose: Legal compliance\n  text: виконання вимог законодавства (зокрема податкового)\n- purpose: Security and stability\n  text: забезпечення безпеки та стабільності Сервісу\n- purpose: Communication and support\n  text: комунікації з користувачами та підтримки\n- purpose: Billing\n  text: виставлення рахунків і обліку розрахунків\nretention:\n- scope: Account data\n  period: протягом дії договору\n  text: Дані\
  \ облікового запису зберігаються протягом дії договору та видаляються або знеособлюються після його припинення\n- scope: Fiscal data\n  period: null\n  text: Фіскальні дані зберігаються не менше строків, установлених податковим законодавством України для первинних\n    документів.\n- scope: Technical logs\n  period: 12 місяців\n  text: Технічні журнали зберігаються не довше 12 місяців, якщо інше не потрібне для розслідування інцидентів безпеки.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email info@prro.cloud\n  text: Для реалізації цих прав звертайтеся на info@prro.cloud .\nrights:\n- right: Access\n  text: отримувати доступ до своїх персональних даних та інформацію про їх обробку\n- right: Rectification\n  text: вимагати виправлення неточних даних\n- right: Erasure\n  text: вимагати видалення даних, якщо вони обробляються неправомірно\n- right: Object and withdraw consent\n  text: заперечувати\
  \ проти обробки та відкликати згоду на обробку, якщо обробка ґрунтується на згоді\n- right: Complaint\n  text: звертатися зі скаргою до Уповноваженого Верховної Ради України з прав людини або до суду\nsale_or_sharing:\n  stance: prohibited\n  text: Ми не продаємо персональні дані та не передаємо їх третім особам у маркетингових цілях.\n"
source_yaml_url: https://artifacts.apis.io/prro-cloud/privacy/prro-cloud-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from prro-cloud's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fiscal
- Ukraine
---
