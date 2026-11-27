---
api_specs:
- filename: certifid-accountverifications-api-openapi.yml
  format: yaml
  label: CertifID Account Verifications API
  slug: certifid-accountverifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-accountverifications-api-openapi.yml
- filename: certifid-banklookup-api-openapi.yml
  format: yaml
  label: CertifID Bank Lookup API
  slug: certifid-banklookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-banklookup-api-openapi.yml
- filename: certifid-collectrequest-api-openapi.yml
  format: yaml
  label: CertifID Collect Request API
  slug: certifid-collectrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-collectrequest-api-openapi.yml
- filename: certifid-confirmrequest-api-openapi.yml
  format: yaml
  label: CertifID Confirm Request API
  slug: certifid-confirmrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-confirmrequest-api-openapi.yml
- filename: certifid-disbursements-api-openapi.yml
  format: yaml
  label: CertifID Disbursements API
  slug: certifid-disbursements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-disbursements-api-openapi.yml
- filename: certifid-identityrequest-api-openapi.yml
  format: yaml
  label: CertifID Identity Request API
  slug: certifid-identityrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-identityrequest-api-openapi.yml
- filename: certifid-integration-api-openapi.yml
  format: yaml
  label: CertifID Integration API
  slug: certifid-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-integration-api-openapi.yml
- filename: certifid-lenders-api-openapi.yml
  format: yaml
  label: CertifID Lenders API
  slug: certifid-lenders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-lenders-api-openapi.yml
- filename: certifid-location-api-openapi.yml
  format: yaml
  label: CertifID Location API
  slug: certifid-location-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-location-api-openapi.yml
- filename: certifid-payoffordering-api-openapi.yml
  format: yaml
  label: CertifID Payoff Ordering API
  slug: certifid-payoffordering-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-payoffordering-api-openapi.yml
- filename: certifid-sendrequest-api-openapi.yml
  format: yaml
  label: CertifID Send Request API
  slug: certifid-sendrequest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-sendrequest-api-openapi.yml
- filename: certifid-test-api-openapi.yml
  format: yaml
  label: CertifID Test API
  slug: certifid-test-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-test-api-openapi.yml
- filename: certifid-underwriter-api-openapi.yml
  format: yaml
  label: CertifID Underwriter API
  slug: certifid-underwriter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-underwriter-api-openapi.yml
- filename: certifid-users-api-openapi.yml
  format: yaml
  label: CertifID Users API
  slug: certifid-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-users-api-openapi.yml
- filename: certifid-wiringinstructions-api-openapi.yml
  format: yaml
  label: CertifID Wiring Instructions API
  slug: certifid-wiringinstructions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/certifid/openapi/certifid-wiringinstructions-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Real name, alias, postal address, email address, telephone number, IP address, driver's license number, passport number
  - category: biometric
    text: Facial geometry (faceprint) from selfie via CertifID Match; liveness detection data
  - category: financial
    text: Bank account numbers, routing numbers, wire transfer details, mortgage payoff amounts, transaction amounts, originator and beneficiary information for funds-transfer records
  - category: location
    text: Approximate location (from IP); precise location only with permission
  - category: behavioral
    text: Browsing history on CertifID websites, platform interactions, device identifiers, browser type and version
  - category: demographic
    text: Date of birth, gender, citizenship (as shown on identification documents)
  deletion:
    route: Email privacy@certifid.com or call 1-616-816-1668
    text: 'Right to Deletion: You may request permanent destruction of your Biometric Data at any time by contacting privacy@certifid.com or 1-616-816-1668.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Identity verification
    text: Verifying the identity of individuals in connection with real estate, mortgage payoff, wire transfer, and other financial transactions facilitated through the CertifID platform
  - purpose: Fraud detection
    text: Detecting, preventing, and investigating fraud, including wire fraud, identity theft, synthetic identity fraud, and business email compromise
  - purpose: Legal compliance
    text: Complying with applicable laws and regulations, including the Bank Secrecy Act / Anti-Money Laundering rules (31 CFR Part 1010), NACHA Operating Rules, Know Your Customer (KYC) obligations, OFAC sanctions screening
  - purpose: Marketing
    text: Marketing our products and services to existing customers, and conducting joint marketing with financial institutions
  residency:
  - region: United States
    text: The Services are intended for use within the United States. CertifID does not knowingly collect personal information from individuals located outside the United States.
  retention:
  - period: 3 years from last interaction OR 1 year after purpose is satisfied, whichever is first
    scope: Biometric data (faceprint)
    text: 3 years from last interaction OR 1 year after purpose is satisfied, whichever is first
  - period: 90 days from verification completion
    scope: Selfie photographs and ID document images
    text: Selfie photographs and ID document images 90 days from verification completion
  - period: 5 years from last transaction
    scope: Bank account and routing numbers
    text: Bank account and routing numbers 5 years from last transaction
  - period: 13 months from collection
    scope: Website usage data
    text: Website usage data (cookies, analytics) 13 months from collection
  - period: 7 years from log creation
    scope: Audit logs
    text: Audit logs (access to personal information) 7 years from log creation
  rights:
  - right: Right to know
    text: Right to Know. You may request that CertifID disclose the categories and specific pieces of personal information we have collected about you
  - right: Right to delete
    text: Right to Delete. You may request that CertifID delete personal information collected from you, subject to exceptions
  - right: Right to correct (CA)
    text: Right to correct inaccurate personal information
  - right: Right to limit sensitive PI (CA)
    text: Right to limit use and disclosure of sensitive personal information (see Section 9)
  - right: Right to opt out of automated decision-making (CA)
    text: Right to opt out of automated decision-making technology.
  - right: Right to withdraw biometric consent
    text: 'Right to Withdraw Consent: You may withdraw your consent to the collection and use of your Biometric Data at any time.'
  role:
    text: When CertifID processes personal information on behalf of an enterprise customer (such as a title company, settlement agent, or lender), CertifID acts as a service provider or data processor with respect to that information
    value: both
  sale_or_sharing:
    stance: prohibited
    text: CertifID does not "sell" or "share" personal information as those terms are defined by the CCPA/CPRA.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CertifID
