---
api_specs:
- filename: on24-client-level-analytics-api-openapi.yml
  format: yaml
  label: On24 Client Level Analytics API
  slug: on24-client-level-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/on24/openapi/on24-client-level-analytics-api-openapi.yml
- filename: on24-content-listings-api-openapi.yml
  format: yaml
  label: On24 Content Listings API
  slug: on24-content-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/on24/openapi/on24-content-listings-api-openapi.yml
- filename: on24-event-level-analytics-api-openapi.yml
  format: yaml
  label: On24 Event Level Analytics API
  slug: on24-event-level-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/on24/openapi/on24-event-level-analytics-api-openapi.yml
- filename: on24-event-management-api-openapi.yml
  format: yaml
  label: On24 Event Management API
  slug: on24-event-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/on24/openapi/on24-event-management-api-openapi.yml
- filename: on24-helpers-api-openapi.yml
  format: yaml
  label: On24 Helpers API
  slug: on24-helpers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/on24/openapi/on24-helpers-api-openapi.yml
- filename: on24-rest-registration-api-openapi.yml
  format: yaml
  label: On24 REST Registration API
  slug: on24-rest-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/on24/openapi/on24-rest-registration-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identifiers: includes direct identifiers, such as name, username, account name, address, phone number, email address, online identifier, IP address, or other similar identifiers.'
  - category: contact
    text: Email address, phone number, mailing address and contact details
  - category: financial
    text: Payment and billing information
  - category: location
    text: 'Geolocation Data: includes precise location information about a particular individual or device.'
  - category: behavioral
    text: 'Usage Data: includes browsing history, clickstream data, search history, access logs and other usage data'
  - category: device
    text: device type, device ID, Internet service provider, referring/exit URLs, operating system, language
  - category: communication
    text: 'Audio and Chat Data: includes call recordings (e.g. of customer support calls) as well as information you submit in our live chatbot'
  - category: professional
    text: 'Professional Information: includes professional and employment-related information, such as current and former employer(s) and position(s) and business contact information.'
  - category: behavioral
    text: 'Inferences: includes inferences drawn from other personal or business information that we collect to create a profile reflecting an individual’s preferences, behavior or other characteristics.'
  deletion:
    route: Email request to dsr@on24.com
    text: request deletion of your information, please send your request to dsr@on24.com
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating the Site and services and providing related support
    text: Operating the Site and services and providing related support
  - purpose: Analyzing and improving the Site, services and business
    text: Analyzing and improving the Site, our services, and our business
  - purpose: Personalizing experiences
    text: Personalizing experiences
  - purpose: Advertising and marketing
    text: 'Advertising and marketing: to promote ON24’s products and services on third-party websites, as well as for direct marketing purposes'
  - purpose: Protecting legal rights and preventing misuse
    text: Protecting our legal rights and preventing misuse
  - purpose: Complying with legal obligations
    text: 'Complying with legal obligations: to comply with the law or legal proceedings.'
  retention:
  - period: three years
    scope: Contact information of clients, prospective clients and Site visitors
    text: we will retain relevant contact information of clients, prospective clients and Site visitors for three years from the date of our last interaction with you
  - period: null
    scope: Platform Data
    text: Our clients instruct us on how long to retain Platform Data, which we handle as a data processor.
  rights:
  - right: Access
    text: 'Right of access: You can ask us to: confirm whether we are processing your personal information; give you a copy of that information'
  - right: Rectification
    text: 'Right to rectify and complete personal information: You can ask us to rectify inaccurate information.'
  - right: Erasure
    text: 'Right of erasure: You can ask us to erase your personal information, but only where'
  - right: Restriction
    text: 'Right of restriction: You can ask us to restrict (i.e. keep but not use) your personal information'
  - right: Objection
    text: Right to object to our use of your personal information for direct marketing purposes
  - right: Portability
    text: Right to (data) portability
  - right: Withdraw consent
    text: 'Right to withdraw consent: You can withdraw your consent in respect of any processing of personal information which is based upon a consent which you have previously provided.'
  - right: Opt-out of sale or sharing (California)
    text: 'Do not sell or share my personal information (opt-out): California residents have the right, at any time, to direct a business that sells or shares personal information about them to third parties not to sell or share their personal information.'
  - right: Correction (California)
    text: 'Right to correct: California residents have the right, at any time, to request the correction of inaccurate personal information the company maintains about them.'
  role:
    text: ON24 is the data controller of your personal information collected pursuant to this Policy. With respect to any Platform Data, our clients are the data controllers or businesses for their respective Platform Data, and we are a data processor or service provider
    value: both
  sale_or_sharing:
    stance: conditional
    text: As defined by the CCPA, we may “sell” or “share” usage data and Identifiers to third party advertising networks, social networks, and data analytics providers.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: putting in place standard contractual clauses approved by the European Commission or the UK
  - mechanism: other
    text: We will take steps to ensure that your personal information receives an adequate level of protection in the jurisdictions in which we process it, including through appropriate written data processing terms and/or data transfer agreements.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: On24
