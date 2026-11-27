---
api_specs:
- filename: myome-institutional-interface-api-openapi.yml
  format: yaml
  label: MyOme Institutional Interface API
  slug: myome-institutional-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-institutional-interface-api-openapi.yml
- filename: myome-requisitions-and-orders-api-openapi.yml
  format: yaml
  label: MyOme Requisitions and Orders API
  slug: myome-requisitions-and-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-requisitions-and-orders-api-openapi.yml
- filename: myome-resources-api-openapi.yml
  format: yaml
  label: MyOme Resources API
  slug: myome-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-resources-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: name, email address, address, phone number, race, ethnicity, professional details, birth date, sex
  - category: health
    text: personal information that relates to your health or medical treatment that you have received
  - category: biometric
    text: Biometric information
  - category: device
    text: Internet protocol (IP) address, user settings, MAC address, cookie identifiers, mobile carrier
  - category: location
    text: location information (including approximate location derived from IP address)
  - category: behavioral
    text: pages that you visit before, during and after using our Web Sites, information about the links you click
  - category: financial
    text: We may collect personal information and details associated with your purchases, including payment information.
  deletion:
    route: Request deletion via contact
    text: Request Deletion of your personal information , subject to applicable data retention laws and requirements
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services
    text: We use your information to fulfill our contract with you and provide you with our Services
  - purpose: Administrative purposes
    text: We use your information for various administrative purposes
  - purpose: Research
    text: We will never use your personal information to conduct research without your consent.
  - purpose: De-identified or aggregated information
    text: We may use your personal information to create de-identified and/or aggregated information
  - purpose: Marketing and advertising
    text: We may use personal information to tailor and provide you with content and advertisements.
  residency:
  - region: United States
    text: All information you provide will be stored or hosted on servers in the United States
  retention:
  - period: null
    scope: Personal information generally
    text: We store the personal information we collect as described in this Privacy Notice for as long as you use our Services, or as necessary to fulfill the purpose(s) for which it was collected
  rights:
  - right: Access and portability
    text: Access to and Portability of Your Personal Information
  - right: Correction
    text: Request Correction of your personal information where it is inaccurate or incomplete.
  - right: Deletion
    text: Request Deletion of your personal information , subject to applicable data retention laws and requirements
  - right: Restriction or objection
    text: Request Restriction of or Object to our processing of your personal information
  - right: Withdraw consent
    text: Withdraw your Consent to our processing of your personal information .
  role:
    text: MyOme is the controller of the personal information we process under this Privacy Notice.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: For purposes of the CCPA, MyOme does not “sell” personal information
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: MyOme
provenance_date: '2026-11-10'
provider_name: MyOme
provider_slug: myome
slug: myome-privacy-policy
source_date: '2026-11-10'
source_filename: myome-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://myome.com/legal/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: MyOme\naid: myome\nurl: https://myome.com/legal/privacy-notice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: MyOme is the controller of the personal information we process under this Privacy Notice.\ndata_categories:\n- category: identifying\n  text: name, email address, address, phone number, race, ethnicity, professional details, birth date, sex\n- category: health\n  text: personal information that relates to your health or medical treatment that you have received\n- category: biometric\n  text: Biometric information\n- category: device\n  text: Internet protocol (IP) address, user settings,\
  \ MAC address, cookie identifiers, mobile carrier\n- category: location\n  text: location information (including approximate location derived from IP address)\n- category: behavioral\n  text: pages that you visit before, during and after using our Web Sites, information about the links you click\n- category: financial\n  text: We may collect personal information and details associated with your purchases, including payment information.\npurposes:\n- purpose: Provide services\n  text: We use your information to fulfill our contract with you and provide you with our Services\n- purpose: Administrative purposes\n  text: We use your information for various administrative purposes\n- purpose: Research\n  text: We will never use your personal information to conduct research without your consent.\n- purpose: De-identified or aggregated information\n  text: We may use your personal information to create de-identified and/or aggregated information\n- purpose: Marketing and advertising\n  text:\
  \ We may use personal information to tailor and provide you with content and advertisements.\nretention:\n- scope: Personal information generally\n  period: null\n  text: We store the personal information we collect as described in this Privacy Notice for as long as you use\n    our Services, or as necessary to fulfill the purpose(s) for which it was collected\nresidency:\n- region: United States\n  text: All information you provide will be stored or hosted on servers in the United States\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request deletion via contact\n  text: Request Deletion of your personal information , subject to applicable data retention laws and requirements\nrights:\n- right: Access and portability\n  text: Access to and Portability of Your Personal Information\n- right: Correction\n  text: Request Correction of your personal information where it is inaccurate or incomplete.\n- right:\
  \ Deletion\n  text: Request Deletion of your personal information , subject to applicable data retention laws and requirements\n- right: Restriction or objection\n  text: Request Restriction of or Object to our processing of your personal information\n- right: Withdraw consent\n  text: Withdraw your Consent to our processing of your personal information .\nsale_or_sharing:\n  stance: conditional\n  text: For purposes of the CCPA, MyOme does not “sell” personal information\n"
source_yaml_url: https://artifacts.apis.io/myome/privacy/myome-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from MyOme's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Genomics
- Healthcare
- Clinical Laboratory
- Whole Genome Sequencing
- Precision Medicine
- Bioinformatics
- Polygenic Risk Scores
- Pharmacogenomics
- Rare Disease
- Diagnostics
- Life Sciences
---
