---
api_specs:
- filename: mailcheer-com-campaigns-api-openapi.yml
  format: yaml
  label: mailcheer-com Campaigns API
  slug: mailcheer-com-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-campaigns-api-openapi.yml
- filename: mailcheer-com-emails-api-openapi.yml
  format: yaml
  label: mailcheer-com Emails API
  slug: mailcheer-com-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-emails-api-openapi.yml
- filename: mailcheer-com-subscribers-api-openapi.yml
  format: yaml
  label: mailcheer-com Subscribers API
  slug: mailcheer-com-subscribers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-subscribers-api-openapi.yml
- filename: mailcheer-com-suppression-api-openapi.yml
  format: yaml
  label: mailcheer-com Suppression API
  slug: mailcheer-com-suppression-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-suppression-api-openapi.yml
- filename: mailcheer-com-webhooks-api-openapi.yml
  format: yaml
  label: mailcheer-com Webhooks API
  slug: mailcheer-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-webhooks-api-openapi.yml
- filename: mailcheer-com-workspace-api-openapi.yml
  format: yaml
  label: mailcheer-com Workspace API
  slug: mailcheer-com-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mailcheer-com/openapi/mailcheer-com-workspace-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account : name, email address, password (stored as a hash, never in plain text), organization name'
  - category: financial
    text: 'Billing : plan subscribed, invoice history, billing address.'
  - category: contact
    text: subscribers' data (email address, name, custom fields, subscription status, open, click, bounce and unsubscribe events)
  - category: device
    text: technical logs (IP address, browser, connection timestamps) necessary for security and operation
  - category: communication
    text: 'Exchanges : messages you send us (support).'
  deletion:
    route: Write to contact@gam-communication.com or delete the account
    text: To exercise them, write to contact@gam-communication.com .
  dpa:
    available: true
    text: A data processing agreement (DPA) formalizing these commitments can be provided upon simple request to contact@gam-communication.com .
    url: null
  purposes:
  - purpose: Provide the service
    text: Provide the service, manage your account and your sends — performance of contract .
  - purpose: Secure the service and prevent abuse
    text: Secure the service, prevent abuse and spam, including through the safety review of your sends
  - purpose: Audience measurement
    text: Know how our customers find us and which pages of the website are read (section 4) — legitimate interest .
  - purpose: Subscriber delivery and statistics
    text: We process your subscribers' data (email address, name, custom fields, subscription status, open, click, bounce and unsubscribe events) solely to deliver your sends, provide you with the statistics and protect the service against abuse.
  residency:
  - region: European Union
    text: 'Your data and that of your subscribers are stored within the European Union : the database in Germany, with Hetzner, and outgoing email in Ireland, with Amazon Web Services.'
  retention:
  - period: 12 months after account closure
    scope: Account data
    text: 'Account data: for the full duration of your subscription, then 12 months after account closure, before deletion.'
  - period: 7 years from the end of the year of the invoice
    scope: Invoices and accounting documents
    text: 'Invoices and accounting documents: 7 years from the end of the year of the invoice.'
  - period: 12 months
    scope: Technical connection logs
    text: 'Technical connection logs: 12 months .'
  - period: 30 days
    scope: Content of sends
    text: 'Content of your sends: 30 days , then automatic deletion.'
  - period: 90 days
    scope: Subscriber data after account closure
    text: When your account is closed, your subscribers' data is deleted within a maximum of 90 days , unless otherwise required by law.
  rights:
  - right: access
    text: you have the right of access , rectification , erasure , restriction of processing , objection and data portability
  - right: human intervention on automated decisions
    text: When facing an automated decision (section 2), you can obtain human intervention, express your point of view and contest the decision.
  - right: withdraw consent
    text: Where processing is based on your consent, such as our newsletter, you may withdraw it at any time.
  - right: complaint to authority
    text: You may also lodge a complaint with the CNIL (Commission nationale de l'informatique et des libertés), www.cnil.fr
  role:
    text: 'Mailcheer operates in two distinct capacities under the General Data Protection Regulation (GDPR): Data controller for the data of our customers (those who create a Mailcheer account) and of website visitors'
    value: both
  sale_or_sharing:
    stance: prohibited
    text: Apart from the fight against abuse described above, we never use that data for our own purposes, sell it, or share it, except with the technical providers listed in section 5.
  subprocessors:
    text: 'To operate, Mailcheer relies on a limited number of technical providers, chosen for their GDPR compliance: Hetzner Online GmbH — application and database hosting ( servers in Europe ). Amazon Web Services EMEA SARL (Amazon SES) — email delivery'
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers are governed by the European Commission's standard contractual clauses, built into each of these providers' terms
  - mechanism: DPF
    text: for Stripe, Cloudflare and Google, by their participation in the EU-U.S. Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: mailcheer-com
provenance_date: '2026-11-10'
provider_name: mailcheer-com
provider_slug: mailcheer-com
slug: mailcheer-com-privacy-policy
source_date: '2026-11-10'
source_filename: mailcheer-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mailcheer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: mailcheer-com\naid: mailcheer-com\nurl: https://mailcheer.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: 'Mailcheer operates in two distinct capacities under the General Data Protection Regulation (GDPR): Data\n    controller for the data of our customers (those who create a Mailcheer account) and of website visitors'\ndata_categories:\n- category: identifying\n  text: 'Account : name, email address, password (stored as a hash, never in plain text), organization name'\n- category: financial\n  text: 'Billing : plan subscribed, invoice history, billing address.'\n- category: contact\n\
  \  text: subscribers' data (email address, name, custom fields, subscription status, open, click, bounce and unsubscribe\n    events)\n- category: device\n  text: technical logs (IP address, browser, connection timestamps) necessary for security and operation\n- category: communication\n  text: 'Exchanges : messages you send us (support).'\npurposes:\n- purpose: Provide the service\n  text: Provide the service, manage your account and your sends — performance of contract .\n- purpose: Secure the service and prevent abuse\n  text: Secure the service, prevent abuse and spam, including through the safety review of your sends\n- purpose: Audience measurement\n  text: Know how our customers find us and which pages of the website are read (section 4) — legitimate interest\n    .\n- purpose: Subscriber delivery and statistics\n  text: We process your subscribers' data (email address, name, custom fields, subscription status, open, click,\n    bounce and unsubscribe events) solely to deliver your\
  \ sends, provide you with the statistics and protect the\n    service against abuse.\nretention:\n- scope: Account data\n  period: 12 months after account closure\n  text: 'Account data: for the full duration of your subscription, then 12 months after account closure, before\n    deletion.'\n- scope: Invoices and accounting documents\n  period: 7 years from the end of the year of the invoice\n  text: 'Invoices and accounting documents: 7 years from the end of the year of the invoice.'\n- scope: Technical connection logs\n  period: 12 months\n  text: 'Technical connection logs: 12 months .'\n- scope: Content of sends\n  period: 30 days\n  text: 'Content of your sends: 30 days , then automatic deletion.'\n- scope: Subscriber data after account closure\n  period: 90 days\n  text: When your account is closed, your subscribers' data is deleted within a maximum of 90 days , unless otherwise\n    required by law.\nresidency:\n- region: European Union\n  text: 'Your data and that of your subscribers\
  \ are stored within the European Union : the database in Germany,\n    with Hetzner, and outgoing email in Ireland, with Amazon Web Services.'\ntransfers:\n- mechanism: SCC\n  text: These transfers are governed by the European Commission's standard contractual clauses, built into each\n    of these providers' terms\n- mechanism: DPF\n  text: for Stripe, Cloudflare and Google, by their participation in the EU-U.S. Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: 'To operate, Mailcheer relies on a limited number of technical providers, chosen for their GDPR compliance:\n    Hetzner Online GmbH — application and database hosting ( servers in Europe ). Amazon Web Services EMEA SARL\n    (Amazon SES) — email delivery'\ndpa:\n  available: true\n  url: null\n  text: A data processing agreement (DPA) formalizing these commitments can be provided upon simple request to contact@gam-communication.com\n    .\ndeletion:\n  route: Write to contact@gam-communication.com or delete the account\n\
  \  text: To exercise them, write to contact@gam-communication.com .\nrights:\n- right: access\n  text: you have the right of access , rectification , erasure , restriction of processing , objection and data\n    portability\n- right: human intervention on automated decisions\n  text: When facing an automated decision (section 2), you can obtain human intervention, express your point of\n    view and contest the decision.\n- right: withdraw consent\n  text: Where processing is based on your consent, such as our newsletter, you may withdraw it at any time.\n- right: complaint to authority\n  text: You may also lodge a complaint with the CNIL (Commission nationale de l'informatique et des libertés), www.cnil.fr\nsale_or_sharing:\n  stance: prohibited\n  text: Apart from the fight against abuse described above, we never use that data for our own purposes, sell it,\n    or share it, except with the technical providers listed in section 5.\n"
source_yaml_url: https://artifacts.apis.io/mailcheer-com/privacy/mailcheer-com-privacy-policy.yml
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
summary_line: 26 quoted statements, read from mailcheer-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Newsletters
- Marketing
- Artificial Intelligence
---
