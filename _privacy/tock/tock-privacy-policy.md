---
api_specs:
- filename: tock-reservation-openapi.yml
  format: yaml
  label: Tock Reservation API
  slug: reservation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tock/openapi/_original/tock-reservation-openapi.yml
- filename: tock-guest-profile-openapi.yml
  format: yaml
  label: Tock Guest API
  slug: guest-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tock/openapi/_original/tock-guest-profile-openapi.yml
claim_count: 29
description: ''
doc:
  data_categories:
  - category: identifying
    text: Information a Guest provides to create an Account or make a Booking, such as email address, first name, last name and phone number.
  - category: financial
    text: For most Paid Bookings, this will include billing address as well as a portion of payment information which is provided to us from our payment processor (such as the last four digits, the country of issuance and the expiration date of the payment card).
  - category: device
    text: information about your browser, network or device (such as browser type and version, operating system, internet service provider, preference settings, unique device IDs and language and other regional settings)
  - category: behavioral
    text: information about how you use the Services (such as timestamps, clicks, scrolling, browsing times, searches, transactions, referral pages, load times, and problems you may encounter, such as loading errors)
  - category: demographic
    text: Guest Diner Profile Information includes a photograph, birthday or anniversary details for the Guest and/or their partner and the Guest's hospitality preferences or dietary restrictions
  - category: location
    text: we use your location information to determine your language preferences or display accurate date and time information
  - category: communication
    text: The emails and other communications that you send us or otherwise contribute, such as customer support inquiries.
  deletion:
    route: Account settings or email privacy@tockhq.com
    text: You can access, correct, or delete Tock Controlled PI either directly in your Account or by contacting us at privacy@tockhq.com to submit your request.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provision of the Services
    text: Create and manage your Account, make Bookings, process payments, respond to your inquiries and enable Merchants to contact you
  - purpose: Communicating with you
    text: Communicate with you, including by sending you emails about your or your business' transactions and Service-related announcements.
  - purpose: Promotion
    text: Promote our Services and send you tailored marketing communications about products, services, offers, programs and promotions of Tock and our Merchants and partners
  - purpose: Advertising
    text: Analyze your interactions with our Services and third parties' online services so we can tailor our advertising to your preferences.
  - purpose: Improving our Services
    text: Analyze and learn about how the Services are accessed and used, evaluate and improve our Services
  - purpose: Security
    text: Ensure the security and integrity of our Services.
  - purpose: Complying with law
    text: Comply with applicable legal requirements, such as tax and other government regulations and industry standards, contracts and law enforcement requests.
  residency:
  - region: United States
    text: such as, for example, to our servers in the U.S.
  retention:
  - period: null
    scope: Account information
    text: We retain personal information about you for as long as your Account is active or for as long as needed to provide you or our Merchants with the Services.
  - period: indefinitely
    scope: Aggregated and anonymized information
    text: we collect and maintain aggregated and anonymized information which we may retain indefinitely.
  rights:
  - right: access
    text: you may have certain rights, including the right to access, correct, or delete personal information.
  - right: correction
    text: You can access, correct, or delete Tock Controlled PI either directly in your Account or by contacting us at privacy@tockhq.com
  - right: deletion
    text: You can access, correct, or delete Tock Controlled PI either directly in your Account or by contacting us at privacy@tockhq.com to submit your request.
  - right: withdraw consent
    text: if we rely on consent for the processing of your personal information, you have the right to withdraw it at any time and free of charge.
  - right: opt out of marketing
    text: You can also elect not to receive marketing communications by following the unsubscribe instructions in such communications.
  - right: lodge complaint
    text: You also have the right to lodge a complaint with a local competent data protection authority
  - right: explanation of automated decision
    text: you may request an explanation of our decision.
  role:
    text: For Merchant Controlled PI, Tock acts as a data processor, service provider or similar term under applicable law.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: We transfer, in accordance with Article 46 of the GDPR, personal information to recipients with whom we have entered into the European Commission approved Standard Contractual Clauses
  - mechanism: other
    text: We transfer, in accordance with UK law, personal information to recipients with whom we have entered into the UK Information Commissioner's Office approved international data transfer agreement and the UK addendum
  - mechanism: adequacy
    text: transfer personal information of individuals in the EEA to recipients that are in a country the European Commission or a European or UK data protection supervisory authority has confirmed, by decision, offers adequate levels of data protection
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tock
provenance_date: '2026-11-10'
provider_name: Tock
provider_slug: tock
slug: tock-privacy-policy
source_date: '2026-11-10'
source_filename: tock-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.exploretock.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tock\naid: tock\nurl: https://www.exploretock.com/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For Merchant Controlled PI, Tock acts as a data processor, service provider or similar term under applicable\n    law.\ndata_categories:\n- category: identifying\n  text: Information a Guest provides to create an Account or make a Booking, such as email address, first name,\n    last name and phone number.\n- category: financial\n  text: For most Paid Bookings, this will include billing address as well as a portion of payment information which\n    is provided to us from our payment processor\
  \ (such as the last four digits, the country of issuance and the\n    expiration date of the payment card).\n- category: device\n  text: information about your browser, network or device (such as browser type and version, operating system, internet\n    service provider, preference settings, unique device IDs and language and other regional settings)\n- category: behavioral\n  text: information about how you use the Services (such as timestamps, clicks, scrolling, browsing times, searches,\n    transactions, referral pages, load times, and problems you may encounter, such as loading errors)\n- category: demographic\n  text: Guest Diner Profile Information includes a photograph, birthday or anniversary details for the Guest and/or\n    their partner and the Guest's hospitality preferences or dietary restrictions\n- category: location\n  text: we use your location information to determine your language preferences or display accurate date and time\n    information\n- category: communication\n\
  \  text: The emails and other communications that you send us or otherwise contribute, such as customer support inquiries.\npurposes:\n- purpose: Provision of the Services\n  text: Create and manage your Account, make Bookings, process payments, respond to your inquiries and enable Merchants\n    to contact you\n- purpose: Communicating with you\n  text: Communicate with you, including by sending you emails about your or your business' transactions and Service-related\n    announcements.\n- purpose: Promotion\n  text: Promote our Services and send you tailored marketing communications about products, services, offers, programs\n    and promotions of Tock and our Merchants and partners\n- purpose: Advertising\n  text: Analyze your interactions with our Services and third parties' online services so we can tailor our advertising\n    to your preferences.\n- purpose: Improving our Services\n  text: Analyze and learn about how the Services are accessed and used, evaluate and improve our Services\n\
  - purpose: Security\n  text: Ensure the security and integrity of our Services.\n- purpose: Complying with law\n  text: Comply with applicable legal requirements, such as tax and other government regulations and industry standards,\n    contracts and law enforcement requests.\nretention:\n- scope: Account information\n  period: null\n  text: We retain personal information about you for as long as your Account is active or for as long as needed\n    to provide you or our Merchants with the Services.\n- scope: Aggregated and anonymized information\n  period: indefinitely\n  text: we collect and maintain aggregated and anonymized information which we may retain indefinitely.\nresidency:\n- region: United States\n  text: such as, for example, to our servers in the U.S.\ntransfers:\n- mechanism: SCC\n  text: We transfer, in accordance with Article 46 of the GDPR, personal information to recipients with whom we\n    have entered into the European Commission approved Standard Contractual Clauses\n\
  - mechanism: other\n  text: We transfer, in accordance with UK law, personal information to recipients with whom we have entered into\n    the UK Information Commissioner's Office approved international data transfer agreement and the UK addendum\n- mechanism: adequacy\n  text: transfer personal information of individuals in the EEA to recipients that are in a country the European\n    Commission or a European or UK data protection supervisory authority has confirmed, by decision, offers adequate\n    levels of data protection\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Account settings or email privacy@tockhq.com\n  text: You can access, correct, or delete Tock Controlled PI either directly in your Account or by contacting us\n    at privacy@tockhq.com to submit your request.\nrights:\n- right: access\n  text: you may have certain rights, including the right to access, correct, or delete personal information.\n- right:\
  \ correction\n  text: You can access, correct, or delete Tock Controlled PI either directly in your Account or by contacting us\n    at privacy@tockhq.com\n- right: deletion\n  text: You can access, correct, or delete Tock Controlled PI either directly in your Account or by contacting us\n    at privacy@tockhq.com to submit your request.\n- right: withdraw consent\n  text: if we rely on consent for the processing of your personal information, you have the right to withdraw it\n    at any time and free of charge.\n- right: opt out of marketing\n  text: You can also elect not to receive marketing communications by following the unsubscribe instructions in\n    such communications.\n- right: lodge complaint\n  text: You also have the right to lodge a complaint with a local competent data protection authority\n- right: explanation of automated decision\n  text: you may request an explanation of our decision.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tock/privacy/tock-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
summary_line: 29 quoted statements, read from Tock's own page on 2026-11-10.
synthetic: false
tags:
- Hospitality
- Reservations
- Restaurant
- Wineries
- Ticketed Events
- Takeout
- Delivery
- Experience
- Dining
- American Express
---
