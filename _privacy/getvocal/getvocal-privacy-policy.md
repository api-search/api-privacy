---
api_specs:
- filename: getvocal-contact-api-openapi.yml
  format: yaml
  label: GetVocal Contact API
  slug: getvocal-contact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-contact-api-openapi.yml
- filename: getvocal-llms-txt-api-openapi.yml
  format: yaml
  label: GetVocal Llms.txt API
  slug: getvocal-llms-txt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-llms-txt-api-openapi.yml
- filename: getvocal-well-known-api-openapi.yml
  format: yaml
  label: GetVocal .well Known API
  slug: getvocal-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/getvocal/openapi/getvocal-well-known-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name
  - category: contact
    text: Contact information (email address, phone number, address, etc.)
  - category: identifying
    text: Identification information (i.e. government-issued ID, passport number, etc.)
  - category: device
    text: Automatically Collected Information We may also collect certain information automatically when you visit our website or use our services, such as your IP address, browser type, and usage data.
  - category: health
    text: Health-related data
  - category: biometric
    text: Biometric data
  deletion:
    route: Contact dpo@getvocal.ai
    text: For specific requests relating to your rights as a data subject including the rights noted in section “Data Subject Rights” noted above, please contact our Data Protection Officer (DPO) directly at dpo@getvocal.ai
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Service delivery
    text: We use your personal information to provide you with the products or services you have requested.
  - purpose: Improvement of services
    text: We analyze your data to understand how our services are used and to make improvements.
  - purpose: Marketing
    text: We may also use your contact information for marketing purposes, such as sending newsletters or promotional offers if you have provided your consent or if we have a legitimate interest in doing so.
  residency:
  - region: European Union
    text: Our service is hosted in the European Union on the Google Cloud Platform and all personal information collected with the service is stored therein, in accordance with GDPR.
  retention:
  - period: 30 days
    scope: Contract termination
    text: In case of contract termination, all data is deleted after 30 days, unless a written demand requests an earlier or later deletion.
  rights:
  - right: Access
    text: You have the right to request access to your personal data that we process.
  - right: Rectification
    text: You can request the correction or updating of your personal data if it is inaccurate or incomplete.
  - right: Erasure
    text: You can request the deletion of your personal data under certain circumstances.
  - right: Restriction of processing
    text: You have the right to request the restriction of the processing of your personal data under specific circumstances.
  - right: Portability
    text: You can request a copy of your personal data in a structured, commonly used, machine-readable format, or you can ask us to transmit it directly to another data controller where technically feasible.
  - right: Object
    text: You have the right to object to the processing of your personal data, including processing based on legitimate interests or for direct marketing purposes.
  - right: Withdraw consent
    text: If we process your personal data based on your consent, you have the right to withdraw that consent at any time.
  role:
    text: We collect and process your personal information, and act as a “data controller” of the Personally Identifiable Information (PII) that you provide to us.
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Service Providers: We may share your personal information with third-party service providers who assist us in delivering our products and services. These service providers include Google Cloud Platform (Cloud infrastructure hosting), OpenAI, Anthropic, Grok (LLM providers), Twilio and Vonage (Voice/Telephony providers), among others.'
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses: We may use standard contractual clauses approved by the European Commission or other relevant data protection authorities to ensure the protection of your personal data during transfer.'
  - mechanism: BCR
    text: 'Binding Corporate Rules (BCRs): Where applicable, we may rely on BCRs adopted by our organization to ensure the protection of personal data transferred across borders within our corporate group.'
  - mechanism: DPF
    text: 'Certification Mechanisms: We may rely on certification mechanisms such as the EU-U.S. Privacy Shield Framework, where applicable, to ensure that third-party recipients of your personal data provide an adequate level of protection.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: GetVocal
provenance_date: '2026-11-09'
provider_name: GetVocal
provider_slug: getvocal
slug: getvocal-privacy-policy
source_date: '2026-11-09'
source_filename: getvocal-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.getvocal.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: GetVocal\naid: getvocal\nurl: https://www.getvocal.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: We collect and process your personal information, and act as a “data controller” of the Personally Identifiable\n    Information (PII) that you provide to us.\ndata_categories:\n- category: identifying\n  text: Name\n- category: contact\n  text: Contact information (email address, phone number, address, etc.)\n- category: identifying\n  text: Identification information (i.e. government-issued ID, passport number, etc.)\n- category: device\n  text: Automatically Collected Information\
  \ We may also collect certain information automatically when you visit\n    our website or use our services, such as your IP address, browser type, and usage data.\n- category: health\n  text: Health-related data\n- category: biometric\n  text: Biometric data\npurposes:\n- purpose: Service delivery\n  text: We use your personal information to provide you with the products or services you have requested.\n- purpose: Improvement of services\n  text: We analyze your data to understand how our services are used and to make improvements.\n- purpose: Marketing\n  text: We may also use your contact information for marketing purposes, such as sending newsletters or promotional\n    offers if you have provided your consent or if we have a legitimate interest in doing so.\nretention:\n- scope: Contract termination\n  period: 30 days\n  text: In case of contract termination, all data is deleted after 30 days, unless a written demand requests an\n    earlier or later deletion.\nresidency:\n- region:\
  \ European Union\n  text: Our service is hosted in the European Union on the Google Cloud Platform and all personal information collected\n    with the service is stored therein, in accordance with GDPR.\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses: We may use standard contractual clauses approved by the European Commission\n    or other relevant data protection authorities to ensure the protection of your personal data during transfer.'\n- mechanism: BCR\n  text: 'Binding Corporate Rules (BCRs): Where applicable, we may rely on BCRs adopted by our organization to ensure\n    the protection of personal data transferred across borders within our corporate group.'\n- mechanism: DPF\n  text: 'Certification Mechanisms: We may rely on certification mechanisms such as the EU-U.S. Privacy Shield Framework,\n    where applicable, to ensure that third-party recipients of your personal data provide an adequate level of protection.'\nsubprocessors:\n  url: null\n  text: 'Service\
  \ Providers: We may share your personal information with third-party service providers who assist\n    us in delivering our products and services. These service providers include Google Cloud Platform (Cloud infrastructure\n    hosting), OpenAI, Anthropic, Grok (LLM providers), Twilio and Vonage (Voice/Telephony providers), among others.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact dpo@getvocal.ai\n  text: For specific requests relating to your rights as a data subject including the rights noted in section “Data\n    Subject Rights” noted above, please contact our Data Protection Officer (DPO) directly at dpo@getvocal.ai\nrights:\n- right: Access\n  text: You have the right to request access to your personal data that we process.\n- right: Rectification\n  text: You can request the correction or updating of your personal data if it is inaccurate or incomplete.\n- right: Erasure\n  text: You can request the deletion of your personal data under certain\
  \ circumstances.\n- right: Restriction of processing\n  text: You have the right to request the restriction of the processing of your personal data under specific circumstances.\n- right: Portability\n  text: You can request a copy of your personal data in a structured, commonly used, machine-readable format, or\n    you can ask us to transmit it directly to another data controller where technically feasible.\n- right: Object\n  text: You have the right to object to the processing of your personal data, including processing based on legitimate\n    interests or for direct marketing purposes.\n- right: Withdraw consent\n  text: If we process your personal data based on your consent, you have the right to withdraw that consent at any\n    time.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getvocal/privacy/getvocal-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
summary_line: 24 quoted statements, read from GetVocal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Conversational AI
- Customer Experience
- AI Agents
- Contact Center
- Agent Governance
- MCP
- Agent-Native
---
