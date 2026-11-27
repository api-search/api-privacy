---
api_specs:
- filename: vanderbilt-broadcasts-api-openapi.yml
  format: yaml
  label: Vanderbilt University Broadcasts API
  slug: vanderbilt-broadcasts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vanderbilt/openapi/vanderbilt-broadcasts-api-openapi.yml
- filename: vanderbilt-metadata-api-openapi.yml
  format: yaml
  label: Vanderbilt University Metadata API
  slug: vanderbilt-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vanderbilt/openapi/vanderbilt-metadata-api-openapi.yml
- filename: vanderbilt-search-api-openapi.yml
  format: yaml
  label: Vanderbilt University Search API
  slug: vanderbilt-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vanderbilt/openapi/vanderbilt-search-api-openapi.yml
- filename: vanderbilt-service-api-openapi.yml
  format: yaml
  label: Vanderbilt University Service API
  slug: vanderbilt-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vanderbilt/openapi/vanderbilt-service-api-openapi.yml
- filename: vanderbilt-sparql-api-openapi.yml
  format: yaml
  label: Vanderbilt University SPARQL API
  slug: vanderbilt-sparql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vanderbilt/openapi/vanderbilt-sparql-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Student applicants: personal and family information related to the application and financial aid process, including supporting documentation, identification and contact information'
  - category: contact
    text: 'Faculty and staff: contact information, biographic information, security video footage, information related to remuneration, to benefits, to family members, or to performance at work.'
  - category: health
    text: 'Students: information submitted as prospective students, information related to their academic record or academic performance, information about their activities on campus, disciplinary records, health records, biometric identifiers, security camera footage.'
  - category: biometric
    text: biometric identifiers, security camera footage
  - category: device
    text: 'Website visitors: the internet domain from which a visitor accesses the website, the IP address assigned to the visitor’s computer, the type of browser the visitor is using, the date and time of visit.'
  - category: location
    text: 'Network users: geolocation, device information'
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: admission and higher education services
    text: To facilitate admission and provide higher education services for our current, former, and prospective students.
  - purpose: employment management
    text: To manage the employment of our faculty members and staff.
  - purpose: website performance
    text: To support website performance and enhance user experience .
  - purpose: security and property protection
    text: To ensure our Community Members’ and visitors’ security and to protect our property.
  retention:
  - period: null
    scope: personal information generally
    text: VU strives to keep personal information in our records only as long as is necessary for the purposes they were collected and processed.
  rights:
  - right: access
    text: the right to access personal information, rectify incorrect personal information, erase personal information, restrict or object to processing, and the right to data portability
  - right: withdraw consent
    text: the right to withdraw consent at any time, if processing is based on consent
  - right: lodge complaint
    text: the right to lodge a complaint with a supervisory authority (established in the EU)
  role:
    text: In the context of data transfers, VU may be a data “controller” or “processor” with regard to certain activities as defined under the GDPR
    value: both
  sale_or_sharing:
    stance: prohibited
    text: VU does not sell your information to third parties
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Vanderbilt University
provenance_date: '2026-11-10'
provider_name: Vanderbilt University
provider_slug: vanderbilt
slug: vanderbilt-privacy-policy
source_date: '2026-11-10'
source_filename: vanderbilt-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.vanderbilt.edu/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Vanderbilt University\naid: vanderbilt\nurl: https://www.vanderbilt.edu/privacy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In the context of data transfers, VU may be a data “controller” or “processor” with regard to certain activities\n    as defined under the GDPR\ndata_categories:\n- category: identifying\n  text: 'Student applicants: personal and family information related to the application and financial aid process,\n    including supporting documentation, identification and contact information'\n- category: contact\n  text: 'Faculty and staff: contact information, biographic information,\
  \ security video footage, information related\n    to remuneration, to benefits, to family members, or to performance at work.'\n- category: health\n  text: 'Students: information submitted as prospective students, information related to their academic record or\n    academic performance, information about their activities on campus, disciplinary records, health records, biometric\n    identifiers, security camera footage.'\n- category: biometric\n  text: biometric identifiers, security camera footage\n- category: device\n  text: 'Website visitors: the internet domain from which a visitor accesses the website, the IP address assigned\n    to the visitor’s computer, the type of browser the visitor is using, the date and time of visit.'\n- category: location\n  text: 'Network users: geolocation, device information'\npurposes:\n- purpose: admission and higher education services\n  text: To facilitate admission and provide higher education services for our current, former, and prospective\
  \ students.\n- purpose: employment management\n  text: To manage the employment of our faculty members and staff.\n- purpose: website performance\n  text: To support website performance and enhance user experience .\n- purpose: security and property protection\n  text: To ensure our Community Members’ and visitors’ security and to protect our property.\nretention:\n- scope: personal information generally\n  period: null\n  text: VU strives to keep personal information in our records only as long as is necessary for the purposes they\n    were collected and processed.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: the right to access personal information, rectify incorrect personal information, erase personal information,\n    restrict or object to processing, and the right to data portability\n- right: withdraw consent\n  text: the right\
  \ to withdraw consent at any time, if processing is based on consent\n- right: lodge complaint\n  text: the right to lodge a complaint with a supervisory authority (established in the EU)\nsale_or_sharing:\n  stance: prohibited\n  text: VU does not sell your information to third parties\n"
source_yaml_url: https://artifacts.apis.io/vanderbilt/privacy/vanderbilt-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Vanderbilt University's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Private Research University
- Research Data
- Institutional Repository
- Linked Data
- SPARQL
- Digital Collections
- Television News Archive
- Identity Federation
- Library
- Nashville
- Tennessee
- United States
---
