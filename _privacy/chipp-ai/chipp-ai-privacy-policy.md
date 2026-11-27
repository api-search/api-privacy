---
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: your name, email address, profile photograph, account credentials, and contact details
  - category: device
    text: your Internet Protocol (IP) address, device identifiers, browser type and version, operating system
  - category: behavioral
    text: information about your activity on our platform (such as pages viewed, features used, and actions taken)
  - category: financial
    text: your payment information (such as card details) is processed securely by our third-party payment processor (Stripe)
  - category: communication
    text: 'What you share: messages, photos (from the camera or your library, only the ones you pick), files you choose, voice notes and voice call audio.'
  deletion:
    route: Delete account in the Chipp iPhone app (Settings, then Delete account) or email info@chipp.ai
    text: You can delete your account yourself in the Chipp iPhone app (Settings, then Delete account).
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account management
    text: We use your data to establish and manage your account, including facilitating account creation, authentication, and secure access to our services.
  - purpose: payments
    text: Your information is also used to process payments and transactions, which are handled securely through our third-party payment processor (Stripe).
  - purpose: analytics and improvement
    text: To improve our platform and user experience, we analyze usage data and trends using analytics tools
  - purpose: marketing
    text: With your consent, we may also send you marketing communications about new features, products, or promotions.
  - purpose: security
    text: we use data to detect, investigate, and prevent fraudulent activities, unauthorized access, and other security threats to our platform and users.
  residency:
  - region: United States
    text: All Chipp servers run on Google Cloud Platform in the United States ( us-central1 ).
  retention:
  - period: 30 days
    scope: account data after deletion request
    text: We then delete your account and its data within 30 days.
  - period: null
    scope: Google OAuth tokens and chat histories on organization deletion
    text: Copies may remain in our encrypted database backups (Google Cloud SQL retains up to 30 rolling daily backups plus 7 days of point-in-time-recovery logs) until those backups age out.
  - period: 12 months
    scope: persistent cookies
    text: Persistent cookies (such as authentication and preference cookies) are retained for up to 12 months unless you delete them sooner.
  rights:
  - right: know, deletion, correction, opt out of sale or sharing (CCPA/CPRA)
    text: the right to know what information we collect, to request deletion, to request correction, to opt out of the sale or sharing of your personal information
  role:
    text: All data processing is conducted under our direct authority and in accordance with this Privacy Policy.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: DPF
    text: we participate in and comply with the EU-U.S. Data Privacy Framework, the UK Extension to the EU-U.S. Data Privacy Framework, and the Swiss-U.S. Data Privacy Framework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: chipp-ai
provenance_date: '2026-11-09'
provider_name: chipp-ai
provider_slug: chipp-ai
slug: chipp-ai-privacy-policy
source_date: '2026-11-09'
source_filename: chipp-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://chipp.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: chipp-ai\naid: chipp-ai\nurl: https://chipp.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: All data processing is conducted under our direct authority and in accordance with this Privacy Policy.\ndata_categories:\n- category: identifying\n  text: your name, email address, profile photograph, account credentials, and contact details\n- category: device\n  text: your Internet Protocol (IP) address, device identifiers, browser type and version, operating system\n- category: behavioral\n  text: information about your activity on our platform (such as pages viewed, features used, and\
  \ actions taken)\n- category: financial\n  text: your payment information (such as card details) is processed securely by our third-party payment processor\n    (Stripe)\n- category: communication\n  text: 'What you share: messages, photos (from the camera or your library, only the ones you pick), files you choose,\n    voice notes and voice call audio.'\npurposes:\n- purpose: account management\n  text: We use your data to establish and manage your account, including facilitating account creation, authentication,\n    and secure access to our services.\n- purpose: payments\n  text: Your information is also used to process payments and transactions, which are handled securely through our\n    third-party payment processor (Stripe).\n- purpose: analytics and improvement\n  text: To improve our platform and user experience, we analyze usage data and trends using analytics tools\n- purpose: marketing\n  text: With your consent, we may also send you marketing communications about new features,\
  \ products, or promotions.\n- purpose: security\n  text: we use data to detect, investigate, and prevent fraudulent activities, unauthorized access, and other security\n    threats to our platform and users.\nretention:\n- scope: account data after deletion request\n  period: 30 days\n  text: We then delete your account and its data within 30 days.\n- scope: Google OAuth tokens and chat histories on organization deletion\n  period: null\n  text: Copies may remain in our encrypted database backups (Google Cloud SQL retains up to 30 rolling daily backups\n    plus 7 days of point-in-time-recovery logs) until those backups age out.\n- scope: persistent cookies\n  period: 12 months\n  text: Persistent cookies (such as authentication and preference cookies) are retained for up to 12 months unless\n    you delete them sooner.\nresidency:\n- region: United States\n  text: All Chipp servers run on Google Cloud Platform in the United States ( us-central1 ).\ntransfers:\n- mechanism: DPF\n  text:\
  \ we participate in and comply with the EU-U.S. Data Privacy Framework, the UK Extension to the EU-U.S. Data\n    Privacy Framework, and the Swiss-U.S. Data Privacy Framework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete account in the Chipp iPhone app (Settings, then Delete account) or email info@chipp.ai\n  text: You can delete your account yourself in the Chipp iPhone app (Settings, then Delete account).\nrights:\n- right: know, deletion, correction, opt out of sale or sharing (CCPA/CPRA)\n  text: the right to know what information we collect, to request deletion, to request correction, to opt out of\n    the sale or sharing of your personal information\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information.\n"
source_yaml_url: https://artifacts.apis.io/chipp-ai/privacy/chipp-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from chipp-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automation
- Software-as-a-Service
- HIPAA
- SOC 2
---
