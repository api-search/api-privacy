---
api_specs:
- filename: graphql-api
  format: yaml
  label: The Brief Public GraphQL API
  slug: the-brief-public-graphql-api
  spec_type: Postman
  url: https://www.postman.com/thebrieftechnical/the-brief-api/collection/1lfct1g/graphql-api
- filename: creatopy-com-openapi-generated.yml
  format: yaml
  label: TheBrief API
  slug: creatopy-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/thebrief/openapi/_ae-authored/creatopy-com-openapi-generated.yml
claim_count: 33
description: ''
doc:
  data_categories:
  - category: contact
    text: Name, email address, phone number, mailing or billing address, job title, and social media profile (if you choose to provide them).
  - category: identifying
    text: Username and encrypted password.
  - category: financial
    text: Payment information and transaction history.
  - category: communication
    text: Records of your communications with us (emails, chat, support tickets, survey responses)
  - category: behavioral
    text: Pages visited, time spent, links clicked, and referring webpage.
  - category: device
    text: IP address, operating system, browser type, device identifiers, and geo-location data (if enabled on your device).
  - category: health
    text: We generally do not seek to collect sensitive data as defined under relevant laws (such as data about race, health, biometrics, or sexual orientation)
  deletion:
    route: Email privacy@thebrief.ai or close your account
    text: If you close your account, we will delete, deidentify or anonymize your data within a reasonable period, except as required to retain for legal reasons.
  dpa:
    available: true
    text: Please refer to our Data Processing Addendum , which includes a list of our sub-processors, for more information.
    url: null
  purposes:
  - purpose: Provide and maintain the Services
    text: We use data to create and manage your account, authenticate you, provide customer support, and operate the core functionality of our platform.
  - purpose: Improve and develop Services
    text: We use data (especially aggregated or de-identified data) to debug issues, run analytics, conduct research, and develop new features.
  - purpose: Train AI features
    text: We may also use your content to provide, improve and customize the Services including to train AI features in order to improve our Service.
  - purpose: Personalize experience
    text: We may tailor the content and advertisements you see on our Services to your interests.
  - purpose: Marketing
    text: If you sign up, we may send newsletters, product updates, and special offers.
  - purpose: Security and fraud prevention
    text: To monitor, prevent, and detect fraud, abuse, illegal uses, and violations of our Terms of Use and Business Subscription Terms of Service.
  residency:
  - region: United States
    text: We primarily store data in the United States.
  retention:
  - period: ninety (90) days
    scope: Account and usage logs
    text: Retained for up to ninety (90) days after the user’s last activity to support security, analytics, and customer service.
  - period: three (3) years
    scope: Marketing leads
    text: 'Marketing leads : Retained for up to three (3) years after the last engagement (e.g., email open, form submission), unless you opt out earlier.'
  - period: three (3) years
    scope: Support communications
    text: 'Support communications : Stored for up to three (3) years, depending on the nature of the inquiry and applicable laws.'
  - period: ninety (90) days
    scope: Interaction data
    text: 'Interaction data : Retained for up to ninety (90) days, unless otherwise specified by tool configuration or legal obligation.'
  - period: seven (7) years
    scope: Legal obligations (transaction records)
    text: transaction records may be kept for accounting/tax statutory retention periods, typically seven (7) years in some jurisdictions.
  rights:
  - right: Access and portability
    text: You can request a copy of the Personal Data we hold about you, and information on how we use it.
  - right: Correction
    text: If any of your Personal Data held by us is inaccurate, outdated, or incomplete, you have the right to request that we correct or update it.
  - right: Deletion
    text: Depending on where you reside, you may have the right to request that we delete your Personal Data, and we will do so unless an exemption applies.
  - right: Objection and restriction
    text: If we process your data based on legitimate interests, you can object to that processing, depending on where you reside.
  - right: Withdraw consent
    text: Where we rely on your consent (e.g., for marketing or certain data uses), you have the right to withdraw that consent at any time.
  - right: Opt out of sale/sharing
    text: Under certain U.S. state laws, you have the right to opt out of the “sale” or “sharing” of your personal information.
  - right: Complaint
    text: If you are located in the European Union (EU) or European Economic Area (EEA), you have the right under the GDPR to file a complaint with the data protection supervisory authority in your country of residence
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell Personal Data to third parties for monetary consideration. However, we may share Personal Data with certain trusted entities, as outlined below
  subprocessors:
    text: Please refer to our Data Processing Addendum , which includes a list of our sub-processors, for more information.
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs) : For transfers to countries without an adequacy decision (e.g., the U.S.), we use the European Commission’s Standard Contractual Clauses as a lawful transfer mechanism.'
  - mechanism: adequacy
    text: 'Adequacy : Where possible, we rely on countries or recipients that have been deemed to provide an “adequate” level of protection by the European Commission (GDPR Article 45).'
  - mechanism: other
    text: 'Binding Corporate Rules (BCRs) : At this time, we do not rely on BCRs, but if we adopt BCRs for intra-group transfers in the future, we will reflect that here.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TheBrief
