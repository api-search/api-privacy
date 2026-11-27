---
api_specs:
- filename: beyond-pricing-accounts-api-openapi.yml
  format: yaml
  label: Beyond Pricing Accounts API
  slug: beyond-pricing-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-accounts-api-openapi.yml
- filename: beyond-pricing-compsets-api-openapi.yml
  format: yaml
  label: Beyond Pricing Compsets API
  slug: beyond-pricing-compsets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-compsets-api-openapi.yml
- filename: beyond-pricing-customizations-api-openapi.yml
  format: yaml
  label: Beyond Pricing Customizations API
  slug: beyond-pricing-customizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-customizations-api-openapi.yml
- filename: beyond-pricing-insights-api-openapi.yml
  format: yaml
  label: Beyond Pricing Insights API
  slug: beyond-pricing-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-insights-api-openapi.yml
- filename: beyond-pricing-listings-api-openapi.yml
  format: yaml
  label: Beyond Pricing Listings API
  slug: beyond-pricing-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-listings-api-openapi.yml
- filename: beyond-pricing-users-api-openapi.yml
  format: yaml
  label: Beyond Pricing Users API
  slug: beyond-pricing-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-users-api-openapi.yml
- filename: beyond-pricing-webhooks-api-openapi.yml
  format: yaml
  label: Beyond Pricing Webhooks API
  slug: beyond-pricing-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-webhooks-api-openapi.yml
- filename: beyond-pricing-oauth2-api-openapi.yml
  format: yaml
  label: Beyond Pricing O Auth2 API
  slug: beyond-pricing-oauth2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-oauth2-api-openapi.yml
- filename: beyond-pricing-reservations-api-openapi.yml
  format: yaml
  label: Beyond Pricing Reservations API
  slug: beyond-pricing-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beyond-pricing/openapi/beyond-pricing-reservations-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: create an account, including email and password, billing address, and payment information (for example, credit card information or ACH bank transfer)
  - category: device
    text: we may automatically collect your IP address or other unique identifier (“Device Identifier”) for any computer, mobile phone, or other device you may use to access the Platform
  - category: location
    text: We may directly collect specific location information from your device if you have opted-in to such collection through one of our applications.
  - category: behavioral
    text: Session Replay Technology. We may record your interactions with the user interfaces, including, what pages you visit on thePlatform and how long you visit those pages, the links you click
  - category: communication
    text: Chat Boxes. When you participate in live chat sessions on the Platform, Beyond can record and use your communications
  deletion:
    route: email legal@beyondpricing.com and request deletion
    text: If you wish to cancel your account or request that we no longer use your information to provide you services, email legal@beyondpricing.com and request deletion.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account and transaction management
    text: enable you to access and use the Platform, the User Services, or other services we offer, including maintaining your account information, managing transactions
  - purpose: advertising and targeting
    text: tailor and target content, advertisements and offers we display to you or others on thePlatform or elsewhere online
  - purpose: internal business and product improvement
    text: for internal business purposes, such as improving the Platform, and to comply with legal requirements
  residency:
  - region: United States
    text: Personal data we collect may be transferred to, and stored and processed in, the UnitedStates or any other country in which we or our subcontractors maintain facilities.
  retention:
  - period: null
    scope: account information
    text: Except as noted differently on the Platform, we retain your information while you have an account with us, or while you are using the Platform.
  rights:
  - right: access
    text: 'Access: You have the right to request access to personal data we collected about you and information about its sources, purposes, and sharing.'
  - right: correction
    text: 'Correction: You have the right to request that we correct the personal data we hold about you if it is inaccurate or incomplete.'
  - right: erasure
    text: 'Erasure : You have the right to request that we erase data we have collected from you.'
  - right: portability
    text: 'Portability : You have the right, in certain circumstances, to request that we provide your personal data to you in a format that can be transferred to another entity.'
  - right: object
    text: 'Object: You have the right to object to our processing if we are processing your personal data based on legitimate interests'
  - right: withdraw consent
    text: 'Withdraw consent: If we have collected personal data with your consent, you have the right to withdraw that consent at anytime.'
  role:
    text: we may receive or collect certain data as a service provider/processor on behalf of Beyond Users, but that data is controlled by the BeyondUser with whom consumers interact
    value: both
  sale_or_sharing:
    stance: conditional
    text: We do not share your personal information with third parties for those third parties’ own direct marketing purposes unless you consent (opt-in or opt-out) to such sharing.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers of personal data to a third country without an adequacy decision (as that term is understood pursuant to Article 45 of GDPR) are required to be subject to appropriate safeguards such as standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Beyond Pricing
