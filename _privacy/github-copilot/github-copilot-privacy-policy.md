---
api_specs:
- filename: github-copilot-copilot-api-openapi.yml
  format: yaml
  label: GitHub Copilot Copilot API
  slug: github-copilot-copilot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-copilot-api-openapi.yml
- filename: github-copilot-copilot-spaces-api-openapi.yml
  format: yaml
  label: GitHub Copilot Copilot Spaces API
  slug: github-copilot-copilot-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-copilot-spaces-api-openapi.yml
- filename: github-copilot-merge-queue-api-openapi.yml
  format: yaml
  label: GitHub Copilot Merge Queue API
  slug: github-copilot-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-merge-queue-api-openapi.yml
- filename: github-copilot-pulls-api-openapi.yml
  format: yaml
  label: GitHub Copilot Pulls API
  slug: github-copilot-pulls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-pulls-api-openapi.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Data: We collect certain information when you open an account such as your GitHub handle, name, email address, password, payment information and transaction information.'
  - category: contact
    text: 'Sales and Marketing Data: This includes information provided for promotional communications, such as name, email address, and company name.'
  - category: financial
    text: 'Payment Information: For paid subscriptions, we collect details like name, billing address, and payment specifics.'
  - category: behavioral
    text: 'Website Usage Data: We automatically log data about your Website interactions, including the referring site, date and time of visit, pages viewed, and links clicked.'
  - category: device
    text: 'Service Usage Information: We collect data about your interactions with the Services, such as IP address, device information, session details, date and time of requests, device type and ID, operating system and application version'
  - category: location
    text: 'Geolocation Information: Depending on the Service''s functionality, we collect regional geolocation data.'
  - category: demographic
    text: 'Demographic information: In some cases, you provide us with ethnicity, gender, or similar demographic details.'
  - category: communication
    text: 'User Content and Files: When you use our Services, we collect Personal Data included as part of the information you provide such as code, inputs, AI outputs, text, documents, images, or feedback.'
  deletion:
    route: Email privacy[at]github[dot]com or submit a request
    text: Upon receiving your verified request, we will promptly delete your personal information (unless an exception applies), and instruct our service providers to do the same.
  dpa:
    available: true
    text: You can review our standard Data Protection Agreement at GitHub Data Protection Agreement
    url: https://docs.github.com/en/site-policy/privacy-policies/github-data-protection-agreement
  purposes:
  - purpose: Product development and improvement
    text: We use Personal Data to develop and improve our products, services, and technologies, including artificial intelligence and machine learning technologies.
  - purpose: Training models
    text: This includes improving features, developing new offerings, enhancing safety and security capabilities, and training models.
  - purpose: Service provision
    text: We use Personal Data to deliver and update our Services as configured and used by You
  - purpose: Safety and security
    text: To promote safety, integrity, and security across our Services, we process Personal Data, using both automated and, at times, manual techniques for abuse detection, prevention, and violations of terms of service.
  - purpose: Personalization and advertising
    text: 'Personalization: We use Personal Data to customize the Service to your preferences, to evaluate the effectiveness of enterprise business ads and promotional communications'
  residency:
  - region: Multiple locations
    text: GitHub stores and processes Personal Data in a variety of locations, including your local region, the United States, and other countries where GitHub, its affiliates, subsidiaries, or subprocessors have operations.
  retention:
  - period: null
    scope: Account and contractual data
    text: We’ll retain your Personal Data as long as your account is active and as needed to fulfill contractual obligations, comply with legal requirements, resolve disputes, and enforce agreements.
  rights:
  - right: Access
    text: The right to access the data collected about you
  - right: Rectification
    text: The right to rectify or update inaccurate or incomplete Personal Data under certain circumstances
  - right: Erasure
    text: The right to erase or limit the processing of your Personal Data under specific conditions
  - right: Objection
    text: The right to object to the processing of your Personal Data, as allowed by applicable law
  - right: Withdraw consent
    text: The right to withdraw consent, where processing is based on your consent
  - right: Portability
    text: The right to receive your collected Personal Data in a structured, commonly used, and machine-readable format
  role:
    text: the Personal Data that GitHub, Inc. or GitHub B.V., processes as the “Data Controller” when you interact with websites, applications, and services that display this Statement
    value: controller
  sale_or_sharing:
    stance: conditional
    text: 'As defined by applicable law, we “shared” the following categories of personal information in the last 12 months: identifiers/contact information, Internet or other electronic network activity information, and inferences drawn from the above.'
  subprocessors:
    text: Please visit GitHub Subprocessors to see our list of Subprocessors.
    url: https://docs.github.com/en/site-policy/privacy-policies/github-subprocessors
  transfers:
  - mechanism: SCC
    text: When we engage in such transfers, we generally rely on the standard contractual clauses published by the European Commission under Commission Implementing Decision 2021/914
  - mechanism: DPF
    text: GitHub also complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GitHub Copilot
