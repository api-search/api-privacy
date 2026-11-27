---
claim_count: 30
description: ''
doc:
  data_categories:
  - category: identifying
    text: Inventory data (e.g. first and last name, address, company, location)
  - category: contact
    text: Contact details (e.g. e-mail address, telephone number)
  - category: financial
    text: Payment data (e.g. bank details, billing information, payment history)
  - category: device
    text: Device data (device name, country code if applicable, language, name of operating system and version)
  - category: location
    text: Country/City/Region
  - category: behavioral
    text: Content of the request (page visited)
  - category: communication
    text: Input, Output and related text (such as prompts)
  deletion:
    route: Account deletion request, or email to legal@mirelo.ai for provider-held data
    text: Contact legal@mirelo.ai to request erasure of provider-held personal data; we assess the request and any applicable retention obligations.
  dpa:
    available: true
    text: We have entered into Data Processing Agreements (DPAs) with these service providers.
    url: null
  purposes:
  - purpose: Customer communication and contract fulfilment
    text: We process this data in particular to communicate with you, to respond to your enquiries, to fulfil our contractual obligations and to safeguard our rights.
  - purpose: Development and improvement, including AI model training
    text: We may use your Input and Output to develop and improve our Services, including to train the AI Models that power them
  - purpose: Website analytics (with consent)
    text: Analytics . Help us understand how the app is used so we can improve the experience
  - purpose: Newsletter
    text: Our newsletter is sent based on your prior explicit consent (Art. 6 para. 1 sentence 1 lit. a GDPR).
  residency:
  - region: Training data store
    text: We do this by copying content into a separate training data store hosted by Amazon Web Services in Mumbai, India.
  retention:
  - period: until you delete it or your account
    scope: Content kept in Studio
    text: 'Content you keep in Studio (projects, generations, transcriptions and the files you upload for them): until you delete it or your account.'
  - period: until you delete your account
    scope: Training data
    text: 'Training data (see B.III.5): kept until you delete your account.'
  - period: 7 days
    scope: Backups
    text: 'Backups : we keep daily backups of our database for 7 days.'
  - period: 24 hours
    scope: Files uploaded through API or plugins
    text: 'Files uploaded through our API or plugins : usable for 24 hours after upload, then deleted automatically.'
  - period: null
    scope: Account deletion
    text: Remaining copies, including older file versions, backups and training data, are gone within 30 days after that.
  rights:
  - right: Access
    text: Access your personal data in accordance with Art. 15 GDPR
  - right: Rectification
    text: Rectification of inaccurate personal data in accordance with Art. 16 GDPR
  - right: Erasure
    text: Erasure of your personal data in accordance with Art. 17 GDPR
  - right: Restriction
    text: Restriction of processing in accordance with Art. 18 GDPR
  - right: Objection
    text: Objection to the processing of your data in accordance with Art. 21
  - right: Portability
    text: Data portability in accordance with Art. 20 GDPR
  - right: Complaint
    text: You also have the right to lodge a complaint with a data protection supervisory authority in accordance with Art. 77 GDPR.
  role:
    text: The Controller within the meaning of Art. 4 (7) GDPR is Mirelo AI GmbH, Eisenbahnstraße 1, 72072 Tübingen, legal@mirelo.ai
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Amazon Web Services ( Amazon Web Services EMEA SARL, Luxembourg ): hosting, file storage, media processing and storage of training data, including in Mumbai, India.'
    url: null
  transfers:
  - mechanism: DPF
    text: For these transfers we rely on the EU-U.S. Data Privacy Framework where the provider is certified under it (Art. 45 GDPR)
  - mechanism: SCC
    text: otherwise on the EU Standard Contractual Clauses (Art. 46 para. 2 lit. c GDPR).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Mirelo
