---
api_specs:
- filename: astraverify-com-discoverability-api-openapi.yml
  format: yaml
  label: AstraVerify Discoverability API
  slug: astraverify-com-discoverability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-discoverability-api-openapi.yml
- filename: astraverify-com-email-api-openapi.yml
  format: yaml
  label: AstraVerify Email API
  slug: astraverify-com-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-email-api-openapi.yml
- filename: astraverify-com-fetch-as-api-openapi.yml
  format: yaml
  label: AstraVerify Fetch As API
  slug: astraverify-com-fetch-as-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-fetch-as-api-openapi.yml
- filename: astraverify-com-report-api-openapi.yml
  format: yaml
  label: AstraVerify Report API
  slug: astraverify-com-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-report-api-openapi.yml
- filename: astraverify-com-verify-api-openapi.yml
  format: yaml
  label: AstraVerify Verify API
  slug: astraverify-com-verify-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/astraverify-com/openapi/astraverify-com-verify-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your IP address and browser user-agent string with each request, including with each scan you run.
  - category: contact
    text: Your email address, when you ask for an emailed report, request a link to your page, send a fix request, or pay for a service.
  - category: financial
    text: We receive your email address, the amount, the package and Stripe’s customer and subscription identifiers. We never see card numbers.
  - category: communication
    text: 'If you email us at [email protected] , we store the message: who it is from, the subject and the text, together with a case number and how it was handled.'
  - category: device
    text: The headers of a test email you choose to send us for the live DKIM check.
  deletion:
    route: Write to the privacy contact to request deletion
    text: You can ask us to show you, correct or delete the personal data we hold about you, to stop marketing email, or to exclude a domain from scanning altogether.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Produce scores and recommendations
    text: 'Purpose: producing the scores and recommendations, and caching them so a repeat visit does not scan the domain again.'
  - purpose: Rate limiting and abuse prevention
    text: 'Purpose: rate limiting, abuse prevention and diagnosing faults.'
  - purpose: Deliver requested service
    text: 'Purpose: delivering what you asked for and, for customers, giving you access to your history and orders.'
  - purpose: Answer messages
    text: 'Purpose: answering you, and not losing track of a message.'
  residency:
  - region: United States
    text: 'Google Cloud (Firestore and Cloud Run, region us-central1, United States): all stored data and the servers that run scans.'
  retention:
  - period: 12 months
    scope: Scan history
    text: 'Scan history (domain, scores, facts, requesting IP and user agent): 12 months, deleted automatically.'
  - period: 30 days
    scope: Request logs
    text: 'Request logs (IP, path, user agent): 30 days, deleted automatically.'
  - period: 30 days
    scope: Live email check findings
    text: 'Live email check findings: 30 days, deleted automatically.'
  - period: 24 months
    scope: Support email and case
    text: 'Email you send to [email protected] , and the case opened for it: 24 months, then the message and the case are deleted.'
  rights:
  - right: Access, correction and deletion
    text: You can ask us to show you, correct or delete the personal data we hold about you, to stop marketing email, or to exclude a domain from scanning altogether.
  - right: Complain to data-protection authority
    text: If you are in the EU, UK or a similar jurisdiction you also have the right to complain to your data-protection authority.
  role:
    text: AstraVerify (astraverify.com) is the controller of the data described here.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it with anyone else.
  subprocessors:
    text: 'Google Cloud (Firestore and Cloud Run, region us-central1, United States): all stored data and the servers that run scans.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AstraVerify
provenance_date: '2026-11-09'
provider_name: AstraVerify
provider_slug: astraverify-com
slug: astraverify-com-privacy-policy
source_date: '2026-11-09'
source_filename: astraverify-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://astraverify.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AstraVerify\naid: astraverify-com\nurl: https://astraverify.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AstraVerify (astraverify.com) is the controller of the data described here.\ndata_categories:\n- category: identifying\n  text: Your IP address and browser user-agent string with each request, including with each scan you run.\n- category: contact\n  text: Your email address, when you ask for an emailed report, request a link to your page, send a fix request,\n    or pay for a service.\n- category: financial\n  text: We receive your email address, the amount, the package and\
  \ Stripe’s customer and subscription identifiers.\n    We never see card numbers.\n- category: communication\n  text: 'If you email us at [email protected] , we store the message: who it is from, the subject and the text,\n    together with a case number and how it was handled.'\n- category: device\n  text: The headers of a test email you choose to send us for the live DKIM check.\npurposes:\n- purpose: Produce scores and recommendations\n  text: 'Purpose: producing the scores and recommendations, and caching them so a repeat visit does not scan the\n    domain again.'\n- purpose: Rate limiting and abuse prevention\n  text: 'Purpose: rate limiting, abuse prevention and diagnosing faults.'\n- purpose: Deliver requested service\n  text: 'Purpose: delivering what you asked for and, for customers, giving you access to your history and orders.'\n- purpose: Answer messages\n  text: 'Purpose: answering you, and not losing track of a message.'\nretention:\n- scope: Scan history\n  period: 12 months\n\
  \  text: 'Scan history (domain, scores, facts, requesting IP and user agent): 12 months, deleted automatically.'\n- scope: Request logs\n  period: 30 days\n  text: 'Request logs (IP, path, user agent): 30 days, deleted automatically.'\n- scope: Live email check findings\n  period: 30 days\n  text: 'Live email check findings: 30 days, deleted automatically.'\n- scope: Support email and case\n  period: 24 months\n  text: 'Email you send to [email protected] , and the case opened for it: 24 months, then the message and the case\n    are deleted.'\nresidency:\n- region: United States\n  text: 'Google Cloud (Firestore and Cloud Run, region us-central1, United States): all stored data and the servers\n    that run scans.'\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Google Cloud (Firestore and Cloud Run, region us-central1, United States): all stored data and the servers\n    that run scans.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to the privacy\
  \ contact to request deletion\n  text: You can ask us to show you, correct or delete the personal data we hold about you, to stop marketing email,\n    or to exclude a domain from scanning altogether.\nrights:\n- right: Access, correction and deletion\n  text: You can ask us to show you, correct or delete the personal data we hold about you, to stop marketing email,\n    or to exclude a domain from scanning altogether.\n- right: Complain to data-protection authority\n  text: If you are in the EU, UK or a similar jurisdiction you also have the right to complain to your data-protection\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and do not share it with anyone else.\n"
source_yaml_url: https://artifacts.apis.io/astraverify-com/privacy/astraverify-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from AstraVerify's own page on 2026-11-09.
synthetic: false
tags:
- Security
- Email
- Artificial Intelligence
- Discoverability
- Domain
---
