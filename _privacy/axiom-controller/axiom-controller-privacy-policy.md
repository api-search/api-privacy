---
api_specs:
- filename: axiom-controller-datasets-api-openapi.yml
  format: yaml
  label: Axiom Controller Datasets API
  slug: axiom-controller-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiom-controller/openapi/axiom-controller-datasets-api-openapi.yml
- filename: axiom-controller-edge-api-openapi.yml
  format: yaml
  label: Axiom Controller Edge API
  slug: axiom-controller-edge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiom-controller/openapi/axiom-controller-edge-api-openapi.yml
- filename: axiom-controller-ingest-api-openapi.yml
  format: yaml
  label: Axiom Controller Ingest API
  slug: axiom-controller-ingest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/axiom-controller/openapi/axiom-controller-ingest-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: contact
    text: First and last name Email address
  - category: device
    text: Type of device, operating system, browser used to access service
  - category: behavioral
    text: Browsing or search history
  - category: location
    text: IP address-based location information
  deletion:
    route: Email privacy@axiom.co
    text: You have the right to request that we delete the Personal Data that we have collected about you.
  dpa:
    available: null
    text: In some circumstances, your Personal Data may be transferred to the U.S. pursuant to a data processing agreement incorporating legally required data protection clauses.
    url: null
  purposes:
  - purpose: Providing, customizing and improving Sites
    text: Providing, Customizing and Improving Sites Creating and managing your account or other user profiles.
  - purpose: Corresponding with you
    text: Responding to correspondence that we receive from you, contacting you when necessary or requested
  - purpose: Legal requirements
    text: Fulfilling our legal obligations under applicable law, regulation, court order or other legal process
  retention:
  - period: as long as you have an account with us
    scope: Profile information and credentials
    text: We retain your profile information and credentials for as long as you have an account with us.
  - period: as long as we need to process your purchase or subscription
    scope: Payment data
    text: We retain your payment data for as long as we need to process your purchase or subscription.
  rights:
  - right: Access
    text: You have the right to request confirmation of whether or not we are processing your Personal Data and to access your Personal Data.
  - right: Correction
    text: You have the right to correct inaccuracies in your Personal Data
  - right: Portability
    text: You have the right to request a copy of your Personal Data in a machine-readable format, to the extent technically feasible.
  - right: Erasure
    text: 'Erasure: You can request that we erase some or all of your Personal Data from our systems.'
  - right: Objection
    text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal Data for certain purposes, such as for direct marketing purposes.'
  role:
    text: Company will be the controller of your Personal Data processed in connection with the Services.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We will not sell your Personal Data, and have not done so over the last 12 months.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Axiom Controller
provenance_date: '2026-11-09'
provider_name: Axiom Controller
provider_slug: axiom-controller
slug: axiom-controller-privacy-policy
source_date: '2026-11-09'
source_filename: axiom-controller-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://axiom.co/docs/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Axiom Controller\naid: axiom-controller\nurl: https://axiom.co/docs/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Company will be the controller of your Personal Data processed in connection with the Services.\ndata_categories:\n- category: contact\n  text: First and last name Email address\n- category: device\n  text: Type of device, operating system, browser used to access service\n- category: behavioral\n  text: Browsing or search history\n- category: location\n  text: IP address-based location information\npurposes:\n- purpose: Providing, customizing and improving Sites\n  text:\
  \ Providing, Customizing and Improving Sites Creating and managing your account or other user profiles.\n- purpose: Corresponding with you\n  text: Responding to correspondence that we receive from you, contacting you when necessary or requested\n- purpose: Legal requirements\n  text: Fulfilling our legal obligations under applicable law, regulation, court order or other legal process\nretention:\n- scope: Profile information and credentials\n  period: as long as you have an account with us\n  text: We retain your profile information and credentials for as long as you have an account with us.\n- scope: Payment data\n  period: as long as we need to process your purchase or subscription\n  text: We retain your payment data for as long as we need to process your purchase or subscription.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: In some circumstances, your Personal Data may be transferred to the U.S. pursuant to\
  \ a data processing agreement\n    incorporating legally required data protection clauses.\ndeletion:\n  route: Email privacy@axiom.co\n  text: You have the right to request that we delete the Personal Data that we have collected about you.\nrights:\n- right: Access\n  text: You have the right to request confirmation of whether or not we are processing your Personal Data and to\n    access your Personal Data.\n- right: Correction\n  text: You have the right to correct inaccuracies in your Personal Data\n- right: Portability\n  text: You have the right to request a copy of your Personal Data in a machine-readable format, to the extent technically\n    feasible.\n- right: Erasure\n  text: 'Erasure: You can request that we erase some or all of your Personal Data from our systems.'\n- right: Objection\n  text: 'Objection: You can contact us to let us know that you object to the further use or disclosure of your Personal\n    Data for certain purposes, such as for direct marketing purposes.'\n\
  sale_or_sharing:\n  stance: conditional\n  text: We will not sell your Personal Data, and have not done so over the last 12 months.\n"
source_yaml_url: https://artifacts.apis.io/axiom-controller/privacy/axiom-controller-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from Axiom Controller's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Cloud-Native
- Logging
- Monitoring
- Observability
- Telemetry
---
