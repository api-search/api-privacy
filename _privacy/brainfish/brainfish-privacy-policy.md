---
api_specs:
- filename: brainfish-agents-api-openapi.yml
  format: yaml
  label: Brainfish Agents API
  slug: brainfish-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-agents-api-openapi.yml
- filename: brainfish-analytics-api-openapi.yml
  format: yaml
  label: Brainfish Analytics API
  slug: brainfish-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-analytics-api-openapi.yml
- filename: brainfish-authentication-api-openapi.yml
  format: yaml
  label: Brainfish Authentication API
  slug: brainfish-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-authentication-api-openapi.yml
- filename: brainfish-catalogs-api-openapi.yml
  format: yaml
  label: Brainfish Catalogs API
  slug: brainfish-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-catalogs-api-openapi.yml
- filename: brainfish-collections-api-openapi.yml
  format: yaml
  label: Brainfish Collections API
  slug: brainfish-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-collections-api-openapi.yml
- filename: brainfish-conversations-api-openapi.yml
  format: yaml
  label: Brainfish Conversations API
  slug: brainfish-conversations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-conversations-api-openapi.yml
- filename: brainfish-documents-api-openapi.yml
  format: yaml
  label: Brainfish Documents API
  slug: brainfish-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-documents-api-openapi.yml
- filename: brainfish-sessions-api-openapi.yml
  format: yaml
  label: Brainfish Sessions API
  slug: brainfish-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-sessions-api-openapi.yml
- filename: brainfish-users-api-openapi.yml
  format: yaml
  label: Brainfish Users API
  slug: brainfish-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/brainfish/openapi/brainfish-users-api-openapi.yml
