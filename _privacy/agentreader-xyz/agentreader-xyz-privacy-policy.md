---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'a short pseudonymous caller ID: a keyed hash (HMAC-SHA-256 with a secret salt kept on our server) of your IP address, or of your API key if you use one'
  - category: device
    text: a coarse user-agent family, such as "browser", "python" or "claude" (never the full user-agent string)
  - category: financial
    text: the paying wallet address, transaction ID, network, amount and the hostname of what was paid for
  - category: contact
    text: any label you gave it, its creation date and your credit balance
  - category: location
    text: If you choose your country for the card checkout, we store that country code with these events
  - category: communication
    text: the reported URL without its query string, the problem type and the short note you add (up to 300 characters)
  deletion:
    route: Email contact@agentreader.xyz
    text: Email contact@agentreader.xyz . To find your records we may need your IP address, API key prefix or wallet address.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service and process payments
    text: We use this data to provide the Service and process payments (performance of a contract)
  - purpose: Keep payment records
    text: to keep payment records (legal obligation)
  - purpose: Security, abuse prevention and aggregate usage counts
    text: to keep the Service secure, prevent free-tier abuse, improve reliability and count, in aggregate only, how the Service is used and paid for (legitimate interests)
  residency:
  - region: Germany (EU)
    text: 'Hosting: Oracle Cloud, Frankfurt, Germany (EU).'
  retention:
  - period: 30 days
    scope: Request log
    text: 'Request log: 30 days, then deleted automatically.'
  - period: 30 days
    scope: Page and checkout events
    text: 'Page and checkout events: 30 days, then deleted automatically.'
  - period: 90 days
    scope: Issue reports
    text: 'Issue reports: 90 days, then deleted automatically.'
  - period: 7 days
    scope: Free-tier counters
    text: 'Free-tier counters: 7 days, then deleted automatically.'
  - period: 7 years
    scope: Payment records
    text: 'Payment records: 7 years, as required by Dutch tax law.'
  - period: 10 minutes
    scope: Cache
    text: 'Cache: 10 minutes.'
  - period: up to 7 days
    scope: Consent cookies
    text: 'Consent cookies: up to 7 days.'
  - period: at most 24 hours
    scope: In-memory rate-limit data
    text: 'In-memory rate-limit data: at most 24 hours.'
  rights:
  - right: Access, correction, deletion, restriction, objection, portability
    text: Under the GDPR you can ask for access to your data, correction, deletion, restriction, objection or a portable copy.
  - right: Complain to supervisory authority
    text: You can also complain to your data protection authority; in the Netherlands that is the Autoriteit Persoonsgegevens.
  role:
    text: AgentReader (agentreader.xyz) is responsible for the data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't sell data, show ads or use tracking cookies.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: If data is processed outside the EEA, we rely on appropriate safeguards such as the EU Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AgentReader
provenance_date: '2026-11-09'
provider_name: AgentReader
provider_slug: agentreader-xyz
slug: agentreader-xyz-privacy-policy
source_date: '2026-11-09'
source_filename: agentreader-xyz-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentreader.xyz/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AgentReader\naid: agentreader-xyz\nurl: https://agentreader.xyz/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AgentReader (agentreader.xyz) is responsible for the data described here.\ndata_categories:\n- category: identifying\n  text: 'a short pseudonymous caller ID: a keyed hash (HMAC-SHA-256 with a secret salt kept on our server) of your\n    IP address, or of your API key if you use one'\n- category: device\n  text: a coarse user-agent family, such as \"browser\", \"python\" or \"claude\" (never the full user-agent string)\n- category: financial\n  text: the paying wallet address,\
  \ transaction ID, network, amount and the hostname of what was paid for\n- category: contact\n  text: any label you gave it, its creation date and your credit balance\n- category: location\n  text: If you choose your country for the card checkout, we store that country code with these events\n- category: communication\n  text: the reported URL without its query string, the problem type and the short note you add (up to 300 characters)\npurposes:\n- purpose: Provide the Service and process payments\n  text: We use this data to provide the Service and process payments (performance of a contract)\n- purpose: Keep payment records\n  text: to keep payment records (legal obligation)\n- purpose: Security, abuse prevention and aggregate usage counts\n  text: to keep the Service secure, prevent free-tier abuse, improve reliability and count, in aggregate only, how\n    the Service is used and paid for (legitimate interests)\nretention:\n- scope: Request log\n  period: 30 days\n  text: 'Request\
  \ log: 30 days, then deleted automatically.'\n- scope: Page and checkout events\n  period: 30 days\n  text: 'Page and checkout events: 30 days, then deleted automatically.'\n- scope: Issue reports\n  period: 90 days\n  text: 'Issue reports: 90 days, then deleted automatically.'\n- scope: Free-tier counters\n  period: 7 days\n  text: 'Free-tier counters: 7 days, then deleted automatically.'\n- scope: Payment records\n  period: 7 years\n  text: 'Payment records: 7 years, as required by Dutch tax law.'\n- scope: Cache\n  period: 10 minutes\n  text: 'Cache: 10 minutes.'\n- scope: Consent cookies\n  period: up to 7 days\n  text: 'Consent cookies: up to 7 days.'\n- scope: In-memory rate-limit data\n  period: at most 24 hours\n  text: 'In-memory rate-limit data: at most 24 hours.'\nresidency:\n- region: Germany (EU)\n  text: 'Hosting: Oracle Cloud, Frankfurt, Germany (EU).'\ntransfers:\n- mechanism: SCC\n  text: If data is processed outside the EEA, we rely on appropriate safeguards such as the\
  \ EU Standard Contractual\n    Clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email contact@agentreader.xyz\n  text: Email contact@agentreader.xyz . To find your records we may need your IP address, API key prefix or wallet\n    address.\nrights:\n- right: Access, correction, deletion, restriction, objection, portability\n  text: Under the GDPR you can ask for access to your data, correction, deletion, restriction, objection or a portable\n    copy.\n- right: Complain to supervisory authority\n  text: You can also complain to your data protection authority; in the Netherlands that is the Autoriteit Persoonsgegevens.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell data, show ads or use tracking cookies.\n"
source_yaml_url: https://artifacts.apis.io/agentreader-xyz/privacy/agentreader-xyz-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from AgentReader's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Data Processing
- PDF
- Markdown
- Agent Tools
---
