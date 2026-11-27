---
api_specs:
- filename: woox-account-api-openapi.yml
  format: yaml
  label: WOO X Account API
  slug: woox-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-account-api-openapi.yml
- filename: woox-asset-api-openapi.yml
  format: yaml
  label: WOO X Asset API
  slug: woox-asset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-asset-api-openapi.yml
- filename: woox-futures-api-openapi.yml
  format: yaml
  label: WOO X Futures API
  slug: woox-futures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-futures-api-openapi.yml
- filename: woox-isolatedmargin-api-openapi.yml
  format: yaml
  label: WOO X Isolated Margin API
  slug: woox-isolatedmargin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-isolatedmargin-api-openapi.yml
- filename: woox-public-api-openapi.yml
  format: yaml
  label: WOO X Public API
  slug: woox-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-public-api-openapi.yml
- filename: woox-spotmargin-api-openapi.yml
  format: yaml
  label: WOO X Spot Margin API
  slug: woox-spotmargin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-spotmargin-api-openapi.yml
- filename: woox-trade-api-openapi.yml
  format: yaml
  label: WOO X Trade API
  slug: woox-trade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/woox/openapi/woox-trade-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers such as name, display name, nationality, username, date and place of birth, ID number, occupation, residential address
  - category: contact
    text: email address, telephone number, country or residency
  - category: financial
    text: Information about your cryptocurrency wallet, transaction history, trading data, and associated fees paid
  - category: location
    text: Your device location and other data (including the time of your visit in our Services) or other geolocation information.
  - category: device
    text: Information about the devices you use to access the Services
  - category: behavioral
    text: Your browsing history, including the areas within our Services that you visit and your activities there
  deletion:
    route: Request via email to support@woo.network
    text: You may exercise their rights of access, rectification, cancellation, or opposition concerning their personal data, as well as request the revocation of their consent, by sending a request to us via email at support@woo.network
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Decide whether to provide services
    text: Decide if we will provide you with our Services.
  - purpose: Direct marketing
    text: Direct marketing via emails and pop-up messages if you decide to subscribe. Our legal basis is your consent.
  - purpose: Providing exchange services
    text: Providing services of our centralised exchange (WOO X). Our legal base is a contractual necessity as we need your personal data to provide our services to you.
  - purpose: AML program
    text: Running our AML program. We do it on the grounds of legitimate interest.
  - purpose: Security
    text: Ensuring the security of WOO, mainly by performing automated and manual security checks; doing backups of data etc.
  residency:
  - region: Outside Panama
    text: We may transfer, store, and process your personal information in countries other than Panama.
  retention:
  - period: up to 1 year
    scope: Direct marketing data
    text: 'Direct Marketing data: retained for up to 1 year after your last interaction, unless you withdraw consent earlier.'
  - period: 5 years
    scope: AML/KYC data
    text: 'AML/KYC data: 5 years for AML data since you end your relationship with us.'
  - period: 5 years
    scope: Other account-related data
    text: 'Other account-related data: 5 years for other data, from the moment you closed your account on WOO X'
  rights:
  - right: withdraw consent
    text: withdraw consent - whenever we ask for your consent to process your personal data, you may opt out.
  - right: access
    text: access your personal data and receive a copy of it
  - right: rectification
    text: rectify (amend) your personal data
  - right: restriction
    text: have the processing of your personal data restricted
  - right: erasure
    text: erasure of your personal data
  - right: objection
    text: object to the processing of your personal data (for processing based on legitimate interest)
  - right: portability
    text: data portability - you may demand from us to provide you with a copy of your personal data in a machine-readable format
  - right: complaint
    text: to lodge a complaint to the supervisory authority (privacy regulator)
  role:
    text: WOOTECH Limited Corp is a controller of your personal data and uses it as you use WOO X or otherwise interact with WOO.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell, rent, or lease your personal information to third parties for their marketing purposes without your explicit consent.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: Taiwan - there is no adequacy decision for this country, hence we utilize Standard Contractual Clauses as a safeguard.
  - mechanism: adequacy
    text: Japan - for this country European Commission issued adequacy decision.
  - mechanism: DPF
    text: The United States - for this country European Commission issued adequacy decision we use processors which are listed in EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: WOO X
