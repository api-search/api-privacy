---
api_specs:
- filename: cornell-library-catalog-api-openapi.yml
  format: yaml
  label: Cornell University Library Catalog Search API
  slug: library-catalog
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cornell/openapi/cornell-library-catalog-api-openapi.yml
- filename: cornell-cugir-api-openapi.yml
  format: yaml
  label: Cornell University Cugir API
  slug: cornell-cugir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cornell/openapi/cornell-cugir-api-openapi.yml
- filename: cornell-config-api-openapi.yml
  format: yaml
  label: Cornell University Config API
  slug: cornell-config-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cornell/openapi/cornell-config-api-openapi.yml
- filename: cornell-search-api-openapi.yml
  format: yaml
  label: Cornell University Search API
  slug: cornell-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cornell/openapi/cornell-search-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, physical address, country, province, phone number, email address, emergency contact information and family and significant other contact information
  - category: identifying
    text: Cornell identifiers (e.g., NetID and/or EmployeeID), university affiliation, current grade level, current college if transferring, graduation date, and group and organization memberships
  - category: demographic
    text: Race, ethnicity, citizenship, gender, gender identity, pronouns, age, date of birth.
  - category: professional
    text: Company name, address, phone, fax, email, website, description, parent organization, union membership status, position/title, years in job
  - category: financial
    text: payroll data, title, years of service, and tax information
  - category: behavioral
    text: Event attendance, volunteer interests, organization affiliations, committee participation, memberships, awards and honors
  - category: device
    text: Device and browser related information that is automatically collected when engaging with Cornell websites and services.
  - category: location
    text: Location Information (see additional information in section below)
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Mission-related use
    text: Personal Data is used to enable Cornell's mission.
  - purpose: Analytics
    text: To perform analytics
  - purpose: Fundraising
    text: To fundraise
  - purpose: Outreach and marketing
    text: To perform outreach and marketing about Cornell
  retention:
  - period: null
    scope: Personal Data
    text: Cornell strives to delete or anonymize Personal Data when it is no longer needed for the purposes for which it was collected, unless required or allowed by policy or law to keep it for a longer period.
  rights:
  - right: access
    text: access your information held by us
  - right: correction
    text: correct inaccurate or incorrect information about you
  - right: erasure
    text: the erasure of your information when it is no longer necessary for us to retain it
  - right: restriction
    text: restrict processing of your personal information in specific situations
  - right: objection
    text: object to processing your information, including sending you communications that may be considered direct-marketing materials
  - right: withdraw consent
    text: the right to withdraw your consent to our processing of your personal data where our processing is solely based on your consent
  - right: complain
    text: complain to a supervisory authority
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cornell University
provenance_date: '2026-11-09'
provider_name: Cornell University
provider_slug: cornell
slug: cornell-privacy-policy
source_date: '2026-11-09'
source_filename: cornell-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://privacy.cornell.edu/university-privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cornell University\naid: cornell\nurl: https://privacy.cornell.edu/university-privacy-statement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, physical address, country, province, phone number, email address, emergency contact information and\n    family and significant other contact information\n- category: identifying\n  text: Cornell identifiers (e.g., NetID and/or EmployeeID), university affiliation, current grade level, current\n    college if transferring, graduation date, and group and organization memberships\n- category: demographic\n\
  \  text: Race, ethnicity, citizenship, gender, gender identity, pronouns, age, date of birth.\n- category: professional\n  text: Company name, address, phone, fax, email, website, description, parent organization, union membership status,\n    position/title, years in job\n- category: financial\n  text: payroll data, title, years of service, and tax information\n- category: behavioral\n  text: Event attendance, volunteer interests, organization affiliations, committee participation, memberships,\n    awards and honors\n- category: device\n  text: Device and browser related information that is automatically collected when engaging with Cornell websites\n    and services.\n- category: location\n  text: Location Information (see additional information in section below)\npurposes:\n- purpose: Mission-related use\n  text: Personal Data is used to enable Cornell's mission.\n- purpose: Analytics\n  text: To perform analytics\n- purpose: Fundraising\n  text: To fundraise\n- purpose: Outreach and\
  \ marketing\n  text: To perform outreach and marketing about Cornell\nretention:\n- scope: Personal Data\n  period: null\n  text: Cornell strives to delete or anonymize Personal Data when it is no longer needed for the purposes for which\n    it was collected, unless required or allowed by policy or law to keep it for a longer period.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: access\n  text: access your information held by us\n- right: correction\n  text: correct inaccurate or incorrect information about you\n- right: erasure\n  text: the erasure of your information when it is no longer necessary for us to retain it\n- right: restriction\n  text: restrict processing of your personal information in specific situations\n- right: objection\n  text: object to processing your information, including sending you communications that may be considered direct-marketing\n\
  \    materials\n- right: withdraw consent\n  text: the right to withdraw your consent to our processing of your personal data where our processing is solely\n    based on your consent\n- right: complain\n  text: complain to a supervisory authority\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cornell/privacy/cornell-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- rights
summary_line: 20 quoted statements, read from Cornell University's own page on 2026-11-09.
synthetic: false
tags:
- University
- Higher Education
- Education
- Ivy League
- United States
- Course Catalog
- Library
- Research Data
- Geospatial
- Identity Federation
---
