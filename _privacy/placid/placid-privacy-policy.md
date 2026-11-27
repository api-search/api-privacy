---
api_specs:
- filename: placid-openai-api-openapi.yml
  format: yaml
  label: Placid Openai API
  slug: placid-openai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/placid/openapi/placid-openai-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: this may include your email address, name, IP address and other information you send to us
  - category: identifying
    text: you need to provide your email address and a password, and (optional) your name and a profile photo
  - category: financial
    text: We don’t have access to any of your payment details (e.g. your credit card number) and only get information about your order / invoice history
  - category: device
    text: browser type and version, OS, referrer URLs, IP address and the inquiring provider
  - category: behavioral
    text: the name of the visited webpage or document, date and time of the visit
  deletion:
    route: delete account in account settings
    text: If you don’t want to receive these emails, you can delete your account in the account settings.
  dpa:
    available: true
    text: we govern this processing by a contract (a data processing addendum)
    url: null
  purposes:
  - purpose: respond to inquiries
    text: To be able to respond to your inquiries / carry out pre-contractual measures
  - purpose: deliver subscribed service
    text: To be able to deliver the service you have purchased and fulfill our contract
  - purpose: marketing
    text: To provide you with news and offers related to our service and your subscription
  - purpose: security and analytics
    text: To be able to ensure system security, manage the website technically and optimising service quality
  retention:
  - period: 24 hours
    scope: IP address in privacy-first analytics
    text: They only retain your IP address for 24 hours for security reasons.
  - period: null
    scope: personal data generally
    text: We retain your personal data where we have an ongoing legitimate business need to do so
  - period: null
    scope: raw request data for processors
    text: We retain the raw request data only for a limited amount of time, and only for the purpose of processing your request and potential troubleshooting
  rights:
  - right: access information
    text: You have the right to request information about origin, recipients and purpose of your data free of charge at any time.
  - right: correction, locking or deletion
    text: You can demand correction, locking or deletion of your data.
  - right: complain to authority
    text: If you’re unhappy about how we process your data, you have a right to complain at the responsible regulating authority
  - right: opt out of marketing
    text: You can opt-out of marketing emails at any time by clicking the unsubscribe link in any of these emails, or in your account settings.
  role:
    text: 'To use our service we process your personal data (read: your account data) in the role of a data controller.'
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'We use sub processors for these purposes: Infrastructure hosting Payments Customer support Emails Analytics We don’t publish further details of our data processors to protect our business.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Placid
provenance_date: '2026-11-10'
provider_name: Placid
provider_slug: placid
slug: placid-privacy-policy
source_date: '2026-11-10'
source_filename: placid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://placid.app/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Placid\naid: placid\nurl: https://placid.app/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'To use our service we process your personal data (read: your account data) in the role of a data controller.'\ndata_categories:\n- category: contact\n  text: this may include your email address, name, IP address and other information you send to us\n- category: identifying\n  text: you need to provide your email address and a password, and (optional) your name and a profile photo\n- category: financial\n  text: We don’t have access to any of your payment details (e.g. your credit card number) and\
  \ only get information\n    about your order / invoice history\n- category: device\n  text: browser type and version, OS, referrer URLs, IP address and the inquiring provider\n- category: behavioral\n  text: the name of the visited webpage or document, date and time of the visit\npurposes:\n- purpose: respond to inquiries\n  text: To be able to respond to your inquiries / carry out pre-contractual measures\n- purpose: deliver subscribed service\n  text: To be able to deliver the service you have purchased and fulfill our contract\n- purpose: marketing\n  text: To provide you with news and offers related to our service and your subscription\n- purpose: security and analytics\n  text: To be able to ensure system security, manage the website technically and optimising service quality\nretention:\n- scope: IP address in privacy-first analytics\n  period: 24 hours\n  text: They only retain your IP address for 24 hours for security reasons.\n- scope: personal data generally\n  period: null\n\
  \  text: We retain your personal data where we have an ongoing legitimate business need to do so\n- scope: raw request data for processors\n  period: null\n  text: We retain the raw request data only for a limited amount of time, and only for the purpose of processing\n    your request and potential troubleshooting\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'We use sub processors for these purposes: Infrastructure hosting Payments Customer support Emails Analytics\n    We don’t publish further details of our data processors to protect our business.'\ndpa:\n  available: true\n  url: null\n  text: we govern this processing by a contract (a data processing addendum)\ndeletion:\n  route: delete account in account settings\n  text: If you don’t want to receive these emails, you can delete your account in the account settings.\nrights:\n- right: access information\n  text: You have the right to request information about origin, recipients and purpose of your data free\
  \ of charge\n    at any time.\n- right: correction, locking or deletion\n  text: You can demand correction, locking or deletion of your data.\n- right: complain to authority\n  text: If you’re unhappy about how we process your data, you have a right to complain at the responsible regulating\n    authority\n- right: opt out of marketing\n  text: You can opt-out of marketing emails at any time by clicking the unsubscribe link in any of these emails,\n    or in your account settings.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/placid/privacy/placid-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- dpa
- deletion
- rights
summary_line: 20 quoted statements, read from Placid's own page on 2026-11-10.
synthetic: false
tags:
- Automation
- Creative
- Image Generation
- No-Code
---
