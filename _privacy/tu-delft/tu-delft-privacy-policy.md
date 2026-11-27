---
api_specs:
- filename: tu-delft-account-api-openapi.yml
  format: yaml
  label: Delft University of Technology Account API
  slug: tu-delft-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tu-delft/openapi/tu-delft-account-api-openapi.yml
- filename: tu-delft-collections-api-openapi.yml
  format: yaml
  label: Delft University of Technology Collections API
  slug: tu-delft-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tu-delft/openapi/tu-delft-collections-api-openapi.yml
- filename: tu-delft-datasets-api-openapi.yml
  format: yaml
  label: Delft University of Technology Datasets API
  slug: tu-delft-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tu-delft/openapi/tu-delft-datasets-api-openapi.yml
- filename: tu-delft-reference-api-openapi.yml
  format: yaml
  label: Delft University of Technology Reference API
  slug: tu-delft-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tu-delft/openapi/tu-delft-reference-api-openapi.yml
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: Identification details (such as name and address, date and place of birth, student number, NetID)
  - category: contact
    text: Contact details and e-data (such as e-mail address, telephone number, logging, IP addresses)
  - category: health
    text: Health data (such as physical and psychological data in the context of study facilities and study support)
  - category: financial
    text: Financial data (such as bank account number and tuition fee payments)
  - category: biometric
    text: Image and sound recordings (e.g. photo, video)
  - category: location
    text: Location data (such as teaching timetable, workplace, room reservation)
  - category: demographic
    text: Nationality
  deletion:
    route: Request to privacy-tud@tudelft.nl
    text: 'Right to ''be forgotten'': you can request that your personal data be deleted from the TU Delft files.'
  dpa:
    available: true
    text: These agreements are laid down contractually in data processing agreements.
    url: null
  purposes:
  - purpose: Application and enrolment
    text: Application, selection and enrolment in a degree programme
  - purpose: Security and access control
    text: Monitoring the safety of people, goods and buildings on the campus, including access control and camera surveillance
  - purpose: Recruitment and staff administration
    text: Well-organised recruitment and selection of staff members
  retention:
  - period: null
    scope: Personal data generally
    text: The data is retained in accordance with the statutory retention period and for no longer than is strictly necessary in order to achieve the purposes for which the data was collected.
  rights:
  - right: Access
    text: 'Right to access: you can request an overview and/or inspection of the personal data that we process about you.'
  - right: Rectification
    text: 'Right to rectification: if there are demonstrable mistakes in your personal data or they are incomplete, you can ask for the data to be rectified or added.'
  - right: Erasure
    text: 'Right to ''be forgotten'': you can request that your personal data be deleted from the TU Delft files.'
  - right: Restriction
    text: 'Right to restrict the processing of your personal data: in certain cases you can ask TU Delft to stop processing your personal data temporarily.'
  - right: Portability
    text: 'Right to data portability: in certain cases you can request that your personal data be transferred to an organisation designated by you.'
  - right: Objection
    text: 'Right to object to the processing of your personal data: in certain situations you can object to the processing of your personal data.'
  role:
    text: Data controller and responsibility TU Delft considers it to be of essential importance that the personal data of its students, researchers, staff and visitors is processed and secured with the utmost possible care.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: TU Delft will not sell your personal data to third parties.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: TU Delft assesses each transfer of personal data by means of a standard process for the application of appropriate measures in order to guarantee an adequate level of protection for the processing of personal data both within and outside the EU.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Delft University of Technology
provenance_date: '2026-11-10'
provider_name: Delft University of Technology
provider_slug: tu-delft
slug: tu-delft-privacy-policy
source_date: '2026-11-10'
source_filename: tu-delft-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.tudelft.nl/en/privacy-statement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Delft University of Technology\naid: tu-delft\nurl: https://www.tudelft.nl/en/privacy-statement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Data controller and responsibility TU Delft considers it to be of essential importance that the personal\n    data of its students, researchers, staff and visitors is processed and secured with the utmost possible care.\ndata_categories:\n- category: identifying\n  text: Identification details (such as name and address, date and place of birth, student number, NetID)\n- category: contact\n  text: Contact details and e-data (such as e-mail address, telephone\
  \ number, logging, IP addresses)\n- category: health\n  text: Health data (such as physical and psychological data in the context of study facilities and study support)\n- category: financial\n  text: Financial data (such as bank account number and tuition fee payments)\n- category: biometric\n  text: Image and sound recordings (e.g. photo, video)\n- category: location\n  text: Location data (such as teaching timetable, workplace, room reservation)\n- category: demographic\n  text: Nationality\npurposes:\n- purpose: Application and enrolment\n  text: Application, selection and enrolment in a degree programme\n- purpose: Security and access control\n  text: Monitoring the safety of people, goods and buildings on the campus, including access control and camera\n    surveillance\n- purpose: Recruitment and staff administration\n  text: Well-organised recruitment and selection of staff members\nretention:\n- scope: Personal data generally\n  period: null\n  text: The data is retained in accordance\
  \ with the statutory retention period and for no longer than is strictly\n    necessary in order to achieve the purposes for which the data was collected.\nresidency: []\ntransfers:\n- mechanism: other\n  text: TU Delft assesses each transfer of personal data by means of a standard process for the application of appropriate\n    measures in order to guarantee an adequate level of protection for the processing of personal data both within\n    and outside the EU.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: These agreements are laid down contractually in data processing agreements.\ndeletion:\n  route: Request to privacy-tud@tudelft.nl\n  text: 'Right to ''be forgotten'': you can request that your personal data be deleted from the TU Delft files.'\nrights:\n- right: Access\n  text: 'Right to access: you can request an overview and/or inspection of the personal data that we process about\n    you.'\n- right: Rectification\n  text: 'Right to rectification:\
  \ if there are demonstrable mistakes in your personal data or they are incomplete,\n    you can ask for the data to be rectified or added.'\n- right: Erasure\n  text: 'Right to ''be forgotten'': you can request that your personal data be deleted from the TU Delft files.'\n- right: Restriction\n  text: 'Right to restrict the processing of your personal data: in certain cases you can ask TU Delft to stop processing\n    your personal data temporarily.'\n- right: Portability\n  text: 'Right to data portability: in certain cases you can request that your personal data be transferred to an\n    organisation designated by you.'\n- right: Objection\n  text: 'Right to object to the processing of your personal data: in certain situations you can object to the processing\n    of your personal data.'\nsale_or_sharing:\n  stance: prohibited\n  text: TU Delft will not sell your personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/tu-delft/privacy/tu-delft-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Delft University of Technology's own page on 2026-11-10.
synthetic: false
tags:
- University
- Higher Education
- Education
- Technical University
- Research Data
- Open Access
- Identity Federation
- Research Repository
- Research Computing
- 4TU.Federation
- Netherlands
- Europe
- Research
- Engineering
---
