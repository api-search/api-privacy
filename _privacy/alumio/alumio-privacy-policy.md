---
api_specs:
- filename: alumio-openapi-generated.yml
  format: yaml
  label: Alumio API
  slug: alumio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alumio/openapi/_ae-authored/alumio-openapi-generated.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: We process your name, job title, business contact details, employer, publicly available professional information and our correspondence with you.
  - category: device
    text: We process your IP address, device and browser characteristics, the pages you view and how you move through the site.
  - category: communication
    text: We process your name and email address, whether you opened or clicked a message, and the events you attended.
  - category: professional
    text: We process your application and CV, our correspondence, interview notes and any references you provide.
  deletion:
    route: email privacy@alumio.com
    text: Send your request to privacy@alumio.com .
  dpa:
    available: true
    text: Every provider that handles personal data on our behalf is bound by a data processing agreement that meets the requirements of the GDPR.
    url: null
  purposes:
  - purpose: operate and secure websites
    text: We use this to operate and secure our websites, to measure how they are used and to improve our content.
  - purpose: deliver and support service
    text: We use this to deliver and support the service, to administer the account, to invoice and to manage the contract.
  - purpose: business marketing
    text: We use this to contact you about our services, to assess whether there is a fit and to arrange meetings.
  residency:
  - region: European Economic Area
    text: We keep processing inside the European Economic Area wherever we can.
  retention:
  - period: three years
    scope: business prospects
    text: We remove your details from our contact database within three years of our last meaningful contact, or immediately if you object.
  - period: seven years
    scope: financial records of customer contacts
    text: financial records for the statutory retention period of seven years
  - period: four weeks
    scope: job applications
    text: We keep this for four weeks after the procedure ends, or one year if you agree to it.
  rights:
  - right: access
    text: give you a copy of the personal data we hold about you
  - right: rectification
    text: correct or complete it if it is wrong or incomplete
  - right: erasure
    text: delete it
  - right: restriction
    text: limit what we do with it while a question about it is open
  - right: portability
    text: transfer the data you gave us to another party
  - right: objection
    text: You can also object to our processing.
  - right: withdraw consent
    text: Where we rely on your consent, you can withdraw it at any time
  role:
    text: As a controller. For everything described here, we decide why and how personal data is used. This statement applies.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data, and we do not share it with third parties for their own marketing.
  subprocessors:
    text: We keep a current list of these providers and will send it to you on request at privacy@alumio.com .
    url: null
  transfers:
  - mechanism: adequacy
    text: we rely on an adequacy decision of the European Commission
  - mechanism: SCC
    text: the European Commission's standard contractual clauses together with any additional measures our assessment shows to be necessary
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Alumio
provenance_date: '2026-11-09'
provider_name: Alumio
provider_slug: alumio
slug: alumio-privacy-policy
source_date: '2026-11-09'
source_filename: alumio-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.alumio.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Alumio\naid: alumio\nurl: https://www.alumio.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: As a controller. For everything described here, we decide why and how personal data is used. This statement\n    applies.\ndata_categories:\n- category: identifying\n  text: We process your name, job title, business contact details, employer, publicly available professional information\n    and our correspondence with you.\n- category: device\n  text: We process your IP address, device and browser characteristics, the pages you view and how you move through\n    the site.\n- category: communication\n\
  \  text: We process your name and email address, whether you opened or clicked a message, and the events you attended.\n- category: professional\n  text: We process your application and CV, our correspondence, interview notes and any references you provide.\npurposes:\n- purpose: operate and secure websites\n  text: We use this to operate and secure our websites, to measure how they are used and to improve our content.\n- purpose: deliver and support service\n  text: We use this to deliver and support the service, to administer the account, to invoice and to manage the\n    contract.\n- purpose: business marketing\n  text: We use this to contact you about our services, to assess whether there is a fit and to arrange meetings.\nretention:\n- scope: business prospects\n  period: three years\n  text: We remove your details from our contact database within three years of our last meaningful contact, or immediately\n    if you object.\n- scope: financial records of customer contacts\n  period:\
  \ seven years\n  text: financial records for the statutory retention period of seven years\n- scope: job applications\n  period: four weeks\n  text: We keep this for four weeks after the procedure ends, or one year if you agree to it.\nresidency:\n- region: European Economic Area\n  text: We keep processing inside the European Economic Area wherever we can.\ntransfers:\n- mechanism: adequacy\n  text: we rely on an adequacy decision of the European Commission\n- mechanism: SCC\n  text: the European Commission's standard contractual clauses together with any additional measures our assessment\n    shows to be necessary\nsubprocessors:\n  url: null\n  text: We keep a current list of these providers and will send it to you on request at privacy@alumio.com .\ndpa:\n  available: true\n  url: null\n  text: Every provider that handles personal data on our behalf is bound by a data processing agreement that meets\n    the requirements of the GDPR.\ndeletion:\n  route: email privacy@alumio.com\n\
  \  text: Send your request to privacy@alumio.com .\nrights:\n- right: access\n  text: give you a copy of the personal data we hold about you\n- right: rectification\n  text: correct or complete it if it is wrong or incomplete\n- right: erasure\n  text: delete it\n- right: restriction\n  text: limit what we do with it while a question about it is open\n- right: portability\n  text: transfer the data you gave us to another party\n- right: objection\n  text: You can also object to our processing.\n- right: withdraw consent\n  text: Where we rely on your consent, you can withdraw it at any time\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data, and we do not share it with third parties for their own marketing.\n"
source_yaml_url: https://artifacts.apis.io/alumio/privacy/alumio-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Alumio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- iPaaS
- Enterprise
---
