---
api_specs:
- filename: keyper-permissions-api-openapi.yml
  format: yaml
  label: Keyper Permissions API
  slug: keyper-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyper/openapi/keyper-permissions-api-openapi.yml
- filename: keyper-transactions-api-openapi.yml
  format: yaml
  label: Keyper Transactions API
  slug: keyper-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keyper/openapi/keyper-transactions-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name + ev. Titel
  - category: contact
    text: E-Mail-Adresse
  - category: contact
    text: Telefonnummer
  - category: financial
    text: Kreditkartendaten
  - category: financial
    text: Bankname
  - category: location
    text: Ort
  - category: device
    text: Browsertyp und -version & Fenstergröße
  - category: behavioral
    text: Hotjar, um Informationen über das Verhalten unserer Nutzer und über ihre Endgeräte zu sammeln
  - category: professional
    text: Berufsbezeichnung
  - category: demographic
    text: Geschlecht
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Website operation and statistics
    text: Diese Daten werden aus technischen Gründen übermittelt und werden lediglich zu statistischen bzw. technischen Zwecken erhoben und verarbeitet
  - purpose: Marketing via search queries
    text: Wir nutzen Google Analytics, um Suchanfragen auf unserer Website für Marketingzwecke verwenden zu können.
  - purpose: Payment processing
    text: Für den Bezahlprozess übermitteln wir Ihre Daten an die Stripe Inc.
  - purpose: Invoicing
    text: Wir nutzen zum Erstellen von Rechnungen die Dienste der FastBill GmbH.
  retention:
  - period: null
    scope: Personal data generally
    text: Die Daten werden verarbeitet, solange dies zur Erfüllung unserer vertraglichen bzw. gesetzlichen Verpflichtungen und zur Abwehr allfälliger Haftungsansprüche erforderlich ist bzw. bis Sie eine erteilte Einwilligung widerrufen.
  rights:
  - right: access
    text: Als Betroffene/r haben Sie jederzeit das Recht auf Auskunft über Ihre gespeicherten personenbezogenen Daten
  - right: rectification and portability
    text: Ferner haben Sie ein Recht auf das Berichtigen und Übertragen Ihrer Daten
  - right: objection, restriction, erasure
    text: gegebenenfalls auf Widerspruch, auf Einschränken der Bearbeitung oder Löschen verarbeiteter Daten.
  - right: withdraw consent
    text: Sie können eine erteilte Einwilligung jederzeit mit Wirkung für die Zukunft widerrufen
  - right: complaint to supervisory authority
    text: besteht die Möglichkeit sich bei der zuständigen Aufsichtsbehörde zu beschweren.
  role:
    text: 'Verantwortlicher im Sinn der Datenschutz-Grundverordnung ("DSGVO") ist: keyper GmbH'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: Wir übermitteln Ihre personenbezogenen Daten jedoch nur in Länder, für welche die EU-Kommission entscheiden hat, dass sie über ein angemessenes Datenschutzniveau verfügen
  - mechanism: other
    text: oder wir setzen Maßnahmen, um zu gewährleisten, dass alle Empfänger ein angemessenes Datenschutzniveau haben.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Keyper
provenance_date: '2026-11-09'
provider_name: Keyper
provider_slug: keyper
slug: keyper-privacy-policy
source_date: '2026-11-09'
source_filename: keyper-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.keyper.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Keyper\naid: keyper\nurl: https://www.keyper.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Verantwortlicher im Sinn der Datenschutz-Grundverordnung (\"DSGVO\") ist: keyper GmbH'\ndata_categories:\n- category: identifying\n  text: Name + ev. Titel\n- category: contact\n  text: E-Mail-Adresse\n- category: contact\n  text: Telefonnummer\n- category: financial\n  text: Kreditkartendaten\n- category: financial\n  text: Bankname\n- category: location\n  text: Ort\n- category: device\n  text: Browsertyp und -version & Fenstergröße\n- category: behavioral\n  text: Hotjar, um\
  \ Informationen über das Verhalten unserer Nutzer und über ihre Endgeräte zu sammeln\n- category: professional\n  text: Berufsbezeichnung\n- category: demographic\n  text: Geschlecht\npurposes:\n- purpose: Website operation and statistics\n  text: Diese Daten werden aus technischen Gründen übermittelt und werden lediglich zu statistischen bzw. technischen\n    Zwecken erhoben und verarbeitet\n- purpose: Marketing via search queries\n  text: Wir nutzen Google Analytics, um Suchanfragen auf unserer Website für Marketingzwecke verwenden zu können.\n- purpose: Payment processing\n  text: Für den Bezahlprozess übermitteln wir Ihre Daten an die Stripe Inc.\n- purpose: Invoicing\n  text: Wir nutzen zum Erstellen von Rechnungen die Dienste der FastBill GmbH.\nretention:\n- scope: Personal data generally\n  period: null\n  text: Die Daten werden verarbeitet, solange dies zur Erfüllung unserer vertraglichen bzw. gesetzlichen Verpflichtungen\n    und zur Abwehr allfälliger Haftungsansprüche erforderlich\
  \ ist bzw. bis Sie eine erteilte Einwilligung widerrufen.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: Wir übermitteln Ihre personenbezogenen Daten jedoch nur in Länder, für welche die EU-Kommission entscheiden\n    hat, dass sie über ein angemessenes Datenschutzniveau verfügen\n- mechanism: other\n  text: oder wir setzen Maßnahmen, um zu gewährleisten, dass alle Empfänger ein angemessenes Datenschutzniveau haben.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: Als Betroffene/r haben Sie jederzeit das Recht auf Auskunft über Ihre gespeicherten personenbezogenen Daten\n- right: rectification and portability\n  text: Ferner haben Sie ein Recht auf das Berichtigen und Übertragen Ihrer Daten\n- right: objection, restriction, erasure\n  text: gegebenenfalls auf Widerspruch, auf Einschränken der Bearbeitung oder Löschen verarbeiteter Daten.\n- right: withdraw\
  \ consent\n  text: Sie können eine erteilte Einwilligung jederzeit mit Wirkung für die Zukunft widerrufen\n- right: complaint to supervisory authority\n  text: besteht die Möglichkeit sich bei der zuständigen Aufsichtsbehörde zu beschweren.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/keyper/privacy/keyper-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- rights
summary_line: 23 quoted statements, read from Keyper's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Ticketing
- Access Control
- Event
- Developer Platform
- SDK
- Sports
- Arts and Culture
- Austria
---
