---
api_specs:
- filename: ciphera-net-openapi-generated.yml
  format: yaml
  label: Ciphera API
  slug: ciphera-net-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ciphera-net/openapi/_ae-authored/ciphera-net-openapi-generated.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address — Used for account identification, verification, and security notifications.
  - category: identifying
    text: Display name — Chosen by you, used for display and identification purposes.
  - category: device
    text: Session metadata — Login timestamps, device type, and browser information for active session management.
  - category: communication
    text: Contact form submissions — Name, email address, subject, and message content, submitted voluntarily through our contact page.
  - category: behavioral
    text: Behavioral insights — Mouse movement patterns, keystroke timing, scroll behavior, and touch input, collected solely to distinguish automated traffic from human visitors.
  - category: location
    text: Approximate location — Country, region and city, unless the site owner has narrowed it.
  deletion:
    route: Verified deletion request to privacy@ciphera.net
    text: Account data is deleted immediately and irreversibly upon a verified request
  dpa:
    available: true
    text: All third-party processors are bound by Data Processing Agreements (DPAs)
    url: null
  purposes:
  - purpose: Account management and security
    text: 'Legal basis: Contract performance (account management), legitimate interest (security).'
  - purpose: Anonymous website analytics
    text: 'Legal basis: Legitimate interest (anonymous website analytics).'
  - purpose: Sending account, security and billing email
    text: Contract performance (account, security and billing email, and the alerts and reports you set up)
  residency:
  - region: Switzerland
    text: All primary data is stored on servers located in Switzerland
  retention:
  - period: While the account is active
    scope: Account data
    text: While the account is active; deleted immediately and irreversibly on a verified deletion request
  - period: Until logout or 30 days (refresh token expiry)
    scope: Session data
    text: Until logout or 30 days (refresh token expiry)
  - period: Up to 180 days
    scope: Security audit logs
    text: Audit logs are retained for up to 180 days , then permanently deleted.
  - period: 30 days
    scope: Server logs
    text: Our own logs keep no IP addresses of visitors or users and are deleted within 30 days .
  - period: 15 minutes
    scope: CAPTCHA behavioral insights
    text: is automatically discarded within 15 minutes
  - period: 90 days
    scope: Email delivery records
    text: 90 days; 365 days for billing and security emails
  rights:
  - right: Access
    text: 'Right of Access (Article 15): You have the right to obtain confirmation of whether we process your personal data'
  - right: Rectification
    text: 'Right to Rectification (Article 16): You have the right to request correction of inaccurate personal data'
  - right: Erasure
    text: 'Right to Erasure (Article 17): You have the right to request deletion of your personal data.'
  - right: Restriction
    text: Right to Restriction of Processing (Article 18)
  - right: Portability
    text: Right to Data Portability (Article 20)
  - right: Object
    text: 'Right to Object (Article 21): You have the right to object to processing based on legitimate interest.'
  - right: Withdraw consent
    text: Right to Withdraw Consent (Article 7(3))
  - right: Lodge a complaint
    text: 'Right to Lodge a Complaint: You have the right to lodge a complaint with a supervisory authority.'
  role:
    text: 'The data controller for all Ciphera services is: Ciphera BV'
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell, trade, rent, or share your personal data with third parties for advertising or marketing purposes
  subprocessors:
    text: A complete list of sub-processor identities, including specific company names and registered addresses, is available upon request at privacy@ciphera.net .
    url: null
  transfers:
  - mechanism: SCC
    text: including Standard Contractual Clauses (SCCs) as approved by the European Commission under GDPR Article 46(2)(c)
  - mechanism: adequacy
    text: Switzerland has been recognized by the European Commission as providing an adequate level of data protection (adequacy decision under GDPR Article 45).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Ciphera
