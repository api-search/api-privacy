---
api_specs:
- filename: replit-deployments-api-openapi.yml
  format: yaml
  label: Replit Deployments API
  slug: replit-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-deployments-api-openapi.yml
- filename: replit-repls-api-openapi.yml
  format: yaml
  label: Replit Repls API
  slug: replit-repls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-repls-api-openapi.yml
- filename: replit-users-api-openapi.yml
  format: yaml
  label: Replit Users API
  slug: replit-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/replit/openapi/replit-users-api-openapi.yml
claim_count: 21
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect data associated with your account registration, including name, username, email address and phone number.
  - category: location
    text: We do not collect precise location information unless you have consented.
  - category: device
    text: We collect data about the device and software you use to access our Services, including internet protocol (IP) address
  - category: financial
    text: we may receive certain payment related data such as the last four digits of payment cards, payment method and financial institution.
  - category: communication
    text: We collect data about and included in communications, including your name, email address, and the contents of communications.
  - category: behavioral
    text: We collect data about your interactions with our Services, like the pages or other content you view or interact with, the searches you conduct
  - category: other
    text: If you choose to use voice dictation, we also collect audio recordings of your voice.
  deletion:
    route: Account settings or email
    text: You can also submit a request to delete your Personal Data through your account settings.
  dpa:
    available: true
    text: Data processing agreement
    url: null
  purposes:
  - purpose: marketing
    text: We use your data for marketing purposes, including advertising on third party platforms
  - purpose: improve machine learning technologies
    text: to improve the accuracy of our machine learning technologies such as code generation
  - purpose: security and fraud prevention
    text: We use data to detect, prevent, and investigate issues that may involve fraud, security, and other malicious activity.
  - purpose: legal compliance
    text: comply with legal obligations under applicable law
  residency:
  - region: United States
    text: Our Services are primarily hosted in the United States and may also be hosted in locations outside of the jurisdiction in which you live.
  retention:
  - period: null
    scope: identifiable data
    text: We take measures to delete your data or maintain it in a de-identified form when it is no longer necessary to be kept in identifiable form
  rights:
  - right: access
    text: The right to access the Personal Data that we have collected about you.
  - right: deletion
    text: The right to request deletion of the Personal Data that we have collected about you.
  - right: correction
    text: The right to request that we correct errors with respect to the data that we hold about you.
  - right: opt out of sale or sharing
    text: The right to opt out of the sale or sharing of your Personal Data.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: The right to opt out of the sale or sharing of your Personal Data.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: By using the Services, you agree to such transfer, storage, and processing.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Replit
provenance_date: '2026-11-10'
provider_name: Replit
provider_slug: replit
slug: replit-privacy-policy
source_date: '2026-11-10'
source_filename: replit-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://replit.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Replit\naid: replit\nurl: https://replit.com/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: We collect data associated with your account registration, including name, username, email address and phone\n    number.\n- category: location\n  text: We do not collect precise location information unless you have consented.\n- category: device\n  text: We collect data about the device and software you use to access our Services, including internet protocol\n    (IP) address\n- category: financial\n  text: we may receive certain\
  \ payment related data such as the last four digits of payment cards, payment method\n    and financial institution.\n- category: communication\n  text: We collect data about and included in communications, including your name, email address, and the contents\n    of communications.\n- category: behavioral\n  text: We collect data about your interactions with our Services, like the pages or other content you view or interact\n    with, the searches you conduct\n- category: other\n  text: If you choose to use voice dictation, we also collect audio recordings of your voice.\npurposes:\n- purpose: marketing\n  text: We use your data for marketing purposes, including advertising on third party platforms\n- purpose: improve machine learning technologies\n  text: to improve the accuracy of our machine learning technologies such as code generation\n- purpose: security and fraud prevention\n  text: We use data to detect, prevent, and investigate issues that may involve fraud, security, and other\
  \ malicious\n    activity.\n- purpose: legal compliance\n  text: comply with legal obligations under applicable law\nretention:\n- scope: identifiable data\n  period: null\n  text: We take measures to delete your data or maintain it in a de-identified form when it is no longer necessary\n    to be kept in identifiable form\nresidency:\n- region: United States\n  text: Our Services are primarily hosted in the United States and may also be hosted in locations outside of the\n    jurisdiction in which you live.\ntransfers:\n- mechanism: other\n  text: By using the Services, you agree to such transfer, storage, and processing.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Data processing agreement\ndeletion:\n  route: Account settings or email\n  text: You can also submit a request to delete your Personal Data through your account settings.\nrights:\n- right: access\n  text: The right to access the Personal Data that we have collected about you.\n\
  - right: deletion\n  text: The right to request deletion of the Personal Data that we have collected about you.\n- right: correction\n  text: The right to request that we correct errors with respect to the data that we hold about you.\n- right: opt out of sale or sharing\n  text: The right to opt out of the sale or sharing of your Personal Data.\nsale_or_sharing:\n  stance: conditional\n  text: The right to opt out of the sale or sharing of your Personal Data.\n"
source_yaml_url: https://artifacts.apis.io/replit/privacy/replit-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 21 quoted statements, read from Replit's own page on 2026-11-10.
synthetic: false
tags:
- Code
- Compiling
- Developer Tools
- Development Environment
- Programming Language
- Version Control
---
