---
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: We associate your API key with your name and optionally a group membership that you provided when requesting a key.
  - category: behavioral
    text: 'We log every request sent with your key, which includes the following data: key user''s name time of request requested model processed number of input and output tokens'
  - category: device
    text: We process device and usage data (e.g. browser type, operating system, IP address, usage times).
  - category: communication
    text: To provide the services we process any content that you send in a request to the API. We do not save the content of your prompt or the model's answer.
  - category: identifying
    source: https://idp.tu-dresden.de/dataprivacy/
    text: Die einem Service Provider (SP) zu übermittelnden Daten (Attribute) werden dem Nutzer nach der erfolgreichen Authentifizierung gegenüber dem ZIH am Identity Provider zunächst angezeigt.
  - category: identifying
    source: https://idp.tu-dresden.de/dataprivacy/
    text: Gegenüber vielen Service Providern genügt eine anonyme Identifikation mittels einer sogenannten transientId
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Research, text and idea generation
    text: Support with research, text and idea generation
  - purpose: Administrative and organizational activities
    text: Facilitation of administrative and organizational activities
  - purpose: Image material
    text: Creation or evaluation of image material
  - purpose: Audio material evaluation
    text: Evaluation of audio material
  - purpose: Teaching, research and administration support
    text: Promotion of teaching, research, and administration through digital assistance functions.
  - purpose: Authentication and authorization
    source: https://idp.tu-dresden.de/dataprivacy/
    text: Der IdP dient zur Authentifizierung und Autorisierung der Nutzer der TU Dresden gegenüber Anbietern, sogenannten Service Providern (SPs), im Rahmen der DFN-AAI.
  - purpose: Data minimisation
    source: https://idp.tu-dresden.de/dataprivacy/
    text: Das ZIH trägt dafür Sorge, dass nur Attribute herausgegeben werden können, die für die Erbringung des Dienstes des Serviceproviders erforderlich sind.
  retention:
  - period: one year
    scope: Usage data
    text: We generally store this data for one year, but no longer than until the end of the contractual relationship.
  - period: 90 days
    scope: Web server software logs
    text: The web server software logs are deleted after 90 days.
  rights:
  - right: Information
    text: You have the right to request information about the data processed about you and the possible recipients of this data at any time.
  - right: Rectification, erasure and restriction
    text: You may at any time request TU Dresden to correct or erase your personal data or to restrict processing.
  - right: Withdraw consent
    text: Consent can be refused or revoked at any time informally and without giving reasons to the person responsible.
  - right: Data portability
    text: You may request that the controller(s) transmit your personal data to you in machine-readable form.
  - right: Object
    text: You have the right to object, on grounds relating to your particular situation, at any time to processing of personal data concerning you which is based on point (e) of Article 6(1).
  - right: Complain to supervisory authority
    text: You can contact the TU Dresden data protection officer at any time (see above) as well as a supervisory authority for data protection in the event of a complaint pursuant to Art. 77 GDPR.
  - right: Withdraw consent to data transfer
    source: https://idp.tu-dresden.de/dataprivacy/
    text: Haben Sie der Übermittlung personenbeziehbarer Daten an den Serviceprovider zugestimmt und wollen Sie dies widerrufen, so wenden Sie sich bitte direkt an den entsprechenden Serviceprovider.
  - right: Information on processed data
    source: https://tu-dresden.de/tu-dresden/organisation/gremien-und-beauftragte/beauftragte/datenschutzbeauftragter
    text: they have the right to request information divulging what data pertaining to their person has been processed by which area of the university and on what legal basis
  - right: Non-discrimination
    source: https://tu-dresden.de/tu-dresden/organisation/gremien-und-beauftragte/beauftragte/datenschutzbeauftragter
    text: No one may be discriminated against or reprimanded for exercising their rights.
  role:
    text: 'Dresden University of Technology Contact person: ScaDS.AI Dresden/Leipzig'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: TU Dresden
