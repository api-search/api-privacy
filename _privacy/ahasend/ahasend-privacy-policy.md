---
api_specs:
- filename: ahasend-accounts-api-openapi.yml
  format: yaml
  label: AhaSend Accounts API
  slug: ahasend-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-accounts-api-openapi.yml
- filename: ahasend-api-keys-api-openapi.yml
  format: yaml
  label: AhaSend API Keys API
  slug: ahasend-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-api-keys-api-openapi.yml
- filename: ahasend-domains-api-openapi.yml
  format: yaml
  label: AhaSend Domains API
  slug: ahasend-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-domains-api-openapi.yml
- filename: ahasend-email-api-openapi.yml
  format: yaml
  label: AhaSend Email API
  slug: ahasend-email-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-email-api-openapi.yml
- filename: ahasend-messages-api-openapi.yml
  format: yaml
  label: AhaSend Messages API
  slug: ahasend-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-messages-api-openapi.yml
- filename: ahasend-routes-api-openapi.yml
  format: yaml
  label: AhaSend Routes API
  slug: ahasend-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-routes-api-openapi.yml
- filename: ahasend-smtp-credentials-api-openapi.yml
  format: yaml
  label: AhaSend SMTP Credentials API
  slug: ahasend-smtp-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-smtp-credentials-api-openapi.yml
- filename: ahasend-statistics-api-openapi.yml
  format: yaml
  label: AhaSend Statistics API
  slug: ahasend-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-statistics-api-openapi.yml
- filename: ahasend-suppressions-api-openapi.yml
  format: yaml
  label: AhaSend Suppressions API
  slug: ahasend-suppressions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-suppressions-api-openapi.yml
- filename: ahasend-utility-api-openapi.yml
  format: yaml
  label: AhaSend Utility API
  slug: ahasend-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-utility-api-openapi.yml
- filename: ahasend-webhooks-api-openapi.yml
  format: yaml
  label: AhaSend Webhooks API
  slug: ahasend-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-webhooks-api-openapi.yml
- filename: ahasend-campaign-templates-api-openapi.yml
  format: yaml
  label: AhaSend Campaign Templates API
  slug: ahasend-campaign-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-campaign-templates-api-openapi.yml
- filename: ahasend-campaigns-api-openapi.yml
  format: yaml
  label: AhaSend Campaigns API
  slug: ahasend-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-campaigns-api-openapi.yml
- filename: ahasend-contacts-api-openapi.yml
  format: yaml
  label: AhaSend Contacts API
  slug: ahasend-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-contacts-api-openapi.yml
- filename: ahasend-lists-api-openapi.yml
  format: yaml
  label: AhaSend Lists API
  slug: ahasend-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-lists-api-openapi.yml
- filename: ahasend-templates-api-openapi.yml
  format: yaml
  label: AhaSend Templates API
  slug: ahasend-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-templates-api-openapi.yml
- filename: ahasend-subaccounts-api-openapi.yml
  format: yaml
  label: AhaSend Subaccounts API
  slug: ahasend-subaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ahasend/openapi/ahasend-subaccounts-api-openapi.yml
