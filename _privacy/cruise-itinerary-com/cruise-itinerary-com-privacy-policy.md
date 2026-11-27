---
api_specs:
- filename: cruise-itinerary-com-bulk-exports-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Bulk exports API
  slug: cruise-itinerary-com-bulk-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-bulk-exports-api-openapi.yml
- filename: cruise-itinerary-com-changes-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Changes API
  slug: cruise-itinerary-com-changes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-changes-api-openapi.yml
- filename: cruise-itinerary-com-cruise-itinerary-data-api-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Cruise Itinerary Data API
  slug: cruise-itinerary-com-cruise-itinerary-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-cruise-itinerary-data-api-api-openapi.yml
- filename: cruise-itinerary-com-price-index-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Price index API
  slug: cruise-itinerary-com-price-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-price-index-api-openapi.yml
- filename: cruise-itinerary-com-reference-data-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Reference data API
  slug: cruise-itinerary-com-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-reference-data-api-openapi.yml
- filename: cruise-itinerary-com-resolver-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Resolver API
  slug: cruise-itinerary-com-resolver-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-resolver-api-openapi.yml
- filename: cruise-itinerary-com-sailings-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Sailings API
  slug: cruise-itinerary-com-sailings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-sailings-api-openapi.yml
- filename: cruise-itinerary-com-service-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Service API
  slug: cruise-itinerary-com-service-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-service-api-openapi.yml
- filename: cruise-itinerary-com-ships-and-ports-api-openapi.yml
  format: yaml
  label: cruise-itinerary-com Ships and ports API
  slug: cruise-itinerary-com-ships-and-ports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cruise-itinerary-com/openapi/cruise-itinerary-com-ships-and-ports-api-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address, a company name if you give one, and how you reached sign-up
  - category: contact
    text: Your email address, a hash of your confirmation token, and the times you confirmed and unsubscribed.
  - category: financial
    text: We store your Stripe customer and subscription identifiers, your plan, billing interval, subscription status and the end of the current period
  - category: location
    text: approximate location (city, region, postal code, country and timezone, as Cloudflare reports them)
  - category: device
    text: browser user agent and language of that request
  - category: behavioral
    text: It records page views, scroll depth and whether the page was visible
  - category: identifying
    text: IP address, time, URL, status, user agent and referrer
  deletion:
    route: Email the controller at the contact address on your account
    text: Write to [email protected] from the address on your account to ask for a copy of your data, to correct it, or to delete the account.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide the Service
    text: 'To provide the Service you asked for: accounts, keys, usage limits, billing, webhooks. (Contract.)'
  - purpose: Security and fairness
    text: 'To keep it secure and fair: rate limiting, abuse prevention, logs. (Legitimate interests.)'
  - purpose: Site analytics
    text: 'To understand and improve the site: analytics. (Legitimate interests, or consent where the law requires it.)'
  - purpose: Price Index email
    text: To send the Price Index email. (Consent, which you can withdraw at any time.)
  - purpose: Legal records
    text: To keep records the law requires, such as payment records. (Legal obligation.)
  residency:
  - region: United States and other countries
    text: Your data may be processed in the United States and other countries where these providers operate.
  retention:
  - period: while your account exists
    scope: Account, key, usage and webhook records
    text: Account, key, usage and webhook records are kept while your account exists.
  - period: within an hour
    scope: Rate limiting counters
    text: which is deleted within an hour.
  - period: 90 days
    scope: AI connector call counts
    text: and we delete them after 90 days.
  - period: 90 days
    scope: Analytics events
    text: We delete these events after 90 days.
  - period: 35 days
    scope: Daily database backups
    text: daily copies are kept for 35 days
  - period: for the period those systems retain them
    scope: Server and CDN logs
    text: Server and CDN logs are kept for the period those systems retain them.
  rights:
  - right: Access
    text: to ask for a copy of your data
  - right: Correction
    text: to correct it
  - right: Deletion
    text: or to delete the account
  - right: Object or restrict processing
    text: you may also have the right to object to or restrict processing
  - right: Portability
    text: to data portability
  - right: Complain to authority
    text: and to complain to your data protection authority
  role:
    text: The controller is BigBalli Consulting LLC.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data and we do not use it for advertising.
  subprocessors:
    text: IONOS , the hosting provider whose servers run the Service.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: cruise-itinerary-com
