---
api_specs:
- filename: minubo-auth-api-openapi.yml
  format: yaml
  label: Minubo Auth API
  slug: minubo-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-auth-api-openapi.yml
- filename: minubo-data-api-openapi.yml
  format: yaml
  label: Minubo Data API
  slug: minubo-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-data-api-openapi.yml
- filename: minubo-etl-api-openapi.yml
  format: yaml
  label: Minubo ETL API
  slug: minubo-etl-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/minubo/openapi/minubo-etl-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: device
    text: IP-Adressen
  - category: contact
    text: Kontaktdaten
  - category: identifying
    text: Namen
  - category: behavioral
    text: Webseitenzugriffe
  deletion:
    route: on request of the data subject to the controller
    text: Ferner berichtigt oder löscht minubo personenbezogene Daten auf Wunsch oder Hinweis der betroffenen Person, soweit dem keine vertraglichen oder gesetzlichen Aufbewahrungspflichten entgegenstehen.
  dpa:
    available: true
    text: die nötigen Auftragsverarbeitungsverträge gem. Art. 28 DSGVO mit uns abgeschlossen
    url: null
  purposes:
  - purpose: secure and professional website operation
    text: Die Rechtsgrundlage für diese Verarbeitung ist das berechtigte Interesse (Artikel 6 (1) lit. f DSGVO), diese Website professionell und sicher zu betreiben.
  - purpose: customer training and webinars
    text: 'Zweck der Verarbeitung: Bereitstellung von Kundenschulungen und Webinaren, Verwaltung der Teilnehmer (z. B. Anmeldebestätigungen, Zugangsdaten), Erfolgskontrolle der Schulungen.'
  residency:
  - region: Ireland
    text: Alle gewonnenen Daten werden gemäß Hotjar Angaben auf Servern in Irland (EU) abgelegt.
  - region: Germany and Netherlands
    text: wurde auf Server-Standorte in Deutschland und den Niederlanden eingeschränkt.
  retention:
  - period: null
    scope: general personal data
    text: Das Kriterium für die Dauer der Speicherung von personenbezogenen Daten ist neben einer ggf. vereinbarten Vertragslaufzeit die jeweilige gesetzliche Aufbewahrungsfrist.
  - period: 365 Tagen
    scope: Hotjar data
    text: Hotjar hat sich selbst eine Datenspeicherungsfrist von 365 Tagen auferlegt
  - period: sechs Monate
    scope: application documents
    text: werden die Bewerbungsunterlagen sechs Monate nach Bekanntgabe der Absageentscheidung automatisch gelöscht
  - period: 14 Tagen
    scope: Google Tag Manager data
    text: Die Daten werden gelöscht, sobald diese nicht mehr benötigt werden, jedoch spätestens mit Ablauf von 14 Tagen nach Abruf.
  rights:
  - right: access, correction, deletion or blocking
    text: Ihnen steht jederzeit das Recht auf unentgeltliche Auskunft, Berichtigung, Löschung bzw. Sperrung Ihrer Daten zu.
  - right: data portability
    text: Sie haben das Recht, Daten, die wir auf Grundlage Ihrer Einwilligung oder in Erfüllung eines Vertrags automatisiert verarbeiten, an sich oder an einen Dritten in einem gängigen, maschinenlesbaren Format aushändigen zu lassen.
  - right: restriction of processing
    text: Sie haben das das Recht, diese Einschränkung der Verarbeitung zu verlangen, wenn die nachfolgend aufgezählten Voraussetzungen vorliegen
  - right: objection
    text: Sie können einer Verarbeitung durch uns jederzeit widersprechen, wenn die Verarbeitung als Aufgabe im öffentlichen Interesse oder in Ausübung öffentlicher Gewalt, oder zur Wahrung berechtigter Interessen des Verantwortlichen erfolgt ist
  - right: complaint to supervisory authority
    text: Gem. Art. 77 DSGVO steht Ihnen das Recht zur Beschwerde bei der Aufsichtsbehörde zu.
  role:
    text: 'Verantwortlich für die Verarbeitung ist: minubo GmbH'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Wir geben grundsätzlich keine Daten an Dritte weiter, insbesondere nicht für Werbezwecke.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Der Transfer von Daten in die USA basiert für Dienstleister, die unter dem EU-US Data Privacy Framework (DPF) zertifiziert sind, auf dem Angemessenheitsbeschluss der EU-Kommission vom 10. Juli 2023 (Art. 45 DSGVO).
  - mechanism: SCC
    text: stellen wir sicher, dass die Übermittlung auf Basis geeigneter Garantien gemäß Art. 44 ff. DSGVO (wie Standardvertragsklauseln) oder anderer gesetzlicher Ausnahmen erfolgt.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Minubo