provenance_date: '2026-11-10'
provider_name: On24
provider_slug: on24
slug: on24-privacy-policy
source_date: '2026-11-10'
source_filename: on24-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.on24.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: On24\naid: on24\nurl: https://www.on24.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: ON24 is the data controller of your personal information collected pursuant to this Policy. With respect\n    to any Platform Data, our clients are the data controllers or businesses for their respective Platform Data,\n    and we are a data processor or service provider\ndata_categories:\n- category: identifying\n  text: 'Identifiers: includes direct identifiers, such as name, username, account name, address, phone number,\n    email address, online identifier, IP address, or other similar\
  \ identifiers.'\n- category: contact\n  text: Email address, phone number, mailing address and contact details\n- category: financial\n  text: Payment and billing information\n- category: location\n  text: 'Geolocation Data: includes precise location information about a particular individual or device.'\n- category: behavioral\n  text: 'Usage Data: includes browsing history, clickstream data, search history, access logs and other usage data'\n- category: device\n  text: device type, device ID, Internet service provider, referring/exit URLs, operating system, language\n- category: communication\n  text: 'Audio and Chat Data: includes call recordings (e.g. of customer support calls) as well as information you\n    submit in our live chatbot'\n- category: professional\n  text: 'Professional Information: includes professional and employment-related information, such as current and\n    former employer(s) and position(s) and business contact information.'\n- category: behavioral\n  text: 'Inferences:\
  \ includes inferences drawn from other personal or business information that we collect to create\n    a profile reflecting an individual’s preferences, behavior or other characteristics.'\npurposes:\n- purpose: Operating the Site and services and providing related support\n  text: Operating the Site and services and providing related support\n- purpose: Analyzing and improving the Site, services and business\n  text: Analyzing and improving the Site, our services, and our business\n- purpose: Personalizing experiences\n  text: Personalizing experiences\n- purpose: Advertising and marketing\n  text: 'Advertising and marketing: to promote ON24’s products and services on third-party websites, as well as\n    for direct marketing purposes'\n- purpose: Protecting legal rights and preventing misuse\n  text: Protecting our legal rights and preventing misuse\n- purpose: Complying with legal obligations\n  text: 'Complying with legal obligations: to comply with the law or legal proceedings.'\n\
  retention:\n- scope: Contact information of clients, prospective clients and Site visitors\n  period: three years\n  text: we will retain relevant contact information of clients, prospective clients and Site visitors for three\n    years from the date of our last interaction with you\n- scope: Platform Data\n  period: null\n  text: Our clients instruct us on how long to retain Platform Data, which we handle as a data processor.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: putting in place standard contractual clauses approved by the European Commission or the UK\n- mechanism: other\n  text: We will take steps to ensure that your personal information receives an adequate level of protection in\n    the jurisdictions in which we process it, including through appropriate written data processing terms and/or\n    data transfer agreements.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email request to dsr@on24.com\n\
  \  text: request deletion of your information, please send your request to dsr@on24.com\nrights:\n- right: Access\n  text: 'Right of access: You can ask us to: confirm whether we are processing your personal information; give you\n    a copy of that information'\n- right: Rectification\n  text: 'Right to rectify and complete personal information: You can ask us to rectify inaccurate information.'\n- right: Erasure\n  text: 'Right of erasure: You can ask us to erase your personal information, but only where'\n- right: Restriction\n  text: 'Right of restriction: You can ask us to restrict (i.e. keep but not use) your personal information'\n- right: Objection\n  text: Right to object to our use of your personal information for direct marketing purposes\n- right: Portability\n  text: Right to (data) portability\n- right: Withdraw consent\n  text: 'Right to withdraw consent: You can withdraw your consent in respect of any processing of personal information\n    which is based upon a consent\
  \ which you have previously provided.'\n- right: Opt-out of sale or sharing (California)\n  text: 'Do not sell or share my personal information (opt-out): California residents have the right, at any time,\n    to direct a business that sells or shares personal information about them to third parties not to sell or share\n    their personal information.'\n- right: Correction (California)\n  text: 'Right to correct: California residents have the right, at any time, to request the correction of inaccurate\n    personal information the company maintains about them.'\nsale_or_sharing:\n  stance: conditional\n  text: As defined by the CCPA, we may “sell” or “share” usage data and Identifiers to third party advertising networks,\n    social networks, and data analytics providers.\n"
source_yaml_url: https://artifacts.apis.io/on24/privacy/on24-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 31 quoted statements, read from On24's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Webinars
- Virtual Events
- Digital Engagement
- Marketing
- Analytics
- Event Management
- MarTech
---
