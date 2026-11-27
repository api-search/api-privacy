---
api_specs:
- filename: pointclickcare-assessments-api-openapi.yml
  format: yaml
  label: PointClickCare Assessments API
  slug: pointclickcare-assessments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-assessments-api-openapi.yml
- filename: pointclickcare-diagnoses-api-openapi.yml
  format: yaml
  label: PointClickCare Diagnoses API
  slug: pointclickcare-diagnoses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-diagnoses-api-openapi.yml
- filename: pointclickcare-facilities-api-openapi.yml
  format: yaml
  label: PointClickCare Facilities API
  slug: pointclickcare-facilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-facilities-api-openapi.yml
- filename: pointclickcare-medications-api-openapi.yml
  format: yaml
  label: PointClickCare Medications API
  slug: pointclickcare-medications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-medications-api-openapi.yml
- filename: pointclickcare-patients-api-openapi.yml
  format: yaml
  label: PointClickCare Patients API
  slug: pointclickcare-patients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-patients-api-openapi.yml
- filename: pointclickcare-vitals-api-openapi.yml
  format: yaml
  label: PointClickCare Vitals API
  slug: pointclickcare-vitals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pointclickcare/openapi/pointclickcare-vitals-api-openapi.yml
claim_count: 18
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information that is used by a government authority, financial institution or insurance carrier to distinguish a person from other individuals ( e.g., social security number, social insurance number, credit card information, or insurance policy number) is private.
  - category: contact
    text: This could include name, email address, mailing address, telephone number(s) and other contact and billing information.
  - category: health
    text: Information about an individual’s health, including insurance and billing information, is also considered – depending on the jurisdiction – to be PI, Protected Health Information (“PHI”)
  - category: device
    text: The model of the device making the request
  - category: behavioral
    text: Search terms used URLs visited
  - category: location
    text: IP addressGeographic location
  deletion:
    route: Edit organization or user record via the Services
    text: If customers or their users need to update or change their Personal Information stored by us, they may do so by editing the organization or user record via the Services.
  dpa:
    available: true
    text: As a Business Associate, we are required to use reasonable and appropriate measures to safeguard the confidentiality, integrity and accessibility of PHI
    url: null
  purposes:
  - purpose: Provide and operate Services
    text: to operate, maintain, manage and administer the Services, including processing registrations and payments, and diagnosing technical problems
  - purpose: Marketing and sales
    text: Some Personal Information (but not PHI) also may be collected for marketing and sales purposes
  - purpose: Analytics and improvement
    text: to perform audits, research, measurements and analyses in an effort to maintain, administer, support, enhance and protect the Services
  residency:
  - region: Canada and United States
    text: hosts customer’s production database in the customer’s country of residence
  retention:
  - period: null
    scope: Personal Information
    text: for as long as a customer account remains active
  rights:
  - right: Access to PHI
    text: Upon written request by an authorized individual, PointClickCare will allow access to any PHI collected and stored about such individual
  - right: Correction of PHI
    text: When provided with reliable evidence of an error in PHI data, PointClickCare will correct any inaccurate PHI
  - right: Opt out of marketing and sharing
    text: send us a request specifying your choice or change of permission by contacting us
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We will never sell your Personal Information (or non-personal information if it can be used in any way to identify you).
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: 'In the case of American customers, PointClickCare may access a customer’s data from Canada for purposes of, for example: responding to support requests'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PointClickCare
provenance_date: '2026-11-10'
provider_name: PointClickCare
provider_slug: pointclickcare
slug: pointclickcare-privacy-policy
source_date: '2026-11-10'
source_filename: pointclickcare-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://pointclickcare.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PointClickCare\naid: pointclickcare\nurl: https://pointclickcare.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Information that is used by a government authority, financial institution or insurance carrier to distinguish\n    a person from other individuals ( e.g., social security number, social insurance number, credit card information,\n    or insurance policy number) is private.\n- category: contact\n  text: This could include name, email address, mailing address, telephone number(s) and other contact and billing\n\
  \    information.\n- category: health\n  text: Information about an individual’s health, including insurance and billing information, is also considered\n    – depending on the jurisdiction – to be PI, Protected Health Information (“PHI”)\n- category: device\n  text: The model of the device making the request\n- category: behavioral\n  text: Search terms used URLs visited\n- category: location\n  text: IP addressGeographic location\npurposes:\n- purpose: Provide and operate Services\n  text: to operate, maintain, manage and administer the Services, including processing registrations and payments,\n    and diagnosing technical problems\n- purpose: Marketing and sales\n  text: Some Personal Information (but not PHI) also may be collected for marketing and sales purposes\n- purpose: Analytics and improvement\n  text: to perform audits, research, measurements and analyses in an effort to maintain, administer, support, enhance\n    and protect the Services\nretention:\n- scope: Personal Information\n\
  \  period: null\n  text: for as long as a customer account remains active\nresidency:\n- region: Canada and United States\n  text: hosts customer’s production database in the customer’s country of residence\ntransfers:\n- mechanism: other\n  text: 'In the case of American customers, PointClickCare may access a customer’s data from Canada for purposes\n    of, for example: responding to support requests'\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: As a Business Associate, we are required to use reasonable and appropriate measures to safeguard the confidentiality,\n    integrity and accessibility of PHI\ndeletion:\n  route: Edit organization or user record via the Services\n  text: If customers or their users need to update or change their Personal Information stored by us, they may do\n    so by editing the organization or user record via the Services.\nrights:\n- right: Access to PHI\n  text: Upon written request by an authorized individual,\
  \ PointClickCare will allow access to any PHI collected\n    and stored about such individual\n- right: Correction of PHI\n  text: When provided with reliable evidence of an error in PHI data, PointClickCare will correct any inaccurate\n    PHI\n- right: Opt out of marketing and sharing\n  text: send us a request specifying your choice or change of permission by contacting us\nsale_or_sharing:\n  stance: prohibited\n  text: We will never sell your Personal Information (or non-personal information if it can be used in any way to\n    identify you).\n"
source_yaml_url: https://artifacts.apis.io/pointclickcare/privacy/pointclickcare-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 18 quoted statements, read from PointClickCare's own page on 2026-11-10.
synthetic: false
tags:
- Healthcare
- Long-Term Care
- Post-Acute Care
- Electronic Health Records
- FHIR
- Senior Care
- Interoperability
---
