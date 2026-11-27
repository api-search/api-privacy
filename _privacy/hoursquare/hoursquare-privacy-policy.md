---
api_specs:
- filename: hoursquare-attendance-api-openapi.yml
  format: yaml
  label: HourSquare Attendance API
  slug: hoursquare-attendance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hoursquare/openapi/hoursquare-attendance-api-openapi.yml
- filename: hoursquare-employees-api-openapi.yml
  format: yaml
  label: HourSquare Employees API
  slug: hoursquare-employees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hoursquare/openapi/hoursquare-employees-api-openapi.yml
- filename: hoursquare-me-api-openapi.yml
  format: yaml
  label: HourSquare Me API
  slug: hoursquare-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hoursquare/openapi/hoursquare-me-api-openapi.yml
- filename: hoursquare-oauth-api-openapi.yml
  format: yaml
  label: HourSquare OAuth API
  slug: hoursquare-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hoursquare/openapi/hoursquare-oauth-api-openapi.yml
claim_count: 36
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Identity Information: Full name, job title, company name, and similar identifying details.'
  - category: contact
    text: 'Contact Information: Email address, telephone number, and business address.'
  - category: financial
    text: 'Billing Information: Billing contacts, company name, country, tax identification number, billing address, and transaction history'
  - category: location
    text: approximate geographic location derived from IP address
  - category: behavioral
    text: 'Usage Information: Pages visited, features utilized, clickstream data, session duration, and interaction patterns within the Platform.'
  - category: device
    text: 'Device Information: Device type, operating system, browser type and version, screen resolution, and unique device identifiers.'
  - category: demographic
    text: 'Personal Identification Data: Names, photographs, dates of birth, national identification numbers, and similar identifiers.'
  - category: professional
    text: 'Employment Information: Job titles, departments, employment dates, work schedules, salary information, and performance records.'
  - category: health
    text: 'Leave and Attendance Records: Vacation requests, sick leave, absences, and time tracking data.'
  - category: communication
    text: 'Correspondence Records: Emails, support tickets, chat transcripts, and other written communications.'
  deletion:
    route: Data subjects may request deletion via privacy@hoursquare.com; Subscribers may request deletion of Employee Data at any time
    text: Data subjects may request deletion of their personal data subject to applicable legal requirements and legitimate retention grounds.
  dpa:
    available: true
    text: The sub-processors that process Employee Data, and where they operate, are listed in Annex III of our Data Processing Agreement .
    url: null
  purposes:
  - purpose: Service provision and contract performance
    text: To create and manage your Account, provide access to the Platform, process transactions, deliver customer support, and fulfill our contractual obligations.
  - purpose: Compliance with legal obligations
    text: To comply with applicable laws, regulations, and legal processes, including tax reporting
  - purpose: Legitimate interests
    text: To improve and develop the Service, conduct analytics, ensure platform security, prevent fraud
  - purpose: Consent-based marketing
    text: To send marketing communications, conduct certain types of analytics, or process special categories of data where consent is required.
  residency:
  - region: Germany
    text: 'Hetzner Online GmbH (hosting of the Service: servers, databases, and file storage, in Germany)'
  retention:
  - period: three (3) years
    scope: Account data
    text: Retained for the duration of your Account and for a period of three (3) years following Account termination
  - period: seven (7) years
    scope: Billing and transaction records
    text: Retained for seven (7) years in accordance with tax and accounting requirements under Georgian law
  - period: thirty (30) days
    scope: Employee Data
    text: Retained for the duration of the Subscriber's use of the Service and for thirty (30) days following Account termination
  - period: twenty-four (24) months
    scope: Technical and usage data
    text: Generally retained for twenty-four (24) months for analytics purposes
  - period: three (3) years
    scope: Communications records
    text: Retained for three (3) years following the last interaction
  rights:
  - right: Access
    text: 'Right of Access: You have the right to request confirmation as to whether personal data concerning you is being processed'
  - right: Rectification
    text: 'Right to Rectification: You have the right to request correction of inaccurate personal data'
  - right: Erasure
    text: 'Right to Erasure: You have the right to request deletion of personal data under certain circumstances'
  - right: Restriction
    text: 'Right to Restriction of Processing: You have the right to request limitation of processing under certain circumstances'
  - right: Portability
    text: 'Right to Data Portability: You have the right to receive personal data you have provided to us in a structured, commonly used, and machine-readable format'
  - right: Object
    text: 'Right to Object: You have the right to object to processing based on legitimate interests or for direct marketing purposes.'
  - right: Withdraw consent
    text: 'Right to Withdraw Consent: Where processing is based on consent, you have the right to withdraw consent at any time'
  - right: Lodge complaint
    text: 'Right to Lodge a Complaint: You have the right to lodge a complaint with a supervisory authority'
  role:
    text: HourSquare acts as the data controller, determining the purposes and means of processing.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data to third parties.
  subprocessors:
    text: The sub-processors that process Employee Data, and where they operate, are listed in Annex III of our Data Processing Agreement .
    url: null
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses: Data transfer agreements approved by the European Commission and recognized under Georgian law.'
  - mechanism: adequacy
    text: 'Adequacy Decisions: Transfers to countries or international organizations determined by competent authorities to provide adequate data protection safeguards.'
  - mechanism: BCR
    text: 'Binding Corporate Rules: Where applicable, internal policies approved by relevant data protection authorities for transfers within a corporate group.'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: HourSquare
