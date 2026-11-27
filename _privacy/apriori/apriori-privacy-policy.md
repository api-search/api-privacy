---
api_specs:
- filename: apriori-agent-api-openapi.yml
  format: yaml
  label: aPriori Agent API
  slug: apriori-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apriori/openapi/apriori-agent-api-openapi.yml
- filename: apriori-workflow-api-openapi.yml
  format: yaml
  label: aPriori Workflow API
  slug: apriori-workflow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/apriori/openapi/apriori-workflow-api-openapi.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identifiers, such as your name, telephone number, physical and/or email addresses, account username, and account password.
  - category: contact
    text: Identifiers, such as your name, telephone number, physical and/or email addresses, account username, and account password.
  - category: financial
    text: Financial account information, such as payment information you provide when making a purchase of or through an offering
  - category: location
    text: Geolocation information,such as region, country, state, zip or postal code.
  - category: behavioral
    text: Internet or other electronic network activity information, such as the website domain visited; which activities and offerings are used, how, and for how long
  - category: device
    text: Electronic information, such as information about operating systems, device types, information about browsers, information relating to automatic updates and technical errors
  - category: professional
    text: Professional information, such as your occupation, industry, professional licenses, work experience and employment history, and other qualifications.
  - category: demographic
    text: Protected characteristics, such as your date of birth (where applicable).
  - category: health
    text: Information that may be deemed sensitive under applicable laws, such as usernames and passwords used to access your account, government identification numbers, and information regarding children under the age of 16 (or 13 where permitted by law).
  deletion:
    route: Email privacy@apriori.com
    text: To exercise the rights you may have, please contact us at privacy@apriori.com.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Deliver services and offerings
    text: To deliver services, products, and other offerings, including information such as insights and recommendations, as necessary to fulfill our contractual obligations.
  - purpose: Billing
    text: For billing or discount purposes.
  - purpose: Targeted advertising and marketing
    text: To deliver targeted advertising and send you promotional offers, advertising, or other marketing content in furtherance of our legitimate interest to engage in direct marketing or with consent as required by applicable law.
  - purpose: Training AI technology
    text: For benchmarking, data analysis, audits, developing new products, enhancing the aPriori services, facilitating product, software and applications development, improving our services, training AI technology used in our products, code testing, conducting research, analysis, studies or surveys, identifying usage trends, as well as for other analytics purposes.
  - purpose: Machine learning model training
    text: To test, develop, train, and improve our current and future technology offerings and your experience, including through the use of automated systems that analyze data using machine learning and other analytic techniques
  - purpose: Security and fraud prevention
    text: To detect, prevent, or otherwise address non-valid use such as through fraud and software piracy
  residency:
  - region: Global
    text: Because we and our service providers maintain servers in global locations, your Information may be transferred across national borders and stored on servers outside of your country or region.
  retention:
  - period: 7 years
    scope: Billing and transactional data
    text: Retention periods vary by category (e.g., billing and transactional data 7 years, marketing data 2–3 years, support logs 18–24 months).
  - period: 2–3 years
    scope: Marketing data
    text: Retention periods vary by category (e.g., billing and transactional data 7 years, marketing data 2–3 years, support logs 18–24 months).
  - period: 18–24 months
    scope: Support logs
    text: Retention periods vary by category (e.g., billing and transactional data 7 years, marketing data 2–3 years, support logs 18–24 months).
  - period: at least twenty-four (24) months
    scope: Account inactivity
    text: at least twenty-four (24) months after your account becomes inactive
  rights:
  - right: Access
    text: You have the right to access, update, delete, receive a copy of, or restrict our use of your Personal Data.
  - right: Withdraw consent
    text: 'When we process Personal Data based on your consent, you have the right to withdraw your consent at any time by emailing us at: privacy@apriori.com.'
  - right: Object to processing
    text: Object to our processing of your Personal Data
  - right: Portability
    text: Receive a copy of your Personal Data to transfer it to a third party
  - right: Opt out of targeted advertising
    text: Opt-out of targeted advertising
  - right: Non-discrimination
    text: Not be denied a good or service for exercising your rights
  - right: Complaint to authority
    text: Lodge a complaint with the relevant data protection authority in the jurisdiction in which you are located
  - right: Appeal
    text: Appeal any decision we may make regarding your requests.
  role:
    text: We also process Information on behalf of our customers subject to a written contract.
    value: both
  sale_or_sharing:
    stance: conditional
    text: aPriori does not exchange your Personal Data for money. However, some of the technologies we use to provide our offerings involve transfers of Personal Data that may be considered a “sale” under California law.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: aPriori complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
  - mechanism: SCC
    text: For transfers outside the EEA, UK, or other jurisdictions without adequacy decisions, we rely on Standard Contractual Clauses (SCCs), the UK IDTA or Addendum, and implement supplementary safeguards such as encryption and access controls.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: aPriori
