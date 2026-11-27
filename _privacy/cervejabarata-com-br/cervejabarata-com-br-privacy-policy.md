---
api_specs:
- filename: cervejabarata-com-br-datasets-api-openapi.yml
  format: yaml
  label: Cerveja Barata Datasets API
  slug: cervejabarata-com-br-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cervejabarata-com-br/openapi/cervejabarata-com-br-datasets-api-openapi.yml
- filename: cervejabarata-com-br-mcp-api-openapi.yml
  format: yaml
  label: Cerveja Barata MCP API
  slug: cervejabarata-com-br-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cervejabarata-com-br/openapi/cervejabarata-com-br-mcp-api-openapi.yml
- filename: cervejabarata-com-br-public-api-openapi.yml
  format: yaml
  label: Cerveja Barata Public API
  slug: cervejabarata-com-br-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cervejabarata-com-br/openapi/cervejabarata-com-br-public-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address and technical browser data, processed by Cloudflare.
  - category: contact
    text: Nickname and email are optional.
  - category: communication
    text: the text of the messages and photo captions
  - category: other
    text: the proof (a photo or the NFC-e link)
  deletion:
    route: privacidade@cervejabarata.com.br
    text: Write to privacidade@cervejabarata.com.br saying what you would like.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: site delivery, security and aggregate traffic measurement
    text: to deliver the pages, protect the site from attacks and measure traffic in aggregate, without cookies
  - purpose: spam prevention
    text: To stop spam we keep codes derived from your IP address, not the address itself, for up to 30 days.
  residency:
  - region: outside Brazil
    text: Some of these services process data outside Brazil, for example in the United States, with the safeguards required by Brazil's General Data Protection Law (LGPD).
  retention:
  - period: null
    scope: menu photos
    text: Menu photos are read by artificial intelligence (Cloudflare's Workers AI) only to extract the beer prices, and are not kept.
  - period: 90 days
    scope: contact on menu photos
    text: Your contact, if you give one, is kept encrypted and deleted after 90 days.
  - period: 30 days
    scope: anti-abuse codes
    text: To stop spam we keep codes derived from your IP address, not the address itself, for up to 30 days.
  - period: 24 hours
    scope: photo sent with a No vote
    text: A photo sent with a “No” on “Still this price?” is deleted 24 hours after it was sent.
  - period: 6 months
    scope: submission and vote log
    text: 6 months, then deleted automatically
  - period: 90 days
    scope: WhatsApp conversation
    text: the conversation is deleted 90 days after the last message, unless the bar is a sponsor.
  - period: 90 days
    scope: bar contact record
    text: the contact is deleted 90 days after the last interaction, unless the bar is a sponsor
  rights:
  - right: confirmation, access, correction, anonymisation, blocking, deletion, portability
    text: Under the LGPD you can ask us to confirm whether we process your data, and for access, correction, anonymisation, blocking or deletion, portability, information about sharing and withdrawal of consent.
  - right: objection
    text: You can also object to processing based on legitimate interest
  - right: complaint
    text: complain to Brazil's data protection authority (ANPD)
  role:
    text: Cerveja Barata (cervejabarata.com.br) is the controller of the personal data processed on this site.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: we don't sell data
  subprocessors:
    text: 'Cloudflare: hosting, network, database, anti-bot check, cookieless statistics, email forwarding, automatic reading of menu photos sent to us and the assistant that reads WhatsApp messages and transcribes voice messages.'
    url: null
  transfers:
  - mechanism: other
    text: with the safeguards required by Brazil's General Data Protection Law (LGPD)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cerveja Barata
provenance_date: '2026-11-09'
provider_name: Cerveja Barata
provider_slug: cervejabarata-com-br
slug: cervejabarata-com-br-privacy-policy
source_date: '2026-11-09'
source_filename: cervejabarata-com-br-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cervejabarata.com.br/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cerveja Barata\naid: cervejabarata-com-br\nurl: https://cervejabarata.com.br/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Cerveja Barata (cervejabarata.com.br) is the controller of the personal data processed on this site.\ndata_categories:\n- category: identifying\n  text: IP address and technical browser data, processed by Cloudflare.\n- category: contact\n  text: Nickname and email are optional.\n- category: communication\n  text: the text of the messages and photo captions\n- category: other\n  text: the proof (a photo or the NFC-e link)\npurposes:\n- purpose: site delivery,\
  \ security and aggregate traffic measurement\n  text: to deliver the pages, protect the site from attacks and measure traffic in aggregate, without cookies\n- purpose: spam prevention\n  text: To stop spam we keep codes derived from your IP address, not the address itself, for up to 30 days.\nretention:\n- scope: menu photos\n  period: null\n  text: Menu photos are read by artificial intelligence (Cloudflare's Workers AI) only to extract the beer prices,\n    and are not kept.\n- scope: contact on menu photos\n  period: 90 days\n  text: Your contact, if you give one, is kept encrypted and deleted after 90 days.\n- scope: anti-abuse codes\n  period: 30 days\n  text: To stop spam we keep codes derived from your IP address, not the address itself, for up to 30 days.\n- scope: photo sent with a No vote\n  period: 24 hours\n  text: A photo sent with a “No” on “Still this price?” is deleted 24 hours after it was sent.\n- scope: submission and vote log\n  period: 6 months\n  text: 6 months, then\
  \ deleted automatically\n- scope: WhatsApp conversation\n  period: 90 days\n  text: the conversation is deleted 90 days after the last message, unless the bar is a sponsor.\n- scope: bar contact record\n  period: 90 days\n  text: the contact is deleted 90 days after the last interaction, unless the bar is a sponsor\nresidency:\n- region: outside Brazil\n  text: Some of these services process data outside Brazil, for example in the United States, with the safeguards\n    required by Brazil's General Data Protection Law (LGPD).\ntransfers:\n- mechanism: other\n  text: with the safeguards required by Brazil's General Data Protection Law (LGPD)\nsubprocessors:\n  url: null\n  text: 'Cloudflare: hosting, network, database, anti-bot check, cookieless statistics, email forwarding, automatic\n    reading of menu photos sent to us and the assistant that reads WhatsApp messages and transcribes voice messages.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: privacidade@cervejabarata.com.br\n\
  \  text: Write to privacidade@cervejabarata.com.br saying what you would like.\nrights:\n- right: confirmation, access, correction, anonymisation, blocking, deletion, portability\n  text: Under the LGPD you can ask us to confirm whether we process your data, and for access, correction, anonymisation,\n    blocking or deletion, portability, information about sharing and withdrawal of consent.\n- right: objection\n  text: You can also object to processing based on legitimate interest\n- right: complaint\n  text: complain to Brazil's data protection authority (ANPD)\nsale_or_sharing:\n  stance: prohibited\n  text: we don't sell data\n"
source_yaml_url: https://artifacts.apis.io/cervejabarata-com-br/privacy/cervejabarata-com-br-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Cerveja Barata's own page on 2026-11-09.
synthetic: false
tags:
- Beer
- Price Comparison
- Brazil
- Salvador
- LauroDeFreitas
---
