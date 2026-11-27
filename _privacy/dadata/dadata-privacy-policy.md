---
api_specs:
- filename: dadata-clean-openapi-generated.yml
  format: yaml
  label: DaData API-методы API
  slug: clean-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadata/openapi/_ae-authored/dadata-clean-openapi-generated.yml
- filename: dadata-core-openapi-generated.yml
  format: yaml
  label: DaData core API
  slug: core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadata/openapi/_ae-authored/dadata-core-openapi-generated.yml
- filename: dadata-suggest-openapi-generated.yml
  format: yaml
  label: DaData API-методы API
  slug: suggest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dadata/openapi/_ae-authored/dadata-suggest-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Имя, фамилия. Номер телефона. Адрес электронной почты.
  - category: device
    text: 'IP-адрес. Индивидуальный сетевой номер устройства: MAC-адрес, ID.'
  - category: behavioral
    text: Информация о браузере, операционной системе, времени доступа, времени посещения, поисковых запросах.
  - category: financial
    text: 'Идентификаторы платежных средств: последние 4 цифры номера банковской карты.'
  - category: professional
    text: Место работы и должность.
  - category: communication
    text: История взаимодействия с Компанией и ее сервисами.
  deletion:
    route: Письмо на info@dadata.ru
    text: 'Напишите на почту info@dadata.ru, и мы: расскажем, какие ваши данные используем и каким образом; исправим и обновим ваши данные; удалим данные, если с ними что-то не так'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Технические функции и безопасная работа Ресурсов
    text: Технические вещи типа IP-адреса и куков, чтобы сайт адекватно работал.
  - purpose: Регистрация и личный кабинет, оплата подписки
    text: Регистрация и авторизация пользователя в клиентском сервисе DaData.
  - purpose: Маркетинговые рассылки с согласия
    text: Получение новостей, информации о продуктах, мероприятиях или услугах, проводимых конкурсах, скидках и специальных предложениях.
  - purpose: Поддержка пользователей
    text: Поддержка по вопросам работы Ресурсов и клиентских сервисов Компании.
  - purpose: Рассмотрение откликов соискателей
    text: Обращения по поводу открытых вакансий
  residency:
  - region: Россия
    text: Храним персданные на серверах в России. Этого требует закон.
  retention:
  - period: Не более 10 лет
    scope: Технические данные и cookies
    text: Не более 10 лет с даты последнего посещения Ресурсов или последнего использования услуг, перечисленных в договоре .
  - period: Пока действует договор
    scope: Данные аккаунта
    text: Пока действует договор на использование DaData.
  - period: Не более 3 лет
    scope: Данные соискателей
    text: Не более 3 лет с даты обращения.
  rights:
  - right: Запрос информации об обработке
    text: запросить информацию, касающуюся обработки их персональных данных
  - right: Уточнение, уничтожение или блокирование
    text: потребовать уточнения, уничтожения или блокирования их персональных данных
  - right: Отзыв согласия
    text: отозвать предоставленные Компании согласия на обработку персональных данных
  - right: Отказ от прямых контактов
    text: отказаться от обработки персональных данных для осуществления прямых контактов (в том числе, в целях продвижения товаров, работ, услуг)
  - right: Обжалование
    text: обжаловать действия Компании в административном или судебном порядке
  role:
    text: Политика конфиденциальности определяет, как ООО «Дейта Кью» обрабатывает и защищает персональные данные пользователей веб-сайтов
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DaData
provenance_date: '2026-11-09'
provider_name: DaData
provider_slug: dadata
slug: dadata-privacy-policy
source_date: '2026-11-09'
source_filename: dadata-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dadata.ru/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DaData\naid: dadata\nurl: https://dadata.ru/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Политика конфиденциальности определяет, как ООО «Дейта Кью» обрабатывает и защищает персональные данные\n    пользователей веб-сайтов\ndata_categories:\n- category: identifying\n  text: Имя, фамилия. Номер телефона. Адрес электронной почты.\n- category: device\n  text: 'IP-адрес. Индивидуальный сетевой номер устройства: MAC-адрес, ID.'\n- category: behavioral\n  text: Информация о браузере, операционной системе, времени доступа, времени посещения, поисковых запросах.\n- category: financial\n\
  \  text: 'Идентификаторы платежных средств: последние 4 цифры номера банковской карты.'\n- category: professional\n  text: Место работы и должность.\n- category: communication\n  text: История взаимодействия с Компанией и ее сервисами.\npurposes:\n- purpose: Технические функции и безопасная работа Ресурсов\n  text: Технические вещи типа IP-адреса и куков, чтобы сайт адекватно работал.\n- purpose: Регистрация и личный кабинет, оплата подписки\n  text: Регистрация и авторизация пользователя в клиентском сервисе DaData.\n- purpose: Маркетинговые рассылки с согласия\n  text: Получение новостей, информации о продуктах, мероприятиях или услугах, проводимых конкурсах, скидках и специальных\n    предложениях.\n- purpose: Поддержка пользователей\n  text: Поддержка по вопросам работы Ресурсов и клиентских сервисов Компании.\n- purpose: Рассмотрение откликов соискателей\n  text: Обращения по поводу открытых вакансий\nretention:\n- scope: Технические данные и cookies\n  period: Не более 10 лет\n \
  \ text: Не более 10 лет с даты последнего посещения Ресурсов или последнего использования услуг, перечисленных в\n    договоре .\n- scope: Данные аккаунта\n  period: Пока действует договор\n  text: Пока действует договор на использование DaData.\n- scope: Данные соискателей\n  period: Не более 3 лет\n  text: Не более 3 лет с даты обращения.\nresidency:\n- region: Россия\n  text: Храним персданные на серверах в России. Этого требует закон.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Письмо на info@dadata.ru\n  text: 'Напишите на почту info@dadata.ru, и мы: расскажем, какие ваши данные используем и каким образом; исправим\n    и обновим ваши данные; удалим данные, если с ними что-то не так'\nrights:\n- right: Запрос информации об обработке\n  text: запросить информацию, касающуюся обработки их персональных данных\n- right: Уточнение, уничтожение или блокирование\n  text: потребовать уточнения, уничтожения\
  \ или блокирования их персональных данных\n- right: Отзыв согласия\n  text: отозвать предоставленные Компании согласия на обработку персональных данных\n- right: Отказ от прямых контактов\n  text: отказаться от обработки персональных данных для осуществления прямых контактов (в том числе, в целях продвижения\n    товаров, работ, услуг)\n- right: Обжалование\n  text: обжаловать действия Компании в административном или судебном порядке\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dadata/privacy/dadata-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 22 quoted statements, read from DaData's own page on 2026-11-09.
synthetic: false
tags:
- Data
- Russian
- Data Enrichment
- AddressStandardization
---