provenance_date: '2026-11-10'
provider_name: TU Dresden
provider_slug: tu-dresden
slug: tu-dresden-privacy-policy
source_date: '2026-11-10'
source_filename: tu-dresden-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://llm.scads.ai/docs/legal/privacy-policy/api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: TU Dresden\naid: tu-dresden\nurl: https://llm.scads.ai/docs/legal/privacy-policy/api/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://idp.tu-dresden.de/dataprivacy/\n  - https://llm.scads.ai/docs/legal/privacy-policy/api/\n  - https://tu-dresden.de/tu-dresden/organisation/gremien-und-beauftragte/beauftragte/datenschutzbeauftragter\nrole:\n  value: controller\n  text: 'Dresden University of Technology Contact person: ScaDS.AI Dresden/Leipzig'\ndata_categories:\n- category: identifying\n  text: We associate your API key with your name and optionally a group membership that you provided when requesting\n\
  \    a key.\n- category: behavioral\n  text: 'We log every request sent with your key, which includes the following data: key user''s name time of request\n    requested model processed number of input and output tokens'\n- category: device\n  text: We process device and usage data (e.g. browser type, operating system, IP address, usage times).\n- category: communication\n  text: To provide the services we process any content that you send in a request to the API. We do not save the\n    content of your prompt or the model's answer.\n- category: identifying\n  text: Die einem Service Provider (SP) zu übermittelnden Daten (Attribute) werden dem Nutzer nach der erfolgreichen\n    Authentifizierung gegenüber dem ZIH am Identity Provider zunächst angezeigt.\n  source: https://idp.tu-dresden.de/dataprivacy/\n- category: identifying\n  text: Gegenüber vielen Service Providern genügt eine anonyme Identifikation mittels einer sogenannten transientId\n  source: https://idp.tu-dresden.de/dataprivacy/\n\
  purposes:\n- purpose: Research, text and idea generation\n  text: Support with research, text and idea generation\n- purpose: Administrative and organizational activities\n  text: Facilitation of administrative and organizational activities\n- purpose: Image material\n  text: Creation or evaluation of image material\n- purpose: Audio material evaluation\n  text: Evaluation of audio material\n- purpose: Teaching, research and administration support\n  text: Promotion of teaching, research, and administration through digital assistance functions.\n- purpose: Authentication and authorization\n  text: Der IdP dient zur Authentifizierung und Autorisierung der Nutzer der TU Dresden gegenüber Anbietern, sogenannten\n    Service Providern (SPs), im Rahmen der DFN-AAI.\n  source: https://idp.tu-dresden.de/dataprivacy/\n- purpose: Data minimisation\n  text: Das ZIH trägt dafür Sorge, dass nur Attribute herausgegeben werden können, die für die Erbringung des Dienstes\n    des Serviceproviders erforderlich\
  \ sind.\n  source: https://idp.tu-dresden.de/dataprivacy/\nretention:\n- scope: Usage data\n  period: one year\n  text: We generally store this data for one year, but no longer than until the end of the contractual relationship.\n- scope: Web server software logs\n  period: 90 days\n  text: The web server software logs are deleted after 90 days.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights:\n- right: Information\n  text: You have the right to request information about the data processed about you and the possible recipients\n    of this data at any time.\n- right: Rectification, erasure and restriction\n  text: You may at any time request TU Dresden to correct or erase your personal data or to restrict processing.\n- right: Withdraw consent\n  text: Consent can be refused or revoked at any time informally and without giving reasons to the person responsible.\n\
  - right: Data portability\n  text: You may request that the controller(s) transmit your personal data to you in machine-readable form.\n- right: Object\n  text: You have the right to object, on grounds relating to your particular situation, at any time to processing\n    of personal data concerning you which is based on point (e) of Article 6(1).\n- right: Complain to supervisory authority\n  text: You can contact the TU Dresden data protection officer at any time (see above) as well as a supervisory\n    authority for data protection in the event of a complaint pursuant to Art. 77 GDPR.\n- right: Withdraw consent to data transfer\n  text: Haben Sie der Übermittlung personenbeziehbarer Daten an den Serviceprovider zugestimmt und wollen Sie dies\n    widerrufen, so wenden Sie sich bitte direkt an den entsprechenden Serviceprovider.\n  source: https://idp.tu-dresden.de/dataprivacy/\n- right: Information on processed data\n  text: they have the right to request information divulging what\
  \ data pertaining to their person has been processed\n    by which area of the university and on what legal basis\n  source: https://tu-dresden.de/tu-dresden/organisation/gremien-und-beauftragte/beauftragte/datenschutzbeauftragter\n- right: Non-discrimination\n  text: No one may be discriminated against or reprimanded for exercising their rights.\n  source: https://tu-dresden.de/tu-dresden/organisation/gremien-und-beauftragte/beauftragte/datenschutzbeauftragter\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tu-dresden/privacy/tu-dresden-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- rights
summary_line: 25 quoted statements, read from TU Dresden's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Germany
- Saxony
- TU9
- Research
- Research Data
- Research Computing
- Artificial Intelligence
- Identity Federation
- OAI-PMH
- Institutional Repository
- Open Access
---
