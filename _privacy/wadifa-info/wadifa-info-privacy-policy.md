---
api_specs:
- filename: wadifa-info-agenda-api-openapi.yml
  format: yaml
  label: Wadifa Info Agenda API
  slug: wadifa-info-agenda-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wadifa-info/openapi/wadifa-info-agenda-api-openapi.yml
- filename: wadifa-info-concours-api-openapi.yml
  format: yaml
  label: Wadifa Info Concours API
  slug: wadifa-info-concours-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wadifa-info/openapi/wadifa-info-concours-api-openapi.yml
- filename: wadifa-info-jours-feries-api-openapi.yml
  format: yaml
  label: Wadifa Info Jours Feries API
  slug: wadifa-info-jours-feries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wadifa-info/openapi/wadifa-info-jours-feries-api-openapi.yml
- filename: wadifa-info-salaires-api-openapi.yml
  format: yaml
  label: Wadifa Info Salaires API
  slug: wadifa-info-salaires-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wadifa-info/openapi/wadifa-info-salaires-api-openapi.yml
- filename: wadifa-info-vacances-scolaires-api-openapi.yml
  format: yaml
  label: Wadifa Info Vacances Scolaires API
  slug: wadifa-info-vacances-scolaires-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wadifa-info/openapi/wadifa-info-vacances-scolaires-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: الاسم، الهاتف، البريد الإلكتروني (اختياري)، المدينة، الملف المهني، ملف السيرة الذاتية وعنوان IP.
  - category: device
    text: عنوان IP، نوع المتصفح والجهاز، الصفحات التي تزورها ومدة التصفح، وملفات تعريف الارتباط (Cookies).
  - category: contact
    text: بريدك الإلكتروني، اللغة، المجال الذي تختاره (مثلاً الشهادة)، الصفحة التي اشتركت منها، وعنوان IP (للحماية من الإساءة).
  - category: behavioral
    text: ربطه باهتماماتك (المدينة، الشهادة، التخصص، اللغة) لنرسل لك مباريات مناسبة.
  deletion:
    route: Request deletion by emailing the site contact address
    text: طلب حذفها
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Email and push alerts
    text: إرسال التنبيهات التي اشتركت فيها (بريد إلكتروني أو إشعارات)، بما فيها رسالة ترحيب عند الاشتراك.
  - purpose: Forwarding CV to employers
    text: إيصال سيرتك الذاتية المودعة إلى المشغلين الباحثين عن تخصصك، كما هو موضح في صفحة الإيداع.
  - purpose: Site analytics and performance
    text: تحسين أداء الموقع وتحليل الإحصائيات (Google Analytics)
  - purpose: Advertising
    text: عرض الإعلانات عبر Google AdSense.
  retention:
  - period: null
    scope: Email while subscribed
    text: نحتفظ ببريدك الإلكتروني ما دمت مشتركاً
  - period: null
    scope: Deposited CV
    text: نحتفظ بالسيرة الذاتية المودعة إلى أن تطلب حذفها.
  rights:
  - right: access
    text: لك الحق في الولوج إلى معطياتك وتصحيحها والتعرض على معالجتها وطلب حذفها
  - right: unsubscribe
    text: كل رسالة بريد إلكتروني تحتوي على رابط «إلغاء الاشتراك» يعمل بنقرة واحدة.
  - right: complaint to regulator
    text: ويمكنك أيضاً اللجوء إلى اللجنة الوطنية لمراقبة حماية المعطيات ذات الطابع الشخصي (CNDP).
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: لا نبيع بياناتك.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Wadifa Info
provenance_date: '2026-11-10'
provider_name: Wadifa Info
provider_slug: wadifa-info
slug: wadifa-info-privacy-policy
source_date: '2026-11-10'
source_filename: wadifa-info-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.wadifa-info.com/index/PrivacyPolicy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Wadifa Info\naid: wadifa-info\nurl: https://www.wadifa-info.com/index/PrivacyPolicy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: الاسم، الهاتف، البريد الإلكتروني (اختياري)، المدينة، الملف المهني، ملف السيرة الذاتية وعنوان IP.\n- category: device\n  text: عنوان IP، نوع المتصفح والجهاز، الصفحات التي تزورها ومدة التصفح، وملفات تعريف الارتباط (Cookies).\n- category: contact\n  text: بريدك الإلكتروني، اللغة، المجال الذي تختاره (مثلاً الشهادة)، الصفحة التي اشتركت منها، وعنوان IP (للحماية\n    من الإساءة).\n- category: behavioral\n  text: ربطه\
  \ باهتماماتك (المدينة، الشهادة، التخصص، اللغة) لنرسل لك مباريات مناسبة.\npurposes:\n- purpose: Email and push alerts\n  text: إرسال التنبيهات التي اشتركت فيها (بريد إلكتروني أو إشعارات)، بما فيها رسالة ترحيب عند الاشتراك.\n- purpose: Forwarding CV to employers\n  text: إيصال سيرتك الذاتية المودعة إلى المشغلين الباحثين عن تخصصك، كما هو موضح في صفحة الإيداع.\n- purpose: Site analytics and performance\n  text: تحسين أداء الموقع وتحليل الإحصائيات (Google Analytics)\n- purpose: Advertising\n  text: عرض الإعلانات عبر Google AdSense.\nretention:\n- scope: Email while subscribed\n  period: null\n  text: نحتفظ ببريدك الإلكتروني ما دمت مشتركاً\n- scope: Deposited CV\n  period: null\n  text: نحتفظ بالسيرة الذاتية المودعة إلى أن تطلب حذفها.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion by emailing the site contact address\n  text: طلب حذفها\nrights:\n- right: access\n  text: لك الحق\
  \ في الولوج إلى معطياتك وتصحيحها والتعرض على معالجتها وطلب حذفها\n- right: unsubscribe\n  text: كل رسالة بريد إلكتروني تحتوي على رابط «إلغاء الاشتراك» يعمل بنقرة واحدة.\n- right: complaint to regulator\n  text: ويمكنك أيضاً اللجوء إلى اللجنة الوطنية لمراقبة حماية المعطيات ذات الطابع الشخصي (CNDP).\nsale_or_sharing:\n  stance: prohibited\n  text: لا نبيع بياناتك.\n"
source_yaml_url: https://artifacts.apis.io/wadifa-info/privacy/wadifa-info-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 15 quoted statements, read from Wadifa Info's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Job
- Public Sector
- Morocco
- Open Data
- Salaries
- Government
---
