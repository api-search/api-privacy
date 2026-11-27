---
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — name, email address, company name
  - category: behavioral
    text: Usage data — API calls, agent runs, browser sessions (automated testing only)
  - category: device
    text: Technical data — IP address, browser type, timestamps
  - category: financial
    text: Payment data — processed by Stripe; we do not store card numbers
  - category: identifying
    source: https://aiqaramba.com/dpa/
    text: Test account credentials provided by the Controller (usernames, passwords, API keys)
  - category: contact
    source: https://aiqaramba.com/dpa/
    text: Page content encountered during testing, which may include names, email addresses, or other personal data visible in the Controller's application
  - category: communication
    source: https://aiqaramba.com/dpa/
    text: Email content accessed through Microsoft 365 integration, if enabled by the Controller (sender, recipient, subject, body, timestamps)
  - category: device
    source: https://aiqaramba.com/dpa/
    text: Browser metadata including URLs visited, console logs, and network request metadata (URLs, status codes, response sizes)
  - category: other
    source: https://aiqaramba.com/dpa/
    text: Screenshots and video recordings of the Controller's application during agent sessions
  deletion:
    route: Request earlier deletion of agent run data; contact alexander.rogiers@alex-ai.eu to exercise rights
    text: Agent run data (screenshots, logs) is retained for 90 days unless you request earlier deletion.
  dpa:
    available: true
    source: https://aiqaramba.com/dpa/
    text: To request a signed copy of this DPA, email us with your company details and subscription reference.
    url: https://aiqaramba.com/dpa/
  purposes:
  - purpose: Provide and improve the service
    text: We process personal data to provide and improve the Aiqaramba service (contract performance, Art. 6(1)(b) GDPR)
  - purpose: Legal obligations
    text: to comply with legal obligations (Art. 6(1)(c))
  - purpose: Platform security and analytics
    text: for our legitimate interests in platform security and analytics (Art. 6(1)(f))
  - purpose: Automated browser-based testing and quality assurance
    source: https://aiqaramba.com/dpa/
    text: Automated browser-based testing and quality assurance of the Controller's web applications
  - purpose: Produce test reports and identify defects
    source: https://aiqaramba.com/dpa/
    text: in order to produce test reports and identify defects
  residency:
  - region: EU/EEA
    text: All data is processed within the EU/EEA.
  - region: EU
    source: https://aiqaramba.com/dpa/
    text: All core processing infrastructure is located in the EU (Google Cloud, Belgium region).
  retention:
  - period: the duration of your subscription plus 30 days
    scope: Account data
    text: Account data is retained for the duration of your subscription plus 30 days.
  - period: 90 days
    scope: Agent run data
    text: Agent run data (screenshots, logs) is retained for 90 days unless you request earlier deletion.
  - period: null
    scope: Payment records
    text: Payment records are kept as required by Belgian tax law.
  - period: ninety (90) days
    scope: Agent session data
    source: https://aiqaramba.com/dpa/
    text: Agent session data (screenshots, conversation logs, test results) is retained for ninety (90) days after creation, after which it is automatically deleted.
  - period: thirty (30) calendar days
    scope: Deletion after termination
    source: https://aiqaramba.com/dpa/
    text: Within thirty (30) calendar days after termination (or after providing the copy under paragraph 1, whichever is later), securely delete all Personal Data
  rights:
  - right: Access
    text: Under GDPR you have the right to access, rectify, erase, restrict, port, and object to processing of your personal data.
  - right: Complaint to supervisory authority
    text: You also have the right to lodge a complaint with the Belgian Data Protection Authority (GBA).
  - right: Data subject rights assistance
    source: https://aiqaramba.com/dpa/
    text: Aiqaramba shall, taking into account the nature of the processing, provide reasonable assistance to Customer in responding to requests from data subjects exercising their rights under the GDPR (access, rectification, erasure, restriction, portability, objection).
  role:
    text: Alex AI BV, Jozef Plateaustraat 75/201, 9000 Gent, Belgium (BCE 1029.742.102) is the data controller for personal data processed through the Aiqaramba platform and website.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: A full list of sub-processors is available on request.
    url: null
  transfers:
  - mechanism: SCC
    text: Where transfers outside the EEA are necessary (e.g. support tools), we rely on Standard Contractual Clauses or adequacy decisions.
  - mechanism: adequacy
    text: Where transfers outside the EEA are necessary (e.g. support tools), we rely on Standard Contractual Clauses or adequacy decisions.
  - mechanism: SCC
    source: https://aiqaramba.com/dpa/
    text: 'relying on the EU Standard Contractual Clauses (Module 2: Controller to Processor) or adequacy decisions, as applicable.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Aiqaramba