provenance_date: '2026-11-09'
provider_name: aPriori
provider_slug: apriori
slug: apriori-privacy-policy
source_date: '2026-11-09'
source_filename: apriori-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.apriori.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: aPriori\naid: apriori\nurl: https://www.apriori.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\nrole:\n  value: both\n  text: We also process Information on behalf of our customers subject to a written contract.\ndata_categories:\n- category: identifying\n  text: Identifiers, such as your name, telephone number, physical and/or email addresses, account username, and\n    account password.\n- category: contact\n  text: Identifiers, such as your name, telephone number, physical and/or email addresses, account username, and\n    account password.\n- category: financial\n  text: Financial account\
  \ information, such as payment information you provide when making a purchase of or through\n    an offering\n- category: location\n  text: Geolocation information,such as region, country, state, zip or postal code.\n- category: behavioral\n  text: Internet or other electronic network activity information, such as the website domain visited; which activities\n    and offerings are used, how, and for how long\n- category: device\n  text: Electronic information, such as information about operating systems, device types, information about browsers,\n    information relating to automatic updates and technical errors\n- category: professional\n  text: Professional information, such as your occupation, industry, professional licenses, work experience and\n    employment history, and other qualifications.\n- category: demographic\n  text: Protected characteristics, such as your date of birth (where applicable).\n- category: health\n  text: Information that may be deemed sensitive under applicable\
  \ laws, such as usernames and passwords used to\n    access your account, government identification numbers, and information regarding children under the age of\n    16 (or 13 where permitted by law).\npurposes:\n- purpose: Deliver services and offerings\n  text: To deliver services, products, and other offerings, including information such as insights and recommendations,\n    as necessary to fulfill our contractual obligations.\n- purpose: Billing\n  text: For billing or discount purposes.\n- purpose: Targeted advertising and marketing\n  text: To deliver targeted advertising and send you promotional offers, advertising, or other marketing content\n    in furtherance of our legitimate interest to engage in direct marketing or with consent as required by applicable\n    law.\n- purpose: Training AI technology\n  text: For benchmarking, data analysis, audits, developing new products, enhancing the aPriori services, facilitating\n    product, software and applications development, improving\
  \ our services, training AI technology used in our products,\n    code testing, conducting research, analysis, studies or surveys, identifying usage trends, as well as for other\n    analytics purposes.\n- purpose: Machine learning model training\n  text: To test, develop, train, and improve our current and future technology offerings and your experience, including\n    through the use of automated systems that analyze data using machine learning and other analytic techniques\n- purpose: Security and fraud prevention\n  text: To detect, prevent, or otherwise address non-valid use such as through fraud and software piracy\nretention:\n- scope: Billing and transactional data\n  period: 7 years\n  text: Retention periods vary by category (e.g., billing and transactional data 7 years, marketing data 2–3 years,\n    support logs 18–24 months).\n- scope: Marketing data\n  period: 2–3 years\n  text: Retention periods vary by category (e.g., billing and transactional data 7 years, marketing data\
  \ 2–3 years,\n    support logs 18–24 months).\n- scope: Support logs\n  period: 18–24 months\n  text: Retention periods vary by category (e.g., billing and transactional data 7 years, marketing data 2–3 years,\n    support logs 18–24 months).\n- scope: Account inactivity\n  period: at least twenty-four (24) months\n  text: at least twenty-four (24) months after your account becomes inactive\nresidency:\n- region: Global\n  text: Because we and our service providers maintain servers in global locations, your Information may be transferred\n    across national borders and stored on servers outside of your country or region.\ntransfers:\n- mechanism: DPF\n  text: aPriori complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the Swiss-U.S. Data Privacy Framework\n    (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\n- mechanism: SCC\n  text: For transfers outside the EEA, UK, or other jurisdictions without adequacy decisions, we rely on Standard\n    Contractual\
  \ Clauses (SCCs), the UK IDTA or Addendum, and implement supplementary safeguards such as encryption\n    and access controls.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email privacy@apriori.com\n  text: To exercise the rights you may have, please contact us at privacy@apriori.com.\nrights:\n- right: Access\n  text: You have the right to access, update, delete, receive a copy of, or restrict our use of your Personal Data.\n- right: Withdraw consent\n  text: 'When we process Personal Data based on your consent, you have the right to withdraw your consent at any\n    time by emailing us at: privacy@apriori.com.'\n- right: Object to processing\n  text: Object to our processing of your Personal Data\n- right: Portability\n  text: Receive a copy of your Personal Data to transfer it to a third party\n- right: Opt out of targeted advertising\n  text: Opt-out of targeted advertising\n- right: Non-discrimination\n  text:\
  \ Not be denied a good or service for exercising your rights\n- right: Complaint to authority\n  text: Lodge a complaint with the relevant data protection authority in the jurisdiction in which you are located\n- right: Appeal\n  text: Appeal any decision we may make regarding your requests.\nsale_or_sharing:\n  stance: conditional\n  text: aPriori does not exchange your Personal Data for money. However, some of the technologies we use to provide\n    our offerings involve transfers of Personal Data that may be considered a “sale” under California law.\n"
source_yaml_url: https://artifacts.apis.io/apriori/privacy/apriori-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 33 quoted statements, read from aPriori's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Manufacturing
- product-cost-management
- design-for-manufacturability
- should-cost
- plm-integration
- cost-engineering
- Digital Manufacturing
- Sustainability
- Workflow Automation
- CAD
---
