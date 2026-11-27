---
api_specs:
- filename: kolayik-approval-process-api-openapi.yml
  format: yaml
  label: KolayIK Approval Process API
  slug: kolayik-approval-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-approval-process-api-openapi.yml
- filename: kolayik-calendar-api-openapi.yml
  format: yaml
  label: KolayIK Calendar API
  slug: kolayik-calendar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-calendar-api-openapi.yml
- filename: kolayik-expense-api-openapi.yml
  format: yaml
  label: KolayIK Expense API
  slug: kolayik-expense-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-expense-api-openapi.yml
- filename: kolayik-leave-api-openapi.yml
  format: yaml
  label: KolayIK Leave API
  slug: kolayik-leave-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-leave-api-openapi.yml
- filename: kolayik-payroll-api-openapi.yml
  format: yaml
  label: KolayIK Payroll API
  slug: kolayik-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-payroll-api-openapi.yml
- filename: kolayik-person-api-openapi.yml
  format: yaml
  label: KolayIK Person API
  slug: kolayik-person-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-person-api-openapi.yml
- filename: kolayik-profile-api-openapi.yml
  format: yaml
  label: KolayIK Profile API
  slug: kolayik-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-profile-api-openapi.yml
- filename: kolayik-timelog-api-openapi.yml
  format: yaml
  label: KolayIK Timelog API
  slug: kolayik-timelog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-timelog-api-openapi.yml
- filename: kolayik-training-api-openapi.yml
  format: yaml
  label: KolayIK Training API
  slug: kolayik-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-training-api-openapi.yml
- filename: kolayik-transaction-api-openapi.yml
  format: yaml
  label: KolayIK Transaction API
  slug: kolayik-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-transaction-api-openapi.yml
- filename: kolayik-unit-api-openapi.yml
  format: yaml
  label: KolayIK Unit API
  slug: kolayik-unit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kolayik/openapi/kolayik-unit-api-openapi.yml
claim_count: 8
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Kimlik Bilgileri: Ad-soyadı'
  - category: contact
    text: 'İletişim Bilgileri: Telefon numarası, e-posta adresi'
  - category: professional
    text: 'Diğer Bilgiler: Teklif talep ettiğiniz şirketin adı, çalışan sayısı, şirketteki unvanınız ve talep amacınız.'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  residency:
  - region: outside Türkiye
    text: sunucuları yurt dışında bulunan bulut tabanlı uygulamalar, bulut çözümleri ve yedekleme sistemlerinde işlenilmek
  rights:
  - right: Kanun’un 11. Maddesi kapsamındaki haklar
    text: Kanun’un 11. Maddesi kapsamında belirtilen haklarınıza ilişkin taleplerinizi
  - right: Written or KEP request
    text: KEP adresinizi kullanmak suretiyle KEP adresine elektronik olarak iletebilirsiniz.
  role:
    text: Kolay Yazılım Anonim Şirketi (“Kolay Yazılım”, “Şirket” veya “Veri Sorumlusu”) kişisel verilerin korunmasına önem vermektedir.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Kanun’da sayılı uygun güvencelerden olan standart sözleşmeler suretiyle
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: KolayIK
provenance_date: '2026-11-09'
provider_name: KolayIK
provider_slug: kolayik
slug: kolayik-privacy-policy
source_date: '2026-11-09'
source_filename: kolayik-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://kolayik.com/internet-sitesi-kvkk
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: KolayIK\naid: kolayik\nurl: https://kolayik.com/internet-sitesi-kvkk\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Kolay Yazılım Anonim Şirketi (“Kolay Yazılım”, “Şirket” veya “Veri Sorumlusu”) kişisel verilerin korunmasına\n    önem vermektedir.\ndata_categories:\n- category: identifying\n  text: 'Kimlik Bilgileri: Ad-soyadı'\n- category: contact\n  text: 'İletişim Bilgileri: Telefon numarası, e-posta adresi'\n- category: professional\n  text: 'Diğer Bilgiler: Teklif talep ettiğiniz şirketin adı, çalışan sayısı, şirketteki unvanınız ve talep amacınız.'\npurposes: []\nretention: []\nresidency:\n\
  - region: outside Türkiye\n  text: sunucuları yurt dışında bulunan bulut tabanlı uygulamalar, bulut çözümleri ve yedekleme sistemlerinde işlenilmek\ntransfers:\n- mechanism: SCC\n  text: Kanun’da sayılı uygun güvencelerden olan standart sözleşmeler suretiyle\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Kanun’un 11. Maddesi kapsamındaki haklar\n  text: Kanun’un 11. Maddesi kapsamında belirtilen haklarınıza ilişkin taleplerinizi\n- right: Written or KEP request\n  text: KEP adresinizi kullanmak suretiyle KEP adresine elektronik olarak iletebilirsiniz.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kolayik/privacy/kolayik-privacy-policy.yml
stated_fields:
- role
- data_categories
- residency
- transfers
- rights
summary_line: 8 quoted statements, read from KolayIK's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Human Resources
- Payroll
- HCM
- Employee Management
- Time and Attendance
- Applicant Tracking
- Software-as-a-Service
- Turkey
---