provenance_date: '2026-11-09'
provider_name: GitHub Copilot
provider_slug: github-copilot
slug: github-copilot-privacy-policy
source_date: '2026-11-09'
source_filename: github-copilot-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GitHub Copilot\naid: github-copilot\nurl: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: the Personal Data that GitHub, Inc. or GitHub B.V., processes as the “Data Controller” when you interact\n    with websites, applications, and services that display this Statement\ndata_categories:\n- category: identifying\n  text: 'Account Data: We collect certain information when you open an account such as your GitHub handle, name,\n    email address, password, payment information and transaction information.'\n\
  - category: contact\n  text: 'Sales and Marketing Data: This includes information provided for promotional communications, such as name,\n    email address, and company name.'\n- category: financial\n  text: 'Payment Information: For paid subscriptions, we collect details like name, billing address, and payment\n    specifics.'\n- category: behavioral\n  text: 'Website Usage Data: We automatically log data about your Website interactions, including the referring\n    site, date and time of visit, pages viewed, and links clicked.'\n- category: device\n  text: 'Service Usage Information: We collect data about your interactions with the Services, such as IP address,\n    device information, session details, date and time of requests, device type and ID, operating system and application\n    version'\n- category: location\n  text: 'Geolocation Information: Depending on the Service''s functionality, we collect regional geolocation data.'\n- category: demographic\n  text: 'Demographic information:\
  \ In some cases, you provide us with ethnicity, gender, or similar demographic details.'\n- category: communication\n  text: 'User Content and Files: When you use our Services, we collect Personal Data included as part of the information\n    you provide such as code, inputs, AI outputs, text, documents, images, or feedback.'\npurposes:\n- purpose: Product development and improvement\n  text: We use Personal Data to develop and improve our products, services, and technologies, including artificial\n    intelligence and machine learning technologies.\n- purpose: Training models\n  text: This includes improving features, developing new offerings, enhancing safety and security capabilities,\n    and training models.\n- purpose: Service provision\n  text: We use Personal Data to deliver and update our Services as configured and used by You\n- purpose: Safety and security\n  text: To promote safety, integrity, and security across our Services, we process Personal Data, using both automated\n\
  \    and, at times, manual techniques for abuse detection, prevention, and violations of terms of service.\n- purpose: Personalization and advertising\n  text: 'Personalization: We use Personal Data to customize the Service to your preferences, to evaluate the effectiveness\n    of enterprise business ads and promotional communications'\nretention:\n- scope: Account and contractual data\n  period: null\n  text: We’ll retain your Personal Data as long as your account is active and as needed to fulfill contractual obligations,\n    comply with legal requirements, resolve disputes, and enforce agreements.\nresidency:\n- region: Multiple locations\n  text: GitHub stores and processes Personal Data in a variety of locations, including your local region, the United\n    States, and other countries where GitHub, its affiliates, subsidiaries, or subprocessors have operations.\ntransfers:\n- mechanism: SCC\n  text: When we engage in such transfers, we generally rely on the standard contractual\
  \ clauses published by the\n    European Commission under Commission Implementing Decision 2021/914\n- mechanism: DPF\n  text: GitHub also complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF), the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF)\nsubprocessors:\n  url: https://docs.github.com/en/site-policy/privacy-policies/github-subprocessors\n  text: Please visit GitHub Subprocessors to see our list of Subprocessors.\ndpa:\n  available: true\n  url: https://docs.github.com/en/site-policy/privacy-policies/github-data-protection-agreement\n  text: You can review our standard Data Protection Agreement at GitHub Data Protection Agreement\ndeletion:\n  route: Email privacy[at]github[dot]com or submit a request\n  text: Upon receiving your verified request, we will promptly delete your personal information (unless an exception\n    applies), and instruct our service providers to do the same.\nrights:\n- right: Access\n  text: The right\
  \ to access the data collected about you\n- right: Rectification\n  text: The right to rectify or update inaccurate or incomplete Personal Data under certain circumstances\n- right: Erasure\n  text: The right to erase or limit the processing of your Personal Data under specific conditions\n- right: Objection\n  text: The right to object to the processing of your Personal Data, as allowed by applicable law\n- right: Withdraw consent\n  text: The right to withdraw consent, where processing is based on your consent\n- right: Portability\n  text: The right to receive your collected Personal Data in a structured, commonly used, and machine-readable format\nsale_or_sharing:\n  stance: conditional\n  text: 'As defined by applicable law, we “shared” the following categories of personal information in the last\n    12 months: identifiers/contact information, Internet or other electronic network activity information, and inferences\n    drawn from the above.'\n"
source_yaml_url: https://artifacts.apis.io/github-copilot/privacy/github-copilot-privacy-policy.yml
stated_fields:
- role
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
summary_line: 28 quoted statements, read from GitHub Copilot's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Artificial Intelligence
- Code Generation
- Code Review
- Coding Agents
- Custom Instructions
- Developer Tools
- Extensions
- IDE
- Machine Learning
- MCP
- Metrics
- Productivity
---
