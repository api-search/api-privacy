---
api_specs:
- filename: vigotime-com-account-api-openapi.yml
  format: yaml
  label: vigotime-com Account API
  slug: vigotime-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-account-api-openapi.yml
- filename: vigotime-com-api-tokens-api-openapi.yml
  format: yaml
  label: vigotime-com API Tokens API
  slug: vigotime-com-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-api-tokens-api-openapi.yml
- filename: vigotime-com-health-api-openapi.yml
  format: yaml
  label: vigotime-com Health API
  slug: vigotime-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-health-api-openapi.yml
- filename: vigotime-com-signup-api-openapi.yml
  format: yaml
  label: vigotime-com Signup API
  slug: vigotime-com-signup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-signup-api-openapi.yml
- filename: vigotime-com-stateless-solve-api-openapi.yml
  format: yaml
  label: vigotime-com Stateless Solve API
  slug: vigotime-com-stateless-solve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vigotime-com/openapi/vigotime-com-stateless-solve-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, Vorname
  - category: contact
    text: E-Mail-Adresse
  - category: financial
    text: Firmenname und Rechnungsadresse
  - category: device
    text: IP-Adresse
  - category: device
    text: Geräte-Identifikation (Mobile App)
  - category: behavioral
    text: Arbeitszeiterfassungen
  - category: other
    text: Urlaubsanträge und Abwesenheiten
  deletion:
    route: account deletion, or rights request to the contact address
    text: Bei Löschung des Benutzerkontos werden alle personenbezogenen Daten innerhalb von 30 Tagen gelöscht, soweit keine gesetzlichen Aufbewahrungspflichten entgegenstehen.
  dpa:
    available: true
    text: Mit Google besteht ein Auftragsverarbeitungsvertrag gemäß Art. 28 DSGVO.
    url: null
  purposes:
  - purpose: Platform operation
    text: Bereitstellung und Betrieb der vigo time -Plattform (Web-App, Mobile App, API)
  - purpose: Payments and subscriptions
    text: Abwicklung von Zahlungen und Abonnements über Stripe
  - purpose: Marketing emails
    text: Versand von Marketing-E-Mails und Newslettern (sofern eingewilligt)
  - purpose: Website analytics
    text: Analyse und Verbesserung unserer Dienste
  residency:
  - region: EU (europe-west1, Belgium)
    text: Die Daten werden in Rechenzentren innerhalb der EU (Region europe-west1, Belgien) gespeichert.
  retention:
  - period: 6 bzw. 10 Jahre
    scope: Contract data
    text: (i.d.R. 6 bzw. 10 Jahre gemäß HGB/AO)
  - period: 90 Tagen
    scope: Usage data after contract end
    text: Nach Vertragsende werden die Daten innerhalb von 90 Tagen gelöscht, sofern keine Aufbewahrungspflichten bestehen.
  - period: 30 Tagen
    scope: Account deletion
    text: Bei Löschung des Benutzerkontos werden alle personenbezogenen Daten innerhalb von 30 Tagen gelöscht, soweit keine gesetzlichen Aufbewahrungspflichten entgegenstehen.
  - period: 14 Monaten
    scope: Google Analytics data
    text: Die erfassten Daten werden nach 14 Monaten automatisch gelöscht.
  rights:
  - right: Access
    text: Sie können Auskunft über Ihre bei uns gespeicherten Daten verlangen.
  - right: Rectification
    text: Sie können die Berichtigung unrichtiger Daten verlangen.
  - right: Erasure
    text: Sie können die Löschung Ihrer Daten verlangen, sofern keine gesetzlichen Aufbewahrungspflichten entgegenstehen.
  - right: Restriction
    text: Sie können die Einschränkung der Verarbeitung Ihrer Daten verlangen.
  - right: Portability
    text: Sie können verlangen, Ihre Daten in einem strukturierten, gängigen Format zu erhalten.
  - right: Objection
    text: Sie können der Verarbeitung Ihrer Daten widersprechen, die auf berechtigten Interessen basiert.
  - right: Withdraw consent
    text: Eine erteilte Einwilligung können Sie jederzeit widerrufen.
  role:
    text: 'Verantwortlicher im Sinne der Datenschutz-Grundverordnung (DSGVO) und anderer datenschutzrechtlicher Bestimmungen ist: peppergrid UG (haftungsbeschränkt)'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: EU-US Data Privacy Framework (DPF) – Stripe, Inc. und Google LLC sind unter dem DPF zertifiziert, was ein angemessenes Datenschutzniveau gemäß Art. 45 DSGVO gewährleistet.
  - mechanism: SCC
    text: Wo kein Angemessenheitsbeschluss vorliegt, werden EU-Standardvertragsklauseln verwendet.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: vigotime-com
