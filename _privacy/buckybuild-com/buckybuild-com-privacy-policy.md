---
api_specs:
- filename: buckybuild-com-addresses-api-openapi.yml
  format: yaml
  label: Bucky Addresses API
  slug: buckybuild-com-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-addresses-api-openapi.yml
- filename: buckybuild-com-citations-api-openapi.yml
  format: yaml
  label: Bucky Citations API
  slug: buckybuild-com-citations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-citations-api-openapi.yml
- filename: buckybuild-com-coverage-api-openapi.yml
  format: yaml
  label: Bucky Coverage API
  slug: buckybuild-com-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-coverage-api-openapi.yml
- filename: buckybuild-com-credentials-api-openapi.yml
  format: yaml
  label: Bucky Credentials API
  slug: buckybuild-com-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-credentials-api-openapi.yml
- filename: buckybuild-com-feasibility-api-openapi.yml
  format: yaml
  label: Bucky Feasibility API
  slug: buckybuild-com-feasibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-feasibility-api-openapi.yml
- filename: buckybuild-com-marketplace-api-openapi.yml
  format: yaml
  label: Bucky Marketplace API
  slug: buckybuild-com-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-marketplace-api-openapi.yml
- filename: buckybuild-com-sites-api-openapi.yml
  format: yaml
  label: Bucky Sites API
  slug: buckybuild-com-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-sites-api-openapi.yml
- filename: buckybuild-com-usage-api-openapi.yml
  format: yaml
  label: Bucky Usage API
  slug: buckybuild-com-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buckybuild-com/openapi/buckybuild-com-usage-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: contact
    text: Email address, name, phone number if you provide one, date of birth if you provide one, user type, company, postal prefix, profile photo, social profile URLs
  - category: location
    text: Addresses, map coordinates, parcel and lot identifiers, zoning and related site facts, street-level or map imagery references, approximate location from IP geocoding, and precise location when you grant the iOS or browser permission
  - category: financial
    text: Payment-processor customer and subscription identifiers, invoices, and in-app purchase records. We do not store full card numbers.
  - category: behavioral
    text: product analytics and session recordings when allowed; error reports; search queries; and cookie preferences
  - category: device
    text: Push tokens and device metadata for iOS notifications
  - category: communication
    text: Support emails, newsletter topic preferences, demo bookings
  - category: professional
    text: we look that address up with a business-contact data provider to find your name, job title, and employer
  - category: identifying
    text: Where public records include them, we may also store registered owner names and mailing addresses for a parcel.
  deletion:
    route: Settings in the Bucky account; or email hello@buckybuild.com
    text: Use Settings to delete a Bucky account yourself.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide, secure, and improve the service
    text: Provide, secure, and improve the service, including authentication, project workspaces, maps, feasibility analysis, reports, and Assist.
  - purpose: Process payments and subscriptions
    text: Process payments, trials, and subscriptions, and send transactional email
  - purpose: Marketing email
    text: Send marketing and product-update email.
  - purpose: Product reliability and usage
    text: Understand product reliability and usage, including error monitoring that is not gated on analytics cookies.
  residency:
  - region: Canada
    text: Bucky is operated from Canada.
  - region: United States and other countries
    text: Several service providers — including those for analytics, error monitoring, payments, maps, advertising and visitor identification, email, customer relationship management, business-contact lookup, email verification, content delivery, hosting, and AI — process data in the United States or other jurisdictions.
  retention:
  - period: null
    scope: Account and project information
    text: We keep account and project information for as long as the account is open and as long as we need it to provide the service
  - period: null
    scope: Account deletion
    text: If you delete your account from Settings, we run an account-deletion process that removes or anonymizes personal information we do not have to keep.
  - period: 180 days
    scope: Cookie consent
    text: up to 180 days if you opt in; 7 days if you reject optional cookies
  rights:
  - right: access
    text: you may request access to the personal information we hold about you
  - right: correction
    text: correction of inaccuracies
  - right: deletion
    text: deletion, a portable copy, and withdrawal of consent for optional processing
  - right: portability
    text: a portable copy
  - right: withdraw consent
    text: withdrawal of consent for optional processing
  role:
    text: We provide a pre-development platform that turns an address into sourced site intelligence
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information.
  subprocessors:
    text: 'The types of provider we use today include: Type of provider What they do for Bucky'
    url: null
  transfers:
  - mechanism: other
    text: When we transfer personal information outside Canada, we use contractual and organizational measures those providers offer, and we remain responsible for the information we send.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Bucky
