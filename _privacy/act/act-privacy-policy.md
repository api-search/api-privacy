---
api_specs:
- filename: v1
  format: yaml
  label: Act! Web API
  slug: web-api
  spec_type: OpenAPI
  url: https://apimta.act.com/act.web.api/swagger/docs/v1
- filename: act-activityseries-api-openapi.yml
  format: yaml
  label: Act! CRM Activity Series API
  slug: act-activityseries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-activityseries-api-openapi.yml
- filename: act-historytypes-api-openapi.yml
  format: yaml
  label: Act! CRM History Types API
  slug: act-historytypes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-historytypes-api-openapi.yml
- filename: act-marketingautomations-api-openapi.yml
  format: yaml
  label: Act! CRM Marketing Automations API
  slug: act-marketingautomations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-marketingautomations-api-openapi.yml
- filename: act-metadatainfo-api-openapi.yml
  format: yaml
  label: Act! CRM Metadata Info API
  slug: act-metadatainfo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-metadatainfo-api-openapi.yml
- filename: act-secondarycontacts-api-openapi.yml
  format: yaml
  label: Act! CRM Secondary Contacts API
  slug: act-secondarycontacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-secondarycontacts-api-openapi.yml
- filename: act-supplementalfiles-api-openapi.yml
  format: yaml
  label: Act! CRM Supplemental Files API
  slug: act-supplementalfiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-supplementalfiles-api-openapi.yml
- filename: act-custom-entities-api-openapi.yml
  format: yaml
  label: Act! CRM Custom Entities API
  slug: act-custom-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-custom-entities-api-openapi.yml
- filename: act-document-types-api-openapi.yml
  format: yaml
  label: Act! CRM Document Types API
  slug: act-document-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-document-types-api-openapi.yml
- filename: act-sync-data-api-openapi.yml
  format: yaml
  label: Act! CRM Sync Data API
  slug: act-sync-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-sync-data-api-openapi.yml
- filename: act-task-types-api-openapi.yml
  format: yaml
  label: Act! CRM Task Types API
  slug: act-task-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/act/openapi/act-task-types-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes first name, last name, username or similar identifier, employment information including company name, title, and industry.
  - category: contact
    text: Contact Data includes billing address, delivery address, email address, telephone numbers, and copies of your correspondence with us.
  - category: financial
    text: Financial Data includes bank account number and payment card details.
  - category: location
    text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location
  - category: behavioral
    text: Usage Data includes information about how you use our website(s), including if you report a problem with the website(s), products, and services.
  - category: device
    text: browser plug-in types and versions, operating system and platform, and other technology on the devices you use to access this website
  - category: communication
    text: Marketing and Communications Data includes your preferences in receiving marketing from us and our third parties and your communication preferences.
  - category: other
    text: AI Interaction Data includes prompts, instructions, and other inputs You submit to AI-powered features within our Services, and the corresponding AI-generated outputs
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide AI-powered features
    text: we process Your data (including AI Interaction Data) to generate AI-powered summaries, content suggestions, and other AI outputs.
  - purpose: Marketing
    text: To market our products and services to you, subject to applicable legislation.
  - purpose: Targeted advertising
    text: we may also use your Personal Data to display targeted advertising to you online
  - purpose: Protect against misuse
    text: So that we can detect and prevent any fraudulent or malicious activity, or other misuse of our website(s) and Services
  residency:
  - region: Outside Canada
    text: Your Personal Data may be stored or processed outside of Canada by Act! or its service providers
  retention:
  - period: up to 6 years
    scope: Customer personal data
    text: If you (or the company/organization you represent) becomes a customer of Act!, typically we will process your Personal Data for up to 6 years after the date of last purchase at which point we will destroy it.
  - period: up to one year
    scope: Non-customer contacts
    text: If you (or your company/organization) do not become a customer, typically we will process it for up to one year before we destroy it
  - period: up to 30 days
    scope: AI service provider data
    text: Data transmitted to AI service providers may be temporarily retained for up to 30 days for safety and abuse monitoring, after which it is deleted.
  rights:
  - right: Access
    text: for access to your Personal Data.
  - right: Rectification or erasure
    text: for rectification or erasure of your Personal Data.
  - right: Restriction of processing
    text: for restriction of processing concerning you.
  - right: Object to direct marketing
    text: to object to direct marketing (including related profiling).
  - right: Portability
    text: to port your Personal Data which you have provided to us
  - right: Withdraw consent
    text: You have the right to withdraw any consent you give us at any time.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell or rent personal information, as defined in the California Consumer Privacy Act (“CCPA”).
  subprocessors:
    text: A current list of our AI service providers and their data practices is maintained in the AI Services Addendum at https://www.act.com/legal/ai-addendum/.
    url: https://www.act.com/legal/ai-addendum/
  transfers:
  - mechanism: SCC
    text: Where we use certain service providers, by putting in place specific contract terms approved for use in the EU/EEA/UK, known as the Standard Contractual Clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Act! CRM
