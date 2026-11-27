---
api_specs:
- filename: chorilo-com-openapi-generated.yml
  format: yaml
  label: Chorilo API
  slug: chorilo-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chorilo-com/openapi/_ae-authored/chorilo-com-openapi-generated.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, Vorname, E-Mail-Adresse, Passwort-Hash, Sprache und Zeitzone.
  - category: contact
    text: Darüber hinaus können alle Nutzenden freiwillig Angaben zu Anschrift und Geburtsdatum machen sowie ein Foto hochladen.
  - category: financial
    text: Übertragen und auf unseren Servern gespeichert werden Kontoinhaber, IBAN, BIC, Kontostand sowie Umsatzdaten
  - category: communication
    text: Nachrichteninhalt, Name des Absenders, Zeitpunkt der Nachricht sowie ggf. angehängte Dateien.
  - category: device
    text: Im Fehlerfall können technische Daten wie Informationen zum Gerät, Betriebssystem, Browser
  - category: behavioral
    text: Die erhobenen Daten (besuchte Seiten, Verweildauer, Herkunftsland, Geräte- und Browserinformationen)
  - category: professional
    text: 'Bei Chorleiter*innen zusätzlich: Chorname, gekürzter Chorname, Chorgröße und Chorstimmen.'
  deletion:
    route: Löschung des Nutzerkontos oder Anfrage per E-Mail an datenschutz@chorilo.com
    text: Zur Geltendmachung Ihrer Rechte wenden Sie sich bitte an die oben unter 1. genannte E-Mail-Adresse (datenschutz@chorilo.com).
  dpa:
    available: true
    text: Auftragsverarbeitung (AVV)
    url: null
  purposes:
  - purpose: Sicherheit und Angriffserkennung
    text: Zum Zweck der Erkennung und Abwehr von Angriffen auf unsere Webseite und die technische Infrastruktur
  - purpose: Webanalyse mit Einwilligung
    text: Mit Ihrer Einwilligung setzen wir Matomo ein, eine selbst gehostete Open-Source-Webanalysesoftware.
  - purpose: Werbemessung und Zielgruppen
    text: um die Wirksamkeit unserer Werbeanzeigen auf Facebook und Instagram zu messen, Zielgruppen für Werbeanzeigen zu erstellen
  - purpose: KI-Funktionen
    text: Für KI-Funktionen nutzen wir Dienste der Anthropic Ireland, Limited
  - purpose: Fehlererkennung
    text: Zur Erkennung und Analyse technischer Fehler in unserer Anwendung setzen wir eine selbst gehostete Sentry-Instanz ein.
  residency:
  - region: Deutschland (Hosting)
    text: Die Server von Hetzner befinden sich ausschließlich in Deutschland.
  - region: Deutschland (Matomo)
    text: ausschließlich auf unserem eigenen Server in Deutschland gespeichert
  retention:
  - period: solange Ihr Konto aktiv ist
    scope: Nutzerkonto
    text: Die Daten in Ihrem Nutzerkonto werden gespeichert, solange Ihr Konto aktiv ist.
  - period: binnen 90 Tagen
    scope: Stammdaten nach Kontolöschung
    text: werden Ihre personenbezogenen Stammdaten binnen 90 Tagen gelöscht
  - period: 7 Tagen
    scope: Sicherheitslogdaten
    text: Logdaten zur Sicherheit (siehe 2.2) werden nach 7 Tagen gelöscht.
  - period: 30 Tagen
    scope: KI-Anbieter Anthropic
    text: löscht sie in der Regel nach 30 Tagen
  - period: drei Kalenderjahren
    scope: Support-Daten
    text: spätestens jedoch nach drei Kalenderjahren
  rights:
  - right: Auskunft
    text: Recht auf Auskunft (Art. 15 DS-GVO)
  - right: Berichtigung
    text: Recht auf Berichtigung (Art. 16 DS-GVO)
  - right: Löschung
    text: Recht auf Löschung (Art. 17 DS-GVO)
  - right: Einschränkung
    text: Recht auf Einschränkung der Verarbeitung (Art. 18 DS-GVO)
  - right: Widerspruch
    text: Recht auf Widerspruch gegen die Verarbeitung (Art. 21 DS-GVO)
  - right: Datenübertragbarkeit
    text: Recht auf Datenübertragbarkeit (Art. 20 DS-GVO)
  - right: Widerruf der Einwilligung
    text: haben Sie das Recht, diese Einwilligung jederzeit mit Wirkung für die Zukunft zu widerrufen (Art. 7 Abs. 3 DS-GVO)
  - right: Beschwerde bei Aufsichtsbehörde
    text: Sie haben außerdem das Recht, sich bei einer Datenschutz-Aufsichtsbehörde über die Verarbeitung Ihrer personenbezogenen Daten durch uns zu beschweren (Art. 77 DS-GVO).
  role:
    text: Verantwortlich für die Verarbeitung Ihrer personenbezogenen Daten ist Chorilo - Melanie Schneider, Tränkstraße 3, 65558 Holzheim.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Die Übermittlung in die USA erfolgt auf Grundlage des EU-US Data Privacy Framework (Angemessenheitsbeschluss, Art. 45 DS-GVO)
  - mechanism: SCC
    text: Die Verarbeitung kann in den USA stattfinden; die Übermittlung erfolgt auf Grundlage von Standardvertragsklauseln (Art. 46 Abs. 2 c DS-GVO).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Chorilo
