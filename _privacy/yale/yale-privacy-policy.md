---
api_specs:
- filename: yale-search-api-openapi.yml
  format: yaml
  label: LUX Collections Discovery — Search API
  slug: yale-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-search-api-openapi.yml
- filename: yale-documents-api-openapi.yml
  format: yaml
  label: LUX Collections Discovery — Documents API
  slug: yale-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-documents-api-openapi.yml
- filename: yale-facets-api-openapi.yml
  format: yaml
  label: LUX Collections Discovery — Facets API
  slug: yale-facets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-facets-api-openapi.yml
- filename: yale-related-api-openapi.yml
  format: yaml
  label: LUX Collections Discovery — Related API
  slug: yale-related-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-related-api-openapi.yml
- filename: yale-configuration-api-openapi.yml
  format: yaml
  label: LUX Collections Discovery — Configuration API
  slug: yale-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-configuration-api-openapi.yml
- filename: yale-federation-api-openapi.yml
  format: yaml
  label: Yale University Federation API
  slug: yale-federation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-federation-api-openapi.yml
- filename: yale-iiif-api-openapi.yml
  format: yaml
  label: Yale University IIIF API
  slug: yale-iiif-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-iiif-api-openapi.yml
- filename: yale-info-api-openapi.yml
  format: yaml
  label: Yale University Info API
  slug: yale-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yale/openapi/yale-info-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: Examples of personal information include name, mailing address, phone number, email address, date of birth, University Personal Identifier
  - category: financial
    text: payment information such as credit card or banking information, tax ID numbers
  - category: health
    text: health information, documentation in support of academic accommodations, dietary needs
  - category: biometric
    text: Employees whose role requires access to restricted facilities may be asked to provide biometric information such as iris scans
  - category: behavioral
    text: we and our education vendors collect information on your interactions with the course
  - category: device
    text: Google Analytics uses cookies to help us analyze the use of our site.
  deletion:
    route: Email privacy@yale.edu
    text: Requests to view, amend or delete personal information may be made by sending an email to privacy@yale.edu .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services and university administration
    text: Personal information you provide to us or that we collect from third parties is used to provide services to you and for administration of the University
  - purpose: Legal and reporting obligations
    text: and to meet our legal and reporting obligations
  - purpose: Website usage analytics
    text: Generic information is collected through the use of “cookies,” which are text files placed on your computer to evaluate usage patterns
  residency:
  - region: United States
    text: The personal information collected will be stored in the United States and will be transferred to the US if collected internationally.
  retention:
  - period: null
    scope: General personal information
    text: We retain your information for as long as needed to fulfill our business and archival purposes, and some information may be retained indefinitely.
  - period: null
    scope: Biometric information
    text: Biometric information is destroyed as soon as no longer needed for the collected purposes unless required to be retained under applicable law or regulation.
  rights:
  - right: View, amend, or delete
    text: You may have the right to view, amend, or request that Yale delete personal information.
  role:
    text: Yale University, (“Yale” or “the University”) collects, uses, and shares personal information
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: personal information may be transferred to our venders in the US and in other countries, so long as those venders have signed an agreement with Yale to protect the privacy of the information
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Yale University
provenance_date: '2026-11-10'
provider_name: Yale University
provider_slug: yale
slug: yale-privacy-policy
source_date: '2026-11-10'
source_filename: yale-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://privacy.yale.edu/resources/privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Yale University\naid: yale\nurl: https://privacy.yale.edu/resources/privacy-statement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Yale University, (“Yale” or “the University”) collects, uses, and shares personal information\ndata_categories:\n- category: identifying\n  text: Examples of personal information include name, mailing address, phone number, email address, date of birth,\n    University Personal Identifier\n- category: financial\n  text: payment information such as credit card or banking information, tax ID numbers\n- category: health\n  text: health information, documentation\
  \ in support of academic accommodations, dietary needs\n- category: biometric\n  text: Employees whose role requires access to restricted facilities may be asked to provide biometric information\n    such as iris scans\n- category: behavioral\n  text: we and our education vendors collect information on your interactions with the course\n- category: device\n  text: Google Analytics uses cookies to help us analyze the use of our site.\npurposes:\n- purpose: Provide services and university administration\n  text: Personal information you provide to us or that we collect from third parties is used to provide services\n    to you and for administration of the University\n- purpose: Legal and reporting obligations\n  text: and to meet our legal and reporting obligations\n- purpose: Website usage analytics\n  text: Generic information is collected through the use of “cookies,” which are text files placed on your computer\n    to evaluate usage patterns\nretention:\n- scope: General personal information\n\
  \  period: null\n  text: We retain your information for as long as needed to fulfill our business and archival purposes, and some\n    information may be retained indefinitely.\n- scope: Biometric information\n  period: null\n  text: Biometric information is destroyed as soon as no longer needed for the collected purposes unless required\n    to be retained under applicable law or regulation.\nresidency:\n- region: United States\n  text: The personal information collected will be stored in the United States and will be transferred to the US\n    if collected internationally.\ntransfers:\n- mechanism: other\n  text: personal information may be transferred to our venders in the US and in other countries, so long as those\n    venders have signed an agreement with Yale to protect the privacy of the information\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@yale.edu\n  text: Requests to view, amend or delete\
  \ personal information may be made by sending an email to privacy@yale.edu\n    .\nrights:\n- right: View, amend, or delete\n  text: You may have the right to view, amend, or request that Yale delete personal information.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/yale/privacy/yale-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 16 quoted statements, read from Yale University's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- United States
- Ivy League
- Research
- Research Data
- Research Repository
- Identity Federation
- Library
- Cultural Heritage
- Linked Data
- IIIF
- Course Catalog
---