provenance_date: '2026-11-10'
provider_name: vigotime-com
provider_slug: vigotime-com
slug: vigotime-com-privacy-policy
source_date: '2026-11-10'
source_filename: vigotime-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vigotime.com/de/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: vigotime-com\naid: vigotime-com\nurl: https://vigotime.com/de/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Verantwortlicher im Sinne der Datenschutz-Grundverordnung (DSGVO) und anderer datenschutzrechtlicher Bestimmungen\n    ist: peppergrid UG (haftungsbeschränkt)'\ndata_categories:\n- category: identifying\n  text: Name, Vorname\n- category: contact\n  text: E-Mail-Adresse\n- category: financial\n  text: Firmenname und Rechnungsadresse\n- category: device\n  text: IP-Adresse\n- category: device\n  text: Geräte-Identifikation (Mobile App)\n- category: behavioral\n  text:\
  \ Arbeitszeiterfassungen\n- category: other\n  text: Urlaubsanträge und Abwesenheiten\npurposes:\n- purpose: Platform operation\n  text: Bereitstellung und Betrieb der vigo time -Plattform (Web-App, Mobile App, API)\n- purpose: Payments and subscriptions\n  text: Abwicklung von Zahlungen und Abonnements über Stripe\n- purpose: Marketing emails\n  text: Versand von Marketing-E-Mails und Newslettern (sofern eingewilligt)\n- purpose: Website analytics\n  text: Analyse und Verbesserung unserer Dienste\nretention:\n- scope: Contract data\n  period: 6 bzw. 10 Jahre\n  text: (i.d.R. 6 bzw. 10 Jahre gemäß HGB/AO)\n- scope: Usage data after contract end\n  period: 90 Tagen\n  text: Nach Vertragsende werden die Daten innerhalb von 90 Tagen gelöscht, sofern keine Aufbewahrungspflichten\n    bestehen.\n- scope: Account deletion\n  period: 30 Tagen\n  text: Bei Löschung des Benutzerkontos werden alle personenbezogenen Daten innerhalb von 30 Tagen gelöscht, soweit\n    keine gesetzlichen Aufbewahrungspflichten\
  \ entgegenstehen.\n- scope: Google Analytics data\n  period: 14 Monaten\n  text: Die erfassten Daten werden nach 14 Monaten automatisch gelöscht.\nresidency:\n- region: EU (europe-west1, Belgium)\n  text: Die Daten werden in Rechenzentren innerhalb der EU (Region europe-west1, Belgien) gespeichert.\ntransfers:\n- mechanism: DPF\n  text: EU-US Data Privacy Framework (DPF) – Stripe, Inc. und Google LLC sind unter dem DPF zertifiziert, was ein\n    angemessenes Datenschutzniveau gemäß Art. 45 DSGVO gewährleistet.\n- mechanism: SCC\n  text: Wo kein Angemessenheitsbeschluss vorliegt, werden EU-Standardvertragsklauseln verwendet.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Mit Google besteht ein Auftragsverarbeitungsvertrag gemäß Art. 28 DSGVO.\ndeletion:\n  route: account deletion, or rights request to the contact address\n  text: Bei Löschung des Benutzerkontos werden alle personenbezogenen Daten innerhalb von 30 Tagen gelöscht, soweit\n    keine\
  \ gesetzlichen Aufbewahrungspflichten entgegenstehen.\nrights:\n- right: Access\n  text: Sie können Auskunft über Ihre bei uns gespeicherten Daten verlangen.\n- right: Rectification\n  text: Sie können die Berichtigung unrichtiger Daten verlangen.\n- right: Erasure\n  text: Sie können die Löschung Ihrer Daten verlangen, sofern keine gesetzlichen Aufbewahrungspflichten entgegenstehen.\n- right: Restriction\n  text: Sie können die Einschränkung der Verarbeitung Ihrer Daten verlangen.\n- right: Portability\n  text: Sie können verlangen, Ihre Daten in einem strukturierten, gängigen Format zu erhalten.\n- right: Objection\n  text: Sie können der Verarbeitung Ihrer Daten widersprechen, die auf berechtigten Interessen basiert.\n- right: Withdraw consent\n  text: Eine erteilte Einwilligung können Sie jederzeit widerrufen.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/vigotime-com/privacy/vigotime-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
summary_line: 28 quoted statements, read from vigotime-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Time Tracking
- Workforce Management
- Automation
---
