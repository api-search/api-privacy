---
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: Account data — if you register, we store your email address and a reference to your account (managed by Clerk).
  - category: financial
    text: Payment data — if you pay for a transcription or top up your balance, the transaction is processed by Stripe. We do not store your card details.
  - category: communication
    text: Feedback from AI agents — the text an AI agent sends through our feedback tool and, if the agent provides one, an email address for a reply.
  - category: device
    text: Automated-client logs — when a bot, crawler or AI agent requests a page (for example a search engine or an AI assistant fetching a page), we record its IP address, the name it sends in its User-Agent header, the page requested and the time.
  - category: behavioral
    text: Website analytics — page views counted by our self-hosted Umami analytics, without cookies; and, only if you accept cookies in the banner, Google Analytics and Google Ads measurement (see Cookies).
  deletion:
    route: Dashboard → Finance → Delete account
    text: 'You can delete your account at any time (Dashboard → Finance → Delete account): your files, transcripts, file names, links and connected assistants are deleted, and your email is removed.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the service
    text: To provide the service — transcribing your audio or video and returning results.
  - purpose: Manage quota
    text: To manage your quota — tracking daily usage to apply your free daily minutes.
  - purpose: Process payments
    text: To process payments — calculating and collecting pay-as-you-go charges via Stripe.
  - purpose: Abuse protection
    text: To understand and protect against automated traffic — seeing which bots and AI agents use the site, and spotting abuse.
  retention:
  - period: within 24 hours
    scope: Audio files and transcripts
    text: Audio files and transcripts in convert.express storage — deleted within 24 hours of the job being created, or sooner when you delete the job.
  - period: 90 days
    scope: Usage records
    text: Usage records — retained for 90 days for billing and dispute resolution, then deleted.
  - period: 90 days
    scope: Automated-client logs
    text: Automated-client logs — deleted automatically after 90 days.
  - period: 24 hours
    scope: Session cookies
    text: Session cookies — expire after 24 hours.
  - period: null
    scope: Balance change records
    text: Only the record of balance changes stays, without your email, as a financial record.
  rights:
  - right: Access
    text: Access the personal data we hold about you.
  - right: Correct
    text: Correct inaccurate data.
  - right: Erasure
    text: Delete your data (right to erasure).
  - right: Object
    text: Object to processing based on legitimate interests.
  - right: Portability
    text: Data portability — receive your data in a machine-readable format.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We never sell your data, and we never use your files, transcripts or summaries for advertising, profiling or training AI models.
  subprocessors:
    text: 'Third-party processors We share data only with the following processors, strictly to deliver the service: Clerk — authentication and account management.'
    url: null
  transfers:
  - mechanism: SCC
    text: These transfers rely on the safeguards the providers offer, such as the EU Standard Contractual Clauses or the EU–US Data Privacy Framework.
  - mechanism: DPF
    text: These transfers rely on the safeguards the providers offer, such as the EU Standard Contractual Clauses or the EU–US Data Privacy Framework.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: convert.express
provenance_date: '2026-11-09'
provider_name: convert.express
provider_slug: convert-express
slug: convert-express-privacy-policy
source_date: '2026-11-09'
source_filename: convert-express-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://convert.express/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: convert.express\naid: convert-express\nurl: https://convert.express/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Account data — if you register, we store your email address and a reference to your account (managed by\n    Clerk).\n- category: financial\n  text: Payment data — if you pay for a transcription or top up your balance, the transaction is processed by Stripe.\n    We do not store your card details.\n- category: communication\n  text: Feedback from AI agents — the text an AI agent sends through our feedback tool and,\
  \ if the agent provides\n    one, an email address for a reply.\n- category: device\n  text: Automated-client logs — when a bot, crawler or AI agent requests a page (for example a search engine or\n    an AI assistant fetching a page), we record its IP address, the name it sends in its User-Agent header, the\n    page requested and the time.\n- category: behavioral\n  text: Website analytics — page views counted by our self-hosted Umami analytics, without cookies; and, only if\n    you accept cookies in the banner, Google Analytics and Google Ads measurement (see Cookies).\npurposes:\n- purpose: Provide the service\n  text: To provide the service — transcribing your audio or video and returning results.\n- purpose: Manage quota\n  text: To manage your quota — tracking daily usage to apply your free daily minutes.\n- purpose: Process payments\n  text: To process payments — calculating and collecting pay-as-you-go charges via Stripe.\n- purpose: Abuse protection\n  text: To understand and\
  \ protect against automated traffic — seeing which bots and AI agents use the site, and\n    spotting abuse.\nretention:\n- scope: Audio files and transcripts\n  period: within 24 hours\n  text: Audio files and transcripts in convert.express storage — deleted within 24 hours of the job being created,\n    or sooner when you delete the job.\n- scope: Usage records\n  period: 90 days\n  text: Usage records — retained for 90 days for billing and dispute resolution, then deleted.\n- scope: Automated-client logs\n  period: 90 days\n  text: Automated-client logs — deleted automatically after 90 days.\n- scope: Session cookies\n  period: 24 hours\n  text: Session cookies — expire after 24 hours.\n- scope: Balance change records\n  period: null\n  text: Only the record of balance changes stays, without your email, as a financial record.\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: These transfers rely on the safeguards the providers offer, such as the EU Standard Contractual Clauses\n\
  \    or the EU–US Data Privacy Framework.\n- mechanism: DPF\n  text: These transfers rely on the safeguards the providers offer, such as the EU Standard Contractual Clauses\n    or the EU–US Data Privacy Framework.\nsubprocessors:\n  url: null\n  text: 'Third-party processors We share data only with the following processors, strictly to deliver the service:\n    Clerk — authentication and account management.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Dashboard → Finance → Delete account\n  text: 'You can delete your account at any time (Dashboard → Finance → Delete account): your files, transcripts,\n    file names, links and connected assistants are deleted, and your email is removed.'\nrights:\n- right: Access\n  text: Access the personal data we hold about you.\n- right: Correct\n  text: Correct inaccurate data.\n- right: Erasure\n  text: Delete your data (right to erasure).\n- right: Object\n  text: Object to processing based on legitimate interests.\n\
  - right: Portability\n  text: Data portability — receive your data in a machine-readable format.\nsale_or_sharing:\n  stance: prohibited\n  text: We never sell your data, and we never use your files, transcripts or summaries for advertising, profiling\n    or training AI models.\n"
source_yaml_url: https://artifacts.apis.io/convert-express/privacy/convert-express-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 24 quoted statements, read from convert.express's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Transcription
- Speech To Text
- Audio
- Video
- Subtitles
- AI
- MCP
---