provenance_date: '2026-11-09'
provider_name: Act! CRM
provider_slug: act
slug: act-privacy-policy
source_date: '2026-11-09'
source_filename: act-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.act.com/legal/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Act! CRM\naid: act\nurl: https://www.act.com/legal/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Identity Data includes first name, last name, username or similar identifier, employment information including\n    company name, title, and industry.\n- category: contact\n  text: Contact Data includes billing address, delivery address, email address, telephone numbers, and copies of\n    your correspondence with us.\n- category: financial\n  text: Financial Data includes bank account number and payment card details.\n- category:\
  \ location\n  text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time\n    zone setting and location\n- category: behavioral\n  text: Usage Data includes information about how you use our website(s), including if you report a problem with\n    the website(s), products, and services.\n- category: device\n  text: browser plug-in types and versions, operating system and platform, and other technology on the devices you\n    use to access this website\n- category: communication\n  text: Marketing and Communications Data includes your preferences in receiving marketing from us and our third\n    parties and your communication preferences.\n- category: other\n  text: AI Interaction Data includes prompts, instructions, and other inputs You submit to AI-powered features within\n    our Services, and the corresponding AI-generated outputs\npurposes:\n- purpose: Provide AI-powered features\n  text: we process Your data (including AI Interaction\
  \ Data) to generate AI-powered summaries, content suggestions,\n    and other AI outputs.\n- purpose: Marketing\n  text: To market our products and services to you, subject to applicable legislation.\n- purpose: Targeted advertising\n  text: we may also use your Personal Data to display targeted advertising to you online\n- purpose: Protect against misuse\n  text: So that we can detect and prevent any fraudulent or malicious activity, or other misuse of our website(s)\n    and Services\nretention:\n- scope: Customer personal data\n  period: up to 6 years\n  text: If you (or the company/organization you represent) becomes a customer of Act!, typically we will process\n    your Personal Data for up to 6 years after the date of last purchase at which point we will destroy it.\n- scope: Non-customer contacts\n  period: up to one year\n  text: If you (or your company/organization) do not become a customer, typically we will process it for up to one\n    year before we destroy it\n- scope: AI\
  \ service provider data\n  period: up to 30 days\n  text: Data transmitted to AI service providers may be temporarily retained for up to 30 days for safety and abuse\n    monitoring, after which it is deleted.\nresidency:\n- region: Outside Canada\n  text: Your Personal Data may be stored or processed outside of Canada by Act! or its service providers\ntransfers:\n- mechanism: SCC\n  text: Where we use certain service providers, by putting in place specific contract terms approved for use in\n    the EU/EEA/UK, known as the Standard Contractual Clauses\nsubprocessors:\n  url: https://www.act.com/legal/ai-addendum/\n  text: A current list of our AI service providers and their data practices is maintained in the AI Services Addendum\n    at https://www.act.com/legal/ai-addendum/.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Access\n  text: for access to your Personal Data.\n- right: Rectification or erasure\n  text: for rectification\
  \ or erasure of your Personal Data.\n- right: Restriction of processing\n  text: for restriction of processing concerning you.\n- right: Object to direct marketing\n  text: to object to direct marketing (including related profiling).\n- right: Portability\n  text: to port your Personal Data which you have provided to us\n- right: Withdraw consent\n  text: You have the right to withdraw any consent you give us at any time.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell or rent personal information, as defined in the California Consumer Privacy Act (“CCPA”).\n"
source_yaml_url: https://artifacts.apis.io/act/privacy/act-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Act! CRM's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Marketing Automation
- Contact Management
- Sales
- Opportunity Management
- OData
- Small Business
---
