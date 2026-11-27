---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: When you sign up we ask for your name, email address, workspace name and country.
  - category: financial
    text: If you pay for a plan we collect billing details (name, address)
  - category: contact
    text: the contact data you upload, which is typically email address, optional name, custom properties and event history
  - category: behavioral
    text: open/click events, bounce codes, and a per-message ID
  - category: device
    text: Server access logs include your IP address, user agent and request path.
  deletion:
    route: Delete contacts or the whole workspace in the application, or request deletion of your account by email
    text: Delete contacts or the whole workspace at any time and they are removed from the live database.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: To provide the Service you signed up for (delivery of email).
  - purpose: Billing and fraud prevention
    text: To bill you and prevent fraud (Stripe handles card data).
  - purpose: Security
    text: To keep the platform secure (rate limiting, abuse detection, audit trail).
  - purpose: Product improvement
    text: To improve the product (aggregated analytics on which features get used).
  residency:
  - region: Germany (EU)
    text: Customer data is stored on servers in Germany (EU).
  - region: Sydney, Australia
    text: Outgoing email and encrypted backups are handled in Sydney, Australia.
  retention:
  - period: the life of your account plus 7 years
    scope: Account and billing records
    text: retained for the life of your account plus 7 years to meet ATO recordkeeping requirements
  - period: while your workspace exists
    scope: Customer data
    text: retained while your workspace exists
  - period: 90 days
    scope: Encrypted backups
    text: 'Encrypted backups : kept for 90 days'
  - period: null
    scope: Server logs
    text: kept in a short rolling window and then overwritten
  - period: no more than 14 months
    scope: Website analytics
    text: kept for no more than 14 months
  rights:
  - right: Access
    text: Access the personal information we hold about you.
  - right: Correction
    text: Correct information that is inaccurate or out of date.
  - right: Deletion
    text: Request deletion of your account and associated data.
  - right: Portability
    text: Export your data in a structured, machine-readable format.
  - right: Complaint
    text: Lodge a complaint with the Office of the Australian Information Commissioner (OAIC) or your local supervisory authority.
  role:
    text: Where you are an EU/UK resident, we apply the General Data Protection Regulation (GDPR) as a data controller for marketing-site visits and a data processor for your customer data sent through the Service.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: We use the following sub-processors to run Send16. Each receives only the data it needs for the purpose listed.
    url: null
  transfers:
  - mechanism: other
    text: By using the Service you consent to these cross-border transfers under APP 8.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: send16-com
provenance_date: '2026-11-10'
provider_name: send16-com
provider_slug: send16-com
slug: send16-com-privacy-policy
source_date: '2026-11-10'
source_filename: send16-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://send16.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: send16-com\naid: send16-com\nurl: https://send16.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where you are an EU/UK resident, we apply the General Data Protection Regulation (GDPR) as a data controller\n    for marketing-site visits and a data processor for your customer data sent through the Service.\ndata_categories:\n- category: identifying\n  text: When you sign up we ask for your name, email address, workspace name and country.\n- category: financial\n  text: If you pay for a plan we collect billing details (name, address)\n- category: contact\n  text: the contact data you upload,\
  \ which is typically email address, optional name, custom properties and event\n    history\n- category: behavioral\n  text: open/click events, bounce codes, and a per-message ID\n- category: device\n  text: Server access logs include your IP address, user agent and request path.\npurposes:\n- purpose: Provide the Service\n  text: To provide the Service you signed up for (delivery of email).\n- purpose: Billing and fraud prevention\n  text: To bill you and prevent fraud (Stripe handles card data).\n- purpose: Security\n  text: To keep the platform secure (rate limiting, abuse detection, audit trail).\n- purpose: Product improvement\n  text: To improve the product (aggregated analytics on which features get used).\nretention:\n- scope: Account and billing records\n  period: the life of your account plus 7 years\n  text: retained for the life of your account plus 7 years to meet ATO recordkeeping requirements\n- scope: Customer data\n  period: while your workspace exists\n  text: retained\
  \ while your workspace exists\n- scope: Encrypted backups\n  period: 90 days\n  text: 'Encrypted backups : kept for 90 days'\n- scope: Server logs\n  period: null\n  text: kept in a short rolling window and then overwritten\n- scope: Website analytics\n  period: no more than 14 months\n  text: kept for no more than 14 months\nresidency:\n- region: Germany (EU)\n  text: Customer data is stored on servers in Germany (EU).\n- region: Sydney, Australia\n  text: Outgoing email and encrypted backups are handled in Sydney, Australia.\ntransfers:\n- mechanism: other\n  text: By using the Service you consent to these cross-border transfers under APP 8.\nsubprocessors:\n  url: null\n  text: We use the following sub-processors to run Send16. Each receives only the data it needs for the purpose\n    listed.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete contacts or the whole workspace in the application, or request deletion of your account by email\n  text: Delete\
  \ contacts or the whole workspace at any time and they are removed from the live database.\nrights:\n- right: Access\n  text: Access the personal information we hold about you.\n- right: Correction\n  text: Correct information that is inaccurate or out of date.\n- right: Deletion\n  text: Request deletion of your account and associated data.\n- right: Portability\n  text: Export your data in a structured, machine-readable format.\n- right: Complaint\n  text: Lodge a complaint with the Office of the Australian Information Commissioner (OAIC) or your local supervisory\n    authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/send16-com/privacy/send16-com-privacy-policy.yml
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
summary_line: 25 quoted statements, read from send16-com's own page on 2026-11-10.
synthetic: false
tags:
- Email
- Marketing
- Automation
- Artificial Intelligence
- Software-as-a-Service
---
