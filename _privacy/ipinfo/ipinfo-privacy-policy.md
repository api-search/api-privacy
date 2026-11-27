---
api_specs:
- filename: ipinfo-abuse-api-openapi.yml
  format: yaml
  label: IPinfo Abuse API
  slug: ipinfo-abuse-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-abuse-api-openapi.yml
- filename: ipinfo-asn-api-openapi.yml
  format: yaml
  label: IPinfo Asn API
  slug: ipinfo-asn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-asn-api-openapi.yml
- filename: ipinfo-carrier-api-openapi.yml
  format: yaml
  label: IPinfo Carrier API
  slug: ipinfo-carrier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-carrier-api-openapi.yml
- filename: ipinfo-company-api-openapi.yml
  format: yaml
  label: IPinfo Company API
  slug: ipinfo-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-company-api-openapi.yml
- filename: ipinfo-domains-api-openapi.yml
  format: yaml
  label: IPinfo Domains API
  slug: ipinfo-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-domains-api-openapi.yml
- filename: ipinfo-general-api-openapi.yml
  format: yaml
  label: IPinfo General API
  slug: ipinfo-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-general-api-openapi.yml
- filename: ipinfo-ipinfo-core-api-openapi.yml
  format: yaml
  label: IPinfo Core API
  slug: ipinfo-ipinfo-core-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-core-api-openapi.yml
- filename: ipinfo-ipinfo-lite-api-openapi.yml
  format: yaml
  label: IPinfo Lite API
  slug: ipinfo-ipinfo-lite-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-lite-api-openapi.yml
- filename: ipinfo-ipinfo-max-api-openapi.yml
  format: yaml
  label: IPinfo Max API
  slug: ipinfo-ipinfo-max-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-max-api-openapi.yml
- filename: ipinfo-ipinfo-plus-api-openapi.yml
  format: yaml
  label: IPinfo Plus API
  slug: ipinfo-ipinfo-plus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ipinfo-plus-api-openapi.yml
- filename: ipinfo-places-api-openapi.yml
  format: yaml
  label: IPinfo Places API
  slug: ipinfo-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-places-api-openapi.yml
- filename: ipinfo-privacy-detection-api-openapi.yml
  format: yaml
  label: IPinfo privacy detection API
  slug: ipinfo-privacy-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-privacy-detection-api-openapi.yml
- filename: ipinfo-privacy-detection-extended-api-openapi.yml
  format: yaml
  label: IPinfo privacy detection extended API
  slug: ipinfo-privacy-detection-extended-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-privacy-detection-extended-api-openapi.yml
- filename: ipinfo-ranges-api-openapi.yml
  format: yaml
  label: IPinfo Ranges API
  slug: ipinfo-ranges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-ranges-api-openapi.yml
- filename: ipinfo-residential-proxy-detection-api-openapi.yml
  format: yaml
  label: IPinfo residential proxy detection API
  slug: ipinfo-residential-proxy-detection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-residential-proxy-detection-api-openapi.yml
- filename: ipinfo-single-api-openapi.yml
  format: yaml
  label: IPinfo Single API
  slug: ipinfo-single-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-single-api-openapi.yml
- filename: ipinfo-whois-api-openapi.yml
  format: yaml
  label: IPinfo Whois API
  slug: ipinfo-whois-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ipinfo/openapi/ipinfo-whois-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: such as name, postal address, e-mail address and telephone number
  - category: location
    text: precise GPS-derived geolocation coordinates (where you have provided consent to the hosting application)
  - category: device
    text: IP addresses, a pseudonymous device identifier, Wi-Fi network information
  - category: financial
    text: billing name and address, and credit card number
  - category: behavioral
    text: Analytical information , including details about your interaction with our website and electronic newsletters.
  deletion:
    route: Request removal from databases or contact support@ipinfo.io
    text: if you request that your Information be removed from our databases, it may not be possible to completely delete all of your Information due to technological and legal constraints.
  dpa:
    available: true
    text: Data Processing Agreement
    url: null
  purposes:
  - purpose: Provide requested services
    text: To provide you with the Services that you request from us.
  - purpose: Customer support
    text: To provide customer support.
  - purpose: Marketing
    text: To communicate with you regarding our Services, including for marketing purposes.
  - purpose: Data products and network analysis
    text: We use the precise geolocation coordinates, Wi-Fi network information and network quality metrics collected via our SDK to analyze network performance, map IP connectivity parameters, identify the networks used at public venues, and improve our regional data licensing services.
  - purpose: Fraud prevention and security
    text: where we have a legitimate interest in providing accurate IP address, network and venue data, including for fraud prevention and network security
  residency:
  - region: United States
    text: These Services are hosted in the United States and are intended primarily for visitors located within the United States.
  retention:
  - period: null
    scope: Raw device observations
    text: We keep raw device observations only for as long as needed to build and maintain our data products, after which they are aggregated or deleted.
  - period: null
    scope: Personal Information generally
    text: We will keep your Information for as long as it remains necessary for the identified purpose or as required by law, which may extend beyond the termination of our relationship with you.
  rights:
  - right: access
    text: ask whether we hold Personal Information about you and request copies of such Personal Information
  - right: rectification
    text: request that inaccurate Personal Information is corrected
  - right: erasure
    text: request deletion of Personal Information that is no longer necessary for the purposes underlying the processing
  - right: restriction
    text: request us to restrict the processing of Personal Information under certain circumstances
  - right: objection
    text: object to the processing of Personal Information
  - right: portability
    text: request portability of Personal Information that you have provided to us
  - right: withdraw consent
    text: you may withdraw your consent at any time, and we will stop any further processing of your data for that purpose
  - right: complaint
    text: lodge a complaint with the appropriate data protection authorities
  role:
    text: IPinfo is the Controller of your Personal Information.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The following is a list of our Data Processors who collect the Information described above.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: IPinfo
