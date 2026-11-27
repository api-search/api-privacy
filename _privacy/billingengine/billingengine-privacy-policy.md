---
api_specs:
- filename: billingengine-customers-api-openapi.yml
  format: yaml
  label: BillingEngine Customers API
  slug: billingengine-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billingengine/openapi/billingengine-customers-api-openapi.yml
- filename: billingengine-invoices-api-openapi.yml
  format: yaml
  label: BillingEngine Invoices API
  slug: billingengine-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billingengine/openapi/billingengine-invoices-api-openapi.yml
- filename: billingengine-payments-api-openapi.yml
  format: yaml
  label: BillingEngine Payments API
  slug: billingengine-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/billingengine/openapi/billingengine-payments-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: contact
    text: Firmenname, E-Mail-Adresse und die Daten, die Sie für Ihre Rechnungen und Ihre Kunden erfassen
  - category: financial
    text: Wenn Sie in einen kostenpflichtigen Tarif wechseln, gehen Ihre Zahlungsdaten direkt an unseren Zahlungsdienstleister Stripe
  - category: device
    text: Ihre IP-Adresse und Browserdaten, um BillingEngine abzusichern und Fehler zu finden.
  - category: behavioral
    text: Übermittelt werden IP-Adresse, Browserdaten und besuchte Seiten
  deletion:
    route: Einstellungen
    text: In Ihren Einstellungen können Sie es jederzeit löschen
  dpa:
    available: true
    text: auf Grundlage unseres Auftragsverarbeitungsvertrags
    url: null
  purposes:
  - purpose: Bereitstellung von BillingEngine
    text: 'Konto und Rechnungen: Firmenname, E-Mail-Adresse und die Daten, die Sie für Ihre Rechnungen und Ihre Kunden erfassen, um BillingEngine bereitzustellen (Vertrag).'
  - purpose: Absicherung und Fehlersuche
    text: um BillingEngine abzusichern und Fehler zu finden
  - purpose: Reichweitenmessung
    text: Seitenaufrufe zählen wir mit Cloudflare Web Analytics , ohne Cookies und ohne Sie wiederzuerkennen (berechtigtes Interesse).
  - purpose: Statistik und Werbung mit Einwilligung
    text: Damit verstehen wir, wie BillingEngine genutzt wird, messen, ob unsere Werbung zu Registrierungen führt, und zeigen Ihnen auf diesen Plattformen passende Anzeigen.
  residency:
  - region: Frankfurt
    text: DigitalOcean (Server in Frankfurt)
  - region: Frankfurt
    text: Amazon Web Services (Dateispeicher und E-Mail-Versand in Frankfurt)
  - region: USA
    text: OpenAI verarbeitet die Inhalte außerhalb der EU, in den USA, auf Grundlage von Standardvertragsklauseln.
  retention:
  - period: zehn Tagen
    scope: Kontodaten nach Löschung
    text: wir löschen Ihre Daten dann innerhalb von zehn Tagen
  - period: 30 Tagen
    scope: Zugriffsprotokolle
    text: Zugriffsprotokolle löschen wir nach spätestens 30 Tagen.
  - period: acht Jahre
    scope: Rechnungen für Abonnement
    text: die Rechnungen für Ihr BillingEngine-Abonnement (acht Jahre)
  - period: zwei Tagen
    scope: Fehlerhafte CSV-Dateien
    text: Wir löschen sie automatisch, spätestens nach zwei Tagen
  rights:
  - right: Auskunft, Berichtigung, Löschung, Einschränkung, Übertragbarkeit
    text: Sie haben das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung und Datenübertragbarkeit.
  - right: Widerspruch
    text: Wo wir Daten aus berechtigtem Interesse verarbeiten, können Sie widersprechen
  - right: Widerruf der Einwilligung
    text: eine erteilte Einwilligung können Sie jederzeit widerrufen
  - right: Beschwerde bei Aufsichtsbehörde
    text: Außerdem können Sie sich bei einer Datenschutzaufsichtsbehörde beschweren.
  role:
    text: Für die Kundendaten, die Sie in BillingEngine erfassen, sind Sie selbst verantwortlich.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Stripe für Zahlungen, in den USA und mit Standardvertragsklauseln abgesichert.
  - mechanism: DPF
    text: Sie verarbeiten Daten auch in den USA und sind nach dem EU-US Data Privacy Framework zertifiziert.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BillingEngine
