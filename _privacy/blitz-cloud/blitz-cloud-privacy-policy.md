---
api_specs:
- filename: blitz-cloud-openapi-generated.yml
  format: yaml
  label: BlitzWorks API
  slug: blitz-cloud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blitz-cloud/openapi/_ae-authored/blitz-cloud-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: contact
    text: your email address, your name, your blitz.cloud address (such as lena.prod.page ) and your plan
  - category: device
    text: Cloudflare processes your IP address, the address requested, date and time, browser and device details and the content of the request
  - category: financial
    text: Stripe processes your name, your email address, your billing address
  - category: behavioral
    text: 'how you use blitz.cloud: every night, how many apps, databases, storage and builds your account has'
  - category: communication
    text: your message goes by email to our inbox feedback@blitzworks.io
  deletion:
    route: Settings, delete account
    text: Under Settings you can also delete your account.
  dpa:
    available: true
    text: You can download the data processing agreement as a PDF once you are signed in, in the dashboard under Settings, Privacy.
    url: null
  purposes:
  - purpose: Performing the contract
    text: The legal basis is performing the contract for blitz.cloud and the steps before it (Art. 6(1)(b) GDPR).
  - purpose: Secure and fast delivery of pages
    text: The legal basis is our legitimate interest in secure and fast delivery (Art. 6(1)(f) GDPR).
  - purpose: Measuring use of own service
    text: The legal basis is our legitimate interest in measuring use of our own service with as little data as possible (Art. 6(1)(f) GDPR).
  - purpose: Abuse prevention
    text: The legal basis is our legitimate interest in protecting the platform and every customer from abuse (Art. 6(1)(f) GDPR).
  residency:
  - region: Germany
    text: Your account, your apps, their files and their databases are stored in Germany, and for some apps in Finland.
  - region: EU (Finland)
    text: Backup copies and the built images of your apps are kept separately, with the same operator, in the EU (Finland).
  retention:
  - period: 30 days
    scope: Sign-in log (Keycloak)
    text: The entries are deleted automatically after 30 days.
  - period: 35 days
    scope: Traffic numbers per app
    text: Traffic numbers per app 35 days
  - period: 400 days
    scope: Usage history
    text: We delete this data after 400 days and with your account.
  - period: until you delete them or your account
    scope: Account data, apps, databases, settings
    text: Account data, apps, databases, settings until you delete them or your account
  - period: 7 nights
    scope: Free plan database backups
    text: We keep the copies of the last 7 nights on which a database was copied on the free plan
  - period: 30 days
    scope: Log of emails sent (content)
    text: We delete the content after 30 days and the entry after 180 days.
  rights:
  - right: access, rectification, erasure, restriction, portability
    text: You have the right of access (Art. 15 GDPR), rectification (Art. 16), erasure (Art. 17), restriction of processing (Art. 18) and data portability (Art. 20).
  - right: withdraw consent
    text: You can withdraw consent at any time with effect for the future (Art. 7(3)).
  - right: object
    text: you can object at any time on grounds relating to your particular situation (Art. 21 GDPR)
  - right: complain to authority
    text: You can also complain to a data protection supervisory authority.
  role:
    text: BlitzWorks UG (haftungsbeschränkt), represented by its managing director Simon Gloël, Graßer Weg 73, 93053 Regensburg, Germany
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data.
  subprocessors:
    text: Some service providers process data on our behalf or receive it because you use their service.
    url: null
  transfers:
  - mechanism: DPF
    text: The transfer is based on the European Commission's adequacy decision for the EU-US Data Privacy Framework, under which Cloudflare is certified, and on standard contractual clauses.
  - mechanism: other
    text: The transfer is necessary to perform the contract with you (Art. 49(1)(b) GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BlitzWorks
provenance_date: '2026-11-09'
provider_name: BlitzWorks
provider_slug: blitz-cloud
slug: blitz-cloud-privacy-policy
source_date: '2026-11-09'
source_filename: blitz-cloud-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://blitz.cloud/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BlitzWorks\naid: blitz-cloud\nurl: https://blitz.cloud/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: BlitzWorks UG (haftungsbeschränkt), represented by its managing director Simon Gloël, Graßer Weg 73, 93053\n    Regensburg, Germany\ndata_categories:\n- category: contact\n  text: your email address, your name, your blitz.cloud address (such as lena.prod.page ) and your plan\n- category: device\n  text: Cloudflare processes your IP address, the address requested, date and time, browser and device details and\n    the content of the request\n- category: financial\n  text: Stripe processes\
  \ your name, your email address, your billing address\n- category: behavioral\n  text: 'how you use blitz.cloud: every night, how many apps, databases, storage and builds your account has'\n- category: communication\n  text: your message goes by email to our inbox feedback@blitzworks.io\npurposes:\n- purpose: Performing the contract\n  text: The legal basis is performing the contract for blitz.cloud and the steps before it (Art. 6(1)(b) GDPR).\n- purpose: Secure and fast delivery of pages\n  text: The legal basis is our legitimate interest in secure and fast delivery (Art. 6(1)(f) GDPR).\n- purpose: Measuring use of own service\n  text: The legal basis is our legitimate interest in measuring use of our own service with as little data as possible\n    (Art. 6(1)(f) GDPR).\n- purpose: Abuse prevention\n  text: The legal basis is our legitimate interest in protecting the platform and every customer from abuse (Art.\n    6(1)(f) GDPR).\nretention:\n- scope: Sign-in log (Keycloak)\n  period:\
  \ 30 days\n  text: The entries are deleted automatically after 30 days.\n- scope: Traffic numbers per app\n  period: 35 days\n  text: Traffic numbers per app 35 days\n- scope: Usage history\n  period: 400 days\n  text: We delete this data after 400 days and with your account.\n- scope: Account data, apps, databases, settings\n  period: until you delete them or your account\n  text: Account data, apps, databases, settings until you delete them or your account\n- scope: Free plan database backups\n  period: 7 nights\n  text: We keep the copies of the last 7 nights on which a database was copied on the free plan\n- scope: Log of emails sent (content)\n  period: 30 days\n  text: We delete the content after 30 days and the entry after 180 days.\nresidency:\n- region: Germany\n  text: Your account, your apps, their files and their databases are stored in Germany, and for some apps in Finland.\n- region: EU (Finland)\n  text: Backup copies and the built images of your apps are kept separately,\
  \ with the same operator, in the EU (Finland).\ntransfers:\n- mechanism: DPF\n  text: The transfer is based on the European Commission's adequacy decision for the EU-US Data Privacy Framework,\n    under which Cloudflare is certified, and on standard contractual clauses.\n- mechanism: other\n  text: The transfer is necessary to perform the contract with you (Art. 49(1)(b) GDPR).\nsubprocessors:\n  url: null\n  text: Some service providers process data on our behalf or receive it because you use their service.\ndpa:\n  available: true\n  url: null\n  text: You can download the data processing agreement as a PDF once you are signed in, in the dashboard under Settings,\n    Privacy.\ndeletion:\n  route: Settings, delete account\n  text: Under Settings you can also delete your account.\nrights:\n- right: access, rectification, erasure, restriction, portability\n  text: You have the right of access (Art. 15 GDPR), rectification (Art. 16), erasure (Art. 17), restriction of\n    processing (Art.\
  \ 18) and data portability (Art. 20).\n- right: withdraw consent\n  text: You can withdraw consent at any time with effect for the future (Art. 7(3)).\n- right: object\n  text: you can object at any time on grounds relating to your particular situation (Art. 21 GDPR)\n- right: complain to authority\n  text: You can also complain to a data protection supervisory authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data.\n"
source_yaml_url: https://artifacts.apis.io/blitz-cloud/privacy/blitz-cloud-privacy-policy.yml
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
summary_line: 28 quoted statements, read from BlitzWorks's own page on 2026-11-09.
synthetic: false
tags:
- Hosting
- EU
- Application
- Bots
- Artificial Intelligence
- Company
---
