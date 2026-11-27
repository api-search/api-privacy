---
claim_count: 47
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information: Email address, full name, username, password (encrypted), company name, job title'
  - category: contact
    text: 'Contact Information: Phone number, billing address'
  - category: financial
    text: 'Payment Information: Billing contact details (payment card details are processed by our PCI-DSS compliant payment processors and are not stored on our servers)'
  - category: location
    text: With your explicit consent, we may collect and process information about your approximate or precise geographic location.
  - category: behavioral
    text: 'Log Data: Access times and dates, pages viewed, features used, clickstream data, referring/exit pages, search queries'
  - category: device
    text: 'Device Information: IP address, device type, operating system, browser type and version, unique device identifiers'
  - category: communication
    text: 'Communication Data: Content of messages sent through our support channels, inquiries, feedback, and correspondence with our team'
  - category: contact
    source: https://vinkius.com/legal/subprocessors
    text: User email addresses, email content (notifications, alerts), email interaction data
  - category: financial
    source: https://vinkius.com/legal/subprocessors
    text: Billing contact information, payment card details, transaction records
  - category: device
    source: https://vinkius.com/legal/subprocessors
    text: IP addresses, browser information, device identifiers, website interactions, advertising performance data
  - category: behavioral
    source: https://vinkius.com/legal/subprocessors
    text: page views, user interactions, approximate location (country/city level)
  deletion:
    route: Upon your request via privacy[at]Vinkius.com or dpo[at]Vinkius.com
    text: Upon expiration of applicable retention periods, or upon your request (where legally permissible), we will securely delete or anonymize your Personal Data using industry-standard data destruction methods.
  dpa:
    available: true
    text: A Data Processing Agreement (DPA) governs this relationship in compliance with GDPR Article 28
    url: null
  purposes:
  - purpose: Service provision
    text: Creating, maintaining, and securing user accounts
  - purpose: Service improvement
    text: Analyzing usage patterns to enhance user experience
  - purpose: Security and fraud prevention
    text: Detecting, preventing, and investigating security incidents
  - purpose: Marketing
    text: Sending promotional materials about new features, products, and services (only with your consent for marketing communications)
  - purpose: Legal compliance
    text: Complying with applicable laws and regulations
  - purpose: Subscription payments and billing
    source: https://vinkius.com/legal/subprocessors
    text: Processes all subscription payments, manages billing, and generates invoices for Vinkius customers.
  - purpose: Transactional email delivery
    source: https://vinkius.com/legal/subprocessors
    text: Delivers transactional emails from Vinkius to users, including account notifications, password reset emails, system alerts, and platform updates.
  - purpose: Web analytics
    source: https://vinkius.com/legal/subprocessors
    text: Analyzes platform usage, user behavior, and performance metrics to improve Vinkius's Services and user experience.
  - purpose: Targeted advertising
    source: https://vinkius.com/legal/subprocessors
    text: Enables targeted advertising, measures campaign effectiveness, and builds audiences for marketing purposes.
  residency:
  - region: European Union, United States, and other locations
    text: Your data is processed and stored in Amazon Web Services (AWS) data centers with global redundancy across multiple geographic regions, including the European Union, United States, and other locations.
  - region: EU (AWS hosting)
    source: https://vinkius.com/legal/subprocessors
    text: EU (Frankfurt, Germany; Dublin, Ireland)
  retention:
  - period: 30 days
    scope: Account Data
    text: Retained for the duration of your active account plus 30 days after account closure or deletion request
  - period: 7 years
    scope: Transaction Records
    text: 'Transaction Records: Retained for 7 years to comply with tax and financial regulations as required by GDPR and EU financial directives'
  - period: 24 months
    scope: Usage Data and Logs
    text: 'Usage Data and Logs: Retained for 24 months for security, analytics, and troubleshooting purposes'
  - period: 3 years
    scope: Support Communications
    text: 'Support Communications: Retained for 3 years to provide ongoing support and improve service quality'
  rights:
  - right: Access
    text: Right to Access (GDPR Article 15)
  - right: Rectification
    text: Right to Rectification (GDPR Article 16)
  - right: Erasure
    text: Right to Erasure / "Right to be Forgotten" (GDPR Article 17)
  - right: Restriction
    text: Right to Restriction of Processing (GDPR Article 18)
  - right: Portability
    text: Right to Data Portability (GDPR Article 20)
  - right: Object
    text: Right to Object (GDPR Article 21)
  - right: Withdraw consent
    text: Right to Withdraw Consent Where processing is based on consent, you have the right to withdraw consent at any time
  - right: Opt-out of sale or sharing (CCPA)
    text: 'Right to Opt-Out: Opt out of the "sale" or "sharing" of personal information (Note: Vinkius does not sell personal information)'
  - right: Audit
    source: https://vinkius.com/legal/subprocessors
    text: Customers have the right to audit Vinkius's compliance with Subprocessor requirements as described in Section 11 of the Vinkius Data Processing Agreement.
  - right: Objection to new subprocessor
    source: https://vinkius.com/legal/subprocessors
    text: 'If a customer has legitimate grounds related to data protection for objecting to Vinkius''s appointment of a new Subprocessor, the customer must: Notify Vinkius in writing within 30 days of receiving notice of the new Subprocessor'
  role:
    text: Vinkius acts as a Data Processor when providing services to you under a Data Processing Agreement.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, rent, or trade your Personal Data.
  subprocessors:
    text: A complete list of subprocessors is available upon request and is governed by our Data Processing Agreement.
    url: null
  transfers:
  - mechanism: SCC
    text: We use European Commission-approved Standard Contractual Clauses (2021) with supplementary measures as required by the Schrems II decision
  - mechanism: adequacy
    text: We transfer data to countries recognized by the European Commission as providing adequate data protection
  - mechanism: DPF
    text: For transfers to certified U.S. entities (where applicable and valid)
  - mechanism: SCC
    source: https://vinkius.com/legal/subprocessors
    text: Standard Contractual Clauses (SCCs) and AWS GDPR Data Processing Addendum.
  - mechanism: DPF
    source: https://vinkius.com/legal/subprocessors
    text: EU-U.S. Data Privacy Framework certification, Standard Contractual Clauses (SCCs), and Stripe DPA.
  - mechanism: SCC
    source: https://vinkius.com/legal/subprocessors
    text: European Commission-approved Standard Contractual Clauses (2021) with Subprocessors located in Third Countries
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vinkius
provenance_date: '2026-11-10'
provider_name: Vinkius
provider_slug: vinkius-com
slug: vinkius-com-privacy-policy
source_date: '2026-11-10'
source_filename: vinkius-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://vinkius.com/legal/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vinkius\naid: vinkius-com\nurl: https://vinkius.com/legal/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://vinkius.com/legal/privacy-policy\n  - https://vinkius.com/legal/subprocessors\nrole:\n  value: both\n  text: Vinkius acts as a Data Processor when providing services to you under a Data Processing Agreement.\ndata_categories:\n- category: identifying\n  text: 'Account Information: Email address, full name, username, password (encrypted), company name, job title'\n- category: contact\n  text: 'Contact Information: Phone number, billing address'\n- category: financial\n  text: 'Payment\
  \ Information: Billing contact details (payment card details are processed by our PCI-DSS compliant\n    payment processors and are not stored on our servers)'\n- category: location\n  text: With your explicit consent, we may collect and process information about your approximate or precise geographic\n    location.\n- category: behavioral\n  text: 'Log Data: Access times and dates, pages viewed, features used, clickstream data, referring/exit pages,\n    search queries'\n- category: device\n  text: 'Device Information: IP address, device type, operating system, browser type and version, unique device\n    identifiers'\n- category: communication\n  text: 'Communication Data: Content of messages sent through our support channels, inquiries, feedback, and correspondence\n    with our team'\n- category: contact\n  text: User email addresses, email content (notifications, alerts), email interaction data\n  source: https://vinkius.com/legal/subprocessors\n- category: financial\n  text: Billing\
  \ contact information, payment card details, transaction records\n  source: https://vinkius.com/legal/subprocessors\n- category: device\n  text: IP addresses, browser information, device identifiers, website interactions, advertising performance data\n  source: https://vinkius.com/legal/subprocessors\n- category: behavioral\n  text: page views, user interactions, approximate location (country/city level)\n  source: https://vinkius.com/legal/subprocessors\npurposes:\n- purpose: Service provision\n  text: Creating, maintaining, and securing user accounts\n- purpose: Service improvement\n  text: Analyzing usage patterns to enhance user experience\n- purpose: Security and fraud prevention\n  text: Detecting, preventing, and investigating security incidents\n- purpose: Marketing\n  text: Sending promotional materials about new features, products, and services (only with your consent for marketing\n    communications)\n- purpose: Legal compliance\n  text: Complying with applicable laws and regulations\n\
  - purpose: Subscription payments and billing\n  text: Processes all subscription payments, manages billing, and generates invoices for Vinkius customers.\n  source: https://vinkius.com/legal/subprocessors\n- purpose: Transactional email delivery\n  text: Delivers transactional emails from Vinkius to users, including account notifications, password reset emails,\n    system alerts, and platform updates.\n  source: https://vinkius.com/legal/subprocessors\n- purpose: Web analytics\n  text: Analyzes platform usage, user behavior, and performance metrics to improve Vinkius's Services and user experience.\n  source: https://vinkius.com/legal/subprocessors\n- purpose: Targeted advertising\n  text: Enables targeted advertising, measures campaign effectiveness, and builds audiences for marketing purposes.\n  source: https://vinkius.com/legal/subprocessors\nretention:\n- scope: Account Data\n  period: 30 days\n  text: Retained for the duration of your active account plus 30 days after account closure\
  \ or deletion request\n- scope: Transaction Records\n  period: 7 years\n  text: 'Transaction Records: Retained for 7 years to comply with tax and financial regulations as required by GDPR\n    and EU financial directives'\n- scope: Usage Data and Logs\n  period: 24 months\n  text: 'Usage Data and Logs: Retained for 24 months for security, analytics, and troubleshooting purposes'\n- scope: Support Communications\n  period: 3 years\n  text: 'Support Communications: Retained for 3 years to provide ongoing support and improve service quality'\nresidency:\n- region: European Union, United States, and other locations\n  text: Your data is processed and stored in Amazon Web Services (AWS) data centers with global redundancy across\n    multiple geographic regions, including the European Union, United States, and other locations.\n- region: EU (AWS hosting)\n  text: EU (Frankfurt, Germany; Dublin, Ireland)\n  source: https://vinkius.com/legal/subprocessors\ntransfers:\n- mechanism: SCC\n  text:\
  \ We use European Commission-approved Standard Contractual Clauses (2021) with supplementary measures as required\n    by the Schrems II decision\n- mechanism: adequacy\n  text: We transfer data to countries recognized by the European Commission as providing adequate data protection\n- mechanism: DPF\n  text: For transfers to certified U.S. entities (where applicable and valid)\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCCs) and AWS GDPR Data Processing Addendum.\n  source: https://vinkius.com/legal/subprocessors\n- mechanism: DPF\n  text: EU-U.S. Data Privacy Framework certification, Standard Contractual Clauses (SCCs), and Stripe DPA.\n  source: https://vinkius.com/legal/subprocessors\n- mechanism: SCC\n  text: European Commission-approved Standard Contractual Clauses (2021) with Subprocessors located in Third Countries\n  source: https://vinkius.com/legal/subprocessors\nsubprocessors:\n  url: null\n  text: A complete list of subprocessors is available upon request and\
  \ is governed by our Data Processing Agreement.\ndpa:\n  available: true\n  url: null\n  text: A Data Processing Agreement (DPA) governs this relationship in compliance with GDPR Article 28\ndeletion:\n  route: Upon your request via privacy[at]Vinkius.com or dpo[at]Vinkius.com\n  text: Upon expiration of applicable retention periods, or upon your request (where legally permissible), we will\n    securely delete or anonymize your Personal Data using industry-standard data destruction methods.\nrights:\n- right: Access\n  text: Right to Access (GDPR Article 15)\n- right: Rectification\n  text: Right to Rectification (GDPR Article 16)\n- right: Erasure\n  text: Right to Erasure / \"Right to be Forgotten\" (GDPR Article 17)\n- right: Restriction\n  text: Right to Restriction of Processing (GDPR Article 18)\n- right: Portability\n  text: Right to Data Portability (GDPR Article 20)\n- right: Object\n  text: Right to Object (GDPR Article 21)\n- right: Withdraw consent\n  text: Right to Withdraw\
  \ Consent Where processing is based on consent, you have the right to withdraw consent at\n    any time\n- right: Opt-out of sale or sharing (CCPA)\n  text: 'Right to Opt-Out: Opt out of the \"sale\" or \"sharing\" of personal information (Note: Vinkius does not sell\n    personal information)'\n- right: Audit\n  text: Customers have the right to audit Vinkius's compliance with Subprocessor requirements as described in Section\n    11 of the Vinkius Data Processing Agreement.\n  source: https://vinkius.com/legal/subprocessors\n- right: Objection to new subprocessor\n  text: 'If a customer has legitimate grounds related to data protection for objecting to Vinkius''s appointment\n    of a new Subprocessor, the customer must: Notify Vinkius in writing within 30 days of receiving notice of the\n    new Subprocessor'\n  source: https://vinkius.com/legal/subprocessors\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, rent, or trade your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/vinkius-com/privacy/vinkius-com-privacy-policy.yml
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
summary_line: 47 quoted statements, read from Vinkius's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Integration
- Connectors
- AI Governance
- Developer Tools
- Agent-Native
---
