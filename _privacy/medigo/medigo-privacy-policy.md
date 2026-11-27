---
api_specs:
- filename: medigo-attachments-api-openapi.yml
  format: yaml
  label: Medigo Attachments API
  slug: medigo-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-attachments-api-openapi.yml
- filename: medigo-inquiries-api-openapi.yml
  format: yaml
  label: Medigo Inquiries API
  slug: medigo-inquiries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-inquiries-api-openapi.yml
- filename: medigo-search-api-openapi.yml
  format: yaml
  label: Medigo Search API
  slug: medigo-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-search-api-openapi.yml
- filename: medigo-second-opinions-api-openapi.yml
  format: yaml
  label: Medigo Second Opinions API
  slug: medigo-second-opinions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-second-opinions-api-openapi.yml
- filename: medigo-tpa-api-openapi.yml
  format: yaml
  label: Medigo Tpa API
  slug: medigo-tpa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-tpa-api-openapi.yml
- filename: medigo-webhooks-api-openapi.yml
  format: yaml
  label: Medigo Webhooks API
  slug: medigo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/medigo/openapi/medigo-webhooks-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: contact
    text: name, email address, company or facility, job title, country, the type of organisation
  - category: device
    text: IP address, date and time, the page requested, the referring page, and browser and operating system
  - category: location
    text: the country, region and city derived from your connection
  - category: health
    text: we process health and claims data
  deletion:
    route: email to dataprotection@medigo.com
    text: To exercise your rights, write to dataprotection@medigo.com
  dpa:
    available: true
    text: We share personal data only with service providers bound by data processing agreements
    url: null
  purposes:
  - purpose: answer enquiries or assess applications
    text: We use them only to answer your enquiry or assess your application.
  - purpose: website security and delivery
    text: This is needed to deliver the website and keep it secure.
  - purpose: website statistics
    text: We use Vercel Web Analytics to understand which pages are used and how visitors find us.
  residency:
  - region: EU
    text: This data is stored and processed within the EU.
  - region: Europe
    text: using servers in Europe
  retention:
  - period: only as long as needed for security
    scope: server logs
    text: Server logs are kept only as long as needed for security and are then deleted.
  - period: once they are concluded
    scope: contact enquiries
    text: We delete enquiries once they are concluded, unless they lead to a contract or we must keep them by law.
  - period: after 24 hours
    scope: visitor counting value
    text: which is discarded after 24 hours
  rights:
  - right: access, rectification, erasure, restriction, portability
    text: You have the right to access, rectification, erasure, restriction of processing and data portability
  - right: withdraw consent
    text: the right to withdraw any consent with effect for the future
  - right: object
    text: you have the right to object to the processing on grounds relating to your particular situation
  - right: complain to supervisory authority
    text: You can also complain to a supervisory authority
  role:
    text: Medigo GmbH, Torstraße 124, 10119 Berlin, Germany, is the controller for the processing described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data or use it for advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: Transfers to Vercel rely on its certification under the EU–US Data Privacy Framework
  - mechanism: SCC
    text: on the EU Standard Contractual Clauses in Vercel’s data processing agreement
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Medigo
provenance_date: '2026-11-10'
provider_name: Medigo
provider_slug: medigo
slug: medigo-privacy-policy
source_date: '2026-11-10'
source_filename: medigo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.medigo.com/en/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Medigo\naid: medigo\nurl: https://www.medigo.com/en/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Medigo GmbH, Torstraße 124, 10119 Berlin, Germany, is the controller for the processing described here.\ndata_categories:\n- category: contact\n  text: name, email address, company or facility, job title, country, the type of organisation\n- category: device\n  text: IP address, date and time, the page requested, the referring page, and browser and operating system\n- category: location\n  text: the country, region and city derived from your connection\n- category: health\n  text:\
  \ we process health and claims data\npurposes:\n- purpose: answer enquiries or assess applications\n  text: We use them only to answer your enquiry or assess your application.\n- purpose: website security and delivery\n  text: This is needed to deliver the website and keep it secure.\n- purpose: website statistics\n  text: We use Vercel Web Analytics to understand which pages are used and how visitors find us.\nretention:\n- scope: server logs\n  period: only as long as needed for security\n  text: Server logs are kept only as long as needed for security and are then deleted.\n- scope: contact enquiries\n  period: once they are concluded\n  text: We delete enquiries once they are concluded, unless they lead to a contract or we must keep them by law.\n- scope: visitor counting value\n  period: after 24 hours\n  text: which is discarded after 24 hours\nresidency:\n- region: EU\n  text: This data is stored and processed within the EU.\n- region: Europe\n  text: using servers in Europe\ntransfers:\n\
  - mechanism: DPF\n  text: Transfers to Vercel rely on its certification under the EU–US Data Privacy Framework\n- mechanism: SCC\n  text: on the EU Standard Contractual Clauses in Vercel’s data processing agreement\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: We share personal data only with service providers bound by data processing agreements\ndeletion:\n  route: email to dataprotection@medigo.com\n  text: To exercise your rights, write to dataprotection@medigo.com\nrights:\n- right: access, rectification, erasure, restriction, portability\n  text: You have the right to access, rectification, erasure, restriction of processing and data portability\n- right: withdraw consent\n  text: the right to withdraw any consent with effect for the future\n- right: object\n  text: you have the right to object to the processing on grounds relating to your particular situation\n- right: complain to supervisory authority\n  text: You can also complain to\
  \ a supervisory authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data or use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/medigo/privacy/medigo-privacy-policy.yml
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
- sale_or_sharing
summary_line: 22 quoted statements, read from Medigo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Healthcare
- Insurance
- Third-Party Administrator
- Claims
- Cost Containment
- Second Medical Opinion
- Medical Travel
- Health Insurance
---