provenance_date: '2026-11-09'
provider_name: BillingEngine
provider_slug: billingengine
slug: billingengine-privacy-policy
source_date: '2026-11-09'
source_filename: billingengine-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.billingengine.com/de/privacy_notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BillingEngine\naid: billingengine\nurl: https://www.billingengine.com/de/privacy_notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Für die Kundendaten, die Sie in BillingEngine erfassen, sind Sie selbst verantwortlich.\ndata_categories:\n- category: contact\n  text: Firmenname, E-Mail-Adresse und die Daten, die Sie für Ihre Rechnungen und Ihre Kunden erfassen\n- category: financial\n  text: Wenn Sie in einen kostenpflichtigen Tarif wechseln, gehen Ihre Zahlungsdaten direkt an unseren Zahlungsdienstleister\n    Stripe\n- category: device\n  text: Ihre IP-Adresse und Browserdaten, um BillingEngine\
  \ abzusichern und Fehler zu finden.\n- category: behavioral\n  text: Übermittelt werden IP-Adresse, Browserdaten und besuchte Seiten\npurposes:\n- purpose: Bereitstellung von BillingEngine\n  text: 'Konto und Rechnungen: Firmenname, E-Mail-Adresse und die Daten, die Sie für Ihre Rechnungen und Ihre Kunden\n    erfassen, um BillingEngine bereitzustellen (Vertrag).'\n- purpose: Absicherung und Fehlersuche\n  text: um BillingEngine abzusichern und Fehler zu finden\n- purpose: Reichweitenmessung\n  text: Seitenaufrufe zählen wir mit Cloudflare Web Analytics , ohne Cookies und ohne Sie wiederzuerkennen (berechtigtes\n    Interesse).\n- purpose: Statistik und Werbung mit Einwilligung\n  text: Damit verstehen wir, wie BillingEngine genutzt wird, messen, ob unsere Werbung zu Registrierungen führt,\n    und zeigen Ihnen auf diesen Plattformen passende Anzeigen.\nretention:\n- scope: Kontodaten nach Löschung\n  period: zehn Tagen\n  text: wir löschen Ihre Daten dann innerhalb von zehn Tagen\n- scope:\
  \ Zugriffsprotokolle\n  period: 30 Tagen\n  text: Zugriffsprotokolle löschen wir nach spätestens 30 Tagen.\n- scope: Rechnungen für Abonnement\n  period: acht Jahre\n  text: die Rechnungen für Ihr BillingEngine-Abonnement (acht Jahre)\n- scope: Fehlerhafte CSV-Dateien\n  period: zwei Tagen\n  text: Wir löschen sie automatisch, spätestens nach zwei Tagen\nresidency:\n- region: Frankfurt\n  text: DigitalOcean (Server in Frankfurt)\n- region: Frankfurt\n  text: Amazon Web Services (Dateispeicher und E-Mail-Versand in Frankfurt)\n- region: USA\n  text: OpenAI verarbeitet die Inhalte außerhalb der EU, in den USA, auf Grundlage von Standardvertragsklauseln.\ntransfers:\n- mechanism: SCC\n  text: Stripe für Zahlungen, in den USA und mit Standardvertragsklauseln abgesichert.\n- mechanism: DPF\n  text: Sie verarbeiten Daten auch in den USA und sind nach dem EU-US Data Privacy Framework zertifiziert.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: auf Grundlage\
  \ unseres Auftragsverarbeitungsvertrags\ndeletion:\n  route: Einstellungen\n  text: In Ihren Einstellungen können Sie es jederzeit löschen\nrights:\n- right: Auskunft, Berichtigung, Löschung, Einschränkung, Übertragbarkeit\n  text: Sie haben das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung und Datenübertragbarkeit.\n- right: Widerspruch\n  text: Wo wir Daten aus berechtigtem Interesse verarbeiten, können Sie widersprechen\n- right: Widerruf der Einwilligung\n  text: eine erteilte Einwilligung können Sie jederzeit widerrufen\n- right: Beschwerde bei Aufsichtsbehörde\n  text: Außerdem können Sie sich bei einer Datenschutzaufsichtsbehörde beschweren.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billingengine/privacy/billingengine-privacy-policy.yml
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
summary_line: 24 quoted statements, read from BillingEngine's own page on 2026-11-09.
synthetic: false
tags:
- Invoicing
- Fintech
- Germany
- Small Business
---
