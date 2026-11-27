---
api_specs:
- filename: agile-crm-campaigns-api-openapi.yml
  format: yaml
  label: Agile CRM Campaigns API
  slug: agile-crm-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-campaigns-api-openapi.yml
- filename: agile-crm-companies-api-openapi.yml
  format: yaml
  label: Agile CRM Companies API
  slug: agile-crm-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-companies-api-openapi.yml
- filename: agile-crm-contacts-api-openapi.yml
  format: yaml
  label: Agile CRM Contacts API
  slug: agile-crm-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-contacts-api-openapi.yml
- filename: agile-crm-deals-api-openapi.yml
  format: yaml
  label: Agile CRM Deals API
  slug: agile-crm-deals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-deals-api-openapi.yml
- filename: agile-crm-documents-api-openapi.yml
  format: yaml
  label: Agile CRM Documents API
  slug: agile-crm-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-documents-api-openapi.yml
- filename: agile-crm-events-api-openapi.yml
  format: yaml
  label: Agile CRM Events API
  slug: agile-crm-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-events-api-openapi.yml
- filename: agile-crm-helpdesk-api-openapi.yml
  format: yaml
  label: Agile CRM HelpDesk API
  slug: agile-crm-helpdesk-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-helpdesk-api-openapi.yml
- filename: agile-crm-notes-api-openapi.yml
  format: yaml
  label: Agile CRM Notes API
  slug: agile-crm-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-notes-api-openapi.yml
- filename: agile-crm-tasks-api-openapi.yml
  format: yaml
  label: Agile CRM Tasks API
  slug: agile-crm-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-tasks-api-openapi.yml
- filename: agile-crm-tracks-api-openapi.yml
  format: yaml
  label: Agile CRM Tracks API
  slug: agile-crm-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agile-crm/openapi/agile-crm-tracks-api-openapi.yml
claim_count: 11
description: ''
doc:
  data_categories:
  - category: contact
    text: name, email address, phone number, website, social media handles, mailing address, billing information
  - category: communication
    text: User’s Mails from Gmail
  - category: professional
    text: Contacts' organization
  deletion:
    route: delete account via support department
    text: if you want to delete all customer data that was imported to Agile CRM simply delete your account in coordination with out support department.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: providing services and product updates
    text: for the sole purpose of providing best services to our customers and to update them of the improvements to our product and services
  - purpose: Google Apps data population and sync
    text: We normally use this information to Populate your Google Apps data in your Agile CRM contact management tool.
  residency:
  - region: Google & Amazon clouds
    text: Hosted on high performing Google & Amazon clouds
  retention:
  - period: for as long as your account is active
    scope: synced/imported information
    text: We will retain the synced/imported information for as long as your account is active or as needed to provide you with our services.
  rights:
  - right: opt out of promotional offers
    text: The customer/ prospect can always opt out from receiving such offers/ notifications by following the opt out link on the specific communication or by contacting Agile CRM directly.
  - right: review, correct, or update
    text: To review, correct, or update your customers' information, you can use the Agile CRM tool or you can update this information directly from Google Apps.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not share or sell your personal information to third parties.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Agile CRM
provenance_date: '2026-11-09'
provider_name: Agile CRM
provider_slug: agile-crm
slug: agile-crm-privacy-policy
source_date: '2026-11-09'
source_filename: agile-crm-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.agilecrm.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Agile CRM\naid: agile-crm\nurl: https://www.agilecrm.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: name, email address, phone number, website, social media handles, mailing address, billing information\n- category: communication\n  text: User’s Mails from Gmail\n- category: professional\n  text: Contacts' organization\npurposes:\n- purpose: providing services and product updates\n  text: for the sole purpose of providing best services to our customers and to update them of the improvements\n    to our product and services\n\
  - purpose: Google Apps data population and sync\n  text: We normally use this information to Populate your Google Apps data in your Agile CRM contact management\n    tool.\nretention:\n- scope: synced/imported information\n  period: for as long as your account is active\n  text: We will retain the synced/imported information for as long as your account is active or as needed to provide\n    you with our services.\nresidency:\n- region: Google & Amazon clouds\n  text: Hosted on high performing Google & Amazon clouds\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: delete account via support department\n  text: if you want to delete all customer data that was imported to Agile CRM simply delete your account in coordination\n    with out support department.\nrights:\n- right: opt out of promotional offers\n  text: The customer/ prospect can always opt out from receiving such offers/ notifications by following\
  \ the opt\n    out link on the specific communication or by contacting Agile CRM directly.\n- right: review, correct, or update\n  text: To review, correct, or update your customers' information, you can use the Agile CRM tool or you can update\n    this information directly from Google Apps.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not share or sell your personal information to third parties.\n"
source_yaml_url: https://artifacts.apis.io/agile-crm/privacy/agile-crm-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 11 quoted statements, read from Agile CRM's own page on 2026-11-09.
synthetic: false
tags:
- CRM
- Sales Automation
- Marketing Automation
- Help Desk
- Small Business
- Contact Management
---
