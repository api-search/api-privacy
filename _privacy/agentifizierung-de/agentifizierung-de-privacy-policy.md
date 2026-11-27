---
api_specs:
- filename: agentifizierung-de-a2a-api-openapi.yml
  format: yaml
  label: Agentifizierung A2a API
  slug: agentifizierung-de-a2a-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentifizierung-de/openapi/agentifizierung-de-a2a-api-openapi.yml
- filename: agentifizierung-de-index-md-api-openapi.yml
  format: yaml
  label: Agentifizierung Index.md API
  slug: agentifizierung-de-index-md-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentifizierung-de/openapi/agentifizierung-de-index-md-api-openapi.yml
- filename: agentifizierung-de-llms-full-txt-api-openapi.yml
  format: yaml
  label: Agentifizierung Llms Full.txt API
  slug: agentifizierung-de-llms-full-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentifizierung-de/openapi/agentifizierung-de-llms-full-txt-api-openapi.yml
- filename: agentifizierung-de-llms-txt-api-openapi.yml
  format: yaml
  label: Agentifizierung Llms.txt API
  slug: agentifizierung-de-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentifizierung-de/openapi/agentifizierung-de-llms-txt-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Kontaktdaten (Name, E-Mail-Adresse, Telefonnummer)
  - category: professional
    text: Unternehmensdaten (Firmenname, Position)
  - category: communication
    text: Kommunikationsdaten (Nachrichten, Anfragen über unsere Formulare)
  - category: device
    text: Server-Logdaten (IP-Adresse, Datum/Uhrzeit des Zugriffs, abgerufene Seite, Browser-/Geräteinformationen)
  deletion:
    route: Email to datenschutz@agentifizierung.de
    text: 'Zur Ausübung Ihrer Rechte kontaktieren Sie uns unter: datenschutz@agentifizierung.de'
  dpa:
    available: true
    text: Mit Vercel besteht ein Vertrag zur Auftragsverarbeitung (Art. 28 DSGVO).
    url: null
  purposes:
  - purpose: Request handling and communication
    text: Bearbeitung von Anfragen und Kommunikation
  - purpose: Website operation and security
    text: Bereitstellung und sicherer Betrieb unserer Website
  - purpose: Contract performance
    text: Vertragsabwicklung und Kundenbetreuung
  - purpose: Audience measurement
    text: Cookielose, anonyme Reichweitenmessung zur Verbesserung unseres Angebots (nur mit Einwilligung)
  residency:
  - region: European Union
    text: Die Auslieferung erfolgt über eine Server-Region innerhalb der Europäischen Union (Frankfurt am Main, Deutschland).
  retention:
  - period: 3 Jahre nach letztem Kontakt
    scope: Contact requests
    text: 'Kontaktanfragen: 3 Jahre nach letztem Kontakt'
  - period: 10 Jahre
    scope: Contract data
    text: 'Vertragsdaten: 10 Jahre (steuer- und handelsrechtliche Aufbewahrungspflicht)'
  - period: 7 Tage
    scope: Server logs
    text: 'Server-Logs: 7 Tage'
  - period: 180 Tage
    scope: Consent cookie
    text: 'Speicherdauer: 180 Tage'
  rights:
  - right: Access
    text: 'Auskunftsrecht (Art. 15 DSGVO): Information über verarbeitete Daten'
  - right: Rectification
    text: 'Berichtigungsrecht (Art. 16 DSGVO): Korrektur unrichtiger Daten'
  - right: Erasure
    text: 'Löschungsrecht (Art. 17 DSGVO): Löschung Ihrer Daten'
  - right: Restriction
    text: 'Einschränkungsrecht (Art. 18 DSGVO): Einschränkung der Verarbeitung'
  - right: Portability
    text: 'Datenübertragbarkeit (Art. 20 DSGVO): Übertragung Ihrer Daten'
  - right: Objection
    text: 'Widerspruchsrecht (Art. 21 DSGVO): Widerspruch gegen Verarbeitung'
  - right: Withdraw consent
    text: 'Widerruf der Einwilligung: Jederzeit mit Wirkung für die Zukunft möglich'
  role:
    text: 'Verantwortlicher für die Datenverarbeitung auf dieser Website ist: yawusa UG (haftungsbeschränkt)'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Die Übermittlung ist über die EU-Standardvertragsklauseln (SCC) sowie das EU-US Data Privacy Framework abgesichert
  - mechanism: DPF
    text: Die Übermittlung ist über die EU-Standardvertragsklauseln (SCC) sowie das EU-US Data Privacy Framework abgesichert
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentifizierung
provenance_date: '2026-11-09'
provider_name: Agentifizierung
provider_slug: agentifizierung-de
slug: agentifizierung-de-privacy-policy
source_date: '2026-11-09'
source_filename: agentifizierung-de-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agentifizierung.de/datenschutz
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentifizierung\naid: agentifizierung-de\nurl: https://www.agentifizierung.de/datenschutz\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Verantwortlicher für die Datenverarbeitung auf dieser Website ist: yawusa UG (haftungsbeschränkt)'\ndata_categories:\n- category: contact\n  text: Kontaktdaten (Name, E-Mail-Adresse, Telefonnummer)\n- category: professional\n  text: Unternehmensdaten (Firmenname, Position)\n- category: communication\n  text: Kommunikationsdaten (Nachrichten, Anfragen über unsere Formulare)\n- category: device\n  text: Server-Logdaten (IP-Adresse, Datum/Uhrzeit des Zugriffs,\
  \ abgerufene Seite, Browser-/Geräteinformationen)\npurposes:\n- purpose: Request handling and communication\n  text: Bearbeitung von Anfragen und Kommunikation\n- purpose: Website operation and security\n  text: Bereitstellung und sicherer Betrieb unserer Website\n- purpose: Contract performance\n  text: Vertragsabwicklung und Kundenbetreuung\n- purpose: Audience measurement\n  text: Cookielose, anonyme Reichweitenmessung zur Verbesserung unseres Angebots (nur mit Einwilligung)\nretention:\n- scope: Contact requests\n  period: 3 Jahre nach letztem Kontakt\n  text: 'Kontaktanfragen: 3 Jahre nach letztem Kontakt'\n- scope: Contract data\n  period: 10 Jahre\n  text: 'Vertragsdaten: 10 Jahre (steuer- und handelsrechtliche Aufbewahrungspflicht)'\n- scope: Server logs\n  period: 7 Tage\n  text: 'Server-Logs: 7 Tage'\n- scope: Consent cookie\n  period: 180 Tage\n  text: 'Speicherdauer: 180 Tage'\nresidency:\n- region: European Union\n  text: Die Auslieferung erfolgt über eine Server-Region innerhalb\
  \ der Europäischen Union (Frankfurt am Main, Deutschland).\ntransfers:\n- mechanism: SCC\n  text: Die Übermittlung ist über die EU-Standardvertragsklauseln (SCC) sowie das EU-US Data Privacy Framework abgesichert\n- mechanism: DPF\n  text: Die Übermittlung ist über die EU-Standardvertragsklauseln (SCC) sowie das EU-US Data Privacy Framework abgesichert\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Mit Vercel besteht ein Vertrag zur Auftragsverarbeitung (Art. 28 DSGVO).\ndeletion:\n  route: Email to datenschutz@agentifizierung.de\n  text: 'Zur Ausübung Ihrer Rechte kontaktieren Sie uns unter: datenschutz@agentifizierung.de'\nrights:\n- right: Access\n  text: 'Auskunftsrecht (Art. 15 DSGVO): Information über verarbeitete Daten'\n- right: Rectification\n  text: 'Berichtigungsrecht (Art. 16 DSGVO): Korrektur unrichtiger Daten'\n- right: Erasure\n  text: 'Löschungsrecht (Art. 17 DSGVO): Löschung Ihrer Daten'\n- right: Restriction\n  text: 'Einschränkungsrecht\
  \ (Art. 18 DSGVO): Einschränkung der Verarbeitung'\n- right: Portability\n  text: 'Datenübertragbarkeit (Art. 20 DSGVO): Übertragung Ihrer Daten'\n- right: Objection\n  text: 'Widerspruchsrecht (Art. 21 DSGVO): Widerspruch gegen Verarbeitung'\n- right: Withdraw consent\n  text: 'Widerruf der Einwilligung: Jederzeit mit Wirkung für die Zukunft möglich'\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentifizierung-de/privacy/agentifizierung-de-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Agentifizierung's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Automation
- Digital Transformation
- Business
---