claim_count: 49
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your name
  - category: contact
    text: Your email address
  - category: financial
    text: Payment information (which is processed by our payment processor, Stripe, though we may receive related transaction details)
  - category: device
    text: Device information (such as operating system, browser type, and version)
  - category: location
    text: Your IP address
  - category: behavioral
    text: Information about how you navigate and interact with our Website and Services (e.g., pages visited, features used, time spent on pages, clickstream data)
  - category: communication
    text: We also collect and store the content of communications we have with you, such as support inquiries submitted via email
  - category: contact
    source: https://ahasend.com/dpa
    text: 'Contact Information of Recipients: primarily email addresses. May also include names if provided by Controller.'
  - category: communication
    source: https://ahasend.com/dpa
    text: 'Email Content: the content of the emails sent by the Controller to Recipients'
  - category: behavioral
    source: https://ahasend.com/dpa
    text: 'Email Metadata and Engagement Data: information related to the sending of emails, such as subject lines, sender/recipient information, delivery logs (deliveries, deferrals, bounces), spam complaints (from Feedback Loops), timestamps'
  - category: device
    source: https://ahasend.com/dpa
    text: IP addresses of Recipients interacting with emails, user agent strings, and engagement metrics (opens, clicks)
  deletion:
    route: Request account deletion
    text: If you request account deletion, your personal data will generally be erased within 14 days, unless we are legally required to retain specific elements for a longer period
  dpa:
    available: true
    text: Our commitments and obligations as a Data Processor are detailed in our Data Processing Agreement (DPA) , which is available on our Website and forms part of our Terms of Service.
    url: null
  purposes:
  - purpose: Provide, maintain and improve services
    text: To create and manage your account, provide the ESP functionalities you request, process your email sending, offer customer support
  - purpose: Process transactions
    text: To process your payments for the use of our Services and send you related information, including confirmations, invoices, and billing notices.
  - purpose: Service integrity and abuse prevention
    text: To monitor trends, usage, and activities to detect, investigate, and prevent fraudulent transactions, unauthorized access, other illegal activities, and violations of our Terms of Service.
  - purpose: Analytics
    text: To understand how our Website and Services are used, to measure the effectiveness of our Website, and to improve our offerings. This is done with Posthog
  - purpose: Affiliate program management
    text: To track referrals from affiliate partners and attribute commissions using Trackdesk.
  - purpose: Enable sending emails to Recipients
    source: https://ahasend.com/dpa
    text: To enable Controller to send emails to its Recipients.
  - purpose: Analytics and reporting
    source: https://ahasend.com/dpa
    text: To provide Controller with analytics and reporting regarding email delivery and engagement.
  - purpose: Maintain and improve Services
    source: https://ahasend.com/dpa
    text: To maintain and improve the Services, including deliverability and security.
  - purpose: Legal compliance and abuse prevention
    source: https://ahasend.com/dpa
    text: To comply with legal obligations and prevent misuse of the Services.
  residency:
  - region: EEA
    source: https://ahasend.com/dpa
    text: Processing occurs within the European Economic Area (EEA), as detailed in Annex 3.
  retention:
  - period: as long as your account is active
    scope: Account information
    text: We retain your account information (such as name, email, timezone, last login IP) as long as your account is active with us.
  - period: 14 days
    scope: Account deletion
    text: If you request account deletion, your personal data will generally be erased within 14 days
  - period: 7 years from the end of the relevant financial year
    scope: Billing information
    text: Transactional data and invoices related to your account (processed via Stripe) will be retained by AhaSend B.V. for 7 years from the end of the relevant financial year
  - period: 1 month
    scope: IP logs
    text: Server logs containing IP addresses (collected for security and operational purposes) are retained for 1 month.
  - period: 30 days
    scope: Analytics data
    text: Data collected via Posthog is retained for 30 days.
  - period: up to 3 years
    scope: Communications
    text: Emails and support communications with you may be retained for up to 3 years after our last interaction
  - period: within a maximum of 90 days
    scope: Account data after termination
    source: https://ahasend.com/dpa
    text: typically within a maximum of 90 days from the effective termination date, unless otherwise required by law or for legitimate operational needs
  - period: null
    scope: Unsubscribe and spam complaint records
    source: https://ahasend.com/dpa
    text: Records of unsubscribe requests and spam complaints may be retained after termination to the extent necessary to continue honouring the opt-out of the Data Subject concerned.
  rights:
  - right: Access
    text: 'The right to access: You can request copies of your personal data that we process.'
  - right: Rectification
    text: 'The right to rectification: You can request that we correct any information you believe is inaccurate or complete information you believe is incomplete.'
  - right: Erasure
    text: 'The right to erasure (''right to be forgotten''): You can request that we erase your personal data, under certain conditions'
  - right: Restrict processing
    text: 'The right to restrict processing: You have the right to request that we restrict the processing of your personal data in certain circumstances.'
  - right: Object
    text: 'The right to object to processing: You can object to our processing of your personal data'
  - right: Portability
    text: 'The right to data portability: You can request that we transfer the data that we have collected and that you provided to us to another organization, or directly to you'
  - right: Withdraw consent
    text: 'The right to withdraw consent: If we are processing your personal data based on your consent'
  - right: Lodge complaint
    text: 'Right to lodge a complaint: You have the right to lodge a complaint with a data protection supervisory authority'
  - right: Assistance with Data Subject requests
    source: https://ahasend.com/dpa
    text: Assist the Controller in ensuring compliance with its obligations pursuant to Articles 32 to 36 GDPR
  - right: Audit and information
    source: https://ahasend.com/dpa
    text: Make available to the Controller all information necessary to demonstrate compliance with the obligations laid down in Article 28 GDPR and allow for and contribute to audits
  role:
    text: AhaSend acts as a Data Processor on their behalf for the email content and subscriber data they provide.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent your personal information.
  subprocessors:
    source: https://ahasend.com/dpa
    text: Processor shall maintain an up-to-date list of its Sub-processors. This list is detailed in Annex 3 (List of Sub-processors) to this DPA and is also available for ongoing review at https://ahasend.com/dpa.
    url: https://ahasend.com/dpa
  transfers:
  - mechanism: DPF
    text: We rely on the European Commission's adequacy decision for the DPF for transfers to US companies that are certified under the DPF.
  - mechanism: SCC
    text: For providers where the DPF may not apply or as a supplementary measure, we rely on Standard Contractual Clauses (SCCs) adopted by the European Commission.
  - mechanism: SCC
    source: https://ahasend.com/dpa
    text: Subject to appropriate safeguards, such as the Standard Contractual Clauses (SCCs) adopted by the European Commission
  - mechanism: DPF
    source: https://ahasend.com/dpa
    text: To a recipient in the United States that is certified under the EU-U.S. Data Privacy Framework (DPF);
  - mechanism: adequacy
    source: https://ahasend.com/dpa
    text: To a country recognized by the European Commission as providing an adequate level of data protection;
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AhaSend
provenance_date: '2026-11-09'
provider_name: AhaSend
provider_slug: ahasend
slug: ahasend-privacy-policy
source_date: '2026-11-09'
source_filename: ahasend-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ahasend.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AhaSend\naid: ahasend\nurl: https://ahasend.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://ahasend.com/dpa\n  - https://ahasend.com/privacy\nrole:\n  value: both\n  text: AhaSend acts as a Data Processor on their behalf for the email content and subscriber data they provide.\ndata_categories:\n- category: identifying\n  text: Your name\n- category: contact\n  text: Your email address\n- category: financial\n  text: Payment information (which is processed by our payment processor, Stripe, though we may receive related\n    transaction details)\n- category: device\n  text: Device information\
  \ (such as operating system, browser type, and version)\n- category: location\n  text: Your IP address\n- category: behavioral\n  text: Information about how you navigate and interact with our Website and Services (e.g., pages visited, features\n    used, time spent on pages, clickstream data)\n- category: communication\n  text: We also collect and store the content of communications we have with you, such as support inquiries submitted\n    via email\n- category: contact\n  text: 'Contact Information of Recipients: primarily email addresses. May also include names if provided by Controller.'\n  source: https://ahasend.com/dpa\n- category: communication\n  text: 'Email Content: the content of the emails sent by the Controller to Recipients'\n  source: https://ahasend.com/dpa\n- category: behavioral\n  text: 'Email Metadata and Engagement Data: information related to the sending of emails, such as subject lines,\n    sender/recipient information, delivery logs (deliveries, deferrals, bounces),\
  \ spam complaints (from Feedback\n    Loops), timestamps'\n  source: https://ahasend.com/dpa\n- category: device\n  text: IP addresses of Recipients interacting with emails, user agent strings, and engagement metrics (opens, clicks)\n  source: https://ahasend.com/dpa\npurposes:\n- purpose: Provide, maintain and improve services\n  text: To create and manage your account, provide the ESP functionalities you request, process your email sending,\n    offer customer support\n- purpose: Process transactions\n  text: To process your payments for the use of our Services and send you related information, including confirmations,\n    invoices, and billing notices.\n- purpose: Service integrity and abuse prevention\n  text: To monitor trends, usage, and activities to detect, investigate, and prevent fraudulent transactions, unauthorized\n    access, other illegal activities, and violations of our Terms of Service.\n- purpose: Analytics\n  text: To understand how our Website and Services are used,\
  \ to measure the effectiveness of our Website, and to\n    improve our offerings. This is done with Posthog\n- purpose: Affiliate program management\n  text: To track referrals from affiliate partners and attribute commissions using Trackdesk.\n- purpose: Enable sending emails to Recipients\n  text: To enable Controller to send emails to its Recipients.\n  source: https://ahasend.com/dpa\n- purpose: Analytics and reporting\n  text: To provide Controller with analytics and reporting regarding email delivery and engagement.\n  source: https://ahasend.com/dpa\n- purpose: Maintain and improve Services\n  text: To maintain and improve the Services, including deliverability and security.\n  source: https://ahasend.com/dpa\n- purpose: Legal compliance and abuse prevention\n  text: To comply with legal obligations and prevent misuse of the Services.\n  source: https://ahasend.com/dpa\nretention:\n- scope: Account information\n  period: as long as your account is active\n  text: We retain your\
  \ account information (such as name, email, timezone, last login IP) as long as your account\n    is active with us.\n- scope: Account deletion\n  period: 14 days\n  text: If you request account deletion, your personal data will generally be erased within 14 days\n- scope: Billing information\n  period: 7 years from the end of the relevant financial year\n  text: Transactional data and invoices related to your account (processed via Stripe) will be retained by AhaSend\n    B.V. for 7 years from the end of the relevant financial year\n- scope: IP logs\n  period: 1 month\n  text: Server logs containing IP addresses (collected for security and operational purposes) are retained for 1\n    month.\n- scope: Analytics data\n  period: 30 days\n  text: Data collected via Posthog is retained for 30 days.\n- scope: Communications\n  period: up to 3 years\n  text: Emails and support communications with you may be retained for up to 3 years after our last interaction\n- scope: Account data after termination\n\
  \  period: within a maximum of 90 days\n  text: typically within a maximum of 90 days from the effective termination date, unless otherwise required by\n    law or for legitimate operational needs\n  source: https://ahasend.com/dpa\n- scope: Unsubscribe and spam complaint records\n  period: null\n  text: Records of unsubscribe requests and spam complaints may be retained after termination to the extent necessary\n    to continue honouring the opt-out of the Data Subject concerned.\n  source: https://ahasend.com/dpa\nresidency:\n- region: EEA\n  text: Processing occurs within the European Economic Area (EEA), as detailed in Annex 3.\n  source: https://ahasend.com/dpa\ntransfers:\n- mechanism: DPF\n  text: We rely on the European Commission's adequacy decision for the DPF for transfers to US companies that are\n    certified under the DPF.\n- mechanism: SCC\n  text: For providers where the DPF may not apply or as a supplementary measure, we rely on Standard Contractual\n    Clauses (SCCs)\
  \ adopted by the European Commission.\n- mechanism: SCC\n  text: Subject to appropriate safeguards, such as the Standard Contractual Clauses (SCCs) adopted by the European\n    Commission\n  source: https://ahasend.com/dpa\n- mechanism: DPF\n  text: To a recipient in the United States that is certified under the EU-U.S. Data Privacy Framework (DPF);\n  source: https://ahasend.com/dpa\n- mechanism: adequacy\n  text: To a country recognized by the European Commission as providing an adequate level of data protection;\n  source: https://ahasend.com/dpa\nsubprocessors:\n  url: https://ahasend.com/dpa\n  text: Processor shall maintain an up-to-date list of its Sub-processors. This list is detailed in Annex 3 (List\n    of Sub-processors) to this DPA and is also available for ongoing review at https://ahasend.com/dpa.\n  source: https://ahasend.com/dpa\ndpa:\n  available: true\n  url: null\n  text: Our commitments and obligations as a Data Processor are detailed in our Data Processing Agreement\
  \ (DPA)\n    , which is available on our Website and forms part of our Terms of Service.\ndeletion:\n  route: Request account deletion\n  text: If you request account deletion, your personal data will generally be erased within 14 days, unless we are\n    legally required to retain specific elements for a longer period\nrights:\n- right: Access\n  text: 'The right to access: You can request copies of your personal data that we process.'\n- right: Rectification\n  text: 'The right to rectification: You can request that we correct any information you believe is inaccurate or\n    complete information you believe is incomplete.'\n- right: Erasure\n  text: 'The right to erasure (''right to be forgotten''): You can request that we erase your personal data, under\n    certain conditions'\n- right: Restrict processing\n  text: 'The right to restrict processing: You have the right to request that we restrict the processing of your\n    personal data in certain circumstances.'\n- right: Object\n\
  \  text: 'The right to object to processing: You can object to our processing of your personal data'\n- right: Portability\n  text: 'The right to data portability: You can request that we transfer the data that we have collected and that\n    you provided to us to another organization, or directly to you'\n- right: Withdraw consent\n  text: 'The right to withdraw consent: If we are processing your personal data based on your consent'\n- right: Lodge complaint\n  text: 'Right to lodge a complaint: You have the right to lodge a complaint with a data protection supervisory\n    authority'\n- right: Assistance with Data Subject requests\n  text: Assist the Controller in ensuring compliance with its obligations pursuant to Articles 32 to 36 GDPR\n  source: https://ahasend.com/dpa\n- right: Audit and information\n  text: Make available to the Controller all information necessary to demonstrate compliance with the obligations\n    laid down in Article 28 GDPR and allow for and contribute to audits\n\
  \  source: https://ahasend.com/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent your personal information.\n"
source_yaml_url: https://artifacts.apis.io/ahasend/privacy/ahasend-privacy-policy.yml
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
summary_line: 49 quoted statements, read from AhaSend's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Transactional Email
- Developer Tools
- SMTP
- Webhook
---
