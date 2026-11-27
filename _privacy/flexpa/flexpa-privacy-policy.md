---
api_specs:
- filename: flexpa-access-tokens-api-openapi.yml
  format: yaml
  label: Flexpa Access Tokens API
  slug: flexpa-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-access-tokens-api-openapi.yml
- filename: flexpa-claims-data-api-openapi.yml
  format: yaml
  label: Flexpa Claims Data API
  slug: flexpa-claims-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-claims-data-api-openapi.yml
- filename: flexpa-fhir-api-openapi.yml
  format: yaml
  label: Flexpa FHIR API
  slug: flexpa-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-fhir-api-openapi.yml
- filename: flexpa-link-api-openapi.yml
  format: yaml
  label: Flexpa Link API
  slug: flexpa-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexpa/openapi/flexpa-link-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: identifies a person either directly or when combined with other information.
  - category: contact
    text: we require certain information such as your first name, last name, telephone number, and email address.
  - category: health
    text: your Personal Health Information from a health care provider or a health plan to a third-party application
  - category: biometric
    text: that provider may collect a selfie, images of your government-issued identification, and biometric information derived from those images
  - category: behavioral
    text: We collect information about your interactions with the Flexpa Platform such as the pages or content you view, your searches, and communications.
  - category: device
    text: It also includes device info, device event info, unique identifiers, crash data, cookie data, and the pages you interacted with.
  - category: communication
    text: If you contact us directly, we may receive additional information about you
  deletion:
    route: Email privacy@flexpa.com or self-serve at privacy.flexpa.com
    text: You may request deletion of your account by contacting us at privacy@flexpa.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Respond to requests
    text: Respond to your requests
  - purpose: Security and technical issues
    text: Secure our Flexpa Platform and resolve technical issues being reported
  - purpose: Operate the platform
    text: Operate the Flexpa Platform, including by storing any information on Flexpa servers
  - purpose: Contact users
    text: Contact you by email, postal mail, or phone regarding Flexpa and the Flexpa Platform
  retention:
  - period: 45 days
    scope: Deleted or terminated accounts
    text: If your account is deleted or terminated, your Personal Information will be deleted within 45 days from termination or request for deletion.
  - period: 45 days
    scope: Dormant accounts
    text: If your account is dormant without activity for over a year, your Personal Information will be deleted within 45 days from the one-year dormant period
  rights:
  - right: Access and portability
    text: You have the right to request that we provide access to and/or a copy of certain information we hold about you in a machine-readable format
  - right: Deletion
    text: You have the right to delete your information to the extent technically feasible and not prohibited by law
  - right: Correction
    text: You have the right to have us update information which is out of date or incorrect.
  - right: Restriction
    text: You have the right to restrict the way that we process and disclose certain of your information.
  - right: Withdraw consent
    text: You have the right to withdraw your consent at any time where we rely on your consent as the basis to process or use your Personal Information.
  - right: Opt out of direct marketing
    text: You have the right to prevent the processing of your information for direct-marketing purposes.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Flexpa does not sell your Personal Information.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Flexpa
provenance_date: '2026-11-09'
provider_name: Flexpa
provider_slug: flexpa
slug: flexpa-privacy-policy
source_date: '2026-11-09'
source_filename: flexpa-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.flexpa.com/docs/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Flexpa\naid: flexpa\nurl: https://www.flexpa.com/docs/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: identifies a person either directly or when combined with other information.\n- category: contact\n  text: we require certain information such as your first name, last name, telephone number, and email address.\n- category: health\n  text: your Personal Health Information from a health care provider or a health plan to a third-party application\n- category: biometric\n  text: that provider may collect a selfie, images of your government-issued\
  \ identification, and biometric information\n    derived from those images\n- category: behavioral\n  text: We collect information about your interactions with the Flexpa Platform such as the pages or content you\n    view, your searches, and communications.\n- category: device\n  text: It also includes device info, device event info, unique identifiers, crash data, cookie data, and the pages\n    you interacted with.\n- category: communication\n  text: If you contact us directly, we may receive additional information about you\npurposes:\n- purpose: Respond to requests\n  text: Respond to your requests\n- purpose: Security and technical issues\n  text: Secure our Flexpa Platform and resolve technical issues being reported\n- purpose: Operate the platform\n  text: Operate the Flexpa Platform, including by storing any information on Flexpa servers\n- purpose: Contact users\n  text: Contact you by email, postal mail, or phone regarding Flexpa and the Flexpa Platform\nretention:\n- scope:\
  \ Deleted or terminated accounts\n  period: 45 days\n  text: If your account is deleted or terminated, your Personal Information will be deleted within 45 days from\n    termination or request for deletion.\n- scope: Dormant accounts\n  period: 45 days\n  text: If your account is dormant without activity for over a year, your Personal Information will be deleted within\n    45 days from the one-year dormant period\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@flexpa.com or self-serve at privacy.flexpa.com\n  text: You may request deletion of your account by contacting us at privacy@flexpa.com\nrights:\n- right: Access and portability\n  text: You have the right to request that we provide access to and/or a copy of certain information we hold about\n    you in a machine-readable format\n- right: Deletion\n  text: You have the right to delete your information to the extent technically\
  \ feasible and not prohibited by law\n- right: Correction\n  text: You have the right to have us update information which is out of date or incorrect.\n- right: Restriction\n  text: You have the right to restrict the way that we process and disclose certain of your information.\n- right: Withdraw consent\n  text: You have the right to withdraw your consent at any time where we rely on your consent as the basis to process\n    or use your Personal Information.\n- right: Opt out of direct marketing\n  text: You have the right to prevent the processing of your information for direct-marketing purposes.\nsale_or_sharing:\n  stance: prohibited\n  text: Flexpa does not sell your Personal Information.\n"
source_yaml_url: https://artifacts.apis.io/flexpa/privacy/flexpa-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Flexpa's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- FHIR
- Patient Access
- Claims Data
- Health Insurance
---