provenance_date: '2026-11-09'
provider_name: Chorilo
provider_slug: chorilo-com
slug: chorilo-com-privacy-policy
source_date: '2026-11-09'
source_filename: chorilo-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.chorilo.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Chorilo\naid: chorilo-com\nurl: https://www.chorilo.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Verantwortlich für die Verarbeitung Ihrer personenbezogenen Daten ist Chorilo - Melanie Schneider, Tränkstraße\n    3, 65558 Holzheim.\ndata_categories:\n- category: identifying\n  text: Name, Vorname, E-Mail-Adresse, Passwort-Hash, Sprache und Zeitzone.\n- category: contact\n  text: Darüber hinaus können alle Nutzenden freiwillig Angaben zu Anschrift und Geburtsdatum machen sowie ein Foto\n    hochladen.\n- category: financial\n  text: Übertragen und auf unseren Servern gespeichert werden\
  \ Kontoinhaber, IBAN, BIC, Kontostand sowie Umsatzdaten\n- category: communication\n  text: Nachrichteninhalt, Name des Absenders, Zeitpunkt der Nachricht sowie ggf. angehängte Dateien.\n- category: device\n  text: Im Fehlerfall können technische Daten wie Informationen zum Gerät, Betriebssystem, Browser\n- category: behavioral\n  text: Die erhobenen Daten (besuchte Seiten, Verweildauer, Herkunftsland, Geräte- und Browserinformationen)\n- category: professional\n  text: 'Bei Chorleiter*innen zusätzlich: Chorname, gekürzter Chorname, Chorgröße und Chorstimmen.'\npurposes:\n- purpose: Sicherheit und Angriffserkennung\n  text: Zum Zweck der Erkennung und Abwehr von Angriffen auf unsere Webseite und die technische Infrastruktur\n- purpose: Webanalyse mit Einwilligung\n  text: Mit Ihrer Einwilligung setzen wir Matomo ein, eine selbst gehostete Open-Source-Webanalysesoftware.\n- purpose: Werbemessung und Zielgruppen\n  text: um die Wirksamkeit unserer Werbeanzeigen auf Facebook und Instagram\
  \ zu messen, Zielgruppen für Werbeanzeigen\n    zu erstellen\n- purpose: KI-Funktionen\n  text: Für KI-Funktionen nutzen wir Dienste der Anthropic Ireland, Limited\n- purpose: Fehlererkennung\n  text: Zur Erkennung und Analyse technischer Fehler in unserer Anwendung setzen wir eine selbst gehostete Sentry-Instanz\n    ein.\nretention:\n- scope: Nutzerkonto\n  period: solange Ihr Konto aktiv ist\n  text: Die Daten in Ihrem Nutzerkonto werden gespeichert, solange Ihr Konto aktiv ist.\n- scope: Stammdaten nach Kontolöschung\n  period: binnen 90 Tagen\n  text: werden Ihre personenbezogenen Stammdaten binnen 90 Tagen gelöscht\n- scope: Sicherheitslogdaten\n  period: 7 Tagen\n  text: Logdaten zur Sicherheit (siehe 2.2) werden nach 7 Tagen gelöscht.\n- scope: KI-Anbieter Anthropic\n  period: 30 Tagen\n  text: löscht sie in der Regel nach 30 Tagen\n- scope: Support-Daten\n  period: drei Kalenderjahren\n  text: spätestens jedoch nach drei Kalenderjahren\nresidency:\n- region: Deutschland (Hosting)\n\
  \  text: Die Server von Hetzner befinden sich ausschließlich in Deutschland.\n- region: Deutschland (Matomo)\n  text: ausschließlich auf unserem eigenen Server in Deutschland gespeichert\ntransfers:\n- mechanism: DPF\n  text: Die Übermittlung in die USA erfolgt auf Grundlage des EU-US Data Privacy Framework (Angemessenheitsbeschluss,\n    Art. 45 DS-GVO)\n- mechanism: SCC\n  text: Die Verarbeitung kann in den USA stattfinden; die Übermittlung erfolgt auf Grundlage von Standardvertragsklauseln\n    (Art. 46 Abs. 2 c DS-GVO).\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Auftragsverarbeitung (AVV)\ndeletion:\n  route: Löschung des Nutzerkontos oder Anfrage per E-Mail an datenschutz@chorilo.com\n  text: Zur Geltendmachung Ihrer Rechte wenden Sie sich bitte an die oben unter 1. genannte E-Mail-Adresse (datenschutz@chorilo.com).\nrights:\n- right: Auskunft\n  text: Recht auf Auskunft (Art. 15 DS-GVO)\n- right: Berichtigung\n  text: Recht auf Berichtigung\
  \ (Art. 16 DS-GVO)\n- right: Löschung\n  text: Recht auf Löschung (Art. 17 DS-GVO)\n- right: Einschränkung\n  text: Recht auf Einschränkung der Verarbeitung (Art. 18 DS-GVO)\n- right: Widerspruch\n  text: Recht auf Widerspruch gegen die Verarbeitung (Art. 21 DS-GVO)\n- right: Datenübertragbarkeit\n  text: Recht auf Datenübertragbarkeit (Art. 20 DS-GVO)\n- right: Widerruf der Einwilligung\n  text: haben Sie das Recht, diese Einwilligung jederzeit mit Wirkung für die Zukunft zu widerrufen (Art. 7 Abs.\n    3 DS-GVO)\n- right: Beschwerde bei Aufsichtsbehörde\n  text: Sie haben außerdem das Recht, sich bei einer Datenschutz-Aufsichtsbehörde über die Verarbeitung Ihrer personenbezogenen\n    Daten durch uns zu beschweren (Art. 77 DS-GVO).\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/chorilo-com/privacy/chorilo-com-privacy-policy.yml
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
summary_line: 32 quoted statements, read from Chorilo's own page on 2026-11-09.
synthetic: false
tags:
- Choir Management
- Sheet Music
- Event Planning
- Finance
- Membership
- Collaboration
- GDPR
- Mobile App
---
