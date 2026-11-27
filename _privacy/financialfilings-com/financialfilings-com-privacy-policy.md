---
api_specs:
- filename: financialfilings-com-openapi.yml
  format: yaml
  label: Financial Filings API
  slug: financial-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/financialfilings-com/openapi/financialfilings-com-openapi.yml
claim_count: 34
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as your name, email address, or IP address
  - category: contact
    text: your name and contact details, your CV, links, and our messages with you
  - category: professional
    text: add business information about you that we obtain from third-party sources, such as your job title, company, company size and public professional profile
  - category: device
    text: technical data such as your IP address, browser type, and usage analytics
  - category: behavioral
    text: We analyze user behavior to understand how our Service is used
  - category: other
    text: These documents can name individuals, for example board members, senior managers, shareholders or parties to legal proceedings
  deletion:
    route: Request via privacy email or account deletion
    text: When you ask us to delete your account, we ask those providers to delete the data linked to it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and maintain the Service
    text: This includes managing your account, providing customer support, and processing payments.
  - purpose: Security and stability
    text: We process technical data to protect our Service from fraud and abuse and to ensure it is functioning correctly.
  - purpose: Improve the Service
    text: We analyze user behavior to understand how our Service is used, which helps us to improve features and user experience.
  - purpose: Follow up on sign-ups
    text: When you sign up, we may follow up with you personally and add business information about you that we obtain from third-party sources
  - purpose: Marketing communications
    text: If you ask us to, we send you product updates, new market coverage and API changelog notices by email.
  - purpose: Published filings archive
    text: We make them available on our website and to our customers through our API, bulk data deliveries, data platforms and AI integrations (MCP).
  residency:
  - region: Germany (EU)
    text: Our application, servers, and databases are hosted with Google Cloud in their Frankfurt, Germany (`europe-west3`) data centers.
  retention:
  - period: 30 days
    scope: Account Data
    text: We delete it within 30 days of account closure or of your deletion request, except billing records.
  - period: up to 3 years
    scope: Support Inquiries
    text: Retained for up to 3 years after resolution.
  - period: 6 months
    scope: Job Applications
    text: Deleted 6 months after we decide on your application, or 12 months after you sent it if no decision was needed
  - period: 30 days
    scope: API request logs
    text: API request logs, including IP address and user agent, are kept for 30 days
  - period: up to 12 months
    scope: Searches
    text: searches made through the Service for up to 12 months
  - period: 14 days
    scope: Database backups
    text: database backups for 14 days
  rights:
  - right: Access
    text: 'Right to Access: The right to obtain a copy of your personal data.'
  - right: Rectification
    text: 'Right to Rectification/Correction: The right to have inaccurate personal data corrected.'
  - right: Erasure
    text: 'Right to Erasure: The right to have your data deleted under certain conditions.'
  - right: Restrict processing
    text: 'Right to Restrict Processing: The right to limit the processing of your data.'
  - right: Portability
    text: 'Right to Data Portability: The right to receive your data in a structured format.'
  - right: Object
    text: 'Right to Object: The right to object to processing based on legitimate interests.'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: The right to withdraw consent at any time.'
  - right: Lodge a complaint
    text: 'Right to Lodge a Complaint: The right to lodge a complaint with a data protection supervisory authority'
  role:
    text: 'The party responsible for the collection, processing, and use of your personal data (the "controller") is: FINANCIALREPORTS PTE. LTD.'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Otherwise, we do not sell your personal data.
  subprocessors:
    text: We share it only with the service providers below, who help us operate and improve our Service.
    url: null
  transfers:
  - mechanism: DPF
    text: These include relying on the EU-U.S. Data Privacy Framework for certified entities
  - mechanism: SCC
    text: executing the European Commission's Standard Contractual Clauses (SCCs) with our partners
  - mechanism: other
    text: For transfers from the United Kingdom, we rely on the UK Extension to the EU-U.S. Data Privacy Framework and on the UK International Data Transfer Addendum to the Standard Contractual Clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: FinancialFilings
