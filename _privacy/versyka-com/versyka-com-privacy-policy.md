---
api_specs:
- filename: versyka-com-openapi-generated.yml
  format: yaml
  label: versyka-com API
  slug: versyka-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/versyka-com/openapi/_ae-authored/versyka-com-openapi-generated.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: names email addresses contact preferences company name
  - category: financial
    text: we keep only your billing email, your name as you entered it at checkout, your plan, subscription status and the end date of your current billing period
  - category: device
    text: device and usage information, such as your IP address, browser and device characteristics, operating system, language preferences, referring URLs, device name, country, location
  - category: behavioral
    text: settings and information about your activity in the Services (such as the date/time stamps associated with your usage, pages and files viewed, searches, and other actions you take
  - category: professional
    text: repository information (repository names, file paths, pull request links)
  - category: health
    text: We do not process sensitive personal information.
  deletion:
    route: Email karthik@versyka.com or uninstall the Versyka GitHub App
    text: You can ask us to delete any of this information at any time by emailing karthik@versyka.com, and we will do so within 30 days, except where the law requires us to keep it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, improve and administer services
    text: We process your information to provide, improve, and administer our Services, communicate with you, for security and fraud prevention, and to comply with law.
  - purpose: Fraud monitoring and security
    text: To protect our Services. We may process your information as part of our efforts to keep our Services safe and secure, including fraud monitoring and prevention.
  - purpose: Identify usage trends
    text: To identify usage trends. We may process information about how you use our Services to better understand how they are being used so we can improve them.
  retention:
  - period: null
    scope: Account and migration records
    text: When you uninstall the Versyka GitHub App, your Versyka account and the records tied to it are deleted right away
  - period: null
    scope: Billing records
    text: billing records, for as long as tax and accounting law requires
  - period: 30 days
    scope: Encrypted database backups
    text: Encrypted database backups are kept for up to 30 days and then deleted.
  - period: 30 days
    scope: Build and test output
    text: build and test output is deleted after 30 days
  - period: 7 days
    scope: Unconfirmed SDK alert requests
    text: Unconfirmed requests are deleted after 7 days.
  rights:
  - right: Access
    text: Right to access your personal data
  - right: Correction
    text: Right to correct inaccuracies in your personal data
  - right: Deletion
    text: Right to request the deletion of your personal data
  - right: Portability
    text: Right to obtain a copy of the personal data you previously shared with us
  - right: Opt out of targeted advertising, sale, profiling
    text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions that produce legal or similarly significant effects ("profiling")
  role:
    text: We are responsible for making decisions about how your personal information is processed.
    value: controller
  sale_or_sharing:
    stance: unstated
    text: We have not sold or shared any personal information to third parties for a business or commercial purpose in the preceding twelve (12) months.
  subprocessors:
    text: We have contracts in place with our third parties, which are designed to help safeguard your personal information.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: versyka-com
provenance_date: '2026-11-10'
provider_name: versyka-com
provider_slug: versyka-com
slug: versyka-com-privacy-policy
source_date: '2026-11-10'
source_filename: versyka-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.versyka.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: versyka-com\naid: versyka-com\nurl: https://www.versyka.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We are responsible for making decisions about how your personal information is processed.\ndata_categories:\n- category: identifying\n  text: names email addresses contact preferences company name\n- category: financial\n  text: we keep only your billing email, your name as you entered it at checkout, your plan, subscription status\n    and the end date of your current billing period\n- category: device\n  text: device and usage information, such as your IP address, browser and\
  \ device characteristics, operating system,\n    language preferences, referring URLs, device name, country, location\n- category: behavioral\n  text: settings and information about your activity in the Services (such as the date/time stamps associated with\n    your usage, pages and files viewed, searches, and other actions you take\n- category: professional\n  text: repository information (repository names, file paths, pull request links)\n- category: health\n  text: We do not process sensitive personal information.\npurposes:\n- purpose: Provide, improve and administer services\n  text: We process your information to provide, improve, and administer our Services, communicate with you, for\n    security and fraud prevention, and to comply with law.\n- purpose: Fraud monitoring and security\n  text: To protect our Services. We may process your information as part of our efforts to keep our Services safe\n    and secure, including fraud monitoring and prevention.\n- purpose: Identify usage\
  \ trends\n  text: To identify usage trends. We may process information about how you use our Services to better understand\n    how they are being used so we can improve them.\nretention:\n- scope: Account and migration records\n  period: null\n  text: When you uninstall the Versyka GitHub App, your Versyka account and the records tied to it are deleted right\n    away\n- scope: Billing records\n  period: null\n  text: billing records, for as long as tax and accounting law requires\n- scope: Encrypted database backups\n  period: 30 days\n  text: Encrypted database backups are kept for up to 30 days and then deleted.\n- scope: Build and test output\n  period: 30 days\n  text: build and test output is deleted after 30 days\n- scope: Unconfirmed SDK alert requests\n  period: 7 days\n  text: Unconfirmed requests are deleted after 7 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: We have contracts in place with our third parties, which are designed to help safeguard\
  \ your personal information.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email karthik@versyka.com or uninstall the Versyka GitHub App\n  text: You can ask us to delete any of this information at any time by emailing karthik@versyka.com, and we will\n    do so within 30 days, except where the law requires us to keep it.\nrights:\n- right: Access\n  text: Right to access your personal data\n- right: Correction\n  text: Right to correct inaccuracies in your personal data\n- right: Deletion\n  text: Right to request the deletion of your personal data\n- right: Portability\n  text: Right to obtain a copy of the personal data you previously shared with us\n- right: Opt out of targeted advertising, sale, profiling\n  text: Right to opt out of the processing of your personal data if it is used for targeted advertising (or sharing\n    as defined under California’s privacy law), the sale of personal data, or profiling in furtherance of decisions\n    that produce legal\
  \ or similarly significant effects (\"profiling\")\nsale_or_sharing:\n  stance: unstated\n  text: We have not sold or shared any personal information to third parties for a business or commercial purpose\n    in the preceding twelve (12) months.\n"
source_yaml_url: https://artifacts.apis.io/versyka-com/privacy/versyka-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 22 quoted statements, read from versyka-com's own page on 2026-11-10.
synthetic: false
tags:
- API Monitoring
- Developer Tools
- Automation
- Change Management
- Open Source
---