provenance_date: '2026-11-09'
provider_name: IPinfo
provider_slug: ipinfo
slug: ipinfo-privacy-policy
source_date: '2026-11-09'
source_filename: ipinfo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ipinfo.io/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: IPinfo\naid: ipinfo\nurl: https://ipinfo.io/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: IPinfo is the Controller of your Personal Information.\ndata_categories:\n- category: identifying\n  text: such as name, postal address, e-mail address and telephone number\n- category: location\n  text: precise GPS-derived geolocation coordinates (where you have provided consent to the hosting application)\n- category: device\n  text: IP addresses, a pseudonymous device identifier, Wi-Fi network information\n- category: financial\n  text: billing name and address, and credit card number\n\
  - category: behavioral\n  text: Analytical information , including details about your interaction with our website and electronic newsletters.\npurposes:\n- purpose: Provide requested services\n  text: To provide you with the Services that you request from us.\n- purpose: Customer support\n  text: To provide customer support.\n- purpose: Marketing\n  text: To communicate with you regarding our Services, including for marketing purposes.\n- purpose: Data products and network analysis\n  text: We use the precise geolocation coordinates, Wi-Fi network information and network quality metrics collected\n    via our SDK to analyze network performance, map IP connectivity parameters, identify the networks used at public\n    venues, and improve our regional data licensing services.\n- purpose: Fraud prevention and security\n  text: where we have a legitimate interest in providing accurate IP address, network and venue data, including\n    for fraud prevention and network security\nretention:\n\
  - scope: Raw device observations\n  period: null\n  text: We keep raw device observations only for as long as needed to build and maintain our data products, after\n    which they are aggregated or deleted.\n- scope: Personal Information generally\n  period: null\n  text: We will keep your Information for as long as it remains necessary for the identified purpose or as required\n    by law, which may extend beyond the termination of our relationship with you.\nresidency:\n- region: United States\n  text: These Services are hosted in the United States and are intended primarily for visitors located within the\n    United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: The following is a list of our Data Processors who collect the Information described above.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreement\ndeletion:\n  route: Request removal from databases or contact support@ipinfo.io\n  text: if you request that your Information be removed from our\
  \ databases, it may not be possible to completely\n    delete all of your Information due to technological and legal constraints.\nrights:\n- right: access\n  text: ask whether we hold Personal Information about you and request copies of such Personal Information\n- right: rectification\n  text: request that inaccurate Personal Information is corrected\n- right: erasure\n  text: request deletion of Personal Information that is no longer necessary for the purposes underlying the processing\n- right: restriction\n  text: request us to restrict the processing of Personal Information under certain circumstances\n- right: objection\n  text: object to the processing of Personal Information\n- right: portability\n  text: request portability of Personal Information that you have provided to us\n- right: withdraw consent\n  text: you may withdraw your consent at any time, and we will stop any further processing of your data for that\n    purpose\n- right: complaint\n  text: lodge a complaint with\
  \ the appropriate data protection authorities\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ipinfo/privacy/ipinfo-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- dpa
- deletion
- rights
summary_line: 25 quoted statements, read from IPinfo's own page on 2026-11-09.
synthetic: false
tags:
- IP Intelligence
- IP Geolocation
- ASN
- Privacy Detection
- VPN Detection
- Threat Intelligence
- Network Data
- Mobile Carrier
- WHOIS
- Public APIs
- Development
---
