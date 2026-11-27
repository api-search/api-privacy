---
api_specs:
- filename: twittrapi-com-account-actions-api-openapi.yml
  format: yaml
  label: twittrapi-com Account actions API
  slug: twittrapi-com-account-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-account-actions-api-openapi.yml
- filename: twittrapi-com-account-api-openapi.yml
  format: yaml
  label: twittrapi-com Account API
  slug: twittrapi-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-account-api-openapi.yml
- filename: twittrapi-com-communities-api-openapi.yml
  format: yaml
  label: twittrapi-com Communities API
  slug: twittrapi-com-communities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-communities-api-openapi.yml
- filename: twittrapi-com-jobs-api-openapi.yml
  format: yaml
  label: twittrapi-com Jobs API
  slug: twittrapi-com-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-jobs-api-openapi.yml
- filename: twittrapi-com-lists-api-openapi.yml
  format: yaml
  label: twittrapi-com Lists API
  slug: twittrapi-com-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-lists-api-openapi.yml
- filename: twittrapi-com-misc-api-openapi.yml
  format: yaml
  label: twittrapi-com Misc API
  slug: twittrapi-com-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-misc-api-openapi.yml
- filename: twittrapi-com-search-api-openapi.yml
  format: yaml
  label: twittrapi-com Search API
  slug: twittrapi-com-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-search-api-openapi.yml
- filename: twittrapi-com-trends-api-openapi.yml
  format: yaml
  label: twittrapi-com Trends API
  slug: twittrapi-com-trends-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-trends-api-openapi.yml
- filename: twittrapi-com-tweets-api-openapi.yml
  format: yaml
  label: twittrapi-com Tweets API
  slug: twittrapi-com-tweets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-tweets-api-openapi.yml
- filename: twittrapi-com-users-api-openapi.yml
  format: yaml
  label: twittrapi-com Users API
  slug: twittrapi-com-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twittrapi-com/openapi/twittrapi-com-users-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: 'Account data: email address, password (stored only as a hash), API key and account settings.'
  - category: financial
    text: 'Business and billing data: company name, VAT ID, country, contact for card requests, invoices and Balance transactions.'
  - category: device
    text: 'Security data: IP address, IP-based country and a coarse browser fingerprint at registration and login, a random device ID at registration, failed login attempts, and a bot check (Cloudflare Turnstile) at registration.'
  - category: behavioral
    text: 'PostHog (PostHog Inc., EU cloud in Frankfurt, as our processor) records page views and interactions: clicks on buttons and links, tab changes, the price calculator, the endpoint explorer'
  - category: location
    text: our website attaches only this country to the events; no city, region or coordinates, and the IP address is neither read for this nor stored.
  deletion:
    route: Delete your account
    text: When you delete your account, we delete or anonymise your personal data within 30 days, subject to these statutory retention obligations.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Hosting and security of the website
    text: When you open a page, your browser sends technical data (for example IP address, browser type, requested URL and time) that the hosting provider processes to deliver the page and keep it secure
  - purpose: Website analytics
    text: We measure how the website is used so we can see which content helps visitors and where the way to an account or a purchase breaks off.
  - purpose: Account, authentication, communication
    text: 'Purpose: account, authentication, communication. Legal basis: Art. 6(1)(b) GDPR (contract).'
  - purpose: Billing and taxes
    text: 'Purpose: billing, taxes. Legal basis: Art. 6(1)(b) and (c) GDPR.'
  - purpose: Preventing abuse and duplicate trial accounts
    text: 'Purpose: preventing abuse, duplicate trial accounts and brute-force attacks. Legal basis: Art. 6(1)(f) GDPR.'
  - purpose: Product emails and offers
    text: 'Product updates and offers (only with your consent): if you tick the optional box at sign-up or on the "Email preferences" page, we email you product updates and offers, at most twice a month.'
  residency:
  - region: EU (Frankfurt)
    text: PostHog (PostHog Inc., EU cloud in Frankfurt, as our processor)
  retention:
  - period: 24 hours
    scope: Request logs
    text: Request logs are deleted after 24 hours.
  - period: 7 days
    scope: Monitoring deliveries
    text: Delivered posts are kept for 7 days
  - period: 10 years
    scope: Invoices and booking records
    text: Invoices and booking records are kept for up to 10 years as required by commercial and tax law.
  - period: 24 months
    scope: Analytics events
    text: 'Retention: analytics events are deleted after 24 months at the latest.'
  - period: 30 days
    scope: Account deletion
    text: When you delete your account, we delete or anonymise your personal data within 30 days, subject to these statutory retention obligations.
  rights:
  - right: access
    text: Under Arts. 15–21 GDPR you have the right of access, rectification, erasure, restriction of processing, data portability and the right to object to processing based on legitimate interests.
  - right: withdraw consent
    text: You can withdraw any consent at any time with effect for the future (Art. 7(3) GDPR)
  - right: object to direct marketing
    text: object to the use of your data for direct marketing at any time (Art. 21(2) GDPR)
  - right: complaint
    text: You also have the right to lodge a complaint with a data protection supervisory authority (Art. 77 GDPR)
  role:
    text: The controller within the meaning of Art. 4(7) GDPR for this website ( www.twittrapi.com ), the dashboard (app.twittrapi.com) and the API is TwittrAPI
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and do not share it with others for their advertising.
  subprocessors:
    text: Hosting and infrastructure providers (servers, databases, website hosting, email delivery), which process data on our behalf.
    url: null
  transfers:
  - mechanism: SCC
    text: PostHog Inc. is based in the USA; access from there is covered by the EU standard contractual clauses.
  - mechanism: adequacy
    text: Where providers process data outside the EU/EEA, this happens on the basis of an adequacy decision or the EU standard contractual clauses.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: twittrapi-com
