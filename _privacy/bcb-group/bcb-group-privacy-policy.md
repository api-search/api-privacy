---
api_specs:
- filename: bcb-group-accounts-api-openapi.yml
  format: yaml
  label: BCB Group Accounts API
  slug: bcb-group-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-accounts-api-openapi.yml
- filename: bcb-group-authentication-api-openapi.yml
  format: yaml
  label: BCB Group Authentication API
  slug: bcb-group-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-authentication-api-openapi.yml
- filename: bcb-group-beneficiaries-api-openapi.yml
  format: yaml
  label: BCB Group Beneficiaries API
  slug: bcb-group-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-beneficiaries-api-openapi.yml
- filename: bcb-group-blinc-api-openapi.yml
  format: yaml
  label: BCB Group BLINC API
  slug: bcb-group-blinc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-blinc-api-openapi.yml
- filename: bcb-group-notifications-api-openapi.yml
  format: yaml
  label: BCB Group Notifications API
  slug: bcb-group-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-notifications-api-openapi.yml
- filename: bcb-group-payments-api-openapi.yml
  format: yaml
  label: BCB Group Payments API
  slug: bcb-group-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-payments-api-openapi.yml
- filename: bcb-group-tools-api-openapi.yml
  format: yaml
  label: BCB Group Tools API
  slug: bcb-group-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-tools-api-openapi.yml
- filename: bcb-group-virtual-accounts-api-openapi.yml
  format: yaml
  label: BCB Group Virtual Accounts API
  slug: bcb-group-virtual-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bcb-group/openapi/bcb-group-virtual-accounts-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identity Data includes first name, last name, username or similar identifier, marital status, title, job title, date of birth and gender.
  - category: contact
    text: Contact Data includes billing address, email address and telephone numbers.
  - category: financial
    text: Financial Data includes bank account and payment card details.
  - category: behavioral
    text: Usage Data includes information about how you use our website, products, and services.
  - category: device
    text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time zone setting and location, browser plug-in types and versions, operating system and platform
  deletion:
    route: Contact the privacy data manager
    text: In some circumstances you can ask us to delete your data. Please see your legal rights below for further information.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Manage relationship with you
    text: 'To manage our relationship with you which may include: (a)Notifying you about changes to our terms of privacy policy (b)Asking you to leave a review or take a survey (c) Adding you to our mailing list'
  - purpose: Targeted advertising and marketing
    text: We may provide you targeted advertisements or marketing communications we believe may be of interest to you.
  - purpose: Website administration and security
    text: To administer and protect our business and our website (including troubleshooting, data analysis, testing, system maintenance, support, reporting and hosting of data)
  retention:
  - period: null
    scope: Personal data generally
    text: We will only retain your personal data for as long as reasonably necessary to fulfil the purposes we collected it for, including for the purposes of satisfying any legal, regulatory, tax, accounting or reporting requirements.
  rights:
  - right: Access
    text: Request access to your personal data (commonly known as a “data subject access request”).
  - right: Correction
    text: Request correction of the personal data that we hold about you.
  - right: Erasure
    text: Request erasure of your personal data.
  - right: Object to processing
    text: Object to processing of your personal data where we are relying on a legitimate interest
  - right: Restriction
    text: Request restriction of processing of your personal data.
  - right: Portability
    text: Request the transfer of your personal data to you or to a third party.
  - right: Withdraw consent
    text: Withdraw consent at any time where we are relying on consent to process your personal data.
  role:
    text: Where we process your personal data because you use our services as a result of your relationship with a customer who we supply our services to, we are not the data controller as we would be processing personal data on behalf of our customer as a data processor.
    value: both
  sale_or_sharing:
    stance: conditional
    text: We will get your express opt-in consent before we share your personal data with any third party for marketing purposes.
  subprocessors:
    text: '(c) our service providers acting as subcontractors or sub-processors which we use from time to time including, for example: (i) Google Analytics; and (ii) HubSpot CRM platform.'
    url: null
  transfers:
  - mechanism: adequacy
    text: We will only transfer your personal data to countries that have been deemed to provide an adequate level of protection for personal data.
  - mechanism: SCC
    text: Where we use certain service providers outside of the UK and/or the EEA (as applicable), we may use specific contracts approved for use in the UK and/or the EEA (as applicable) which give personal data the same protection it has in the UK and/or the EEA (as applicable).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BCB Group