provenance_date: '2026-11-10'
provider_name: WOO X
provider_slug: woox
slug: woox-privacy-policy
source_date: '2026-11-10'
source_filename: woox-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://support.woox.io/hc/en-us/articles/4404573651097--Privacy-Policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: WOO X\naid: woox\nurl: https://support.woox.io/hc/en-us/articles/4404573651097--Privacy-Policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: WOOTECH Limited Corp is a controller of your personal data and uses it as you use WOO X or otherwise interact\n    with WOO.\ndata_categories:\n- category: identifying\n  text: Identifiers such as name, display name, nationality, username, date and place of birth, ID number, occupation,\n    residential address\n- category: contact\n  text: email address, telephone number, country or residency\n- category: financial\n  text: Information about your cryptocurrency\
  \ wallet, transaction history, trading data, and associated fees paid\n- category: location\n  text: Your device location and other data (including the time of your visit in our Services) or other geolocation\n    information.\n- category: device\n  text: Information about the devices you use to access the Services\n- category: behavioral\n  text: Your browsing history, including the areas within our Services that you visit and your activities there\npurposes:\n- purpose: Decide whether to provide services\n  text: Decide if we will provide you with our Services.\n- purpose: Direct marketing\n  text: Direct marketing via emails and pop-up messages if you decide to subscribe. Our legal basis is your consent.\n- purpose: Providing exchange services\n  text: Providing services of our centralised exchange (WOO X). Our legal base is a contractual necessity as we\n    need your personal data to provide our services to you.\n- purpose: AML program\n  text: Running our AML program. We do it on\
  \ the grounds of legitimate interest.\n- purpose: Security\n  text: Ensuring the security of WOO, mainly by performing automated and manual security checks; doing backups of\n    data etc.\nretention:\n- scope: Direct marketing data\n  period: up to 1 year\n  text: 'Direct Marketing data: retained for up to 1 year after your last interaction, unless you withdraw consent\n    earlier.'\n- scope: AML/KYC data\n  period: 5 years\n  text: 'AML/KYC data: 5 years for AML data since you end your relationship with us.'\n- scope: Other account-related data\n  period: 5 years\n  text: 'Other account-related data: 5 years for other data, from the moment you closed your account on WOO X'\nresidency:\n- region: Outside Panama\n  text: We may transfer, store, and process your personal information in countries other than Panama.\ntransfers:\n- mechanism: SCC\n  text: Taiwan - there is no adequacy decision for this country, hence we utilize Standard Contractual Clauses as\n    a safeguard.\n- mechanism:\
  \ adequacy\n  text: Japan - for this country European Commission issued adequacy decision.\n- mechanism: DPF\n  text: The United States - for this country European Commission issued adequacy decision we use processors which\n    are listed in EU-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via email to support@woo.network\n  text: You may exercise their rights of access, rectification, cancellation, or opposition concerning their personal\n    data, as well as request the revocation of their consent, by sending a request to us via email at support@woo.network\nrights:\n- right: withdraw consent\n  text: withdraw consent - whenever we ask for your consent to process your personal data, you may opt out.\n- right: access\n  text: access your personal data and receive a copy of it\n- right: rectification\n  text: rectify (amend) your personal data\n- right: restriction\n  text: have the\
  \ processing of your personal data restricted\n- right: erasure\n  text: erasure of your personal data\n- right: objection\n  text: object to the processing of your personal data (for processing based on legitimate interest)\n- right: portability\n  text: data portability - you may demand from us to provide you with a copy of your personal data in a machine-readable\n    format\n- right: complaint\n  text: to lodge a complaint to the supervisory authority (privacy regulator)\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell, rent, or lease your personal information to third parties for their marketing purposes without\n    your explicit consent.\n"
source_yaml_url: https://artifacts.apis.io/woox/privacy/woox-privacy-policy.yml
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
summary_line: 29 quoted statements, read from WOO X's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Derivatives
---
