---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: first and last name, work email address, company, role, your interest
  - category: contact
    text: account email, plan tier, language preference
  - category: device
    text: Timestamp, tool name invoked, request size, response status, IP address (truncated to /24 after 24 hours)
  - category: biometric
    text: We do not collect biometric data
  - category: other
    text: Scientific input data. Chemical structures (SMILES, InChI, MOL, SDF), biological sequences (protein, RNA, DNA), spectral data (NMR, IR, MS, UV-Vis), experimental measurements
  deletion:
    route: email to support@covasyn.com
    text: To exercise these rights, email support@covasyn.com .
  dpa:
    available: true
    text: Data Processing Agreements (DPA / AVV) are in place with each and are available on request via support@covasyn.com .
    url: null
  purposes:
  - purpose: Providing the requested computational result
    text: Providing the requested computational result Art. 6(1)(b) GDPR, contract performance
  - purpose: Rate-limiting, abuse prevention, security
    text: Rate-limiting, abuse prevention, security Art. 6(1)(f) GDPR, legitimate interest
  - purpose: Billing and account management
    text: Billing and account management (paid tiers) Art. 6(1)(b) GDPR, contract performance
  residency:
  - region: Germany
    text: primary hosting in Nuremberg (DE) for covasyn.com, workspace.covasyn.com, the MCP gateway, application backend, database servers, and internal systems. EU processing.
  retention:
  - period: null
    scope: Scientific inputs and outputs
    text: 'Scientific inputs and outputs: processed in memory and not persisted to long-term storage.'
  - period: 30 days
    scope: Short-term operational logs
    text: Short-term operational logs that may include payloads are discarded within 30 days.
  - period: 90 days
    scope: Technical metadata
    text: 'Technical metadata (truncated IP, tool name, timestamp, allowance consumed): 90 days for security and abuse prevention.'
  - period: 10 years
    scope: Billing records
    text: 'Billing records (paid tiers): retained for 10 years per German tax law (§ 147 AO).'
  rights:
  - right: Access
    text: Access the personal data we hold about you (Art. 15)
  - right: Erase
    text: Erase your data (Art. 17), subject to legal retention obligations
  - right: Object
    text: Object to processing based on legitimate interest (Art. 21)
  - right: Withdraw consent
    text: Withdraw consent at any time, without affecting prior processing
  role:
    text: 'The controller is: CovaSyn GmbH Naunhofer Straße 67, 04299 Leipzig, Saxony, Germany'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: We share data only with the following categories of recipients, acting as processors under Art. 28 GDPR.
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers to the USA are based on the EU-U.S. Data Privacy Framework and Standard Contractual Clauses (SCCs).
  - mechanism: DPF
    text: under which OpenAI is self-certified
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CovaSyn
provenance_date: '2026-11-09'
provider_name: CovaSyn
provider_slug: covasyn-com
slug: covasyn-com-privacy-policy
source_date: '2026-11-09'
source_filename: covasyn-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://covasyn.com/en/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CovaSyn\naid: covasyn-com\nurl: https://covasyn.com/en/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The controller is: CovaSyn GmbH Naunhofer Straße 67, 04299 Leipzig, Saxony, Germany'\ndata_categories:\n- category: identifying\n  text: first and last name, work email address, company, role, your interest\n- category: contact\n  text: account email, plan tier, language preference\n- category: device\n  text: Timestamp, tool name invoked, request size, response status, IP address (truncated to /24 after 24 hours)\n- category: biometric\n  text: We do not collect biometric data\n\
  - category: other\n  text: Scientific input data. Chemical structures (SMILES, InChI, MOL, SDF), biological sequences (protein, RNA,\n    DNA), spectral data (NMR, IR, MS, UV-Vis), experimental measurements\npurposes:\n- purpose: Providing the requested computational result\n  text: Providing the requested computational result Art. 6(1)(b) GDPR, contract performance\n- purpose: Rate-limiting, abuse prevention, security\n  text: Rate-limiting, abuse prevention, security Art. 6(1)(f) GDPR, legitimate interest\n- purpose: Billing and account management\n  text: Billing and account management (paid tiers) Art. 6(1)(b) GDPR, contract performance\nretention:\n- scope: Scientific inputs and outputs\n  period: null\n  text: 'Scientific inputs and outputs: processed in memory and not persisted to long-term storage.'\n- scope: Short-term operational logs\n  period: 30 days\n  text: Short-term operational logs that may include payloads are discarded within 30 days.\n- scope: Technical metadata\n\
  \  period: 90 days\n  text: 'Technical metadata (truncated IP, tool name, timestamp, allowance consumed): 90 days for security and abuse\n    prevention.'\n- scope: Billing records\n  period: 10 years\n  text: 'Billing records (paid tiers): retained for 10 years per German tax law (§ 147 AO).'\nresidency:\n- region: Germany\n  text: primary hosting in Nuremberg (DE) for covasyn.com, workspace.covasyn.com, the MCP gateway, application backend,\n    database servers, and internal systems. EU processing.\ntransfers:\n- mechanism: SCC\n  text: Transfers to the USA are based on the EU-U.S. Data Privacy Framework and Standard Contractual Clauses (SCCs).\n- mechanism: DPF\n  text: under which OpenAI is self-certified\nsubprocessors:\n  url: null\n  text: We share data only with the following categories of recipients, acting as processors under Art. 28 GDPR.\ndpa:\n  available: true\n  url: null\n  text: Data Processing Agreements (DPA / AVV) are in place with each and are available on request\
  \ via support@covasyn.com\n    .\ndeletion:\n  route: email to support@covasyn.com\n  text: To exercise these rights, email support@covasyn.com .\nrights:\n- right: Access\n  text: Access the personal data we hold about you (Art. 15)\n- right: Erase\n  text: Erase your data (Art. 17), subject to legal retention obligations\n- right: Object\n  text: Object to processing based on legitimate interest (Art. 21)\n- right: Withdraw consent\n  text: Withdraw consent at any time, without affecting prior processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/covasyn-com/privacy/covasyn-com-privacy-policy.yml
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
summary_line: 24 quoted statements, read from CovaSyn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Chemistry
- Pharma
- Biotech
- Cheminformatics
- MCP
- Artificial Intelligence
- Quality and Regulatory
---
