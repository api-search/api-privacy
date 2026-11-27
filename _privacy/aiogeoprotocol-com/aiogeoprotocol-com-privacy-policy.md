---
api_specs:
- filename: aiogeoprotocol-com-audit-api-openapi.yml
  format: yaml
  label: AIO.GEO Protocol Audit API
  slug: aiogeoprotocol-com-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiogeoprotocol-com/openapi/aiogeoprotocol-com-audit-api-openapi.yml
- filename: aiogeoprotocol-com-brief-api-openapi.yml
  format: yaml
  label: AIO.GEO Protocol Brief API
  slug: aiogeoprotocol-com-brief-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aiogeoprotocol-com/openapi/aiogeoprotocol-com-brief-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account data: name, email, password or auth tokens, organization name, role, billing contact.'
  - category: financial
    text: 'Payment data: processed by payment providers (for example Stripe); we typically receive limited billing metadata, not full card numbers.'
  - category: location
    text: approximate location from IP
  - category: device
    text: 'Usage and device data: IP address, approximate location from IP, browser/OS, referring URLs, pages viewed, feature usage, timestamps.'
  - category: communication
    text: 'Support and ops messages: emails, contact forms, tickets.'
  - category: behavioral
    text: 'Logs and security telemetry: authentication events, rate-limit hits, error traces, abuse signals, firewall events.'
  deletion:
    route: Privacy requests via aiogeoprotocol@gmail.com or /contact form
    text: When no longer needed, we delete or de-identify using reasonable commercial methods.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate Services
    text: Provide, operate, secure, and improve the Services.
  - purpose: Authentication and fraud prevention
    text: Authenticate users, prevent fraud/abuse, enforce Terms.
  - purpose: Service and security messages
    text: Communicate service and security messages; limited product messages as allowed.
  - purpose: Legal compliance
    text: Comply with law and protect legal rights.
  - purpose: Aggregated statistics
    text: Create aggregated or de-identified statistics that do not reasonably identify you.
  residency:
  - region: United States and other countries
    text: We may process data in the United States and other countries where we or our providers operate.
  retention:
  - period: null
    scope: General information
    text: We retain information as long as needed to provide the Services, comply with law, resolve disputes, and enforce agreements.
  - period: limited rotation window
    scope: Backups
    text: Backups may persist for a limited rotation window.
  rights:
  - right: access, correct, delete, export, restrict, object
    text: Depending on your location, you may have rights to access, correct, delete, export, restrict, or object to certain processing, and to withdraw consent.
  - right: CCPA/CPRA
    text: California residents may have rights under the CCPA/CPRA.
  - right: complaint to supervisory authority
    text: You may lodge a complaint with a supervisory authority where applicable.
  role:
    text: the operator reachable at aiogeoprotocol@gmail.com acts as controller (or equivalent) unless a written enterprise agreement names a different party. For Customer Content you process about your own end users or clients, you are typically the controller and we act as a processor/service provider.
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell personal information as "sell" is commonly understood in consumer retail.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Where required, we use appropriate transfer mechanisms and vendor diligence.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AIO.GEO Protocol
provenance_date: '2026-11-09'
provider_name: AIO.GEO Protocol
provider_slug: aiogeoprotocol-com
slug: aiogeoprotocol-com-privacy-policy
source_date: '2026-11-09'
source_filename: aiogeoprotocol-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.aiogeoprotocol.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AIO.GEO Protocol\naid: aiogeoprotocol-com\nurl: https://www.aiogeoprotocol.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: the operator reachable at aiogeoprotocol@gmail.com acts as controller (or equivalent) unless a written enterprise\n    agreement names a different party. For Customer Content you process about your own end users or clients, you\n    are typically the controller and we act as a processor/service provider.\ndata_categories:\n- category: identifying\n  text: 'Account data: name, email, password or auth tokens, organization name, role, billing contact.'\n- category: financial\n\
  \  text: 'Payment data: processed by payment providers (for example Stripe); we typically receive limited billing\n    metadata, not full card numbers.'\n- category: location\n  text: approximate location from IP\n- category: device\n  text: 'Usage and device data: IP address, approximate location from IP, browser/OS, referring URLs, pages viewed,\n    feature usage, timestamps.'\n- category: communication\n  text: 'Support and ops messages: emails, contact forms, tickets.'\n- category: behavioral\n  text: 'Logs and security telemetry: authentication events, rate-limit hits, error traces, abuse signals, firewall\n    events.'\npurposes:\n- purpose: Provide and operate Services\n  text: Provide, operate, secure, and improve the Services.\n- purpose: Authentication and fraud prevention\n  text: Authenticate users, prevent fraud/abuse, enforce Terms.\n- purpose: Service and security messages\n  text: Communicate service and security messages; limited product messages as allowed.\n- purpose:\
  \ Legal compliance\n  text: Comply with law and protect legal rights.\n- purpose: Aggregated statistics\n  text: Create aggregated or de-identified statistics that do not reasonably identify you.\nretention:\n- scope: General information\n  period: null\n  text: We retain information as long as needed to provide the Services, comply with law, resolve disputes, and\n    enforce agreements.\n- scope: Backups\n  period: limited rotation window\n  text: Backups may persist for a limited rotation window.\nresidency:\n- region: United States and other countries\n  text: We may process data in the United States and other countries where we or our providers operate.\ntransfers:\n- mechanism: other\n  text: Where required, we use appropriate transfer mechanisms and vendor diligence.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Privacy requests via aiogeoprotocol@gmail.com or /contact form\n  text: When no longer needed, we delete\
  \ or de-identify using reasonable commercial methods.\nrights:\n- right: access, correct, delete, export, restrict, object\n  text: Depending on your location, you may have rights to access, correct, delete, export, restrict, or object\n    to certain processing, and to withdraw consent.\n- right: CCPA/CPRA\n  text: California residents may have rights under the CCPA/CPRA.\n- right: complaint to supervisory authority\n  text: You may lodge a complaint with a supervisory authority where applicable.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell personal information as \"sell\" is commonly understood in consumer retail.\n"
source_yaml_url: https://artifacts.apis.io/aiogeoprotocol-com/privacy/aiogeoprotocol-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 20 quoted statements, read from AIO.GEO Protocol's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Search
- Audit
- Measurements
- CLI
---
