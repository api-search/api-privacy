---
api_specs:
- filename: capawesome-io-app-build-shares-api-openapi.yml
  format: yaml
  label: capawesome-io App Build Shares API
  slug: capawesome-io-app-build-shares-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capawesome-io/openapi/capawesome-io-app-build-shares-api-openapi.yml
- filename: capawesome-io-apps-api-openapi.yml
  format: yaml
  label: capawesome-io Apps API
  slug: capawesome-io-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capawesome-io/openapi/capawesome-io-apps-api-openapi.yml
- filename: capawesome-io-jobs-api-openapi.yml
  format: yaml
  label: capawesome-io Jobs API
  slug: capawesome-io-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/capawesome-io/openapi/capawesome-io-jobs-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, e-mail address, company name, postal address, telephone number (where provided), login credentials (password hash), account settings, organisation and team membership
  - category: financial
    text: Payment details (credit card numbers, bank details) are processed exclusively by the Merchant of Record and are not transmitted to the Provider.
  - category: device
    text: IP address, date and time of access, requested resource, HTTP status code, referrer URL, browser type and version, operating system
  - category: behavioral
    text: usage events (features used, actions performed, pages viewed) linked to the account holder's user ID and organisation ID
  deletion:
    route: account deletion
    text: When an account is deleted, the Provider deletes the associated analytics profile including its events at the analytics provider.
  dpa:
    available: true
    text: The provisions of the Data Processing Agreement (DPA) at https://capawesome.io/legal/data-processing-agreement/ apply.
    url: https://capawesome.io/legal/data-processing-agreement/
  purposes:
  - purpose: Website provision and security
    text: Provision of the website, ensuring technical security, detection and prevention of misuse
  - purpose: Account and contract performance
    text: Creation and administration of the customer account, provision of the contractual services, communication within the contractual relationship
  - purpose: Product analytics
    text: Understanding feature usage, product improvement, error detection, capacity planning
  - purpose: Newsletters and product information
    text: Sending newsletters and product information
  residency:
  - region: Germany, EU
    text: Hosting, server infrastructure Germany, EU Adequacy (EU)
  retention:
  - period: 7 days
    scope: Server logs
    text: 'Retention period : 7 days, then deletion or anonymisation'
  - period: Duration of the contractual relationship plus 30 days export period after termination
    scope: Account data
    text: Duration of the contractual relationship plus 30 days export period after termination.
  - period: 90 days
    scope: Security logs
    text: 'Retention period : 90 days.'
  - period: up to 3 years
    scope: Newsletter suppression list
    text: for up to 3 years (legitimate interest, Art. 6(1)(f) GDPR)
  - period: Duration of the contractual relationship plus 3 years
    scope: Support requests
    text: Duration of the contractual relationship plus 3 years (standard limitation period, § 195 BGB)
  rights:
  - right: Access
    text: 'Access (Art. 15 GDPR): Right to confirmation and information about the data processed'
  - right: Erasure
    text: 'Erasure (Art. 17 GDPR): Right to erasure, provided no statutory retention obligation prevails'
  - right: Objection
    text: 'Objection (Art. 21 GDPR): Right to object to Processing based on legitimate interests'
  - right: Withdrawal of consent
    text: Consent given may be withdrawn at any time with effect for the future
  - right: Complaint
    text: Data Subjects have the right to lodge a complaint with a Supervisory Authority.
  role:
    text: 'The controller within the meaning of the General Data Protection Regulation (GDPR) is:'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The sub-processor list for customer data processed by the Provider on behalf of customers is available at https://capawesome.io/legal/subprocessors/ .
    url: https://capawesome.io/legal/subprocessors/
  transfers:
  - mechanism: DPF
    text: For US recipients certified under the EU-US Data Privacy Framework, an adequacy decision of the European Commission applies (Implementing Decision (EU) 2023/1795 of 10 July 2023).
  - mechanism: SCC
    text: Where no adequacy decision exists, EU Standard Contractual Clauses (Implementing Decision (EU) 2021/914) are used as the transfer mechanism.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: capawesome-io