provenance_date: '2026-11-10'
provider_name: Mirelo
provider_slug: mirelo
slug: mirelo-privacy-policy
source_date: '2026-11-10'
source_filename: mirelo-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://mirelo.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Mirelo\naid: mirelo\nurl: https://mirelo.ai/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The Controller within the meaning of Art. 4 (7) GDPR is Mirelo AI GmbH, Eisenbahnstraße 1, 72072 Tübingen,\n    legal@mirelo.ai\ndata_categories:\n- category: identifying\n  text: Inventory data (e.g. first and last name, address, company, location)\n- category: contact\n  text: Contact details (e.g. e-mail address, telephone number)\n- category: financial\n  text: Payment data (e.g. bank details, billing information, payment history)\n- category: device\n  text: Device data (device name, country\
  \ code if applicable, language, name of operating system and version)\n- category: location\n  text: Country/City/Region\n- category: behavioral\n  text: Content of the request (page visited)\n- category: communication\n  text: Input, Output and related text (such as prompts)\npurposes:\n- purpose: Customer communication and contract fulfilment\n  text: We process this data in particular to communicate with you, to respond to your enquiries, to fulfil our\n    contractual obligations and to safeguard our rights.\n- purpose: Development and improvement, including AI model training\n  text: We may use your Input and Output to develop and improve our Services, including to train the AI Models that\n    power them\n- purpose: Website analytics (with consent)\n  text: Analytics . Help us understand how the app is used so we can improve the experience\n- purpose: Newsletter\n  text: Our newsletter is sent based on your prior explicit consent (Art. 6 para. 1 sentence 1 lit. a GDPR).\nretention:\n\
  - scope: Content kept in Studio\n  period: until you delete it or your account\n  text: 'Content you keep in Studio (projects, generations, transcriptions and the files you upload for them): until\n    you delete it or your account.'\n- scope: Training data\n  period: until you delete your account\n  text: 'Training data (see B.III.5): kept until you delete your account.'\n- scope: Backups\n  period: 7 days\n  text: 'Backups : we keep daily backups of our database for 7 days.'\n- scope: Files uploaded through API or plugins\n  period: 24 hours\n  text: 'Files uploaded through our API or plugins : usable for 24 hours after upload, then deleted automatically.'\n- scope: Account deletion\n  period: null\n  text: Remaining copies, including older file versions, backups and training data, are gone within 30 days after\n    that.\nresidency:\n- region: Training data store\n  text: We do this by copying content into a separate training data store hosted by Amazon Web Services in Mumbai,\n   \
  \ India.\ntransfers:\n- mechanism: DPF\n  text: For these transfers we rely on the EU-U.S. Data Privacy Framework where the provider is certified under\n    it (Art. 45 GDPR)\n- mechanism: SCC\n  text: otherwise on the EU Standard Contractual Clauses (Art. 46 para. 2 lit. c GDPR).\nsubprocessors:\n  url: null\n  text: 'Amazon Web Services ( Amazon Web Services EMEA SARL, Luxembourg ): hosting, file storage, media processing\n    and storage of training data, including in Mumbai, India.'\ndpa:\n  available: true\n  url: null\n  text: We have entered into Data Processing Agreements (DPAs) with these service providers.\ndeletion:\n  route: Account deletion request, or email to legal@mirelo.ai for provider-held data\n  text: Contact legal@mirelo.ai to request erasure of provider-held personal data; we assess the request and any\n    applicable retention obligations.\nrights:\n- right: Access\n  text: Access your personal data in accordance with Art. 15 GDPR\n- right: Rectification\n  text:\
  \ Rectification of inaccurate personal data in accordance with Art. 16 GDPR\n- right: Erasure\n  text: Erasure of your personal data in accordance with Art. 17 GDPR\n- right: Restriction\n  text: Restriction of processing in accordance with Art. 18 GDPR\n- right: Objection\n  text: Objection to the processing of your data in accordance with Art. 21\n- right: Portability\n  text: Data portability in accordance with Art. 20 GDPR\n- right: Complaint\n  text: You also have the right to lodge a complaint with a data protection supervisory authority in accordance\n    with Art. 77 GDPR.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mirelo/privacy/mirelo-privacy-policy.yml
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
summary_line: 30 quoted statements, read from Mirelo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Audio
- Sound Effects
- Generative AI
- Video
- Text to Audio
- Audio to MIDI
- Machine Learning
---
