---
api_specs:
- filename: reachdesk-bulk-sends-api-openapi.yml
  format: yaml
  label: Reachdesk Bulk Sends API
  slug: reachdesk-bulk-sends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-bulk-sends-api-openapi.yml
- filename: reachdesk-campaigns-api-openapi.yml
  format: yaml
  label: Reachdesk Campaigns API
  slug: reachdesk-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-campaigns-api-openapi.yml
- filename: reachdesk-contacts-api-openapi.yml
  format: yaml
  label: Reachdesk Contacts API
  slug: reachdesk-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-contacts-api-openapi.yml
- filename: reachdesk-gdpr-api-openapi.yml
  format: yaml
  label: Reachdesk Gdpr API
  slug: reachdesk-gdpr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-gdpr-api-openapi.yml
- filename: reachdesk-organization-api-openapi.yml
  format: yaml
  label: Reachdesk Organization API
  slug: reachdesk-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-organization-api-openapi.yml
- filename: reachdesk-sends-api-openapi.yml
  format: yaml
  label: Reachdesk Sends API
  slug: reachdesk-sends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-sends-api-openapi.yml
- filename: reachdesk-transactions-api-openapi.yml
  format: yaml
  label: Reachdesk Transactions API
  slug: reachdesk-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reachdesk/openapi/reachdesk-transactions-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes first name, last name, username or similar identifier, social media handle, job title and company
  - category: contact
    text: Contact Data includes billing address, delivery address, email address and telephone numbers
  - category: financial
    text: Transaction Data includes details of products and services you have purchased from us.
  - category: device
    text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location
  - category: behavioral
    text: Usage Data includes information about how you use our website, products and services.
  - category: behavioral
    text: Profile Data includes downloads, purchases or requests made by you, your interests, preferences, feedback and survey responses.
  deletion:
    route: Request erasure by contacting legals@reachdesk.com
    text: Request erasure of your personal data. This enables you to ask us to delete or remove personal data where there is no good reason for us continuing to process it.
  dpa:
    available: null
    text: agreed to with Reachdesk
    url: null
  purposes:
  - purpose: Register and manage customers
    text: To register you as a new customer
  - purpose: Deliver services and collect payments
    text: 'To process and deliver our services including: (a) Manage payments, fees and charges (b) Collect and recover money owed to us'
  - purpose: Send gifts for customers
    text: To send you a gift on behalf of a Customer of ours (Controller) with Reachdesk as a Processor.
  - purpose: Webinar registration and episode partner sharing
    text: To register you for and run a webinar or podcast episode and, where you have opted in, to share your registration details with the named episode partner for its own marketing.
  retention:
  - period: the duration of the term of the agreement that we have with the relevant customer
    scope: Processor capacity
    text: In our capacity as a processor of our customers, we will only retain your personal data for the duration of the term of the agreement that we have with the relevant customer.
  - period: null
    scope: Controller capacity
    text: In our capacity as a controller, we will only retain your personal data for as long as necessary to fulfill the purposes we collected it for, including for the purposes of satisfying any legal, accounting, or reporting requirements, and in some cases for six years after that to identify any issues and resolve any legal proceedings.
  rights:
  - right: Access
    text: Request access to your personal data (commonly known as a “data subject access request”).
  - right: Correction
    text: Request correction of the personal data that we hold about you.
  - right: Erasure
    text: Request erasure of your personal data.
  - right: Objection
    text: Object to processing of your personal data where we are relying on a legitimate interest
  - right: Restriction
    text: Request restriction of processing of your personal data.
  - right: Portability
    text: Request the transfer of your personal data to you or to a third party.
  - right: Withdraw consent
    text: Withdraw consent at any time where we are relying on consent to process your personal data.
  role:
    text: We are either the controller responsible for your personal data or the processor for the purposes specific to providing our services to our customers
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not and will not sell any personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: adequacy
    text: We will only transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data by the European Commission or equivalent authority in the UK.
  - mechanism: SCC
    text: We may use specific contracts approved by the European Commission and Information Commissioner's Office which give personal data the same protection it has in the UK and EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Reachdesk
