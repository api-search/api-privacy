---
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data, name, email, profile image, hashed password (bcrypt), and tokens issued by the identity provider you sign in with (Google, X/Twitter)
  - category: financial
    text: Billing & buyer data required by our payment processor iyzico, full name, surname, GSM/mobile phone number, billing email, government identity number (for Turkish payments, T.C. Kimlik No)
  - category: location
    text: approximate location derived from your IP address
  - category: device
    text: Device and connection data, browser type, device type, operating system, screen size, language, time zone
  - category: behavioral
    text: Session replays and heatmaps, if you accept analytics cookies, Microsoft Clarity records a pseudonymous reconstruction of your interactions (mouse movement, scrolls, clicks)
  - category: communication
    text: Communications, bug reports (title, description, steps to reproduce, expected/actual behavior, severity, contact email), export feedback (rating, comment, optional project info, optional public-review opt-in), and any free-text you send us
  deletion:
    route: email to help@appscreenstudio.com
    text: To exercise any right, email us at the address in section 17.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operate the Service
    text: Operate the Service, provide the editor, store your projects, render exports, and serve your assets
  - purpose: Run AI features
    text: Run AI features, forward your prompts and reference images to Google Gemini and (when configured) OpenAI for inference
  - purpose: Process payments
    text: Process payments, pass your buyer information to iyzico to initialize a checkout form, verify the callback, allocate credits or activate your Pro subscription, and issue an invoice
  - purpose: Analytics and experiments
    text: Provide product analytics and A/B tests, analyze aggregate usage, route feature flags, and run experiments via PostHog
  - purpose: Advertising
    text: Show ads and measure conversions, operate Google AdSense and Google Ads (and optional rewarded ads via Google Ad Manager)
  residency:
  - region: Germany (eu-central-1, Frankfurt)
    text: AWS S3 (eu-central-1, Frankfurt, Germany), your uploaded screenshots, AI-generated images
  retention:
  - period: 30 days
    scope: Account data
    text: Account data, kept for the life of your account; deleted within 30 days after account deletion, except where law requires longer retention
  - period: 10 years
    scope: Payment records and invoices
    text: Payment records and invoices, kept up to 10 years to comply with tax and commercial law
  - period: 24 months
    scope: AI usage logs
    text: AI usage logs (LLMUsage), kept up to 24 months for billing, abuse-prevention, and quality review, then deleted or aggregated
  - period: 90 days
    scope: Server and security logs
    text: Server and security logs, kept up to 90 days
  rights:
  - right: Access
    text: Right to access, request a copy of the personal data we hold about you
  - right: Rectification
    text: Right to rectification, ask us to correct inaccurate or incomplete data
  - right: Erasure
    text: Right to erasure ("right to be forgotten"), ask us to delete your data, subject to legal retention obligations
  - right: Portability
    text: Right to data portability, receive your data in a machine-readable format and/or have it transmitted to another controller
  - right: Object
    text: Right to object, object to processing based on legitimate interests, including profiling, and to direct marketing at any time
  - right: Withdraw consent
    text: Right to withdraw consent, where processing is based on consent, withdraw it without affecting prior processing
  role:
    text: AppScreenStudio is the data controller for personal data processed through the Service.
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for money. Our use of Google AdSense and Google Ads may qualify as "sharing" for cross-context behavioral advertising under the CPRA; you can opt out by declining cookies in our banner or by sending us a request
  subprocessors:
    text: 'Google LLC, Gemini API (Generative AI) : Receives the screenshot, reference image, and/or text prompt you submit'
    url: null
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (SCCs), the UK International Data Transfer Addendum, the EU–US Data Privacy Framework where the recipient is certified, or other lawful transfer mechanisms
  - mechanism: DPF
    text: the EU–US Data Privacy Framework where the recipient is certified
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AppScreenStudio
provenance_date: '2026-11-09'
provider_name: AppScreenStudio
provider_slug: appscreenstudio-com
slug: appscreenstudio-com-privacy-policy
source_date: '2026-11-09'
source_filename: appscreenstudio-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.appscreenstudio.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AppScreenStudio\naid: appscreenstudio-com\nurl: https://www.appscreenstudio.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: AppScreenStudio is the data controller for personal data processed through the Service.\ndata_categories:\n- category: identifying\n  text: Account data, name, email, profile image, hashed password (bcrypt), and tokens issued by the identity provider\n    you sign in with (Google, X/Twitter)\n- category: financial\n  text: Billing & buyer data required by our payment processor iyzico, full name, surname, GSM/mobile phone number,\n    billing email, government\
  \ identity number (for Turkish payments, T.C. Kimlik No)\n- category: location\n  text: approximate location derived from your IP address\n- category: device\n  text: Device and connection data, browser type, device type, operating system, screen size, language, time zone\n- category: behavioral\n  text: Session replays and heatmaps, if you accept analytics cookies, Microsoft Clarity records a pseudonymous\n    reconstruction of your interactions (mouse movement, scrolls, clicks)\n- category: communication\n  text: Communications, bug reports (title, description, steps to reproduce, expected/actual behavior, severity,\n    contact email), export feedback (rating, comment, optional project info, optional public-review opt-in), and\n    any free-text you send us\npurposes:\n- purpose: Operate the Service\n  text: Operate the Service, provide the editor, store your projects, render exports, and serve your assets\n- purpose: Run AI features\n  text: Run AI features, forward your prompts and\
  \ reference images to Google Gemini and (when configured) OpenAI\n    for inference\n- purpose: Process payments\n  text: Process payments, pass your buyer information to iyzico to initialize a checkout form, verify the callback,\n    allocate credits or activate your Pro subscription, and issue an invoice\n- purpose: Analytics and experiments\n  text: Provide product analytics and A/B tests, analyze aggregate usage, route feature flags, and run experiments\n    via PostHog\n- purpose: Advertising\n  text: Show ads and measure conversions, operate Google AdSense and Google Ads (and optional rewarded ads via Google\n    Ad Manager)\nretention:\n- scope: Account data\n  period: 30 days\n  text: Account data, kept for the life of your account; deleted within 30 days after account deletion, except where\n    law requires longer retention\n- scope: Payment records and invoices\n  period: 10 years\n  text: Payment records and invoices, kept up to 10 years to comply with tax and commercial law\n\
  - scope: AI usage logs\n  period: 24 months\n  text: AI usage logs (LLMUsage), kept up to 24 months for billing, abuse-prevention, and quality review, then deleted\n    or aggregated\n- scope: Server and security logs\n  period: 90 days\n  text: Server and security logs, kept up to 90 days\nresidency:\n- region: Germany (eu-central-1, Frankfurt)\n  text: AWS S3 (eu-central-1, Frankfurt, Germany), your uploaded screenshots, AI-generated images\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (SCCs), the UK International Data Transfer\n    Addendum, the EU–US Data Privacy Framework where the recipient is certified, or other lawful transfer mechanisms\n- mechanism: DPF\n  text: the EU–US Data Privacy Framework where the recipient is certified\nsubprocessors:\n  url: null\n  text: 'Google LLC, Gemini API (Generative AI) : Receives the screenshot, reference image, and/or text prompt you\n    submit'\ndpa:\n  available: null\n  url: null\n\
  \  text: null\ndeletion:\n  route: email to help@appscreenstudio.com\n  text: To exercise any right, email us at the address in section 17.\nrights:\n- right: Access\n  text: Right to access, request a copy of the personal data we hold about you\n- right: Rectification\n  text: Right to rectification, ask us to correct inaccurate or incomplete data\n- right: Erasure\n  text: Right to erasure (\"right to be forgotten\"), ask us to delete your data, subject to legal retention obligations\n- right: Portability\n  text: Right to data portability, receive your data in a machine-readable format and/or have it transmitted to\n    another controller\n- right: Object\n  text: Right to object, object to processing based on legitimate interests, including profiling, and to direct\n    marketing at any time\n- right: Withdraw consent\n  text: Right to withdraw consent, where processing is based on consent, withdraw it without affecting prior processing\nsale_or_sharing:\n  stance: conditional\n  text:\
  \ We do not sell personal information for money. Our use of Google AdSense and Google Ads may qualify as \"sharing\"\n    for cross-context behavioral advertising under the CPRA; you can opt out by declining cookies in our banner\n    or by sending us a request\n"
source_yaml_url: https://artifacts.apis.io/appscreenstudio-com/privacy/appscreenstudio-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from AppScreenStudio's own page on 2026-11-09.
synthetic: false
tags:
- AppScreenStudio
- ScreenshotGenerator
- Mobile Development
- AI Integration
---