provenance_date: '2026-11-09'
provider_name: HourSquare
provider_slug: hoursquare
slug: hoursquare-privacy-policy
source_date: '2026-11-09'
source_filename: hoursquare-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hoursquare.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: HourSquare\naid: hoursquare\nurl: https://hoursquare.com/privacy-policy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: HourSquare acts as the data controller, determining the purposes and means of processing.\ndata_categories:\n- category: identifying\n  text: 'Identity Information: Full name, job title, company name, and similar identifying details.'\n- category: contact\n  text: 'Contact Information: Email address, telephone number, and business address.'\n- category: financial\n  text: 'Billing Information: Billing contacts, company name, country, tax identification number, billing address,\n\
  \    and transaction history'\n- category: location\n  text: approximate geographic location derived from IP address\n- category: behavioral\n  text: 'Usage Information: Pages visited, features utilized, clickstream data, session duration, and interaction\n    patterns within the Platform.'\n- category: device\n  text: 'Device Information: Device type, operating system, browser type and version, screen resolution, and unique\n    device identifiers.'\n- category: demographic\n  text: 'Personal Identification Data: Names, photographs, dates of birth, national identification numbers, and\n    similar identifiers.'\n- category: professional\n  text: 'Employment Information: Job titles, departments, employment dates, work schedules, salary information,\n    and performance records.'\n- category: health\n  text: 'Leave and Attendance Records: Vacation requests, sick leave, absences, and time tracking data.'\n- category: communication\n  text: 'Correspondence Records: Emails, support tickets,\
  \ chat transcripts, and other written communications.'\npurposes:\n- purpose: Service provision and contract performance\n  text: To create and manage your Account, provide access to the Platform, process transactions, deliver customer\n    support, and fulfill our contractual obligations.\n- purpose: Compliance with legal obligations\n  text: To comply with applicable laws, regulations, and legal processes, including tax reporting\n- purpose: Legitimate interests\n  text: To improve and develop the Service, conduct analytics, ensure platform security, prevent fraud\n- purpose: Consent-based marketing\n  text: To send marketing communications, conduct certain types of analytics, or process special categories of data\n    where consent is required.\nretention:\n- scope: Account data\n  period: three (3) years\n  text: Retained for the duration of your Account and for a period of three (3) years following Account termination\n- scope: Billing and transaction records\n  period: seven (7)\
  \ years\n  text: Retained for seven (7) years in accordance with tax and accounting requirements under Georgian law\n- scope: Employee Data\n  period: thirty (30) days\n  text: Retained for the duration of the Subscriber's use of the Service and for thirty (30) days following Account\n    termination\n- scope: Technical and usage data\n  period: twenty-four (24) months\n  text: Generally retained for twenty-four (24) months for analytics purposes\n- scope: Communications records\n  period: three (3) years\n  text: Retained for three (3) years following the last interaction\nresidency:\n- region: Germany\n  text: 'Hetzner Online GmbH (hosting of the Service: servers, databases, and file storage, in Germany)'\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses: Data transfer agreements approved by the European Commission and recognized\n    under Georgian law.'\n- mechanism: adequacy\n  text: 'Adequacy Decisions: Transfers to countries or international organizations determined\
  \ by competent authorities\n    to provide adequate data protection safeguards.'\n- mechanism: BCR\n  text: 'Binding Corporate Rules: Where applicable, internal policies approved by relevant data protection authorities\n    for transfers within a corporate group.'\nsubprocessors:\n  url: null\n  text: The sub-processors that process Employee Data, and where they operate, are listed in Annex III of our Data\n    Processing Agreement .\ndpa:\n  available: true\n  url: null\n  text: The sub-processors that process Employee Data, and where they operate, are listed in Annex III of our Data\n    Processing Agreement .\ndeletion:\n  route: Data subjects may request deletion via privacy@hoursquare.com; Subscribers may request deletion of Employee\n    Data at any time\n  text: Data subjects may request deletion of their personal data subject to applicable legal requirements and legitimate\n    retention grounds.\nrights:\n- right: Access\n  text: 'Right of Access: You have the right to request\
  \ confirmation as to whether personal data concerning you\n    is being processed'\n- right: Rectification\n  text: 'Right to Rectification: You have the right to request correction of inaccurate personal data'\n- right: Erasure\n  text: 'Right to Erasure: You have the right to request deletion of personal data under certain circumstances'\n- right: Restriction\n  text: 'Right to Restriction of Processing: You have the right to request limitation of processing under certain\n    circumstances'\n- right: Portability\n  text: 'Right to Data Portability: You have the right to receive personal data you have provided to us in a structured,\n    commonly used, and machine-readable format'\n- right: Object\n  text: 'Right to Object: You have the right to object to processing based on legitimate interests or for direct\n    marketing purposes.'\n- right: Withdraw consent\n  text: 'Right to Withdraw Consent: Where processing is based on consent, you have the right to withdraw consent\n    at any\
  \ time'\n- right: Lodge complaint\n  text: 'Right to Lodge a Complaint: You have the right to lodge a complaint with a supervisory authority'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data to third parties.\n"
source_yaml_url: https://artifacts.apis.io/hoursquare/privacy/hoursquare-privacy-policy.yml
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
summary_line: 36 quoted statements, read from HourSquare's own page on 2026-11-09.
synthetic: false
tags:
- Human Resources
- Payroll
- Time Tracking
- Workforce Management
- Software-as-a-Service
---