provenance_date: '2026-11-10'
provider_name: Reachdesk
provider_slug: reachdesk
slug: reachdesk-privacy-policy
source_date: '2026-11-10'
source_filename: reachdesk-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.reachdesk.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Reachdesk\naid: reachdesk\nurl: https://www.reachdesk.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: We are either the controller responsible for your personal data or the processor for the purposes specific\n    to providing our services to our customers\ndata_categories:\n- category: identifying\n  text: Identity Data includes first name, last name, username or similar identifier, social media handle, job title\n    and company\n- category: contact\n  text: Contact Data includes billing address, delivery address, email address and telephone numbers\n- category: financial\n \
  \ text: Transaction Data includes details of products and services you have purchased from us.\n- category: device\n  text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time\n    zone setting and location\n- category: behavioral\n  text: Usage Data includes information about how you use our website, products and services.\n- category: behavioral\n  text: Profile Data includes downloads, purchases or requests made by you, your interests, preferences, feedback\n    and survey responses.\npurposes:\n- purpose: Register and manage customers\n  text: To register you as a new customer\n- purpose: Deliver services and collect payments\n  text: 'To process and deliver our services including: (a) Manage payments, fees and charges (b) Collect and recover\n    money owed to us'\n- purpose: Send gifts for customers\n  text: To send you a gift on behalf of a Customer of ours (Controller) with Reachdesk as a Processor.\n- purpose: Webinar registration\
  \ and episode partner sharing\n  text: To register you for and run a webinar or podcast episode and, where you have opted in, to share your registration\n    details with the named episode partner for its own marketing.\nretention:\n- scope: Processor capacity\n  period: the duration of the term of the agreement that we have with the relevant customer\n  text: In our capacity as a processor of our customers, we will only retain your personal data for the duration\n    of the term of the agreement that we have with the relevant customer.\n- scope: Controller capacity\n  period: null\n  text: In our capacity as a controller, we will only retain your personal data for as long as necessary to fulfill\n    the purposes we collected it for, including for the purposes of satisfying any legal, accounting, or reporting\n    requirements, and in some cases for six years after that to identify any issues and resolve any legal proceedings.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text:\
  \ We will only transfer your personal data to countries that have been deemed to provide an adequate level\n    of protection for personal data by the European Commission or equivalent authority in the UK.\n- mechanism: SCC\n  text: We may use specific contracts approved by the European Commission and Information Commissioner's Office\n    which give personal data the same protection it has in the UK and EEA.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: agreed to with Reachdesk\ndeletion:\n  route: Request erasure by contacting legals@reachdesk.com\n  text: Request erasure of your personal data. This enables you to ask us to delete or remove personal data where\n    there is no good reason for us continuing to process it.\nrights:\n- right: Access\n  text: Request access to your personal data (commonly known as a “data subject access request”).\n- right: Correction\n  text: Request correction of the personal data that we hold about you.\n- right:\
  \ Erasure\n  text: Request erasure of your personal data.\n- right: Objection\n  text: Object to processing of your personal data where we are relying on a legitimate interest\n- right: Restriction\n  text: Request restriction of processing of your personal data.\n- right: Portability\n  text: Request the transfer of your personal data to you or to a third party.\n- right: Withdraw consent\n  text: Withdraw consent at any time where we are relying on consent to process your personal data.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not and will not sell any personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/reachdesk/privacy/reachdesk-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from Reachdesk's own page on 2026-11-10.
synthetic: false
tags:
- Corporate Gifting
- Direct Mail
- Swag
- B2B
- Sales Enablement
- Customer Success
- Marketing Automation
- Gifting Platform
- Rewards
- MCP
- AI Agents
- OpenAPI
---
