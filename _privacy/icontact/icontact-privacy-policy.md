---
api_specs:
- filename: icontact-webhooks-asyncapi.yml
  format: yaml
  label: iContact REST API
  slug: rest-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/icontact/asyncapi/icontact-webhooks-asyncapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Account Information (Personal Details): Information you provide to us such as, your name; postal address; telephone and/or mobile number; email address; employer; login details, including username and password'
  - category: financial
    text: 'Transaction Information: information on how you interact with the Services, including records of products or services purchased, obtained or considered'
  - category: location
    text: We collect your IP address from which we can derive imprecise location information, for example, at the city or zip code level
  - category: device
    text: 'Device Information and Device ID: Device ID, which is a distinctive number associated with a smartphone or similar handheld device.'
  - category: behavioral
    text: 'Engagement Data: Information about (i) your visits to, and interaction and engagement with the services, content and ads on third party websites'
  - category: health
    text: We do not seek to collect or process sensitive personal information, such as, race or ethnicity, political opinions, religious or philosophical beliefs, trade union membership, physical or mental health, or sex life.
  deletion:
    route: Request via Privacy Portal or email privacy@icontact.com
    text: 'Right to Delete/Erase : You can request us to delete all the information we have collected about you.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide services as agreed
    text: To provide use of our services as agreed in the ToU.
  - purpose: Marketing with consent
    text: 'Advertising Identifiers: A user-resettable identification number for advertising associated with a device (e.g., iOS uses the Identifier for Advertising (IDFA) and Android uses Google Advertising ID). Marketing _________ Consent'
  - purpose: Direct marketing
    text: We may use the contact details you provided us to reach out to you with information regarding services that may be of interest to you, for example, upcoming promotions.
  retention:
  - period: For the life of the account and a reasonable and legally compliant time thereafter
    scope: Account information and most data
    text: For the life of the account and a reasonable and legally compliant time thereafter.
  - period: in accordance with applicable laws
    scope: Customer records
    text: Customer records will be kept in accordance with applicable laws.
  rights:
  - right: Access
    text: 'Right of Access : You can request a copy of the personal information we have collected about you from us.'
  - right: Deletion
    text: 'Right to Delete/Erase : You can request us to delete all the information we have collected about you.'
  - right: Rectification
    text: 'Right to Request Rectification : If you find that any of your information that we are processing is inaccurate, you can contact us to have your information corrected.'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: Where you are requested to consent to the processing of your personal information by IeL, you have the right to withdraw your consent at any time.'
  - right: Object to processing
    text: 'Right to Object to the Processing : You can object to our processing of your personal information via our Privacy Portal , under certain circumstances.'
  - right: Opt-out of sale or sharing (CA)
    text: 'Right to Opt-out of the Sale or Sharing for Targeted Ads (CA): Under some circumstances we may sell or share the personal data you provide to us to provide ads to you that align with your interests.'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: Under some circumstances we may sell or share the personal data you provide to us to provide ads to you that align with your interests.
  subprocessors:
    text: A list of sub-processors is available upon request.
    url: null
  transfers:
  - mechanism: DPF
    text: Email Marketing participates in the E.U.-U.S. Data Privacy Framework, the UK extension to the EU-U.S. DPF, the Swiss-U.S. Privacy Framework and the APEC Cross Border Privacy Rules System.
  - mechanism: SCC
    text: Where we transfer information from the European Economic Area (“EEA”) to a recipient outside the EEA that is not in an adequate jurisdiction, we do so on the basis of standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: iContact
provenance_date: '2026-11-09'
provider_name: iContact
provider_slug: icontact
slug: icontact-privacy-policy
source_date: '2026-11-09'
source_filename: icontact-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.icontact.com/legal/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: iContact\naid: icontact\nurl: https://www.icontact.com/legal/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: 'Account Information (Personal Details): Information you provide to us such as, your name; postal address;\n    telephone and/or mobile number; email address; employer; login details, including username and password'\n- category: financial\n  text: 'Transaction Information: information on how you interact with the Services, including records of products\n    or services purchased, obtained or considered'\n- category: location\n\
  \  text: We collect your IP address from which we can derive imprecise location information, for example, at the\n    city or zip code level\n- category: device\n  text: 'Device Information and Device ID: Device ID, which is a distinctive number associated with a smartphone\n    or similar handheld device.'\n- category: behavioral\n  text: 'Engagement Data: Information about (i) your visits to, and interaction and engagement with the services,\n    content and ads on third party websites'\n- category: health\n  text: We do not seek to collect or process sensitive personal information, such as, race or ethnicity, political\n    opinions, religious or philosophical beliefs, trade union membership, physical or mental health, or sex life.\npurposes:\n- purpose: Provide services as agreed\n  text: To provide use of our services as agreed in the ToU.\n- purpose: Marketing with consent\n  text: 'Advertising Identifiers: A user-resettable identification number for advertising associated with a\
  \ device\n    (e.g., iOS uses the Identifier for Advertising (IDFA) and Android uses Google Advertising ID). Marketing _________\n    Consent'\n- purpose: Direct marketing\n  text: We may use the contact details you provided us to reach out to you with information regarding services that\n    may be of interest to you, for example, upcoming promotions.\nretention:\n- scope: Account information and most data\n  period: For the life of the account and a reasonable and legally compliant time thereafter\n  text: For the life of the account and a reasonable and legally compliant time thereafter.\n- scope: Customer records\n  period: in accordance with applicable laws\n  text: Customer records will be kept in accordance with applicable laws.\nresidency: []\ntransfers:\n- mechanism: DPF\n  text: Email Marketing participates in the E.U.-U.S. Data Privacy Framework, the UK extension to the EU-U.S. DPF,\n    the Swiss-U.S. Privacy Framework and the APEC Cross Border Privacy Rules System.\n- mechanism:\
  \ SCC\n  text: Where we transfer information from the European Economic Area (“EEA”) to a recipient outside the EEA that\n    is not in an adequate jurisdiction, we do so on the basis of standard contractual clauses.\nsubprocessors:\n  url: null\n  text: A list of sub-processors is available upon request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request via Privacy Portal or email privacy@icontact.com\n  text: 'Right to Delete/Erase : You can request us to delete all the information we have collected about you.'\nrights:\n- right: Access\n  text: 'Right of Access : You can request a copy of the personal information we have collected about you from us.'\n- right: Deletion\n  text: 'Right to Delete/Erase : You can request us to delete all the information we have collected about you.'\n- right: Rectification\n  text: 'Right to Request Rectification : If you find that any of your information that we are processing is inaccurate,\n    you can contact us to have\
  \ your information corrected.'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent: Where you are requested to consent to the processing of your personal information\n    by IeL, you have the right to withdraw your consent at any time.'\n- right: Object to processing\n  text: 'Right to Object to the Processing : You can object to our processing of your personal information via our\n    Privacy Portal , under certain circumstances.'\n- right: Opt-out of sale or sharing (CA)\n  text: 'Right to Opt-out of the Sale or Sharing for Targeted Ads (CA): Under some circumstances we may sell or\n    share the personal data you provide to us to provide ads to you that align with your interests.'\nsale_or_sharing:\n  stance: conditional\n  text: Under some circumstances we may sell or share the personal data you provide to us to provide ads to you\n    that align with your interests.\n"
source_yaml_url: https://artifacts.apis.io/icontact/privacy/icontact-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from iContact's own page on 2026-11-09.
synthetic: false
tags:
- Email Marketing
- Marketing Automation
- Campaigns
- Contacts
- List
- Segments
- Webhook
- Email Deliverability
- Small Business
---