provenance_date: '2026-11-09'
provider_name: Ciphera
provider_slug: ciphera-net
slug: ciphera-net-privacy-policy
source_date: '2026-11-09'
source_filename: ciphera-net-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ciphera.net/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Ciphera\naid: ciphera-net\nurl: https://ciphera.net/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'The data controller for all Ciphera services is: Ciphera BV'\ndata_categories:\n- category: contact\n  text: Email address — Used for account identification, verification, and security notifications.\n- category: identifying\n  text: Display name — Chosen by you, used for display and identification purposes.\n- category: device\n  text: Session metadata — Login timestamps, device type, and browser information for active session management.\n- category: communication\n  text: Contact\
  \ form submissions — Name, email address, subject, and message content, submitted voluntarily through\n    our contact page.\n- category: behavioral\n  text: Behavioral insights — Mouse movement patterns, keystroke timing, scroll behavior, and touch input, collected\n    solely to distinguish automated traffic from human visitors.\n- category: location\n  text: Approximate location — Country, region and city, unless the site owner has narrowed it.\npurposes:\n- purpose: Account management and security\n  text: 'Legal basis: Contract performance (account management), legitimate interest (security).'\n- purpose: Anonymous website analytics\n  text: 'Legal basis: Legitimate interest (anonymous website analytics).'\n- purpose: Sending account, security and billing email\n  text: Contract performance (account, security and billing email, and the alerts and reports you set up)\nretention:\n- scope: Account data\n  period: While the account is active\n  text: While the account is active; deleted\
  \ immediately and irreversibly on a verified deletion request\n- scope: Session data\n  period: Until logout or 30 days (refresh token expiry)\n  text: Until logout or 30 days (refresh token expiry)\n- scope: Security audit logs\n  period: Up to 180 days\n  text: Audit logs are retained for up to 180 days , then permanently deleted.\n- scope: Server logs\n  period: 30 days\n  text: Our own logs keep no IP addresses of visitors or users and are deleted within 30 days .\n- scope: CAPTCHA behavioral insights\n  period: 15 minutes\n  text: is automatically discarded within 15 minutes\n- scope: Email delivery records\n  period: 90 days\n  text: 90 days; 365 days for billing and security emails\nresidency:\n- region: Switzerland\n  text: All primary data is stored on servers located in Switzerland\ntransfers:\n- mechanism: SCC\n  text: including Standard Contractual Clauses (SCCs) as approved by the European Commission under GDPR Article\n    46(2)(c)\n- mechanism: adequacy\n  text: Switzerland\
  \ has been recognized by the European Commission as providing an adequate level of data protection\n    (adequacy decision under GDPR Article 45).\nsubprocessors:\n  url: null\n  text: A complete list of sub-processor identities, including specific company names and registered addresses,\n    is available upon request at privacy@ciphera.net .\ndpa:\n  available: true\n  url: null\n  text: All third-party processors are bound by Data Processing Agreements (DPAs)\ndeletion:\n  route: Verified deletion request to privacy@ciphera.net\n  text: Account data is deleted immediately and irreversibly upon a verified request\nrights:\n- right: Access\n  text: 'Right of Access (Article 15): You have the right to obtain confirmation of whether we process your personal\n    data'\n- right: Rectification\n  text: 'Right to Rectification (Article 16): You have the right to request correction of inaccurate personal data'\n- right: Erasure\n  text: 'Right to Erasure (Article 17): You have the right to request\
  \ deletion of your personal data.'\n- right: Restriction\n  text: Right to Restriction of Processing (Article 18)\n- right: Portability\n  text: Right to Data Portability (Article 20)\n- right: Object\n  text: 'Right to Object (Article 21): You have the right to object to processing based on legitimate interest.'\n- right: Withdraw consent\n  text: Right to Withdraw Consent (Article 7(3))\n- right: Lodge a complaint\n  text: 'Right to Lodge a Complaint: You have the right to lodge a complaint with a supervisory authority.'\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell, trade, rent, or share your personal data with third parties for advertising or marketing\n    purposes\n"
source_yaml_url: https://artifacts.apis.io/ciphera-net/privacy/ciphera-net-privacy-policy.yml
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
summary_line: 31 quoted statements, read from Ciphera's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Privacy
- Security
- Europe
- Open Source
---