provenance_date: '2026-11-09'
provider_name: cruise-itinerary-com
provider_slug: cruise-itinerary-com
slug: cruise-itinerary-com-privacy-policy
source_date: '2026-11-09'
source_filename: cruise-itinerary-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cruise-itinerary.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: cruise-itinerary-com\naid: cruise-itinerary-com\nurl: https://cruise-itinerary.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: The controller is BigBalli Consulting LLC.\ndata_categories:\n- category: identifying\n  text: Your email address, a company name if you give one, and how you reached sign-up\n- category: contact\n  text: Your email address, a hash of your confirmation token, and the times you confirmed and unsubscribed.\n- category: financial\n  text: We store your Stripe customer and subscription identifiers, your plan, billing interval, subscription status\n    and the\
  \ end of the current period\n- category: location\n  text: approximate location (city, region, postal code, country and timezone, as Cloudflare reports them)\n- category: device\n  text: browser user agent and language of that request\n- category: behavioral\n  text: It records page views, scroll depth and whether the page was visible\n- category: identifying\n  text: IP address, time, URL, status, user agent and referrer\npurposes:\n- purpose: Provide the Service\n  text: 'To provide the Service you asked for: accounts, keys, usage limits, billing, webhooks. (Contract.)'\n- purpose: Security and fairness\n  text: 'To keep it secure and fair: rate limiting, abuse prevention, logs. (Legitimate interests.)'\n- purpose: Site analytics\n  text: 'To understand and improve the site: analytics. (Legitimate interests, or consent where the law requires\n    it.)'\n- purpose: Price Index email\n  text: To send the Price Index email. (Consent, which you can withdraw at any time.)\n- purpose: Legal\
  \ records\n  text: To keep records the law requires, such as payment records. (Legal obligation.)\nretention:\n- scope: Account, key, usage and webhook records\n  period: while your account exists\n  text: Account, key, usage and webhook records are kept while your account exists.\n- scope: Rate limiting counters\n  period: within an hour\n  text: which is deleted within an hour.\n- scope: AI connector call counts\n  period: 90 days\n  text: and we delete them after 90 days.\n- scope: Analytics events\n  period: 90 days\n  text: We delete these events after 90 days.\n- scope: Daily database backups\n  period: 35 days\n  text: daily copies are kept for 35 days\n- scope: Server and CDN logs\n  period: for the period those systems retain them\n  text: Server and CDN logs are kept for the period those systems retain them.\nresidency:\n- region: United States and other countries\n  text: Your data may be processed in the United States and other countries where these providers operate.\ntransfers:\
  \ []\nsubprocessors:\n  url: null\n  text: IONOS , the hosting provider whose servers run the Service.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email the controller at the contact address on your account\n  text: Write to [email protected] from the address on your account to ask for a copy of your data, to correct it,\n    or to delete the account.\nrights:\n- right: Access\n  text: to ask for a copy of your data\n- right: Correction\n  text: to correct it\n- right: Deletion\n  text: or to delete the account\n- right: Object or restrict processing\n  text: you may also have the right to object to or restrict processing\n- right: Portability\n  text: to data portability\n- right: Complain to authority\n  text: and to complain to your data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal data and we do not use it for advertising.\n"
source_yaml_url: https://artifacts.apis.io/cruise-itinerary-com/privacy/cruise-itinerary-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 29 quoted statements, read from cruise-itinerary-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Data
- Cruise
---