provenance_date: '2026-11-09'
provider_name: FinancialFilings
provider_slug: financialfilings-com
slug: financialfilings-com-privacy-policy
source_date: '2026-11-09'
source_filename: financialfilings-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://financialfilings.com/data-privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: FinancialFilings\naid: financialfilings-com\nurl: https://financialfilings.com/data-privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The party responsible for the collection, processing, and use of your personal data (the \"controller\")\n    is: FINANCIALREPORTS PTE. LTD.'\ndata_categories:\n- category: identifying\n  text: such as your name, email address, or IP address\n- category: contact\n  text: your name and contact details, your CV, links, and our messages with you\n- category: professional\n  text: add business information about you that we obtain from third-party sources,\
  \ such as your job title, company,\n    company size and public professional profile\n- category: device\n  text: technical data such as your IP address, browser type, and usage analytics\n- category: behavioral\n  text: We analyze user behavior to understand how our Service is used\n- category: other\n  text: These documents can name individuals, for example board members, senior managers, shareholders or parties\n    to legal proceedings\npurposes:\n- purpose: Provide and maintain the Service\n  text: This includes managing your account, providing customer support, and processing payments.\n- purpose: Security and stability\n  text: We process technical data to protect our Service from fraud and abuse and to ensure it is functioning correctly.\n- purpose: Improve the Service\n  text: We analyze user behavior to understand how our Service is used, which helps us to improve features and user\n    experience.\n- purpose: Follow up on sign-ups\n  text: When you sign up, we may follow up\
  \ with you personally and add business information about you that we obtain\n    from third-party sources\n- purpose: Marketing communications\n  text: If you ask us to, we send you product updates, new market coverage and API changelog notices by email.\n- purpose: Published filings archive\n  text: We make them available on our website and to our customers through our API, bulk data deliveries, data platforms\n    and AI integrations (MCP).\nretention:\n- scope: Account Data\n  period: 30 days\n  text: We delete it within 30 days of account closure or of your deletion request, except billing records.\n- scope: Support Inquiries\n  period: up to 3 years\n  text: Retained for up to 3 years after resolution.\n- scope: Job Applications\n  period: 6 months\n  text: Deleted 6 months after we decide on your application, or 12 months after you sent it if no decision was\n    needed\n- scope: API request logs\n  period: 30 days\n  text: API request logs, including IP address and user agent, are\
  \ kept for 30 days\n- scope: Searches\n  period: up to 12 months\n  text: searches made through the Service for up to 12 months\n- scope: Database backups\n  period: 14 days\n  text: database backups for 14 days\nresidency:\n- region: Germany (EU)\n  text: Our application, servers, and databases are hosted with Google Cloud in their Frankfurt, Germany (`europe-west3`)\n    data centers.\ntransfers:\n- mechanism: DPF\n  text: These include relying on the EU-U.S. Data Privacy Framework for certified entities\n- mechanism: SCC\n  text: executing the European Commission's Standard Contractual Clauses (SCCs) with our partners\n- mechanism: other\n  text: For transfers from the United Kingdom, we rely on the UK Extension to the EU-U.S. Data Privacy Framework\n    and on the UK International Data Transfer Addendum to the Standard Contractual Clauses.\nsubprocessors:\n  url: null\n  text: We share it only with the service providers below, who help us operate and improve our Service.\ndpa:\n  available:\
  \ null\n  url: null\n  text: null\ndeletion:\n  route: Request via privacy email or account deletion\n  text: When you ask us to delete your account, we ask those providers to delete the data linked to it.\nrights:\n- right: Access\n  text: 'Right to Access: The right to obtain a copy of your personal data.'\n- right: Rectification\n  text: 'Right to Rectification/Correction: The right to have inaccurate personal data corrected.'\n- right: Erasure\n  text: 'Right to Erasure: The right to have your data deleted under certain conditions.'\n- right: Restrict processing\n  text: 'Right to Restrict Processing: The right to limit the processing of your data.'\n- right: Portability\n  text: 'Right to Data Portability: The right to receive your data in a structured format.'\n- right: Object\n  text: 'Right to Object: The right to object to processing based on legitimate interests.'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent: The right to withdraw consent at any time.'\n- right:\
  \ Lodge a complaint\n  text: 'Right to Lodge a Complaint: The right to lodge a complaint with a data protection supervisory authority'\nsale_or_sharing:\n  stance: prohibited\n  text: Otherwise, we do not sell your personal data.\n"
source_yaml_url: https://artifacts.apis.io/financialfilings-com/privacy/financialfilings-com-privacy-policy.yml
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
summary_line: 34 quoted statements, read from FinancialFilings's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Data
- Filings
- Market Data
- Research
---