provenance_date: '2026-11-09'
provider_name: Beyond Pricing
provider_slug: beyond-pricing
slug: beyond-pricing-privacy-policy
source_date: '2026-11-09'
source_filename: beyond-pricing-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://beyondpricing.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Beyond Pricing\naid: beyond-pricing\nurl: https://beyondpricing.com/legal/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: we may receive or collect certain data as a service provider/processor on behalf of Beyond Users, but that\n    data is controlled by the BeyondUser with whom consumers interact\ndata_categories:\n- category: identifying\n  text: create an account, including email and password, billing address, and payment information (for example,\n    credit card information or ACH bank transfer)\n- category: device\n  text: we may automatically collect your IP address or other unique\
  \ identifier (“Device Identifier”) for any computer,\n    mobile phone, or other device you may use to access the Platform\n- category: location\n  text: We may directly collect specific location information from your device if you have opted-in to such collection\n    through one of our applications.\n- category: behavioral\n  text: Session Replay Technology. We may record your interactions with the user interfaces, including, what pages\n    you visit on thePlatform and how long you visit those pages, the links you click\n- category: communication\n  text: Chat Boxes. When you participate in live chat sessions on the Platform, Beyond can record and use your communications\npurposes:\n- purpose: account and transaction management\n  text: enable you to access and use the Platform, the User Services, or other services we offer, including maintaining\n    your account information, managing transactions\n- purpose: advertising and targeting\n  text: tailor and target content, advertisements\
  \ and offers we display to you or others on thePlatform or elsewhere\n    online\n- purpose: internal business and product improvement\n  text: for internal business purposes, such as improving the Platform, and to comply with legal requirements\nretention:\n- scope: account information\n  period: null\n  text: Except as noted differently on the Platform, we retain your information while you have an account with us,\n    or while you are using the Platform.\nresidency:\n- region: United States\n  text: Personal data we collect may be transferred to, and stored and processed in, the UnitedStates or any other\n    country in which we or our subcontractors maintain facilities.\ntransfers:\n- mechanism: SCC\n  text: Transfers of personal data to a third country without an adequacy decision (as that term is understood pursuant\n    to Article 45 of GDPR) are required to be subject to appropriate safeguards such as standard contractual clauses.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n\
  \  available: null\n  url: null\n  text: null\ndeletion:\n  route: email legal@beyondpricing.com and request deletion\n  text: If you wish to cancel your account or request that we no longer use your information to provide you services,\n    email legal@beyondpricing.com and request deletion.\nrights:\n- right: access\n  text: 'Access: You have the right to request access to personal data we collected about you and information about\n    its sources, purposes, and sharing.'\n- right: correction\n  text: 'Correction: You have the right to request that we correct the personal data we hold about you if it is\n    inaccurate or incomplete.'\n- right: erasure\n  text: 'Erasure : You have the right to request that we erase data we have collected from you.'\n- right: portability\n  text: 'Portability : You have the right, in certain circumstances, to request that we provide your personal data\n    to you in a format that can be transferred to another entity.'\n- right: object\n  text: 'Object:\
  \ You have the right to object to our processing if we are processing your personal data based on\n    legitimate interests'\n- right: withdraw consent\n  text: 'Withdraw consent: If we have collected personal data with your consent, you have the right to withdraw\n    that consent at anytime.'\nsale_or_sharing:\n  stance: conditional\n  text: We do not share your personal information with third parties for those third parties’ own direct marketing\n    purposes unless you consent (opt-in or opt-out) to such sharing.\n"
source_yaml_url: https://artifacts.apis.io/beyond-pricing/privacy/beyond-pricing-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from Beyond Pricing's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Short-Term Rental
- Vacation Rentals
- Revenue Management
- Dynamic Pricing
- Hospitality
- Property Management
- Travel
- Pricing
- JSON:API
---
