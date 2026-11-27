---
api_specs:
- filename: sailpoint-access-profiles-api-openapi.yml
  format: yaml
  label: SailPoint Access Profiles API
  slug: sailpoint-access-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-access-profiles-api-openapi.yml
- filename: sailpoint-certifications-api-openapi.yml
  format: yaml
  label: SailPoint Certifications API
  slug: sailpoint-certifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-certifications-api-openapi.yml
- filename: sailpoint-identities-api-openapi.yml
  format: yaml
  label: SailPoint Identities API
  slug: sailpoint-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-identities-api-openapi.yml
- filename: sailpoint-roles-api-openapi.yml
  format: yaml
  label: SailPoint Roles API
  slug: sailpoint-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sailpoint/openapi/sailpoint-roles-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: First and last name; Username; Email; Phone number; Account login credentials
  - category: financial
    text: Payment card type; Last 4 digits of payment card and expiration date; Billing address
  - category: device
    text: IP address; Device ID; Domain server; Type of device/operating system/browser used to access the Services
  - category: behavioral
    text: Web page interactions; Referring webpage/source through which you accessed the Services; Browsing activity, including the addresses of websites that you visit
  - category: demographic
    text: Age / date of birth; Zip code
  - category: professional
    text: Employer; Job title
  - category: location
    text: IP-address-based location information
  - category: communication
    text: Identifying information in emails, letters, texts, or other communications you send us
  deletion:
    route: Data Subject Request Privacy Webform or privacy@sailpoint.com
    text: You may submit a Valid Request by submitting a request through the Data Subject Request Privacy Webform located at this link .
  dpa:
    available: true
    text: Our Data Processing Addendum available on our Trust Center
    url: null
  purposes:
  - purpose: Providing, customizing and improving the Services
    text: Creating and managing your account or other user profiles. Processing orders or other transactions; billing.
  - purpose: Marketing the Services
    text: Showing you advertisements, including interest-based, online behavioral or targeted advertising.
  - purpose: Legal requirements and fraud/security
    text: Doing fraud protection, security and debugging.
  residency:
  - region: United States
    text: The Services are hosted and operated in the United States (“U.S.”) through SailPoint and its service providers
  retention:
  - period: null
    scope: Personal Data generally
    text: We retain Personal Data about you for as long as necessary to provide you with our Services or to perform our business or commercial purposes for collecting your Personal Data.
  rights:
  - right: Access
    text: 'Access : You may have the right to request confirmation of or access to the Personal Data that we process about you.'
  - right: Deletion
    text: 'Deletion : You may have the right to request that we delete the Personal Data that we have collected about you.'
  - right: Correction
    text: 'Correction : You may have the right to request that we correct any inaccurate Personal Data we have collected about you.'
  - right: Portability
    text: 'Portability : You may have the right to request a copy of your Personal Data in a machine-readable format, to the extent technically feasible.'
  - right: Opt-out of sharing/sale
    text: You have the right to opt-out of the Sharing of your Personal Data for the purposes of targeted advertising and the “sale” of your Personal Data.
  - right: Objection
    text: Objection :You can contact us to let us know that you object to the further use or disclosure of your Personal Data for certain purposes, such as for direct marketing purposes.
  - right: Restriction of processing
    text: Restriction of Processing :You can ask us to restrict further processing of your Personal Data.
  role:
    text: SailPoint acts as the “Controller” of your Personal Data for the purposes described in this Privacy Statement.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: Please note that we do not sell Personal Data for monetary consideration.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: SailPoint and our affiliates, SailPoint International, Inc., SailPoint Technologies Holdings, Inc., and SailPoint SZ LLC comply with the EU-U.S. Data Privacy Framework (“EU-U.S. DPF”)
  - mechanism: SCC
    text: In some circumstances, your Personal Data may be transferred to the U.S. pursuant to (i) a data processing agreement incorporating standard data protection clauses
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: SailPoint
provenance_date: '2026-11-10'
provider_name: SailPoint
provider_slug: sailpoint
slug: sailpoint-privacy-policy
source_date: '2026-11-10'
source_filename: sailpoint-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.sailpoint.com/legal/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: SailPoint\naid: sailpoint\nurl: https://www.sailpoint.com/legal/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: SailPoint acts as the “Controller” of your Personal Data for the purposes described in this Privacy Statement.\ndata_categories:\n- category: contact\n  text: First and last name; Username; Email; Phone number; Account login credentials\n- category: financial\n  text: Payment card type; Last 4 digits of payment card and expiration date; Billing address\n- category: device\n  text: IP address; Device ID; Domain server; Type of device/operating system/browser used to access\
  \ the Services\n- category: behavioral\n  text: Web page interactions; Referring webpage/source through which you accessed the Services; Browsing activity,\n    including the addresses of websites that you visit\n- category: demographic\n  text: Age / date of birth; Zip code\n- category: professional\n  text: Employer; Job title\n- category: location\n  text: IP-address-based location information\n- category: communication\n  text: Identifying information in emails, letters, texts, or other communications you send us\npurposes:\n- purpose: Providing, customizing and improving the Services\n  text: Creating and managing your account or other user profiles. Processing orders or other transactions; billing.\n- purpose: Marketing the Services\n  text: Showing you advertisements, including interest-based, online behavioral or targeted advertising.\n- purpose: Legal requirements and fraud/security\n  text: Doing fraud protection, security and debugging.\nretention:\n- scope: Personal Data generally\n\
  \  period: null\n  text: We retain Personal Data about you for as long as necessary to provide you with our Services or to perform\n    our business or commercial purposes for collecting your Personal Data.\nresidency:\n- region: United States\n  text: The Services are hosted and operated in the United States (“U.S.”) through SailPoint and its service providers\ntransfers:\n- mechanism: DPF\n  text: SailPoint and our affiliates, SailPoint International, Inc., SailPoint Technologies Holdings, Inc., and\n    SailPoint SZ LLC comply with the EU-U.S. Data Privacy Framework (“EU-U.S. DPF”)\n- mechanism: SCC\n  text: In some circumstances, your Personal Data may be transferred to the U.S. pursuant to (i) a data processing\n    agreement incorporating standard data protection clauses\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: Our Data Processing Addendum available on our Trust Center\ndeletion:\n  route: Data Subject Request Privacy Webform or privacy@sailpoint.com\n\
  \  text: You may submit a Valid Request by submitting a request through the Data Subject Request Privacy Webform\n    located at this link .\nrights:\n- right: Access\n  text: 'Access : You may have the right to request confirmation of or access to the Personal Data that we process\n    about you.'\n- right: Deletion\n  text: 'Deletion : You may have the right to request that we delete the Personal Data that we have collected about\n    you.'\n- right: Correction\n  text: 'Correction : You may have the right to request that we correct any inaccurate Personal Data we have collected\n    about you.'\n- right: Portability\n  text: 'Portability : You may have the right to request a copy of your Personal Data in a machine-readable format,\n    to the extent technically feasible.'\n- right: Opt-out of sharing/sale\n  text: You have the right to opt-out of the Sharing of your Personal Data for the purposes of targeted advertising\n    and the “sale” of your Personal Data.\n- right: Objection\n\
  \  text: Objection :You can contact us to let us know that you object to the further use or disclosure of your Personal\n    Data for certain purposes, such as for direct marketing purposes.\n- right: Restriction of processing\n  text: Restriction of Processing :You can ask us to restrict further processing of your Personal Data.\nsale_or_sharing:\n  stance: conditional\n  text: Please note that we do not sell Personal Data for monetary consideration.\n"
source_yaml_url: https://artifacts.apis.io/sailpoint/privacy/sailpoint-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from SailPoint's own page on 2026-11-10.
synthetic: false
tags:
- Access Governance
- Compliance
- Identity and Access Management
- Identity Security
- Security
---