provenance_date: '2026-11-09'
provider_name: CertifID
provider_slug: certifid
slug: certifid-privacy-policy
source_date: '2026-11-09'
source_filename: certifid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.certifid.com/company/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CertifID\naid: certifid\nurl: https://www.certifid.com/company/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: When CertifID processes personal information on behalf of an enterprise customer (such as a title company,\n    settlement agent, or lender), CertifID acts as a service provider or data processor with respect to that information\ndata_categories:\n- category: identifying\n  text: Real name, alias, postal address, email address, telephone number, IP address, driver's license number,\n    passport number\n- category: biometric\n  text: Facial geometry (faceprint)\
  \ from selfie via CertifID Match; liveness detection data\n- category: financial\n  text: Bank account numbers, routing numbers, wire transfer details, mortgage payoff amounts, transaction amounts,\n    originator and beneficiary information for funds-transfer records\n- category: location\n  text: Approximate location (from IP); precise location only with permission\n- category: behavioral\n  text: Browsing history on CertifID websites, platform interactions, device identifiers, browser type and version\n- category: demographic\n  text: Date of birth, gender, citizenship (as shown on identification documents)\npurposes:\n- purpose: Identity verification\n  text: Verifying the identity of individuals in connection with real estate, mortgage payoff, wire transfer, and\n    other financial transactions facilitated through the CertifID platform\n- purpose: Fraud detection\n  text: Detecting, preventing, and investigating fraud, including wire fraud, identity theft, synthetic identity\n  \
  \  fraud, and business email compromise\n- purpose: Legal compliance\n  text: Complying with applicable laws and regulations, including the Bank Secrecy Act / Anti-Money Laundering rules\n    (31 CFR Part 1010), NACHA Operating Rules, Know Your Customer (KYC) obligations, OFAC sanctions screening\n- purpose: Marketing\n  text: Marketing our products and services to existing customers, and conducting joint marketing with financial\n    institutions\nretention:\n- scope: Biometric data (faceprint)\n  period: 3 years from last interaction OR 1 year after purpose is satisfied, whichever is first\n  text: 3 years from last interaction OR 1 year after purpose is satisfied, whichever is first\n- scope: Selfie photographs and ID document images\n  period: 90 days from verification completion\n  text: Selfie photographs and ID document images 90 days from verification completion\n- scope: Bank account and routing numbers\n  period: 5 years from last transaction\n  text: Bank account and routing\
  \ numbers 5 years from last transaction\n- scope: Website usage data\n  period: 13 months from collection\n  text: Website usage data (cookies, analytics) 13 months from collection\n- scope: Audit logs\n  period: 7 years from log creation\n  text: Audit logs (access to personal information) 7 years from log creation\nresidency:\n- region: United States\n  text: The Services are intended for use within the United States. CertifID does not knowingly collect personal\n    information from individuals located outside the United States.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@certifid.com or call 1-616-816-1668\n  text: 'Right to Deletion: You may request permanent destruction of your Biometric Data at any time by contacting\n    privacy@certifid.com or 1-616-816-1668.'\nrights:\n- right: Right to know\n  text: Right to Know. You may request that CertifID disclose the categories and specific\
  \ pieces of personal information\n    we have collected about you\n- right: Right to delete\n  text: Right to Delete. You may request that CertifID delete personal information collected from you, subject to\n    exceptions\n- right: Right to correct (CA)\n  text: Right to correct inaccurate personal information\n- right: Right to limit sensitive PI (CA)\n  text: Right to limit use and disclosure of sensitive personal information (see Section 9)\n- right: Right to opt out of automated decision-making (CA)\n  text: Right to opt out of automated decision-making technology.\n- right: Right to withdraw biometric consent\n  text: 'Right to Withdraw Consent: You may withdraw your consent to the collection and use of your Biometric Data\n    at any time.'\nsale_or_sharing:\n  stance: prohibited\n  text: CertifID does not \"sell\" or \"share\" personal information as those terms are defined by the CCPA/CPRA.\n"
source_yaml_url: https://artifacts.apis.io/certifid/privacy/certifid-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 25 quoted statements, read from CertifID's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wire Fraud Prevention
- Real Estate
- Title Insurance
- Identity Verification
- Business Verification
- Payments
- Fraud Prevention
- Escrow and Settlement
- Financial Services
- Security
---
