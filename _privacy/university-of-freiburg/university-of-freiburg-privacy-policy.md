---
api_specs:
- filename: university-of-freiburg-institutions-api-openapi.yml
  format: yaml
  label: University of Freiburg Institutions API
  slug: university-of-freiburg-institutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-freiburg/openapi/university-of-freiburg-institutions-api-openapi.yml
- filename: university-of-freiburg-persons-api-openapi.yml
  format: yaml
  label: University of Freiburg Persons API
  slug: university-of-freiburg-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-freiburg/openapi/university-of-freiburg-persons-api-openapi.yml
- filename: university-of-freiburg-projects-api-openapi.yml
  format: yaml
  label: University of Freiburg Projects API
  slug: university-of-freiburg-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-freiburg/openapi/university-of-freiburg-projects-api-openapi.yml
- filename: university-of-freiburg-publications-api-openapi.yml
  format: yaml
  label: University of Freiburg Publications API
  slug: university-of-freiburg-publications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/university-of-freiburg/openapi/university-of-freiburg-publications-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: contact
    text: Name E-Mail-Adresse Inhalt der Nachricht
  - category: device
    text: Informationen über den Browsertyp, die verwendete Version und das Betriebssystem des aufrufenden Rechners
  - category: behavioral
    text: Die Verweildauer auf der Webseite
  deletion:
    route: request to the university to delete data
    text: Sie können von der Universität Freiburg verlangen, dass die Sie betreffenden personenbezogenen Daten unverzüglich gelöscht werden
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: contact handling
    text: Die Verarbeitung der personenbezogenen Daten aus der Eingabemaske dient uns allein zur Bearbeitung der Kontaktaufnahme.
  - purpose: website analytics
    text: Durch die Analyse des Nutzungsverhaltens unserer Besucher*innen sind wir in der Lage, Informationen über die Verwendung der einzelnen Komponenten unserer Internetseite zusammenzustellen.
  residency:
  - region: university servers
    text: Die von Matomo erhobenen Daten werden ausschließlich auf Servern der Universität Freiburg gespeichert.
  retention:
  - period: zwei Wochen
    scope: server logfiles
    text: Im Falle der Speicherung der Daten in den Logfiles ist dies nach zwei Wochen der Fall.
  - period: zwei Jahre
    scope: Matomo analytics data
    text: werden die Daten in der Regel für zwei Jahre gespeichert und anschließend automatisch gelöscht.
  - period: sieben Tagen
    scope: additional submission data
    text: Die während des Absendevorgangs zusätzlich erhobenen personenbezogenen Daten werden spätestens nach einer Frist von sieben Tagen gelöscht.
  rights:
  - right: access
    text: Sie können von der Universität Freiburg eine Bestätigung darüber verlangen, ob personenbezogene Daten von Ihnen verarbeitet werden.
  - right: rectification
    text: Sie haben ein Recht auf Berichtigung und/oder Vervollständigung gegenüber der Universität Freiburg
  - right: objection
    text: Sie haben das Recht, aus Gründen, die sich aus ihrer besonderen Situation ergeben, jederzeit gegen die Verarbeitung
  - right: complaint to supervisory authority
    text: Unbeschadet eines anderweitigen verwaltungsrechtlichen oder gerichtlichen Rechtsbehelfs steht Ihnen das Recht auf Beschwerde bei einer Aufsichtsbehörde
  role:
    text: Albert-Ludwigs-Universität Freiburg
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
name: University of Freiburg
provenance_date: '2026-11-10'
provider_name: University of Freiburg
provider_slug: university-of-freiburg
slug: university-of-freiburg-privacy-policy
source_date: '2026-11-10'
source_filename: university-of-freiburg-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://uni-freiburg.de/datenschutzerklaerung/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: University of Freiburg\naid: university-of-freiburg\nurl: https://uni-freiburg.de/datenschutzerklaerung/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Albert-Ludwigs-Universität Freiburg\ndata_categories:\n- category: contact\n  text: Name E-Mail-Adresse Inhalt der Nachricht\n- category: device\n  text: Informationen über den Browsertyp, die verwendete Version und das Betriebssystem des aufrufenden Rechners\n- category: behavioral\n  text: Die Verweildauer auf der Webseite\npurposes:\n- purpose: contact handling\n  text: Die Verarbeitung der personenbezogenen Daten aus der Eingabemaske dient\
  \ uns allein zur Bearbeitung der Kontaktaufnahme.\n- purpose: website analytics\n  text: Durch die Analyse des Nutzungsverhaltens unserer Besucher*innen sind wir in der Lage, Informationen über\n    die Verwendung der einzelnen Komponenten unserer Internetseite zusammenzustellen.\nretention:\n- scope: server logfiles\n  period: zwei Wochen\n  text: Im Falle der Speicherung der Daten in den Logfiles ist dies nach zwei Wochen der Fall.\n- scope: Matomo analytics data\n  period: zwei Jahre\n  text: werden die Daten in der Regel für zwei Jahre gespeichert und anschließend automatisch gelöscht.\n- scope: additional submission data\n  period: sieben Tagen\n  text: Die während des Absendevorgangs zusätzlich erhobenen personenbezogenen Daten werden spätestens nach einer\n    Frist von sieben Tagen gelöscht.\nresidency:\n- region: university servers\n  text: Die von Matomo erhobenen Daten werden ausschließlich auf Servern der Universität Freiburg gespeichert.\ntransfers: []\nsubprocessors:\n  url:\
  \ null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: request to the university to delete data\n  text: Sie können von der Universität Freiburg verlangen, dass die Sie betreffenden personenbezogenen Daten unverzüglich\n    gelöscht werden\nrights:\n- right: access\n  text: Sie können von der Universität Freiburg eine Bestätigung darüber verlangen, ob personenbezogene Daten von\n    Ihnen verarbeitet werden.\n- right: rectification\n  text: Sie haben ein Recht auf Berichtigung und/oder Vervollständigung gegenüber der Universität Freiburg\n- right: objection\n  text: Sie haben das Recht, aus Gründen, die sich aus ihrer besonderen Situation ergeben, jederzeit gegen die Verarbeitung\n- right: complaint to supervisory authority\n  text: Unbeschadet eines anderweitigen verwaltungsrechtlichen oder gerichtlichen Rechtsbehelfs steht Ihnen das\n    Recht auf Beschwerde bei einer Aufsichtsbehörde\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/university-of-freiburg/privacy/university-of-freiburg-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
summary_line: 15 quoted statements, read from University of Freiburg's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Research
- Research Data
- Open Data
- Library
- Repository
- OAI-PMH
- Identity Federation
- Germany
---
