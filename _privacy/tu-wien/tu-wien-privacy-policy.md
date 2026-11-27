---
api_specs:
- filename: tu-wien-public-api-openapi.yml
  format: yaml
  label: TU Wien Public API
  slug: tu-wien-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tu-wien/openapi/tu-wien-public-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: IP address
  - category: behavioral
    text: Previously visited URL (Reffer URL)
  - category: device
    text: Operating system and browser type
  - category: demographic
    text: Gender
  - category: demographic
    text: Date of birth
  - category: contact
    text: Telephone number
  - category: communication
    text: Message
  deletion:
    route: Contact datenschutz@tuwien.ac.at for data subject rights requests
    text: If data subject rights within the meaning of this privacy policy (e.g. right to information, right to cancellation, etc.) are asserted, these requests or applications must be addressed to datenschutz@tuwien.ac.at without exception.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision and operation of websites and services
    text: We use your personal data to provide the information, products and services we offer, to answer your questions and to operate and improve our websites and applications.
  - purpose: Ensure functionality and security of websites
    text: Data is stored in log files to ensure the functionality of the website. We also use the data to optimise the website and to ensure the security of our information technology systems.
  - purpose: Newsletter sending
    text: The purpose of collecting the user's email address is to send the newsletter.
  - purpose: Web statistics and analysis
    text: This process is used to evaluate the effectiveness of TUW's marketing campaigns for statistical and market research purposes and can help to optimise future advertising measures.
  retention:
  - period: 30 days
    scope: Log files
    text: This takes place after 30 days at the latest.
  - period: 30 days
    scope: Newsletter registration data other than e-mail address
    text: The other personal data collected during the registration process is generally deleted after a period of 30 days.
  - period: null
    scope: Newsletter e-mail address
    text: The e-mail addresses of users are therefore stored for as long as the subscription to the respective newsletter is active.
  - period: null
    scope: Contact form data
    text: Personal data from the input screen of the contact form or an email will be deleted as soon as the conversation with the user has ended.
  rights:
  - right: Right to information
    text: Right to information
  - right: Right to rectification
    text: Right to rectification
  - right: Right to cancellation
    text: Right to cancellation
  - right: Right to restriction of processing
    text: Right to restriction of processing
  - right: Right to data portability
    text: Right to data portability
  - right: Right to object
    text: Right to object
  - right: Complaint to supervisory authority
    text: You also have the option of lodging a complaint with a data protection supervisory authority.
  role:
    text: The controller within the meaning of the General Data Protection Regulation (GDPR)1 is the Rectorate of TUW Karlsplatz 13,1040 Vienna
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: An adequacy decision ("EU -US Privacy Shield") currently exists for the transfer of data to the USA, which certifies that participating organisations have an adequate level of data protection.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TU Wien
provenance_date: '2026-11-10'
provider_name: TU Wien
provider_slug: tu-wien
slug: tu-wien-privacy-policy
source_date: '2026-11-10'
source_filename: tu-wien-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tuwien.at/fileadmin/Datenschutz/Data_Protection_Declaration_Websites.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TU Wien\naid: tu-wien\nurl: https://www.tuwien.at/fileadmin/Datenschutz/Data_Protection_Declaration_Websites.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller within the meaning of the General Data Protection Regulation (GDPR)1 is the Rectorate of\n    TUW Karlsplatz 13,1040 Vienna\ndata_categories:\n- category: identifying\n  text: IP address\n- category: behavioral\n  text: Previously visited URL (Reffer URL)\n- category: device\n  text: Operating system and browser type\n- category: demographic\n  text: Gender\n- category: demographic\n  text: Date of birth\n- category:\
  \ contact\n  text: Telephone number\n- category: communication\n  text: Message\npurposes:\n- purpose: Provision and operation of websites and services\n  text: We use your personal data to provide the information, products and services we offer, to answer your questions\n    and to operate and improve our websites and applications.\n- purpose: Ensure functionality and security of websites\n  text: Data is stored in log files to ensure the functionality of the website. We also use the data to optimise\n    the website and to ensure the security of our information technology systems.\n- purpose: Newsletter sending\n  text: The purpose of collecting the user's email address is to send the newsletter.\n- purpose: Web statistics and analysis\n  text: This process is used to evaluate the effectiveness of TUW's marketing campaigns for statistical and market\n    research purposes and can help to optimise future advertising measures.\nretention:\n- scope: Log files\n  period: 30 days\n  text:\
  \ This takes place after 30 days at the latest.\n- scope: Newsletter registration data other than e-mail address\n  period: 30 days\n  text: The other personal data collected during the registration process is generally deleted after a period of\n    30 days.\n- scope: Newsletter e-mail address\n  period: null\n  text: The e-mail addresses of users are therefore stored for as long as the subscription to the respective newsletter\n    is active.\n- scope: Contact form data\n  period: null\n  text: Personal data from the input screen of the contact form or an email will be deleted as soon as the conversation\n    with the user has ended.\nresidency: []\ntransfers:\n- mechanism: other\n  text: An adequacy decision (\"EU -US Privacy Shield\") currently exists for the transfer of data to the USA, which\n    certifies that participating organisations have an adequate level of data protection.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n\
  \  route: Contact datenschutz@tuwien.ac.at for data subject rights requests\n  text: If data subject rights within the meaning of this privacy policy (e.g. right to information, right to cancellation,\n    etc.) are asserted, these requests or applications must be addressed to datenschutz@tuwien.ac.at without exception.\nrights:\n- right: Right to information\n  text: Right to information\n- right: Right to rectification\n  text: Right to rectification\n- right: Right to cancellation\n  text: Right to cancellation\n- right: Right to restriction of processing\n  text: Right to restriction of processing\n- right: Right to data portability\n  text: Right to data portability\n- right: Right to object\n  text: Right to object\n- right: Complaint to supervisory authority\n  text: You also have the option of lodging a complaint with a data protection supervisory authority.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tu-wien/privacy/tu-wien-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- deletion
- rights
summary_line: 25 quoted statements, read from TU Wien's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Technical University
- Austria
- Europe
- Research Data
- Research Repository
- Open Access
- OAI-PMH
- Identity Federation
- Research Computing
- InvenioRDM
- DataCite
- ORCID
- SAML
- RIS Synergy
---
