---
api_specs:
- filename: arxiv-oai-pmh-api-openapi.yml
  format: yaml
  label: arXiv OAI-PMH API
  slug: arxiv-oai-pmh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arxiv/openapi/arxiv-oai-pmh-api-openapi.yml
- filename: arxiv-query-api-openapi.yml
  format: yaml
  label: arXiv Query API
  slug: arxiv-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/arxiv/openapi/arxiv-query-api-openapi.yml
claim_count: 20
description: ''
doc:
  data_categories:
  - category: identifying
    text: Registered users – name, email address, ORCID, past email addresses, affiliation, country, additional contact information and/or online identifiers.
  - category: device
    text: Users who browse the website – IP address, pathways navigated through the website, type of internet browser used.
  - category: financial
    text: Donors – name, address, email address, institutional affiliation (if provided), and financial information to enable the processing of the donation.
  - category: communication
    text: Users who submit feedback or help requests – name, email address, and information pertaining to operating environment.
  deletion:
    route: Privacy Data Subject Rights Request Form
    text: You can also request deletion of your Personal Data by completing our Privacy Data Subject Rights Request Form
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Scholarly paper submission, hosting, and archiving
    text: In the content submission and moderation process we link user accounts, authorship, and submitted content to track and process submissions
  - purpose: Fraud and abuse protection
    text: We log requests in order to detect fraud and prevent unauthorized access, for example, from DDoS (distributed denial-of-service) attacks.
  - purpose: Fundraising
    text: Should you decide to donate to arXiv through the Donate page, you will be asked for information to process your donation, and you may receive fundraising emails, from which you can unsubscribe at any time.
  - purpose: Conducting research in the public interest
    text: Certain information we gather, including your IP address, information about your browser, the date and time of your visit, the referrer field (if present), your personal preferences, and the pages on our website that you accessed, may be used for secondary research purposes
  residency:
  - region: United States
    text: your data generally will be hosted on U.S. servers
  retention:
  - period: five years
    scope: Personal Data collected for research
    text: Personal Data collected for use in research will be completely anonymized or deleted by arXiv after five years.
  - period: up to one year
    scope: Cookies and browser local storage
    text: When arXiv.org stores Personal Data in a cookie or local storage, that data may persist for up to one year, unless cleared by you.
  rights:
  - right: access/copy
    text: obtain a copy of your Personal Data in an easily accessible format
  - right: correction
    text: request that we correct or update any of your Personal Data that is inaccurate
  - right: restriction
    text: restrict or limit the ways in which we use your Personal Data
  - right: objection
    text: object to the processing of your Personal Data
  - right: deletion
    text: request the deletion of your Personal Data
  - right: portability
    text: request that we transmit your Personal Data to another party
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: However, we will not sell this data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: you consent to the transfer of such data to the U.S. for processing by us in accordance with this Privacy Policy
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: arXiv
provenance_date: '2026-11-09'
provider_name: arXiv
provider_slug: arxiv
slug: arxiv-privacy-policy
source_date: '2026-11-09'
source_filename: arxiv-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://info.arxiv.org/help/policies/privacy_policy.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: arXiv\naid: arxiv\nurl: https://info.arxiv.org/help/policies/privacy_policy.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Registered users – name, email address, ORCID, past email addresses, affiliation, country, additional contact\n    information and/or online identifiers.\n- category: device\n  text: Users who browse the website – IP address, pathways navigated through the website, type of internet browser\n    used.\n- category: financial\n  text: Donors – name, address, email address, institutional affiliation (if provided),\
  \ and financial information\n    to enable the processing of the donation.\n- category: communication\n  text: Users who submit feedback or help requests – name, email address, and information pertaining to operating\n    environment.\npurposes:\n- purpose: Scholarly paper submission, hosting, and archiving\n  text: In the content submission and moderation process we link user accounts, authorship, and submitted content\n    to track and process submissions\n- purpose: Fraud and abuse protection\n  text: We log requests in order to detect fraud and prevent unauthorized access, for example, from DDoS (distributed\n    denial-of-service) attacks.\n- purpose: Fundraising\n  text: Should you decide to donate to arXiv through the Donate page, you will be asked for information to process\n    your donation, and you may receive fundraising emails, from which you can unsubscribe at any time.\n- purpose: Conducting research in the public interest\n  text: Certain information we gather, including\
  \ your IP address, information about your browser, the date and time\n    of your visit, the referrer field (if present), your personal preferences, and the pages on our website that\n    you accessed, may be used for secondary research purposes\nretention:\n- scope: Personal Data collected for research\n  period: five years\n  text: Personal Data collected for use in research will be completely anonymized or deleted by arXiv after five\n    years.\n- scope: Cookies and browser local storage\n  period: up to one year\n  text: When arXiv.org stores Personal Data in a cookie or local storage, that data may persist for up to one year,\n    unless cleared by you.\nresidency:\n- region: United States\n  text: your data generally will be hosted on U.S. servers\ntransfers:\n- mechanism: other\n  text: you consent to the transfer of such data to the U.S. for processing by us in accordance with this Privacy\n    Policy\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url:\
  \ null\n  text: null\ndeletion:\n  route: Privacy Data Subject Rights Request Form\n  text: You can also request deletion of your Personal Data by completing our Privacy Data Subject Rights Request\n    Form\nrights:\n- right: access/copy\n  text: obtain a copy of your Personal Data in an easily accessible format\n- right: correction\n  text: request that we correct or update any of your Personal Data that is inaccurate\n- right: restriction\n  text: restrict or limit the ways in which we use your Personal Data\n- right: objection\n  text: object to the processing of your Personal Data\n- right: deletion\n  text: request the deletion of your Personal Data\n- right: portability\n  text: request that we transmit your Personal Data to another party\nsale_or_sharing:\n  stance: prohibited\n  text: However, we will not sell this data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/arxiv/privacy/arxiv-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 20 quoted statements, read from arXiv's own page on 2026-11-09.
synthetic: false
tags:
- Scholarly Publishing
- Preprints
- Open Access
- Research
- Open Source
- Public APIs
- Research Data
- OAI-PMH
- Research Repository
- Science
---
