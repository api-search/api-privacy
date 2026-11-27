---
api_specs:
- filename: bidmachine-io-authentication-api-openapi.yml
  format: yaml
  label: BidMachine Authentication API
  slug: bidmachine-io-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidmachine-io/openapi/bidmachine-io-authentication-api-openapi.yml
- filename: bidmachine-io-placements-api-openapi.yml
  format: yaml
  label: BidMachine Placements API
  slug: bidmachine-io-placements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidmachine-io/openapi/bidmachine-io-placements-api-openapi.yml
- filename: bidmachine-io-reporting-api-openapi.yml
  format: yaml
  label: BidMachine Reporting API
  slug: bidmachine-io-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bidmachine-io/openapi/bidmachine-io-reporting-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, address, telephone number, email address, and billing information such as your credit card number
  - category: device
    text: your Internet protocol (IP) address, cookie identifiers, mobile advertising identifiers, and other device identifiers
  - category: location
    text: location data
  - category: behavioral
    text: pages that you visit before and after using the Website or our Services, the date and time of your visit
  - category: health
    text: details of health and disability, including mental health, medical leave, and maternity leave
  - category: identifying
    source: https://www.bidmachine.com/dpa
    text: 'Online Identifiers: Location (Country level only), IP address, Advertisement ID'
  - category: contact
    source: https://www.bidmachine.com/dpa
    text: 'For the Website : email address IP address'
  - category: demographic
    source: https://www.bidmachine.com/dpa
    text: 'User data: gender, language, age, relationship status, interests, device data, application data'
  deletion:
    route: email legal@BidMachine.com
    text: ask that we correct, amend or delete your Personal Information where it is inaccurate
  dpa:
    available: true
    source: https://www.bidmachine.com/dpa
    text: Privacy and data protection addendum
    url: https://www.bidmachine.com/dpa
  purposes:
  - purpose: provide requested services or information
    text: BidMachine may use information about you to fulfill requests for Services or information
  - purpose: marketing
    text: BidMachine may use Personal Information to provide you with materials about offers, products, and Services that may be of interest
  - purpose: research and development
    text: BidMachine may use Personal Information to create non-identifiable information that we may use alone or in the aggregate
  - purpose: interest-based advertising
    text: We may also share such de-identified information as well as selected Personal Information (such as demographic information and past purchase history) we have collected with Third-Party advertising partners.
  - purpose: Provide the Service
    source: https://www.bidmachine.com/dpa
    text: 'to provide the Service to assess the performance of the ServiceFor the Website: Account Registration Communications with Service Provider'
  - purpose: Account registration and communications
    source: https://www.bidmachine.com/dpa
    text: 'For the Website: Account Registration Communications with Service Provider'
  residency:
  - region: United States
    text: All Personal Information collected via or by BidMachine may be stored anywhere in the world, including but not limited to, in the United States
  retention:
  - period: null
    scope: general
    text: BidMachine retains the Personal Information we receive as described in this Policy for as long as you use our Services or as necessary to fulfill the purpose(s) for which it was collected
  - period: null
    scope: Shared Personal Data from bids
    source: https://www.bidmachine.com/dpa
    text: 'the Company must promptly delete the Shared Personal Data under the following circumstances: (i) when the Company does not win the bid for an impression associated with that Shared Personal Data'
  - period: null
    scope: Data importer storage
    source: https://www.bidmachine.com/dpa
    text: The data importer will access, reproduce, display and store the relevant personal data in order to provide the services as set out in the Agreement and for no other purposes whatsoever.
  rights:
  - right: access
    text: You may inquire as to whether BidMachine is Processing Personal Information about you, request access to Personal Information
  - right: rectification
    text: ask that we correct, amend or delete your Personal Information where it is inaccurate
  - right: erasure
    text: request erasure of Personal Information held about you by BidMachine
  - right: restriction
    text: restrict Processing
  - right: portability
    text: request access to, receive (port), restrict Processing
  - right: opt-out of marketing
    text: You may contact us at any time to opt-out of the use of your Personal Information for marketing purposes
  - right: Data Subject Rights
    source: https://www.bidmachine.com/dpa
    text: Each Party must establish and uphold the necessary mechanisms to comply with Data Subject Rights as outlined by Data Protection Laws
  role:
    source: https://www.bidmachine.com/dpa
    text: Each Controller will individually determine the purposes and means of its Processing of the Shared Personal Data
    value: controller
  sale_or_sharing:
    source: https://www.bidmachine.com/dpa
    stance: prohibited
    text: Company is prohibited from disclosing Shared Personal Data to any third parties unless expressly permitted under the Agreement.
  subprocessors:
    text: 'The complete Third-Party service provider list can be found here: bidmachine.io/partners-privacy-policies/'
    url: bidmachine.io/partners-privacy-policies/
  transfers:
  - mechanism: SCC
    source: https://www.bidmachine.com/dpa
    text: The Parties agree to use the EU SCC as the adequacy mechanism supporting the Data Transfer and Processing of the Shared Personal Data
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BidMachine
provenance_date: '2026-11-09'
provider_name: BidMachine
provider_slug: bidmachine-io
slug: bidmachine-io-privacy-policy
source_date: '2026-11-09'
source_filename: bidmachine-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bidmachine.com/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BidMachine\naid: bidmachine-io\nurl: https://www.bidmachine.com/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.bidmachine.com/dpa\n  - https://www.bidmachine.com/privacy-policy\nrole:\n  value: controller\n  text: Each Controller will individually determine the purposes and means of its Processing of the Shared Personal\n    Data\n  source: https://www.bidmachine.com/dpa\ndata_categories:\n- category: identifying\n  text: your name, address, telephone number, email address, and billing information such as your credit card number\n- category: device\n  text: your Internet protocol (IP)\
  \ address, cookie identifiers, mobile advertising identifiers, and other device\n    identifiers\n- category: location\n  text: location data\n- category: behavioral\n  text: pages that you visit before and after using the Website or our Services, the date and time of your visit\n- category: health\n  text: details of health and disability, including mental health, medical leave, and maternity leave\n- category: identifying\n  text: 'Online Identifiers: Location (Country level only), IP address, Advertisement ID'\n  source: https://www.bidmachine.com/dpa\n- category: contact\n  text: 'For the Website : email address IP address'\n  source: https://www.bidmachine.com/dpa\n- category: demographic\n  text: 'User data: gender, language, age, relationship status, interests, device data, application data'\n  source: https://www.bidmachine.com/dpa\npurposes:\n- purpose: provide requested services or information\n  text: BidMachine may use information about you to fulfill requests for Services\
  \ or information\n- purpose: marketing\n  text: BidMachine may use Personal Information to provide you with materials about offers, products, and Services\n    that may be of interest\n- purpose: research and development\n  text: BidMachine may use Personal Information to create non-identifiable information that we may use alone or\n    in the aggregate\n- purpose: interest-based advertising\n  text: We may also share such de-identified information as well as selected Personal Information (such as demographic\n    information and past purchase history) we have collected with Third-Party advertising partners.\n- purpose: Provide the Service\n  text: 'to provide the Service to assess the performance of the ServiceFor the Website: Account Registration Communications\n    with Service Provider'\n  source: https://www.bidmachine.com/dpa\n- purpose: Account registration and communications\n  text: 'For the Website: Account Registration Communications with Service Provider'\n  source: https://www.bidmachine.com/dpa\n\
  retention:\n- scope: general\n  period: null\n  text: BidMachine retains the Personal Information we receive as described in this Policy for as long as you use\n    our Services or as necessary to fulfill the purpose(s) for which it was collected\n- scope: Shared Personal Data from bids\n  period: null\n  text: 'the Company must promptly delete the Shared Personal Data under the following circumstances: (i) when the\n    Company does not win the bid for an impression associated with that Shared Personal Data'\n  source: https://www.bidmachine.com/dpa\n- scope: Data importer storage\n  period: null\n  text: The data importer will access, reproduce, display and store the relevant personal data in order to provide\n    the services as set out in the Agreement and for no other purposes whatsoever.\n  source: https://www.bidmachine.com/dpa\nresidency:\n- region: United States\n  text: All Personal Information collected via or by BidMachine may be stored anywhere in the world, including but\n\
  \    not limited to, in the United States\ntransfers:\n- mechanism: SCC\n  text: The Parties agree to use the EU SCC as the adequacy mechanism supporting the Data Transfer and Processing\n    of the Shared Personal Data\n  source: https://www.bidmachine.com/dpa\nsubprocessors:\n  url: bidmachine.io/partners-privacy-policies/\n  text: 'The complete Third-Party service provider list can be found here: bidmachine.io/partners-privacy-policies/'\ndpa:\n  available: true\n  url: https://www.bidmachine.com/dpa\n  text: Privacy and data protection addendum\n  source: https://www.bidmachine.com/dpa\ndeletion:\n  route: email legal@BidMachine.com\n  text: ask that we correct, amend or delete your Personal Information where it is inaccurate\nrights:\n- right: access\n  text: You may inquire as to whether BidMachine is Processing Personal Information about you, request access to\n    Personal Information\n- right: rectification\n  text: ask that we correct, amend or delete your Personal Information\
  \ where it is inaccurate\n- right: erasure\n  text: request erasure of Personal Information held about you by BidMachine\n- right: restriction\n  text: restrict Processing\n- right: portability\n  text: request access to, receive (port), restrict Processing\n- right: opt-out of marketing\n  text: You may contact us at any time to opt-out of the use of your Personal Information for marketing purposes\n- right: Data Subject Rights\n  text: Each Party must establish and uphold the necessary mechanisms to comply with Data Subject Rights as outlined\n    by Data Protection Laws\n  source: https://www.bidmachine.com/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: Company is prohibited from disclosing Shared Personal Data to any third parties unless expressly permitted\n    under the Agreement.\n  source: https://www.bidmachine.com/dpa\n"
source_yaml_url: https://artifacts.apis.io/bidmachine-io/privacy/bidmachine-io-privacy-policy.yml
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
summary_line: 31 quoted statements, read from BidMachine's own page on 2026-11-09.
synthetic: false
tags:
- Advertising
- AdTech
- Mobile Advertising
- Ad Exchange
- Ad Mediation
- In-App Bidding
- OpenRTB
- App Monetization
- Programmatic Advertising
- Mobile SDK
- Reporting
- Company
---
