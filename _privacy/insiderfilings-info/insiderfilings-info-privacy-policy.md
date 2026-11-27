---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: InsiderFilings API
  slug: insiderfilings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/insiderfilings-info/openapi/_original/openapi.yaml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: Wir speichern die E-Mail-Adresse verschlüsselt
  - category: device
    text: IP-Adresse des zugreifenden Geräts
  - category: device
    text: Browsertyp und Browserversion verwendetes Betriebssystem
  - category: behavioral
    text: aufgerufene URL Referrer-URL
  - category: identifying
    text: Dabei können auch personenbezogene Angaben zu Reporting Owners bzw. Insidern enthalten sein, insbesondere Namen, Rollen/Funktionen, Transaktionsdaten und Beteiligungsangaben.
  deletion:
    route: email to the contact address in section 1
    text: Zur Ausübung Ihrer Rechte können Sie uns unter der oben genannten E-Mail-Adresse kontaktieren.
  dpa:
    available: null
    text: Soweit erforderlich, besteht mit dem Hosting-Anbieter ein Vertrag zur Auftragsverarbeitung gemäß Art. 28 DSGVO.
    url: null
  purposes:
  - purpose: Website operation and security
    text: Die Verarbeitung erfolgt zur technischen Bereitstellung der Website, zur Fehleranalyse, zur Gewährleistung der Systemsicherheit und zur Abwehr missbräuchlicher Nutzung.
  - purpose: Sending filing emails on consent
    text: Der Versand der gewünschten Benachrichtigungen erfolgt auf Grundlage Ihrer Einwilligung nach Art. 6 Abs. 1 lit. a DSGVO.
  - purpose: Structured access to public SEC data
    text: Die Verarbeitung dient der strukturierten Auffindbarkeit, Darstellung und Analyse öffentlich verfügbarer Kapitalmarktinformationen.
  retention:
  - period: null
    scope: API test registration IP fingerprints
    text: IP-Fingerabdrücke und ihre Zuordnungen zu E-Mail-Fingerabdrücken werden für rollierende Registrierungsprüfungen bis zu 30 Tage nach der jeweils letzten berücksichtigten Registrierungsanfrage benötigt.
  - period: 90-Tage
    scope: Activated API test email fingerprint
    text: Der E-Mail-Fingerabdruck und die zugehörigen Berechtigungsdaten eines aktivierten Testzugangs werden für die 90-Tage-Sperre ab Aktivierung aufbewahrt.
  - period: 90 Tagen
    scope: Filing email subscription
    text: Ein bestätigtes Abo endet in der Startkonfiguration nach 90 Tagen ohne automatische Verlängerung.
  - period: sieben Tagen
    scope: Filing email dispatch orders
    text: Sie werden standardmäßig nach sieben Tagen gelöscht.
  rights:
  - right: access
    text: Recht auf Auskunft über die zu Ihrer Person verarbeiteten Daten
  - right: rectification
    text: Recht auf Berichtigung unrichtiger Daten
  - right: erasure
    text: Recht auf Löschung
  - right: restriction
    text: Recht auf Einschränkung der Verarbeitung
  - right: portability
    text: Recht auf Datenübertragbarkeit
  - right: objection
    text: Recht auf Widerspruch gegen Verarbeitungen auf Grundlage berechtigter Interessen
  - right: complaint
    text: Recht auf Beschwerde bei einer Datenschutzaufsichtsbehörde
  role:
    text: 'Verantwortlich für die Datenverarbeitung auf dieser Website ist: Tilman Ambach'
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
name: insiderfilings.info
provenance_date: '2026-11-09'
provider_name: insiderfilings.info
provider_slug: insiderfilings-info
slug: insiderfilings-info-privacy-policy
source_date: '2026-11-09'
source_filename: insiderfilings-info-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://insiderfilings.info/privacy.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: insiderfilings.info\naid: insiderfilings-info\nurl: https://insiderfilings.info/privacy.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Verantwortlich für die Datenverarbeitung auf dieser Website ist: Tilman Ambach'\ndata_categories:\n- category: contact\n  text: Wir speichern die E-Mail-Adresse verschlüsselt\n- category: device\n  text: IP-Adresse des zugreifenden Geräts\n- category: device\n  text: Browsertyp und Browserversion verwendetes Betriebssystem\n- category: behavioral\n  text: aufgerufene URL Referrer-URL\n- category: identifying\n  text: Dabei können auch personenbezogene\
  \ Angaben zu Reporting Owners bzw. Insidern enthalten sein, insbesondere\n    Namen, Rollen/Funktionen, Transaktionsdaten und Beteiligungsangaben.\npurposes:\n- purpose: Website operation and security\n  text: Die Verarbeitung erfolgt zur technischen Bereitstellung der Website, zur Fehleranalyse, zur Gewährleistung\n    der Systemsicherheit und zur Abwehr missbräuchlicher Nutzung.\n- purpose: Sending filing emails on consent\n  text: Der Versand der gewünschten Benachrichtigungen erfolgt auf Grundlage Ihrer Einwilligung nach Art. 6 Abs.\n    1 lit. a DSGVO.\n- purpose: Structured access to public SEC data\n  text: Die Verarbeitung dient der strukturierten Auffindbarkeit, Darstellung und Analyse öffentlich verfügbarer\n    Kapitalmarktinformationen.\nretention:\n- scope: API test registration IP fingerprints\n  period: null\n  text: IP-Fingerabdrücke und ihre Zuordnungen zu E-Mail-Fingerabdrücken werden für rollierende Registrierungsprüfungen\n    bis zu 30 Tage nach der jeweils letzten\
  \ berücksichtigten Registrierungsanfrage benötigt.\n- scope: Activated API test email fingerprint\n  period: 90-Tage\n  text: Der E-Mail-Fingerabdruck und die zugehörigen Berechtigungsdaten eines aktivierten Testzugangs werden für\n    die 90-Tage-Sperre ab Aktivierung aufbewahrt.\n- scope: Filing email subscription\n  period: 90 Tagen\n  text: Ein bestätigtes Abo endet in der Startkonfiguration nach 90 Tagen ohne automatische Verlängerung.\n- scope: Filing email dispatch orders\n  period: sieben Tagen\n  text: Sie werden standardmäßig nach sieben Tagen gelöscht.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Soweit erforderlich, besteht mit dem Hosting-Anbieter ein Vertrag zur Auftragsverarbeitung gemäß Art. 28\n    DSGVO.\ndeletion:\n  route: email to the contact address in section 1\n  text: Zur Ausübung Ihrer Rechte können Sie uns unter der oben genannten E-Mail-Adresse kontaktieren.\nrights:\n- right: access\n\
  \  text: Recht auf Auskunft über die zu Ihrer Person verarbeiteten Daten\n- right: rectification\n  text: Recht auf Berichtigung unrichtiger Daten\n- right: erasure\n  text: Recht auf Löschung\n- right: restriction\n  text: Recht auf Einschränkung der Verarbeitung\n- right: portability\n  text: Recht auf Datenübertragbarkeit\n- right: objection\n  text: Recht auf Widerspruch gegen Verarbeitungen auf Grundlage berechtigter Interessen\n- right: complaint\n  text: Recht auf Beschwerde bei einer Datenschutzaufsichtsbehörde\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/insiderfilings-info/privacy/insiderfilings-info-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
summary_line: 22 quoted statements, read from insiderfilings.info's own page on 2026-11-09.
synthetic: false
tags:
- Insider Trading
- SEC Filings
- Financial Data
- Research Tools
- Market Data
---
