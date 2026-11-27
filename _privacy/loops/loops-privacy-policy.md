---
api_specs:
- filename: loops-api-key-api-openapi.yml
  format: yaml
  label: Loops API key API
  slug: loops-api-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-api-key-api-openapi.yml
- filename: loops-audience-segments-api-openapi.yml
  format: yaml
  label: Loops Audience segments API
  slug: loops-audience-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-audience-segments-api-openapi.yml
- filename: loops-campaign-groups-api-openapi.yml
  format: yaml
  label: Loops Campaign groups API
  slug: loops-campaign-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-campaign-groups-api-openapi.yml
- filename: loops-campaigns-api-openapi.yml
  format: yaml
  label: Loops Campaigns API
  slug: loops-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-campaigns-api-openapi.yml
- filename: loops-components-api-openapi.yml
  format: yaml
  label: Loops Components API
  slug: loops-components-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-components-api-openapi.yml
- filename: loops-configuration-api-openapi.yml
  format: yaml
  label: Loops Configuration API
  slug: loops-configuration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-configuration-api-openapi.yml
- filename: loops-contact-properties-api-openapi.yml
  format: yaml
  label: Loops Contact properties API
  slug: loops-contact-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-contact-properties-api-openapi.yml
- filename: loops-contacts-api-openapi.yml
  format: yaml
  label: Loops Contacts API
  slug: loops-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-contacts-api-openapi.yml
- filename: loops-email-messages-api-openapi.yml
  format: yaml
  label: Loops Email messages API
  slug: loops-email-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-email-messages-api-openapi.yml
- filename: loops-event-patterns-api-openapi.yml
  format: yaml
  label: Loops Event patterns API
  slug: loops-event-patterns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-event-patterns-api-openapi.yml
- filename: loops-events-api-openapi.yml
  format: yaml
  label: Loops Events API
  slug: loops-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-events-api-openapi.yml
- filename: loops-mailing-lists-api-openapi.yml
  format: yaml
  label: Loops Mailing lists API
  slug: loops-mailing-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-mailing-lists-api-openapi.yml
- filename: loops-themes-api-openapi.yml
  format: yaml
  label: Loops Themes API
  slug: loops-themes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-themes-api-openapi.yml
- filename: loops-transactional-emails-api-openapi.yml
  format: yaml
  label: Loops Transactional emails API
  slug: loops-transactional-emails-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-transactional-emails-api-openapi.yml
- filename: loops-transactional-groups-api-openapi.yml
  format: yaml
  label: Loops Transactional groups API
  slug: loops-transactional-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-transactional-groups-api-openapi.yml
- filename: loops-uploads-api-openapi.yml
  format: yaml
  label: Loops Uploads API
  slug: loops-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-uploads-api-openapi.yml
- filename: loops-workflow-nodes-api-openapi.yml
  format: yaml
  label: Loops Workflow nodes API
  slug: loops-workflow-nodes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-workflow-nodes-api-openapi.yml
- filename: loops-workflows-api-openapi.yml
  format: yaml
  label: Loops Workflows API
  slug: loops-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-workflows-api-openapi.yml
- filename: loops-webhooks-asyncapi.yml
  format: yaml
  label: Loops Webhooks
  slug: loops-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/loops/asyncapi/loops-webhooks-asyncapi.yml
