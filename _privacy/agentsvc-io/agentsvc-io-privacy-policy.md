---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: the IP address and user agent of the request, the time, the service and its input
  - category: financial
    text: 'for paid calls the payment: wallet address, amount, network and transaction'
  - category: contact
    text: When you connect a client such as Claude or ChatGPT with OAuth at /mcp/credit , we store the client name and redirect address it registered
  - category: behavioral
    text: For page statistics the site sends the page, referrer, browser, operating system, screen size and campaign parameters
  - category: device
    text: the web server logs each request (IP address, user agent, path, status, time)
  deletion:
    route: Write to agents@agentsvc.io
    text: Write to agents@agentsvc.io .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: run the call and settle payment
    text: We need this to run the call, to verify and settle the payment, to stop abuse and to fix errors.
  - purpose: website statistics
    text: 'Legal basis: legitimate interest in knowing which pages are used (Art. 6(1)(f)).'
  - purpose: preventing abuse of free credit
    text: 'Legal basis: Art. 6(1)(b) GDPR (you ask for the credit) and Art. 6(1)(f) GDPR (preventing abuse of the free credit).'
  retention:
  - period: 30 days
    scope: Server logs
    text: Server logs (IP address, user agent, path, status) 30 days in the database, then compressed archive ; deleted after 90 days .
  - period: 10 years
    scope: Payments
    text: Payments (wallet address, amount, transaction hash, service) 10 years ; required for bookkeeping; this data is public on the blockchain anyway .
  - period: 180 days after the last top-up
    scope: Prepaid credit
    text: Prepaid credit (hash of the token, paying wallet, balance) 180 days after the last top-up ; then expired .
  - period: 30 days
    scope: Payment journal
    text: Payment journal (structure of your input, for reconciling payments) 30 days ; deleted .
  - period: IP removed after 90 days
    scope: Website statistics
    text: Website statistics (pages, referrer, browser, country, shortened IP) IP removed after 90 days ; no cookies, nothing stored in your browser .
  rights:
  - right: access
    text: You can ask for access to your data, correction, deletion, restriction of processing and a copy in a common format
  - right: objection
    text: you can object to processing based on legitimate interest (Art. 15 to 21 GDPR)
  - right: complain to supervisory authority
    text: You can also complain to a data protection supervisory authority, for example in the EU country where you live.
  role:
    text: 'The controller under the GDPR is the operator of agentsvc.io: Jakob Baumgärtner c/o IP-Management #8061 Ludwig-Erhard-Straße 18 20459 Hamburg Germany'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not use it for advertising or to train AI models.
  subprocessors:
    text: 'Hosting: Hetzner Online GmbH, Germany (server and encrypted backups). Processor under Art. 28 GDPR. Payment settlement: Coinbase (CDP facilitator, USA) and PayAI receive the signed payment (wallet address, amount) to verify and settle it on the blockchain.'
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers to the USA (Coinbase, Anthropic, Google) rely on the EU-U.S. Data Privacy Framework where the recipient is certified, otherwise on the EU standard contractual clauses (Art. 46 GDPR).
  - mechanism: SCC
    text: otherwise on the EU standard contractual clauses (Art. 46 GDPR)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agentsvc
provenance_date: '2026-11-09'
provider_name: Agentsvc
provider_slug: agentsvc-io
slug: agentsvc-io-privacy-policy
source_date: '2026-11-09'
source_filename: agentsvc-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://agentsvc.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agentsvc\naid: agentsvc-io\nurl: https://agentsvc.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller under the GDPR is the operator of agentsvc.io: Jakob Baumgärtner c/o IP-Management #8061\n    Ludwig-Erhard-Straße 18 20459 Hamburg Germany'\ndata_categories:\n- category: identifying\n  text: the IP address and user agent of the request, the time, the service and its input\n- category: financial\n  text: 'for paid calls the payment: wallet address, amount, network and transaction'\n- category: contact\n  text: When you connect a client such as Claude or ChatGPT with\
  \ OAuth at /mcp/credit , we store the client name\n    and redirect address it registered\n- category: behavioral\n  text: For page statistics the site sends the page, referrer, browser, operating system, screen size and campaign\n    parameters\n- category: device\n  text: the web server logs each request (IP address, user agent, path, status, time)\npurposes:\n- purpose: run the call and settle payment\n  text: We need this to run the call, to verify and settle the payment, to stop abuse and to fix errors.\n- purpose: website statistics\n  text: 'Legal basis: legitimate interest in knowing which pages are used (Art. 6(1)(f)).'\n- purpose: preventing abuse of free credit\n  text: 'Legal basis: Art. 6(1)(b) GDPR (you ask for the credit) and Art. 6(1)(f) GDPR (preventing abuse of the\n    free credit).'\nretention:\n- scope: Server logs\n  period: 30 days\n  text: Server logs (IP address, user agent, path, status) 30 days in the database, then compressed archive ; deleted\n    after 90\
  \ days .\n- scope: Payments\n  period: 10 years\n  text: Payments (wallet address, amount, transaction hash, service) 10 years ; required for bookkeeping; this data\n    is public on the blockchain anyway .\n- scope: Prepaid credit\n  period: 180 days after the last top-up\n  text: Prepaid credit (hash of the token, paying wallet, balance) 180 days after the last top-up ; then expired\n    .\n- scope: Payment journal\n  period: 30 days\n  text: Payment journal (structure of your input, for reconciling payments) 30 days ; deleted .\n- scope: Website statistics\n  period: IP removed after 90 days\n  text: Website statistics (pages, referrer, browser, country, shortened IP) IP removed after 90 days ; no cookies,\n    nothing stored in your browser .\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Transfers to the USA (Coinbase, Anthropic, Google) rely on the EU-U.S. Data Privacy Framework where the\n    recipient is certified, otherwise on the EU standard contractual clauses (Art. 46\
  \ GDPR).\n- mechanism: SCC\n  text: otherwise on the EU standard contractual clauses (Art. 46 GDPR)\nsubprocessors:\n  url: null\n  text: 'Hosting: Hetzner Online GmbH, Germany (server and encrypted backups). Processor under Art. 28 GDPR. Payment\n    settlement: Coinbase (CDP facilitator, USA) and PayAI receive the signed payment (wallet address, amount) to\n    verify and settle it on the blockchain.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to agents@agentsvc.io\n  text: Write to agents@agentsvc.io .\nrights:\n- right: access\n  text: You can ask for access to your data, correction, deletion, restriction of processing and a copy in a common\n    format\n- right: objection\n  text: you can object to processing based on legitimate interest (Art. 15 to 21 GDPR)\n- right: complain to supervisory authority\n  text: You can also complain to a data protection supervisory authority, for example in the EU country where you\n    live.\nsale_or_sharing:\n\
  \  stance: prohibited\n  text: We do not sell personal data and do not use it for advertising or to train AI models.\n"
source_yaml_url: https://artifacts.apis.io/agentsvc-io/privacy/agentsvc-io-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Agentsvc's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Marketplace
- Payments
- Web Services
- Agents
---
