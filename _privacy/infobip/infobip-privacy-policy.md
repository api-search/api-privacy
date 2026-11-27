---
api_specs:
- filename: infobip-ai-hub-api-openapi.yml
  format: yaml
  label: Infobip AI Hub API
  slug: infobip-ai-hub-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-ai-hub-api-openapi.yml
- filename: infobip-channels-api-openapi.yml
  format: yaml
  label: Infobip Channels API
  slug: infobip-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-channels-api-openapi.yml
- filename: infobip-connectivity-api-openapi.yml
  format: yaml
  label: Infobip Connectivity API
  slug: infobip-connectivity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-connectivity-api-openapi.yml
- filename: infobip-customer-engagement-api-openapi.yml
  format: yaml
  label: Infobip Customer Engagement API
  slug: infobip-customer-engagement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-customer-engagement-api-openapi.yml
- filename: infobip-platform-api-openapi.yml
  format: yaml
  label: Infobip Platform API
  slug: infobip-platform-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-platform-api-openapi.yml
- filename: infobip-tools-api-openapi.yml
  format: yaml
  label: Infobip Tools API
  slug: infobip-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/infobip/openapi/infobip-tools-api-openapi.yml
claim_count: 37
description: ''
doc:
  data_categories:
  - category: identifying
    text: Registration details of a customer and account users (e.g. name and surname, business address, phone number, email address, company’s name and industry, business role, as well as login details)
  - category: financial
    text: Billing and financial details of a customer
  - category: location
    text: location information (including approximate location derived from IP address)
  - category: behavioral
    text: which is data you generate as our customer’s account user during your activity on our website and our platform
  - category: device
    text: browser or device information
  - category: communication
    text: message text, voice, video or audio media, documents, or images exchanged between the customer and their end-users via Infobip Services
  - category: contact
    text: We may collect your name, contact details (like email, phone number, and country), and business information
  deletion:
    route: Email to the data protection officer
    text: 'If you wish to withdraw your consent for the processing of your personal data for any purpose and to delete your data, you can do that at any time by sending an email to:'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account creation and management
    text: Create and manage accounts of customers and users’ accounts on our platform
  - purpose: AI chatbot for customer care
    text: Enable AI powered chatbot on Infobip Portal for customer care purposes
  - purpose: Fraud prevention and security
    text: prevent fraudulent activities such as misuse of accounts, sending spam and artificially inflated traffic
  - purpose: Product improvement statistics
    text: Create statistics on the use of our tools to understand which tools have a user-friendly design and which should be enhanced.
  - purpose: Marketing information
    text: Inform you about our Services, company news, webinars and upcoming events
  - purpose: Personalized product notices
    text: Display personalized pop-up notices about new products, features and tips on Infobip Portal
  - purpose: Provision of cloud services and infrastructure
    source: https://www.infobip.com/policies/processors
    text: Provisioning of cloud services for storage and computing, networking, monitoring and analytics, including proxying and balancing
  - purpose: Customer care and technical support
    source: https://www.infobip.com/policies/processors
    text: Provisioning of customer care and technical support.
  - purpose: LLM capabilities within AgentOS
    source: https://www.infobip.com/policies/processors
    text: Provisioning of large language model (LLM) capabilities within Infobip AgentOS platform, enabling autonomous multimodal AI-driven task execution, information retrieval and conversational assistance.
  - purpose: Speech-to-text and text-to-speech
    source: https://www.infobip.com/policies/processors
    text: Provisioning of Speech-to-Text (STT) and Text-to-Speech (TTS) services for voice transcription and voice interaction features
  retention:
  - period: seven (7) years
    scope: Customer accounts
    text: Personal data in customers’ accounts are kept for seven (7) years after the end of our business relationship.
  - period: twelve (12) months
    scope: Account users and business contacts
    text: Personal data of account users and business contacts are retained for twelve (12) months after the end of our business relationship with the customer.
  - period: twelve (12) months
    scope: Traffic data with end-user personal data
    text: Traffic data containing end-users’ personal data (such as phone number or email address) is deleted from communication detail records twelve (12) months after the end of the month in which the communication took place.
  - period: fifteen (15) months
    scope: Activity (audit) logs
    text: Activity (audit) logs are retained for fifteen (15) months for security purposes
  - period: twenty-five (25) months
    scope: User analytics data
    text: User analytics data is retained for twenty-five (25) months after it was generated.
  - period: two (2) years
    scope: Meeting recordings
    text: Recordings of our meetings will be deleted after two (2) years.
  - period: ninety (90) days
    scope: CCTV recordings
    text: CCTV surveillance recordings are generally deleted ninety (90) days after the recording date
  - period: six (6) months
    scope: Chatbot communication
    text: The chatbot communication is stored for six (6) months from the moment the chat was initiated
  rights:
  - right: Withdraw consent
    text: Withdraw your consent to our processing of your personal data
  - right: Access
    text: Request from us to access your personal data
  - right: Rectification
    text: Ask us to rectify (correct) your personal data that you think is inaccurate
  - right: Erasure
    text: Ask us to erase your personal data in certain circumstances
  - right: Restriction
    text: Ask us to restrict the processing of your personal data in certain circumstances
  - right: Portability
    text: you can exercise the right of data portability
  - right: Objection
    text: If we process your personal data upon our legitimate interest, you have the right to object to the processing.
  - right: Complaint
    text: you can lodge a complaint with the supervisory authority of the EU member state of your habitual residence
  role:
    text: While providing Services to our customers, we act either as the controller or the processor, depending on the situation.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: we will complete and execute standard contractual clauses for data transfers where required
  - mechanism: DPF
    source: https://www.infobip.com/policies/processors
    text: EU-U.S. Data Privacy Framework, UK Extension to the EU-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Infobip