- filename: loops-webhooks-api-openapi.yml
  format: yaml
  label: Loops Webhooks API
  slug: loops-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/loops/openapi/loops-webhooks-api-openapi.yml
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account Information, such as email address, first name, and company or domain information
  - category: device
    text: the type of mobile device you use, your mobile device unique ID, the IP address of your mobile device
  - category: behavioral
    text: what webpages you accessed, and your interaction with website features
  - category: communication
    text: User Uploaded Content may include content containing Personal Data.
  - category: location
    text: Geolocation data Such as device location and IP location.
  - category: identifying
    source: https://loops.so/dpa
    text: Typical data may include names, email addresses, contact details, and other data supplied by the Data Controller for sending or managing emails.
  deletion:
    route: Email request to the company, or delete User Uploaded Content from account
    text: If you make this request, we will delete the Personal Data we hold about you as of the date of your request from our records and direct any service providers to do the same.
  dpa:
    available: true
    text: Customer contact and message data that Astrodon processes on your behalf as a processor is governed by the Data Processing Agreement
    url: null
  purposes:
  - purpose: provide and improve the Service
    text: We use your data to provide and improve the Service.
  - purpose: marketing communications
    text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials and other information that may be of interest to you regarding the Services or other Astrodon products and services.
  - purpose: machine learning on aggregated data
    text: We use such aggregated and/or anonymized data for machine learning to support and improve certain product features and functionality within the Service.
  - purpose: email scanning for spam and malicious links
    text: to ensure that your emails do not contain spam or malicious links
  - purpose: email-sending services and support
    source: https://loops.so/dpa
    text: The purpose of the processing is to offer and maintain email-sending services, troubleshoot issues, and provide related customer support.
  residency:
  - region: United States
    text: Astrodon is based in the United States but operates globally.
  retention:
  - period: twelve (12) months
    scope: account, billing, and support information (controller)
    text: account-associated Personal Data will be deleted within twelve (12) months after your account is deleted, deactivated, or terminated
  - period: thirty (30) days
    scope: customer contact and message data (processor)
    text: it is returned or securely deleted within thirty (30) days following termination of the Services or your written request
  - period: thirty (30) days
    scope: Personal Data on termination or request
    source: https://loops.so/dpa
    text: including customer contact and message data within thirty (30) days
  rights:
  - right: access, update or delete
    text: The right to access, update or to delete the information we have on you.
  - right: rectification
    text: The right of rectification.
  - right: object
    text: The right to object. You have the right to object to our processing of your Personal Data.
  - right: restriction
    text: The right of restriction.
  - right: data portability
    text: The right to data portability.
  - right: withdraw consent
    text: The right to withdraw consent.
  - right: erasure
    text: The right to erasure (“being forgotten”) of your Personal Data, under certain conditions.
  - right: complain to DPA
    text: You have the right to complain to a Data Protection Authority about our collection and use of your Personal Data.
  - right: access, rectification, deletion, restriction, portability
    source: https://loops.so/dpa
    text: The Data Processor will provide reasonable assistance to the Data Controller in responding to data subject requests (e.g., access, rectification, deletion, restriction, portability)
  role:
    text: We act as a processor for customer contact and message data that we process on our users’ behalf to provide the Services under the Data Processing Agreement. We act as a controller for account, billing, and support information that we process to manage our relationship with our users.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We don't sell or rent your Personal Data to any third parties for any purpose.
  subprocessors:
    text: We may share your Personal Data with third party vendors (or subprocessors) (collectively “ Service Providers ”) that help us operate our Services
    url: null
  transfers:
  - mechanism: SCC
    text: For transfers outside regions with strict data protection laws, such as the EU/EEA, we use Standard Contractual Clauses (SCCs) or other legal mechanisms to safeguard your data.
  - mechanism: DPF
    text: Astrodon complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S. DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.
  - mechanism: SCC
    source: https://loops.so/dpa
    text: Standard Contractual Clauses, reliance on recognized adequacy decisions, or other legally accepted mechanisms
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Loops
provenance_date: '2026-11-09'
provider_name: Loops
provider_slug: loops
slug: loops-privacy-policy
source_date: '2026-11-09'
source_filename: loops-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://loops.so/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Loops\naid: loops\nurl: https://loops.so/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://loops.so/dpa\n  - https://loops.so/privacy\nrole:\n  value: both\n  text: We act as a processor for customer contact and message data that we process on our users’ behalf to provide\n    the Services under the Data Processing Agreement. We act as a controller for account, billing, and support information\n    that we process to manage our relationship with our users.\ndata_categories:\n- category: identifying\n  text: Account Information, such as email address, first name, and company or domain information\n\
  - category: device\n  text: the type of mobile device you use, your mobile device unique ID, the IP address of your mobile device\n- category: behavioral\n  text: what webpages you accessed, and your interaction with website features\n- category: communication\n  text: User Uploaded Content may include content containing Personal Data.\n- category: location\n  text: Geolocation data Such as device location and IP location.\n- category: identifying\n  text: Typical data may include names, email addresses, contact details, and other data supplied by the Data Controller\n    for sending or managing emails.\n  source: https://loops.so/dpa\npurposes:\n- purpose: provide and improve the Service\n  text: We use your data to provide and improve the Service.\n- purpose: marketing communications\n  text: We may use your Personal Data to contact you with newsletters, marketing or promotional materials and other\n    information that may be of interest to you regarding the Services or other Astrodon\
  \ products and services.\n- purpose: machine learning on aggregated data\n  text: We use such aggregated and/or anonymized data for machine learning to support and improve certain product\n    features and functionality within the Service.\n- purpose: email scanning for spam and malicious links\n  text: to ensure that your emails do not contain spam or malicious links\n- purpose: email-sending services and support\n  text: The purpose of the processing is to offer and maintain email-sending services, troubleshoot issues, and\n    provide related customer support.\n  source: https://loops.so/dpa\nretention:\n- scope: account, billing, and support information (controller)\n  period: twelve (12) months\n  text: account-associated Personal Data will be deleted within twelve (12) months after your account is deleted,\n    deactivated, or terminated\n- scope: customer contact and message data (processor)\n  period: thirty (30) days\n  text: it is returned or securely deleted within thirty (30)\
  \ days following termination of the Services or your\n    written request\n- scope: Personal Data on termination or request\n  period: thirty (30) days\n  text: including customer contact and message data within thirty (30) days\n  source: https://loops.so/dpa\nresidency:\n- region: United States\n  text: Astrodon is based in the United States but operates globally.\ntransfers:\n- mechanism: SCC\n  text: For transfers outside regions with strict data protection laws, such as the EU/EEA, we use Standard Contractual\n    Clauses (SCCs) or other legal mechanisms to safeguard your data.\n- mechanism: DPF\n  text: Astrodon complies with the EU-U.S. Data Privacy Framework (EU-U.S. DPF) and the UK Extension to the EU-U.S.\n    DPF, and the Swiss-U.S. Data Privacy Framework (Swiss-U.S. DPF) as set forth by the U.S. Department of Commerce.\n- mechanism: SCC\n  text: Standard Contractual Clauses, reliance on recognized adequacy decisions, or other legally accepted mechanisms\n  source: https://loops.so/dpa\n\
  subprocessors:\n  url: null\n  text: We may share your Personal Data with third party vendors (or subprocessors) (collectively “ Service Providers\n    ”) that help us operate our Services\ndpa:\n  available: true\n  url: null\n  text: Customer contact and message data that Astrodon processes on your behalf as a processor is governed by the\n    Data Processing Agreement\ndeletion:\n  route: Email request to the company, or delete User Uploaded Content from account\n  text: If you make this request, we will delete the Personal Data we hold about you as of the date of your request\n    from our records and direct any service providers to do the same.\nrights:\n- right: access, update or delete\n  text: The right to access, update or to delete the information we have on you.\n- right: rectification\n  text: The right of rectification.\n- right: object\n  text: The right to object. You have the right to object to our processing of your Personal Data.\n- right: restriction\n  text: The right\
  \ of restriction.\n- right: data portability\n  text: The right to data portability.\n- right: withdraw consent\n  text: The right to withdraw consent.\n- right: erasure\n  text: The right to erasure (“being forgotten”) of your Personal Data, under certain conditions.\n- right: complain to DPA\n  text: You have the right to complain to a Data Protection Authority about our collection and use of your Personal\n    Data.\n- right: access, rectification, deletion, restriction, portability\n  text: The Data Processor will provide reasonable assistance to the Data Controller in responding to data subject\n    requests (e.g., access, rectification, deletion, restriction, portability)\n  source: https://loops.so/dpa\nsale_or_sharing:\n  stance: prohibited\n  text: We don't sell or rent your Personal Data to any third parties for any purpose.\n"
source_yaml_url: https://artifacts.apis.io/loops/privacy/loops-privacy-policy.yml
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
summary_line: 32 quoted statements, read from Loops's own page on 2026-11-09.
synthetic: false
tags:
- Email
- Email API
- Marketing Automation
- Transactional Email
- Lifecycle Email
- Webhook
- Software-as-a-Service
- Communications
- Developer Tools
- MCP
- Agents
- Campaigns
---