claim_count: 23
description: ''
doc:
  data_categories:
  - category: identifying
    text: ‘Identity Data’ includes first name, last name, marital status, title, job title, profile photo, company, location, date of birth and gender
  - category: contact
    text: ‘Contact Data’ includes billing address, email address and telephone numbers
  - category: financial
    text: ‘Financial Data’ includes bank account and payment card details (through our third-party payment processor, Stripe) if you start a subscription
  - category: device
    text: ‘Technical Data’ includes internet protocol (IP) address, your login data for our services
  - category: behavioral
    text: ‘Usage Data’ includes information about how you use our website, products and services.
  - category: other
    text: ‘Customer Content Data’ includes any personal data contained within data, documents, files, communications, transaction records, stored files, analytics data, metrics, or other materials that you (or your authorised users) submit, upload, store, transmit, create, generate, or otherwise process when using our services
  - category: professional
    text: ‘Job Seeker Data’ includes CVs and résumés, application and interview notes, right-to-work documentation and background checks (where lawful), references, professional profiles, and payroll or tax identification information for staff or contractors
  deletion:
    route: email privacy@brainfi.sh
    text: To contact us or submit requests in relation to any of the above, please email privacy@brainfi.sh
  dpa:
    available: true
    text: we act as a processor/service provider under our Data Processing Agreement and the customer’s instructions
    url: null
  purposes:
  - purpose: Account and subscription management
    text: To manage your account and subscription, enable logging in to our services, and customize your use of our services
  - purpose: Website administration and security
    text: To administer and protect our business and our website (including troubleshooting, data analysis, testing, system maintenance, validating against fraudulent transactions, support, reporting and hosting of data)
  - purpose: Recruitment
    text: To assess and administer job applications, conduct interviews, carry out right-to-work and background checks (where lawful), obtain references, evaluate professional profiles, and, where relevant, onboard staff or contractors (including payroll and tax administration)
  residency:
  - region: United States
    text: Our production infrastructure is hosted primarily in the United States with major cloud providers (AWS and Google Cloud)
  retention:
  - period: null
    scope: General
    text: We will only retain your Personal Data for as long as necessary to fulfil the purposes we collected it for.
  - period: null
    scope: Enquiries and mailing list
    text: If you have asked for information from us or you have subscribed to our mailing list, we keep your details until you ask us to stop contacting you.
  rights:
  - right: access
    text: You can request access of your Personal Data.
  - right: correction
    text: You can ask us to correct your Personal Data if it is inaccurate or incomplete.
  - right: deletion
    text: You can ask us to delete or remove your Personal Data if there is no good reason for us to continuing holding it or if you have asked us to stop using it.
  - right: objection, restriction and portability
    text: You can object to processing of your Personal Data, ask us to restrict processing of your Personal Data or request portability of your Personal Data.
  - right: withdraw consent
    text: If we have collected your Personal Data with your consent, you can withdraw your consent at any time.
  - right: opt-out of sale or sharing (CCPA)
    text: You have the right to opt-out of the sale or sharing of your Personal Data.
  role:
    text: we are the controller of your Personal Data
    value: both
  sale_or_sharing:
    stance: unstated
    text: We do not sell or share your Personal Data for cross-context behavioural advertising.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: where applicable, participation in the EU-U.S. Data Privacy Framework, the UK Extension and the Swiss-U.S. DPF
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Brainfish
provenance_date: '2026-11-09'
provider_name: Brainfish
provider_slug: brainfish
slug: brainfish-privacy-policy
source_date: '2026-11-09'
source_filename: brainfish-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.brainfishai.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Brainfish\naid: brainfish\nurl: https://www.brainfishai.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we are the controller of your Personal Data\ndata_categories:\n- category: identifying\n  text: ‘Identity Data’ includes first name, last name, marital status, title, job title, profile photo, company,\n    location, date of birth and gender\n- category: contact\n  text: ‘Contact Data’ includes billing address, email address and telephone numbers\n- category: financial\n  text: ‘Financial Data’ includes bank account and payment card details (through our third-party payment processor,\n\
  \    Stripe) if you start a subscription\n- category: device\n  text: ‘Technical Data’ includes internet protocol (IP) address, your login data for our services\n- category: behavioral\n  text: ‘Usage Data’ includes information about how you use our website, products and services.\n- category: other\n  text: ‘Customer Content Data’ includes any personal data contained within data, documents, files, communications,\n    transaction records, stored files, analytics data, metrics, or other materials that you (or your authorised\n    users) submit, upload, store, transmit, create, generate, or otherwise process when using our services\n- category: professional\n  text: ‘Job Seeker Data’ includes CVs and résumés, application and interview notes, right-to-work documentation\n    and background checks (where lawful), references, professional profiles, and payroll or tax identification information\n    for staff or contractors\npurposes:\n- purpose: Account and subscription management\n  text:\
  \ To manage your account and subscription, enable logging in to our services, and customize your use of our\n    services\n- purpose: Website administration and security\n  text: To administer and protect our business and our website (including troubleshooting, data analysis, testing,\n    system maintenance, validating against fraudulent transactions, support, reporting and hosting of data)\n- purpose: Recruitment\n  text: To assess and administer job applications, conduct interviews, carry out right-to-work and background checks\n    (where lawful), obtain references, evaluate professional profiles, and, where relevant, onboard staff or contractors\n    (including payroll and tax administration)\nretention:\n- scope: General\n  period: null\n  text: We will only retain your Personal Data for as long as necessary to fulfil the purposes we collected it for.\n- scope: Enquiries and mailing list\n  period: null\n  text: If you have asked for information from us or you have subscribed to\
  \ our mailing list, we keep your details\n    until you ask us to stop contacting you.\nresidency:\n- region: United States\n  text: Our production infrastructure is hosted primarily in the United States with major cloud providers (AWS and\n    Google Cloud)\ntransfers:\n- mechanism: DPF\n  text: where applicable, participation in the EU-U.S. Data Privacy Framework, the UK Extension and the Swiss-U.S.\n    DPF\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: we act as a processor/service provider under our Data Processing Agreement and the customer’s instructions\ndeletion:\n  route: email privacy@brainfi.sh\n  text: To contact us or submit requests in relation to any of the above, please email privacy@brainfi.sh\nrights:\n- right: access\n  text: You can request access of your Personal Data.\n- right: correction\n  text: You can ask us to correct your Personal Data if it is inaccurate or incomplete.\n- right: deletion\n  text: You can ask us to\
  \ delete or remove your Personal Data if there is no good reason for us to continuing holding\n    it or if you have asked us to stop using it.\n- right: objection, restriction and portability\n  text: You can object to processing of your Personal Data, ask us to restrict processing of your Personal Data\n    or request portability of your Personal Data.\n- right: withdraw consent\n  text: If we have collected your Personal Data with your consent, you can withdraw your consent at any time.\n- right: opt-out of sale or sharing (CCPA)\n  text: You have the right to opt-out of the sale or sharing of your Personal Data.\nsale_or_sharing:\n  stance: unstated\n  text: We do not sell or share your Personal Data for cross-context behavioural advertising.\n"
source_yaml_url: https://artifacts.apis.io/brainfish/privacy/brainfish-privacy-policy.yml
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
summary_line: 23 quoted statements, read from Brainfish's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Customer Service
- Knowledge Base
- Help Desk
- Agents
- Support Automation
- Software-as-a-Service
---