provenance_date: '2026-11-10'
provider_name: TheBrief
provider_slug: thebrief
slug: thebrief-privacy-policy
source_date: '2026-11-10'
source_filename: thebrief-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.thebrief.ai/legal-information/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TheBrief\naid: thebrief\nurl: https://www.thebrief.ai/legal-information/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Name, email address, phone number, mailing or billing address, job title, and social media profile (if you\n    choose to provide them).\n- category: identifying\n  text: Username and encrypted password.\n- category: financial\n  text: Payment information and transaction history.\n- category: communication\n  text: Records of your communications with us (emails, chat, support tickets, survey responses)\n- category:\
  \ behavioral\n  text: Pages visited, time spent, links clicked, and referring webpage.\n- category: device\n  text: IP address, operating system, browser type, device identifiers, and geo-location data (if enabled on your\n    device).\n- category: health\n  text: We generally do not seek to collect sensitive data as defined under relevant laws (such as data about race,\n    health, biometrics, or sexual orientation)\npurposes:\n- purpose: Provide and maintain the Services\n  text: We use data to create and manage your account, authenticate you, provide customer support, and operate the\n    core functionality of our platform.\n- purpose: Improve and develop Services\n  text: We use data (especially aggregated or de-identified data) to debug issues, run analytics, conduct research,\n    and develop new features.\n- purpose: Train AI features\n  text: We may also use your content to provide, improve and customize the Services including to train AI features\n    in order to improve our Service.\n\
  - purpose: Personalize experience\n  text: We may tailor the content and advertisements you see on our Services to your interests.\n- purpose: Marketing\n  text: If you sign up, we may send newsletters, product updates, and special offers.\n- purpose: Security and fraud prevention\n  text: To monitor, prevent, and detect fraud, abuse, illegal uses, and violations of our Terms of Use and Business\n    Subscription Terms of Service.\nretention:\n- scope: Account and usage logs\n  period: ninety (90) days\n  text: Retained for up to ninety (90) days after the user’s last activity to support security, analytics, and customer\n    service.\n- scope: Marketing leads\n  period: three (3) years\n  text: 'Marketing leads : Retained for up to three (3) years after the last engagement (e.g., email open, form\n    submission), unless you opt out earlier.'\n- scope: Support communications\n  period: three (3) years\n  text: 'Support communications : Stored for up to three (3) years, depending on the\
  \ nature of the inquiry and applicable\n    laws.'\n- scope: Interaction data\n  period: ninety (90) days\n  text: 'Interaction data : Retained for up to ninety (90) days, unless otherwise specified by tool configuration\n    or legal obligation.'\n- scope: Legal obligations (transaction records)\n  period: seven (7) years\n  text: transaction records may be kept for accounting/tax statutory retention periods, typically seven (7) years\n    in some jurisdictions.\nresidency:\n- region: United States\n  text: We primarily store data in the United States.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs) : For transfers to countries without an adequacy decision (e.g., the\n    U.S.), we use the European Commission’s Standard Contractual Clauses as a lawful transfer mechanism.'\n- mechanism: adequacy\n  text: 'Adequacy : Where possible, we rely on countries or recipients that have been deemed to provide an “adequate”\n    level of protection by the European Commission\
  \ (GDPR Article 45).'\n- mechanism: other\n  text: 'Binding Corporate Rules (BCRs) : At this time, we do not rely on BCRs, but if we adopt BCRs for intra-group\n    transfers in the future, we will reflect that here.'\nsubprocessors:\n  url: null\n  text: Please refer to our Data Processing Addendum , which includes a list of our sub-processors, for more information.\ndpa:\n  available: true\n  url: null\n  text: Please refer to our Data Processing Addendum , which includes a list of our sub-processors, for more information.\ndeletion:\n  route: Email privacy@thebrief.ai or close your account\n  text: If you close your account, we will delete, deidentify or anonymize your data within a reasonable period,\n    except as required to retain for legal reasons.\nrights:\n- right: Access and portability\n  text: You can request a copy of the Personal Data we hold about you, and information on how we use it.\n- right: Correction\n  text: If any of your Personal Data held by us is inaccurate,\
  \ outdated, or incomplete, you have the right to request\n    that we correct or update it.\n- right: Deletion\n  text: Depending on where you reside, you may have the right to request that we delete your Personal Data, and\n    we will do so unless an exemption applies.\n- right: Objection and restriction\n  text: If we process your data based on legitimate interests, you can object to that processing, depending on where\n    you reside.\n- right: Withdraw consent\n  text: Where we rely on your consent (e.g., for marketing or certain data uses), you have the right to withdraw\n    that consent at any time.\n- right: Opt out of sale/sharing\n  text: Under certain U.S. state laws, you have the right to opt out of the “sale” or “sharing” of your personal\n    information.\n- right: Complaint\n  text: If you are located in the European Union (EU) or European Economic Area (EEA), you have the right under\n    the GDPR to file a complaint with the data protection supervisory authority in your\
  \ country of residence\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell Personal Data to third parties for monetary consideration. However, we may share Personal\n    Data with certain trusted entities, as outlined below\n"
source_yaml_url: https://artifacts.apis.io/thebrief/privacy/thebrief-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 33 quoted statements, read from TheBrief's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Creative
- Design
- Artificial Intelligence
- Marketing
- Ad Serving
- Software-as-a-Service
- GraphQL
- Creative Automation
- Digital Asset Management
- Webhook
- Platform
---