provenance_date: '2026-11-09'
provider_name: capawesome-io
provider_slug: capawesome-io
slug: capawesome-io-privacy-policy
source_date: '2026-11-09'
source_filename: capawesome-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://capawesome.io/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: capawesome-io\naid: capawesome-io\nurl: https://capawesome.io/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller within the meaning of the General Data Protection Regulation (GDPR) is:'\ndata_categories:\n- category: identifying\n  text: Name, e-mail address, company name, postal address, telephone number (where provided), login credentials\n    (password hash), account settings, organisation and team membership\n- category: financial\n  text: Payment details (credit card numbers, bank details) are processed exclusively by the Merchant of Record\n    and are\
  \ not transmitted to the Provider.\n- category: device\n  text: IP address, date and time of access, requested resource, HTTP status code, referrer URL, browser type and\n    version, operating system\n- category: behavioral\n  text: usage events (features used, actions performed, pages viewed) linked to the account holder's user ID and\n    organisation ID\npurposes:\n- purpose: Website provision and security\n  text: Provision of the website, ensuring technical security, detection and prevention of misuse\n- purpose: Account and contract performance\n  text: Creation and administration of the customer account, provision of the contractual services, communication\n    within the contractual relationship\n- purpose: Product analytics\n  text: Understanding feature usage, product improvement, error detection, capacity planning\n- purpose: Newsletters and product information\n  text: Sending newsletters and product information\nretention:\n- scope: Server logs\n  period: 7 days\n  text:\
  \ 'Retention period : 7 days, then deletion or anonymisation'\n- scope: Account data\n  period: Duration of the contractual relationship plus 30 days export period after termination\n  text: Duration of the contractual relationship plus 30 days export period after termination.\n- scope: Security logs\n  period: 90 days\n  text: 'Retention period : 90 days.'\n- scope: Newsletter suppression list\n  period: up to 3 years\n  text: for up to 3 years (legitimate interest, Art. 6(1)(f) GDPR)\n- scope: Support requests\n  period: Duration of the contractual relationship plus 3 years\n  text: Duration of the contractual relationship plus 3 years (standard limitation period, § 195 BGB)\nresidency:\n- region: Germany, EU\n  text: Hosting, server infrastructure Germany, EU Adequacy (EU)\ntransfers:\n- mechanism: DPF\n  text: For US recipients certified under the EU-US Data Privacy Framework, an adequacy decision of the European\n    Commission applies (Implementing Decision (EU) 2023/1795 of 10 July\
  \ 2023).\n- mechanism: SCC\n  text: Where no adequacy decision exists, EU Standard Contractual Clauses (Implementing Decision (EU) 2021/914)\n    are used as the transfer mechanism.\nsubprocessors:\n  url: https://capawesome.io/legal/subprocessors/\n  text: The sub-processor list for customer data processed by the Provider on behalf of customers is available at\n    https://capawesome.io/legal/subprocessors/ .\ndpa:\n  available: true\n  url: https://capawesome.io/legal/data-processing-agreement/\n  text: The provisions of the Data Processing Agreement (DPA) at https://capawesome.io/legal/data-processing-agreement/\n    apply.\ndeletion:\n  route: account deletion\n  text: When an account is deleted, the Provider deletes the associated analytics profile including its events at\n    the analytics provider.\nrights:\n- right: Access\n  text: 'Access (Art. 15 GDPR): Right to confirmation and information about the data processed'\n- right: Erasure\n  text: 'Erasure (Art. 17 GDPR): Right to\
  \ erasure, provided no statutory retention obligation prevails'\n- right: Objection\n  text: 'Objection (Art. 21 GDPR): Right to object to Processing based on legitimate interests'\n- right: Withdrawal of consent\n  text: Consent given may be withdrawn at any time with effect for the future\n- right: Complaint\n  text: Data Subjects have the right to lodge a complaint with a Supervisory Authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/capawesome-io/privacy/capawesome-io-privacy-policy.yml
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
summary_line: 25 quoted statements, read from capawesome-io's own page on 2026-11-09.
synthetic: false
tags:
- Mobile
- DevOps
- CI/CD
- OTA
- Capacitor
- Ionic
---
