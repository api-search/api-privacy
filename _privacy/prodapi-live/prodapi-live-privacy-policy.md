---
api_specs:
- filename: prodapi-live-openapi-generated.yml
  format: yaml
  label: prodapi-live API
  slug: prodapi-live-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prodapi-live/openapi/_ae-authored/prodapi-live-openapi-generated.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: identificativi account
  - category: contact
    text: e-mail di contatto
  - category: financial
    text: riferimenti di fatturazione gestiti da Stripe
  - category: other
    text: dati necessari al workflow API scelto e preferenze privacy
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery and contact requests
    text: Gestiamo richieste di contatto, accesso account, sottoscrizioni e workflow API per eseguire il servizio o rispondere a richieste precontrattuali.
  - purpose: security and abuse prevention
    text: Usiamo misure di sicurezza e prevenzione abusi per interesse legittimo.
  - purpose: optional analytics
    text: Le analytics opzionali si attivano solo dopo consenso esplicito e revocabile.
  retention:
  - period: 180 giorni
    scope: consent log
    text: Il registro consenso resta 180 giorni;
  - period: 90 giorni
    scope: first-party analytics
    text: analytics first-party 90 giorni;
  - period: 180 giorni
    scope: contact requests
    text: richieste contatto 180 giorni;
  rights:
  - right: access, rectification, erasure, restriction, objection, portability
    text: Puoi chiedere accesso, rettifica, cancellazione, limitazione, opposizione o portabilità nei casi applicabili
  - right: withdraw consent
    text: revocare il consenso in qualsiasi momento dal pulsante Privacy
  - right: complaint to supervisory authority
    text: Puoi inoltre proporre reclamo al Garante per la protezione dei dati personali.
  role:
    text: 'Titolare del trattamento: Foundry/API'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: L’elenco effettivo dei responsabili, sub-responsabili e trasferimenti extra SEE deve essere confermato contrattualmente dal titolare.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: prodapi-live
provenance_date: '2026-11-10'
provider_name: prodapi-live
provider_slug: prodapi-live
slug: prodapi-live-privacy-policy
source_date: '2026-11-10'
source_filename: prodapi-live-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://prodapi.live/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: prodapi-live\naid: prodapi-live\nurl: https://prodapi.live/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Titolare del trattamento: Foundry/API'\ndata_categories:\n- category: identifying\n  text: identificativi account\n- category: contact\n  text: e-mail di contatto\n- category: financial\n  text: riferimenti di fatturazione gestiti da Stripe\n- category: other\n  text: dati necessari al workflow API scelto e preferenze privacy\npurposes:\n- purpose: service delivery and contact requests\n  text: Gestiamo richieste di contatto, accesso account, sottoscrizioni e workflow API\
  \ per eseguire il servizio\n    o rispondere a richieste precontrattuali.\n- purpose: security and abuse prevention\n  text: Usiamo misure di sicurezza e prevenzione abusi per interesse legittimo.\n- purpose: optional analytics\n  text: Le analytics opzionali si attivano solo dopo consenso esplicito e revocabile.\nretention:\n- scope: consent log\n  period: 180 giorni\n  text: Il registro consenso resta 180 giorni;\n- scope: first-party analytics\n  period: 90 giorni\n  text: analytics first-party 90 giorni;\n- scope: contact requests\n  period: 180 giorni\n  text: richieste contatto 180 giorni;\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: L’elenco effettivo dei responsabili, sub-responsabili e trasferimenti extra SEE deve essere confermato contrattualmente\n    dal titolare.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access, rectification, erasure, restriction, objection, portability\n  text: Puoi\
  \ chiedere accesso, rettifica, cancellazione, limitazione, opposizione o portabilità nei casi applicabili\n- right: withdraw consent\n  text: revocare il consenso in qualsiasi momento dal pulsante Privacy\n- right: complaint to supervisory authority\n  text: Puoi inoltre proporre reclamo al Garante per la protezione dei dati personali.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prodapi-live/privacy/prodapi-live-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- rights
summary_line: 15 quoted statements, read from prodapi-live's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Artificial Intelligence
- Data Extraction
- Monitoring
---