provenance_date: '2026-11-09'
provider_name: Aiqaramba
provider_slug: aiqaramba-com
slug: aiqaramba-com-privacy-policy
source_date: '2026-11-09'
source_filename: aiqaramba-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://aiqaramba.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Aiqaramba\naid: aiqaramba-com\nurl: https://aiqaramba.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://aiqaramba.com/dpa/\n  - https://aiqaramba.com/privacy/\nrole:\n  value: controller\n  text: Alex AI BV, Jozef Plateaustraat 75/201, 9000 Gent, Belgium (BCE 1029.742.102) is the data controller for\n    personal data processed through the Aiqaramba platform and website.\ndata_categories:\n- category: identifying\n  text: Account data — name, email address, company name\n- category: behavioral\n  text: Usage data — API calls, agent runs, browser sessions (automated testing only)\n- category:\
  \ device\n  text: Technical data — IP address, browser type, timestamps\n- category: financial\n  text: Payment data — processed by Stripe; we do not store card numbers\n- category: identifying\n  text: Test account credentials provided by the Controller (usernames, passwords, API keys)\n  source: https://aiqaramba.com/dpa/\n- category: contact\n  text: Page content encountered during testing, which may include names, email addresses, or other personal data\n    visible in the Controller's application\n  source: https://aiqaramba.com/dpa/\n- category: communication\n  text: Email content accessed through Microsoft 365 integration, if enabled by the Controller (sender, recipient,\n    subject, body, timestamps)\n  source: https://aiqaramba.com/dpa/\n- category: device\n  text: Browser metadata including URLs visited, console logs, and network request metadata (URLs, status codes,\n    response sizes)\n  source: https://aiqaramba.com/dpa/\n- category: other\n  text: Screenshots and video\
  \ recordings of the Controller's application during agent sessions\n  source: https://aiqaramba.com/dpa/\npurposes:\n- purpose: Provide and improve the service\n  text: We process personal data to provide and improve the Aiqaramba service (contract performance, Art. 6(1)(b)\n    GDPR)\n- purpose: Legal obligations\n  text: to comply with legal obligations (Art. 6(1)(c))\n- purpose: Platform security and analytics\n  text: for our legitimate interests in platform security and analytics (Art. 6(1)(f))\n- purpose: Automated browser-based testing and quality assurance\n  text: Automated browser-based testing and quality assurance of the Controller's web applications\n  source: https://aiqaramba.com/dpa/\n- purpose: Produce test reports and identify defects\n  text: in order to produce test reports and identify defects\n  source: https://aiqaramba.com/dpa/\nretention:\n- scope: Account data\n  period: the duration of your subscription plus 30 days\n  text: Account data is retained for the duration\
  \ of your subscription plus 30 days.\n- scope: Agent run data\n  period: 90 days\n  text: Agent run data (screenshots, logs) is retained for 90 days unless you request earlier deletion.\n- scope: Payment records\n  period: null\n  text: Payment records are kept as required by Belgian tax law.\n- scope: Agent session data\n  period: ninety (90) days\n  text: Agent session data (screenshots, conversation logs, test results) is retained for ninety (90) days after\n    creation, after which it is automatically deleted.\n  source: https://aiqaramba.com/dpa/\n- scope: Deletion after termination\n  period: thirty (30) calendar days\n  text: Within thirty (30) calendar days after termination (or after providing the copy under paragraph 1, whichever\n    is later), securely delete all Personal Data\n  source: https://aiqaramba.com/dpa/\nresidency:\n- region: EU/EEA\n  text: All data is processed within the EU/EEA.\n- region: EU\n  text: All core processing infrastructure is located in the EU (Google\
  \ Cloud, Belgium region).\n  source: https://aiqaramba.com/dpa/\ntransfers:\n- mechanism: SCC\n  text: Where transfers outside the EEA are necessary (e.g. support tools), we rely on Standard Contractual Clauses\n    or adequacy decisions.\n- mechanism: adequacy\n  text: Where transfers outside the EEA are necessary (e.g. support tools), we rely on Standard Contractual Clauses\n    or adequacy decisions.\n- mechanism: SCC\n  text: 'relying on the EU Standard Contractual Clauses (Module 2: Controller to Processor) or adequacy decisions,\n    as applicable.'\n  source: https://aiqaramba.com/dpa/\nsubprocessors:\n  url: null\n  text: A full list of sub-processors is available on request.\ndpa:\n  available: true\n  url: https://aiqaramba.com/dpa/\n  text: To request a signed copy of this DPA, email us with your company details and subscription reference.\n  source: https://aiqaramba.com/dpa/\ndeletion:\n  route: Request earlier deletion of agent run data; contact alexander.rogiers@alex-ai.eu\
  \ to exercise rights\n  text: Agent run data (screenshots, logs) is retained for 90 days unless you request earlier deletion.\nrights:\n- right: Access\n  text: Under GDPR you have the right to access, rectify, erase, restrict, port, and object to processing of your\n    personal data.\n- right: Complaint to supervisory authority\n  text: You also have the right to lodge a complaint with the Belgian Data Protection Authority (GBA).\n- right: Data subject rights assistance\n  text: Aiqaramba shall, taking into account the nature of the processing, provide reasonable assistance to Customer\n    in responding to requests from data subjects exercising their rights under the GDPR (access, rectification,\n    erasure, restriction, portability, objection).\n  source: https://aiqaramba.com/dpa/\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/aiqaramba-com/privacy/aiqaramba-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 32 quoted statements, read from Aiqaramba's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Monitoring
- Tracing
- Evaluation
- Cost-Quality
---