provenance_date: '2026-11-09'
provider_name: Bucky
provider_slug: buckybuild-com
slug: buckybuild-com-privacy-policy
source_date: '2026-11-09'
source_filename: buckybuild-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://buckybuild.com/en-us/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Bucky\naid: buckybuild-com\nurl: https://buckybuild.com/en-us/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We provide a pre-development platform that turns an address into sourced site intelligence\ndata_categories:\n- category: contact\n  text: Email address, name, phone number if you provide one, date of birth if you provide one, user type, company,\n    postal prefix, profile photo, social profile URLs\n- category: location\n  text: Addresses, map coordinates, parcel and lot identifiers, zoning and related site facts, street-level or map\n    imagery references, approximate location\
  \ from IP geocoding, and precise location when you grant the iOS or browser\n    permission\n- category: financial\n  text: Payment-processor customer and subscription identifiers, invoices, and in-app purchase records. We do not\n    store full card numbers.\n- category: behavioral\n  text: product analytics and session recordings when allowed; error reports; search queries; and cookie preferences\n- category: device\n  text: Push tokens and device metadata for iOS notifications\n- category: communication\n  text: Support emails, newsletter topic preferences, demo bookings\n- category: professional\n  text: we look that address up with a business-contact data provider to find your name, job title, and employer\n- category: identifying\n  text: Where public records include them, we may also store registered owner names and mailing addresses for a\n    parcel.\npurposes:\n- purpose: Provide, secure, and improve the service\n  text: Provide, secure, and improve the service, including authentication,\
  \ project workspaces, maps, feasibility\n    analysis, reports, and Assist.\n- purpose: Process payments and subscriptions\n  text: Process payments, trials, and subscriptions, and send transactional email\n- purpose: Marketing email\n  text: Send marketing and product-update email.\n- purpose: Product reliability and usage\n  text: Understand product reliability and usage, including error monitoring that is not gated on analytics cookies.\nretention:\n- scope: Account and project information\n  period: null\n  text: We keep account and project information for as long as the account is open and as long as we need it to\n    provide the service\n- scope: Account deletion\n  period: null\n  text: If you delete your account from Settings, we run an account-deletion process that removes or anonymizes\n    personal information we do not have to keep.\n- scope: Cookie consent\n  period: 180 days\n  text: up to 180 days if you opt in; 7 days if you reject optional cookies\nresidency:\n- region:\
  \ Canada\n  text: Bucky is operated from Canada.\n- region: United States and other countries\n  text: Several service providers — including those for analytics, error monitoring, payments, maps, advertising\n    and visitor identification, email, customer relationship management, business-contact lookup, email verification,\n    content delivery, hosting, and AI — process data in the United States or other jurisdictions.\ntransfers:\n- mechanism: other\n  text: When we transfer personal information outside Canada, we use contractual and organizational measures those\n    providers offer, and we remain responsible for the information we send.\nsubprocessors:\n  url: null\n  text: 'The types of provider we use today include: Type of provider What they do for Bucky'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Settings in the Bucky account; or email hello@buckybuild.com\n  text: Use Settings to delete a Bucky account yourself.\nrights:\n- right: access\n  text:\
  \ you may request access to the personal information we hold about you\n- right: correction\n  text: correction of inaccuracies\n- right: deletion\n  text: deletion, a portable copy, and withdrawal of consent for optional processing\n- right: portability\n  text: a portable copy\n- right: withdraw consent\n  text: withdrawal of consent for optional processing\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information.\n"
source_yaml_url: https://artifacts.apis.io/buckybuild-com/privacy/buckybuild-com-privacy-policy.yml
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
summary_line: 27 quoted statements, read from Bucky's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- Zoning
- Mapping
- Data API
- Visualization
- Company
---