provenance_date: '2026-11-09'
provider_name: Infobip
provider_slug: infobip
slug: infobip-privacy-policy
source_date: '2026-11-09'
source_filename: infobip-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.infobip.com/policies/privacy-notice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Infobip\naid: infobip\nurl: https://www.infobip.com/policies/privacy-notice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\n  sources:\n  - https://www.infobip.com/policies/privacy-notice\n  - https://www.infobip.com/policies/processors\nrole:\n  value: both\n  text: While providing Services to our customers, we act either as the controller or the processor, depending on\n    the situation.\ndata_categories:\n- category: identifying\n  text: Registration details of a customer and account users (e.g. name and surname, business address, phone number,\n    email address, company’s name and industry, business role,\
  \ as well as login details)\n- category: financial\n  text: Billing and financial details of a customer\n- category: location\n  text: location information (including approximate location derived from IP address)\n- category: behavioral\n  text: which is data you generate as our customer’s account user during your activity on our website and our platform\n- category: device\n  text: browser or device information\n- category: communication\n  text: message text, voice, video or audio media, documents, or images exchanged between the customer and their\n    end-users via Infobip Services\n- category: contact\n  text: We may collect your name, contact details (like email, phone number, and country), and business information\npurposes:\n- purpose: Account creation and management\n  text: Create and manage accounts of customers and users’ accounts on our platform\n- purpose: AI chatbot for customer care\n  text: Enable AI powered chatbot on Infobip Portal for customer care purposes\n- purpose:\
  \ Fraud prevention and security\n  text: prevent fraudulent activities such as misuse of accounts, sending spam and artificially inflated traffic\n- purpose: Product improvement statistics\n  text: Create statistics on the use of our tools to understand which tools have a user-friendly design and which\n    should be enhanced.\n- purpose: Marketing information\n  text: Inform you about our Services, company news, webinars and upcoming events\n- purpose: Personalized product notices\n  text: Display personalized pop-up notices about new products, features and tips on Infobip Portal\n- purpose: Provision of cloud services and infrastructure\n  text: Provisioning of cloud services for storage and computing, networking, monitoring and analytics, including\n    proxying and balancing\n  source: https://www.infobip.com/policies/processors\n- purpose: Customer care and technical support\n  text: Provisioning of customer care and technical support.\n  source: https://www.infobip.com/policies/processors\n\
  - purpose: LLM capabilities within AgentOS\n  text: Provisioning of large language model (LLM) capabilities within Infobip AgentOS platform, enabling autonomous\n    multimodal AI-driven task execution, information retrieval and conversational assistance.\n  source: https://www.infobip.com/policies/processors\n- purpose: Speech-to-text and text-to-speech\n  text: Provisioning of Speech-to-Text (STT) and Text-to-Speech (TTS) services for voice transcription and voice\n    interaction features\n  source: https://www.infobip.com/policies/processors\nretention:\n- scope: Customer accounts\n  period: seven (7) years\n  text: Personal data in customers’ accounts are kept for seven (7) years after the end of our business relationship.\n- scope: Account users and business contacts\n  period: twelve (12) months\n  text: Personal data of account users and business contacts are retained for twelve (12) months after the end of\n    our business relationship with the customer.\n- scope: Traffic data\
  \ with end-user personal data\n  period: twelve (12) months\n  text: Traffic data containing end-users’ personal data (such as phone number or email address) is deleted from\n    communication detail records twelve (12) months after the end of the month in which the communication took place.\n- scope: Activity (audit) logs\n  period: fifteen (15) months\n  text: Activity (audit) logs are retained for fifteen (15) months for security purposes\n- scope: User analytics data\n  period: twenty-five (25) months\n  text: User analytics data is retained for twenty-five (25) months after it was generated.\n- scope: Meeting recordings\n  period: two (2) years\n  text: Recordings of our meetings will be deleted after two (2) years.\n- scope: CCTV recordings\n  period: ninety (90) days\n  text: CCTV surveillance recordings are generally deleted ninety (90) days after the recording date\n- scope: Chatbot communication\n  period: six (6) months\n  text: The chatbot communication is stored for six (6)\
  \ months from the moment the chat was initiated\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: we will complete and execute standard contractual clauses for data transfers where required\n- mechanism: DPF\n  text: EU-U.S. Data Privacy Framework, UK Extension to the EU-U.S. Data Privacy Framework\n  source: https://www.infobip.com/policies/processors\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email to the data protection officer\n  text: 'If you wish to withdraw your consent for the processing of your personal data for any purpose and to delete\n    your data, you can do that at any time by sending an email to:'\nrights:\n- right: Withdraw consent\n  text: Withdraw your consent to our processing of your personal data\n- right: Access\n  text: Request from us to access your personal data\n- right: Rectification\n  text: Ask us to rectify (correct) your personal data that you think is inaccurate\n- right: Erasure\n\
  \  text: Ask us to erase your personal data in certain circumstances\n- right: Restriction\n  text: Ask us to restrict the processing of your personal data in certain circumstances\n- right: Portability\n  text: you can exercise the right of data portability\n- right: Objection\n  text: If we process your personal data upon our legitimate interest, you have the right to object to the processing.\n- right: Complaint\n  text: you can lodge a complaint with the supervisory authority of the EU member state of your habitual residence\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/infobip/privacy/infobip-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 37 quoted statements, read from Infobip's own page on 2026-11-09.
synthetic: false
tags:
- Telecommunications
- Croatia
- CPaaS
- Messaging
- SMS
- Voice
- RCS
- WhatsApp
- Email
- Network APIs
- CAMARA
- Open Gateway
- Identity Verification
- SIM Swap
- Number Verification
- Omnichannel
- Aggregator
- Customer Engagement
- Communications
---
