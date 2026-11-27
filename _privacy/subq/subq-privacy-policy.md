---
api_specs:
- filename: subq-openapi-generated.yml
  format: yaml
  label: Subquadratic API
  slug: subq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/subq/openapi/_ae-authored/subq-openapi-generated.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: behavioral
    text: Usage Data. We collect information about your use of the Services, such as the types of content that you process, the features you use and the actions you take
  - category: device
    text: Device Information. We collect information about the device you use to access the Services, such as the name of the device, operating system, device identifiers, and browser you are using.
  - category: location
    text: We may determine the general area from which your device accesses our Services based on information like its IP address
  - category: communication
    text: If you communicate with us, such as via email, support requests, or our pages on social media sites, we may collect Personal Data like your name, contact information, and the contents of the messages you send
  - category: other
    text: User Content. We collect Personal Data that you provide in the input to our Services and that our Services generate in response ("Content").
  deletion:
    route: Account settings or email privacy@subq.ai
    text: You can exercise some of these rights through your Subquadratic account settings. If you are unable to exercise your rights through your account, please submit your request to privacy@subq.ai .
  dpa:
    available: true
    text: Our use of that data is governed by our customer agreements covering access to and use of those offerings, including our Data Processing Agreement (available at https://subq.ai/data-processing-agreement )
    url: https://subq.ai/data-processing-agreement
  purposes:
  - purpose: Provide, analyze, and maintain Services
    text: To provide, analyze, and maintain our Services, for example to process your prompts and generate completions through our foundational models
  - purpose: Improve and develop Services and research
    text: To improve and develop our Services and conduct research, for example to enhance model performance, improve accuracy and quality, and develop new features (subject to the limitations on the use of Content described below)
  - purpose: Content moderation and misuse detection
    text: To review, classify, and moderate Content in order to detect and prevent violations of our Usage Policy and other misuse of our Services
  - purpose: Fraud and security
    text: To prevent fraud, illegal activity, or misuses of our Services, and to protect the security of our systems and Services
  residency:
  - region: United States
    text: processing and storing your Personal Data in our facilities and servers in the United States
  retention:
  - period: sixty (60) days
    scope: Content
    text: We retain Content, including related safety classification results, for no more than sixty (60) days after processing
  - period: sixty (60) days
    scope: Deleted account data
    text: If you delete your account, we delete your Content and other Personal Data associated with it within sixty (60) days, except for records we are required to keep by law, such as billing and tax records.
  rights:
  - right: Access
    text: Access your Personal Data and information relating to how it is processed
  - right: Delete
    text: Delete your Personal Data from our records
  - right: Correct
    text: Update or correct your Personal Data
  - right: Portability
    text: Transfer your Personal Data to a third party (right to data portability)
  - right: Object or restrict
    text: Restrict how we process your Personal Data
  - right: Withdraw consent
    text: Withdraw your consent—where we rely on consent as the legal basis for processing at any time
  - right: Appeal
    text: Depending on where you live, you may have the right to appeal a decision we make relating to requests to exercise your rights.
  role:
    text: We at Subquadratic Inc. (together with our affiliates, "Subquadratic", "we", "our" or "us") respect your privacy
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We don't "sell" Personal Data or "share" Personal Data for cross-contextual behavioral advertising
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: only transfer that data pursuant to legally valid transfer mechanisms such as Standard Contractual Clauses approved by the European Commission
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Subquadratic
provenance_date: '2026-11-10'
provider_name: Subquadratic
provider_slug: subq
slug: subq-privacy-policy
source_date: '2026-11-10'
source_filename: subq-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://subq.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Subquadratic\naid: subq\nurl: https://subq.ai/privacy-policy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We at Subquadratic Inc. (together with our affiliates, \"Subquadratic\", \"we\", \"our\" or \"us\") respect your\n    privacy\ndata_categories:\n- category: behavioral\n  text: Usage Data. We collect information about your use of the Services, such as the types of content that you\n    process, the features you use and the actions you take\n- category: device\n  text: Device Information. We collect information about the device you use to access the Services, such as the\n    name of\
  \ the device, operating system, device identifiers, and browser you are using.\n- category: location\n  text: We may determine the general area from which your device accesses our Services based on information like\n    its IP address\n- category: communication\n  text: If you communicate with us, such as via email, support requests, or our pages on social media sites, we\n    may collect Personal Data like your name, contact information, and the contents of the messages you send\n- category: other\n  text: User Content. We collect Personal Data that you provide in the input to our Services and that our Services\n    generate in response (\"Content\").\npurposes:\n- purpose: Provide, analyze, and maintain Services\n  text: To provide, analyze, and maintain our Services, for example to process your prompts and generate completions\n    through our foundational models\n- purpose: Improve and develop Services and research\n  text: To improve and develop our Services and conduct research,\
  \ for example to enhance model performance, improve\n    accuracy and quality, and develop new features (subject to the limitations on the use of Content described below)\n- purpose: Content moderation and misuse detection\n  text: To review, classify, and moderate Content in order to detect and prevent violations of our Usage Policy\n    and other misuse of our Services\n- purpose: Fraud and security\n  text: To prevent fraud, illegal activity, or misuses of our Services, and to protect the security of our systems\n    and Services\nretention:\n- scope: Content\n  period: sixty (60) days\n  text: We retain Content, including related safety classification results, for no more than sixty (60) days after\n    processing\n- scope: Deleted account data\n  period: sixty (60) days\n  text: If you delete your account, we delete your Content and other Personal Data associated with it within sixty\n    (60) days, except for records we are required to keep by law, such as billing and tax records.\n\
  residency:\n- region: United States\n  text: processing and storing your Personal Data in our facilities and servers in the United States\ntransfers:\n- mechanism: SCC\n  text: only transfer that data pursuant to legally valid transfer mechanisms such as Standard Contractual Clauses\n    approved by the European Commission\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: https://subq.ai/data-processing-agreement\n  text: Our use of that data is governed by our customer agreements covering access to and use of those offerings,\n    including our Data Processing Agreement (available at https://subq.ai/data-processing-agreement )\ndeletion:\n  route: Account settings or email privacy@subq.ai\n  text: You can exercise some of these rights through your Subquadratic account settings. If you are unable to exercise\n    your rights through your account, please submit your request to privacy@subq.ai .\nrights:\n- right: Access\n  text: Access your Personal Data and information\
  \ relating to how it is processed\n- right: Delete\n  text: Delete your Personal Data from our records\n- right: Correct\n  text: Update or correct your Personal Data\n- right: Portability\n  text: Transfer your Personal Data to a third party (right to data portability)\n- right: Object or restrict\n  text: Restrict how we process your Personal Data\n- right: Withdraw consent\n  text: Withdraw your consent—where we rely on consent as the legal basis for processing at any time\n- right: Appeal\n  text: Depending on where you live, you may have the right to appeal a decision we make relating to requests to\n    exercise your rights.\nsale_or_sharing:\n  stance: prohibited\n  text: We don't \"sell\" Personal Data or \"share\" Personal Data for cross-contextual behavioral advertising\n"
source_yaml_url: https://artifacts.apis.io/subq/privacy/subq-privacy-policy.yml
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
summary_line: 24 quoted statements, read from Subquadratic's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Enterprise
- Decision Models
- Long Context
---