provenance_date: '2026-11-10'
provider_name: Minubo
provider_slug: minubo
slug: minubo-privacy-policy
source_date: '2026-11-10'
source_filename: minubo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.minubo.com/de/datenschutzerklaerung
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Minubo\naid: minubo\nurl: https://www.minubo.com/de/datenschutzerklaerung\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: controller\n  text: 'Verantwortlich für die Verarbeitung ist: minubo GmbH'\ndata_categories:\n- category: device\n  text: IP-Adressen\n- category: contact\n  text: Kontaktdaten\n- category: identifying\n  text: Namen\n- category: behavioral\n  text: Webseitenzugriffe\npurposes:\n- purpose: secure and professional website operation\n  text: Die Rechtsgrundlage für diese Verarbeitung ist das berechtigte Interesse (Artikel 6 (1) lit. f DSGVO), diese\n    Website professionell\
  \ und sicher zu betreiben.\n- purpose: customer training and webinars\n  text: 'Zweck der Verarbeitung: Bereitstellung von Kundenschulungen und Webinaren, Verwaltung der Teilnehmer (z.\n    B. Anmeldebestätigungen, Zugangsdaten), Erfolgskontrolle der Schulungen.'\nretention:\n- scope: general personal data\n  period: null\n  text: Das Kriterium für die Dauer der Speicherung von personenbezogenen Daten ist neben einer ggf. vereinbarten\n    Vertragslaufzeit die jeweilige gesetzliche Aufbewahrungsfrist.\n- scope: Hotjar data\n  period: 365 Tagen\n  text: Hotjar hat sich selbst eine Datenspeicherungsfrist von 365 Tagen auferlegt\n- scope: application documents\n  period: sechs Monate\n  text: werden die Bewerbungsunterlagen sechs Monate nach Bekanntgabe der Absageentscheidung automatisch gelöscht\n- scope: Google Tag Manager data\n  period: 14 Tagen\n  text: Die Daten werden gelöscht, sobald diese nicht mehr benötigt werden, jedoch spätestens mit Ablauf von 14\n    Tagen nach Abruf.\nresidency:\n\
  - region: Ireland\n  text: Alle gewonnenen Daten werden gemäß Hotjar Angaben auf Servern in Irland (EU) abgelegt.\n- region: Germany and Netherlands\n  text: wurde auf Server-Standorte in Deutschland und den Niederlanden eingeschränkt.\ntransfers:\n- mechanism: DPF\n  text: Der Transfer von Daten in die USA basiert für Dienstleister, die unter dem EU-US Data Privacy Framework\n    (DPF) zertifiziert sind, auf dem Angemessenheitsbeschluss der EU-Kommission vom 10. Juli 2023 (Art. 45 DSGVO).\n- mechanism: SCC\n  text: stellen wir sicher, dass die Übermittlung auf Basis geeigneter Garantien gemäß Art. 44 ff. DSGVO (wie Standardvertragsklauseln)\n    oder anderer gesetzlicher Ausnahmen erfolgt.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: die nötigen Auftragsverarbeitungsverträge gem. Art. 28 DSGVO mit uns abgeschlossen\ndeletion:\n  route: on request of the data subject to the controller\n  text: Ferner berichtigt oder löscht minubo personenbezogene\
  \ Daten auf Wunsch oder Hinweis der betroffenen Person,\n    soweit dem keine vertraglichen oder gesetzlichen Aufbewahrungspflichten entgegenstehen.\nrights:\n- right: access, correction, deletion or blocking\n  text: Ihnen steht jederzeit das Recht auf unentgeltliche Auskunft, Berichtigung, Löschung bzw. Sperrung Ihrer\n    Daten zu.\n- right: data portability\n  text: Sie haben das Recht, Daten, die wir auf Grundlage Ihrer Einwilligung oder in Erfüllung eines Vertrags automatisiert\n    verarbeiten, an sich oder an einen Dritten in einem gängigen, maschinenlesbaren Format aushändigen zu lassen.\n- right: restriction of processing\n  text: Sie haben das das Recht, diese Einschränkung der Verarbeitung zu verlangen, wenn die nachfolgend aufgezählten\n    Voraussetzungen vorliegen\n- right: objection\n  text: Sie können einer Verarbeitung durch uns jederzeit widersprechen, wenn die Verarbeitung als Aufgabe im öffentlichen\n    Interesse oder in Ausübung öffentlicher Gewalt, oder zur Wahrung\
  \ berechtigter Interessen des Verantwortlichen\n    erfolgt ist\n- right: complaint to supervisory authority\n  text: Gem. Art. 77 DSGVO steht Ihnen das Recht zur Beschwerde bei der Aufsichtsbehörde zu.\nsale_or_sharing:\n  stance: prohibited\n  text: Wir geben grundsätzlich keine Daten an Dritte weiter, insbesondere nicht für Werbezwecke.\n"
source_yaml_url: https://artifacts.apis.io/minubo/privacy/minubo-privacy-policy.yml
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
- sale_or_sharing
summary_line: 23 quoted statements, read from Minubo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Business Intelligence
- Analytics
- Retail
- Data
- ETL
- Reporting
---