provenance_date: '2026-11-10'
provider_name: twittrapi-com
provider_slug: twittrapi-com
slug: twittrapi-com-privacy-policy
source_date: '2026-11-10'
source_filename: twittrapi-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.twittrapi.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: twittrapi-com\naid: twittrapi-com\nurl: https://www.twittrapi.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller within the meaning of Art. 4(7) GDPR for this website ( www.twittrapi.com ), the dashboard\n    (app.twittrapi.com) and the API is TwittrAPI\ndata_categories:\n- category: contact\n  text: 'Account data: email address, password (stored only as a hash), API key and account settings.'\n- category: financial\n  text: 'Business and billing data: company name, VAT ID, country, contact for card requests, invoices and Balance\n    transactions.'\n- category: device\n\
  \  text: 'Security data: IP address, IP-based country and a coarse browser fingerprint at registration and login,\n    a random device ID at registration, failed login attempts, and a bot check (Cloudflare Turnstile) at registration.'\n- category: behavioral\n  text: 'PostHog (PostHog Inc., EU cloud in Frankfurt, as our processor) records page views and interactions: clicks\n    on buttons and links, tab changes, the price calculator, the endpoint explorer'\n- category: location\n  text: our website attaches only this country to the events; no city, region or coordinates, and the IP address\n    is neither read for this nor stored.\npurposes:\n- purpose: Hosting and security of the website\n  text: When you open a page, your browser sends technical data (for example IP address, browser type, requested\n    URL and time) that the hosting provider processes to deliver the page and keep it secure\n- purpose: Website analytics\n  text: We measure how the website is used so we can see which\
  \ content helps visitors and where the way to an account\n    or a purchase breaks off.\n- purpose: Account, authentication, communication\n  text: 'Purpose: account, authentication, communication. Legal basis: Art. 6(1)(b) GDPR (contract).'\n- purpose: Billing and taxes\n  text: 'Purpose: billing, taxes. Legal basis: Art. 6(1)(b) and (c) GDPR.'\n- purpose: Preventing abuse and duplicate trial accounts\n  text: 'Purpose: preventing abuse, duplicate trial accounts and brute-force attacks. Legal basis: Art. 6(1)(f)\n    GDPR.'\n- purpose: Product emails and offers\n  text: 'Product updates and offers (only with your consent): if you tick the optional box at sign-up or on the\n    \"Email preferences\" page, we email you product updates and offers, at most twice a month.'\nretention:\n- scope: Request logs\n  period: 24 hours\n  text: Request logs are deleted after 24 hours.\n- scope: Monitoring deliveries\n  period: 7 days\n  text: Delivered posts are kept for 7 days\n- scope: Invoices and\
  \ booking records\n  period: 10 years\n  text: Invoices and booking records are kept for up to 10 years as required by commercial and tax law.\n- scope: Analytics events\n  period: 24 months\n  text: 'Retention: analytics events are deleted after 24 months at the latest.'\n- scope: Account deletion\n  period: 30 days\n  text: When you delete your account, we delete or anonymise your personal data within 30 days, subject to these\n    statutory retention obligations.\nresidency:\n- region: EU (Frankfurt)\n  text: PostHog (PostHog Inc., EU cloud in Frankfurt, as our processor)\ntransfers:\n- mechanism: SCC\n  text: PostHog Inc. is based in the USA; access from there is covered by the EU standard contractual clauses.\n- mechanism: adequacy\n  text: Where providers process data outside the EU/EEA, this happens on the basis of an adequacy decision or the\n    EU standard contractual clauses.\nsubprocessors:\n  url: null\n  text: Hosting and infrastructure providers (servers, databases, website\
  \ hosting, email delivery), which process\n    data on our behalf.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Delete your account\n  text: When you delete your account, we delete or anonymise your personal data within 30 days, subject to these\n    statutory retention obligations.\nrights:\n- right: access\n  text: Under Arts. 15–21 GDPR you have the right of access, rectification, erasure, restriction of processing,\n    data portability and the right to object to processing based on legitimate interests.\n- right: withdraw consent\n  text: You can withdraw any consent at any time with effect for the future (Art. 7(3) GDPR)\n- right: object to direct marketing\n  text: object to the use of your data for direct marketing at any time (Art. 21(2) GDPR)\n- right: complaint\n  text: You also have the right to lodge a complaint with a data protection supervisory authority (Art. 77 GDPR)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data\
  \ and do not share it with others for their advertising.\n"
source_yaml_url: https://artifacts.apis.io/twittrapi-com/privacy/twittrapi-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from twittrapi-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Twitter
- X
- Data API
- MCP
---