provenance_date: '2026-11-09'
provider_name: BCB Group
provider_slug: bcb-group
slug: bcb-group-privacy-policy
source_date: '2026-11-09'
source_filename: bcb-group-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bcbgroup.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BCB Group\naid: bcb-group\nurl: https://www.bcbgroup.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Where we process your personal data because you use our services as a result of your relationship with a\n    customer who we supply our services to, we are not the data controller as we would be processing personal data\n    on behalf of our customer as a data processor.\ndata_categories:\n- category: identifying\n  text: Identity Data includes first name, last name, username or similar identifier, marital status, title, job\n    title, date of birth and gender.\n- category: contact\n\
  \  text: Contact Data includes billing address, email address and telephone numbers.\n- category: financial\n  text: Financial Data includes bank account and payment card details.\n- category: behavioral\n  text: Usage Data includes information about how you use our website, products, and services.\n- category: device\n  text: Technical Data includes internet protocol (IP) address, your login data, browser type and version, time\n    zone setting and location, browser plug-in types and versions, operating system and platform\npurposes:\n- purpose: Manage relationship with you\n  text: 'To manage our relationship with you which may include: (a)Notifying you about changes to our terms of privacy\n    policy (b)Asking you to leave a review or take a survey (c) Adding you to our mailing list'\n- purpose: Targeted advertising and marketing\n  text: We may provide you targeted advertisements or marketing communications we believe may be of interest to\n    you.\n- purpose: Website administration\
  \ and security\n  text: To administer and protect our business and our website (including troubleshooting, data analysis, testing,\n    system maintenance, support, reporting and hosting of data)\nretention:\n- scope: Personal data generally\n  period: null\n  text: We will only retain your personal data for as long as reasonably necessary to fulfil the purposes we collected\n    it for, including for the purposes of satisfying any legal, regulatory, tax, accounting or reporting requirements.\nresidency: []\ntransfers:\n- mechanism: adequacy\n  text: We will only transfer your personal data to countries that have been deemed to provide an adequate level\n    of protection for personal data.\n- mechanism: SCC\n  text: Where we use certain service providers outside of the UK and/or the EEA (as applicable), we may use specific\n    contracts approved for use in the UK and/or the EEA (as applicable) which give personal data the same protection\n    it has in the UK and/or the EEA (as applicable).\n\
  subprocessors:\n  url: null\n  text: '(c) our service providers acting as subcontractors or sub-processors which we use from time to time including,\n    for example: (i) Google Analytics; and (ii) HubSpot CRM platform.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact the privacy data manager\n  text: In some circumstances you can ask us to delete your data. Please see your legal rights below for further\n    information.\nrights:\n- right: Access\n  text: Request access to your personal data (commonly known as a “data subject access request”).\n- right: Correction\n  text: Request correction of the personal data that we hold about you.\n- right: Erasure\n  text: Request erasure of your personal data.\n- right: Object to processing\n  text: Object to processing of your personal data where we are relying on a legitimate interest\n- right: Restriction\n  text: Request restriction of processing of your personal data.\n- right: Portability\n  text: Request\
  \ the transfer of your personal data to you or to a third party.\n- right: Withdraw consent\n  text: Withdraw consent at any time where we are relying on consent to process your personal data.\nsale_or_sharing:\n  stance: conditional\n  text: We will get your express opt-in consent before we share your personal data with any third party for marketing\n    purposes.\n"
source_yaml_url: https://artifacts.apis.io/bcb-group/privacy/bcb-group-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from BCB Group's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Banking
- Digital Assets
- Stablecoins
- Financial Services
- Fintech
---
