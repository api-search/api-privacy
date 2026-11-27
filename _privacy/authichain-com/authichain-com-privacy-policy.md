---
claim_count: 23
description: ''
doc:
  data_categories:
  - category: contact
    text: Checkout email. Starting a card checkout requires a work email.
  - category: identifying
    text: Your name, job title or role, work email address, company name, and company details (domain, headquarters country, product category).
  - category: financial
    text: We keep the result Stripe sends back (paid or not), the email, the amount, and the plan.
  - category: device
    text: Cloudflare serves the site and receives the IP address, browser type, and URL of each request in order to deliver the page and block abuse.
  - category: communication
    text: Messages to hello@authichain.com, support@authichain.com, or proposals@authichain.com, and our replies.
  deletion:
    route: email hello@authichain.com or authichain@mail.grokbot.com
    text: Email hello@authichain.com to ask for a copy of the off-chain personal data we hold about you, to correct it, or to delete it.
  dpa:
    available: null
    text: we have no data processing agreement with AgentMail (the reply-inbox provider) or with Apollo.io, and we do not claim one is in place.
    url: null
  purposes:
  - purpose: receipt and checkout follow-up
    text: We use it for the receipt and to follow up if checkout does not finish.
  - purpose: operate and secure the service
    text: We use those logs to operate and secure the service.
  - purpose: DPP readiness outreach
    text: 'Legal basis: legitimate interest (GDPR Art. 6(1)(f)) in offering EU DPP readiness tools to businesses whose products fall under the DPP rules.'
  residency:
  - region: United States
    text: Your data is processed in the United States.
  retention:
  - period: 12 months
    scope: 1-to-1 business contact data
    text: We delete your contact data 12 months after our last contact with you if you have not replied.
  - period: null
    scope: order and payment records
    text: We keep order and payment records for as long as we need them to deliver what you bought, to handle a dispute, and to meet tax and accounting duties.
  - period: about a day
    scope: IP hash for sign-ups
    text: we also keep a salted hash of the IP address used to sign up for about a day
  rights:
  - right: access, correction, erasure, restriction, portability
    text: You can ask for access to, correction, erasure, restriction, or a portable copy of your data (GDPR Arts. 15-20) by emailing authichain@mail.grokbot.com .
  - right: object to direct marketing
    text: 'You can object at any time to the use of your data for direct marketing: reply ''stop'' (or tell us in any words) to our email'
  - right: complain to supervisory authority
    text: You can complain to a data protection supervisory authority, in particular in the EU member state where you live or work
  - right: withdraw consent
    text: You will be able to withdraw consent at any time through the unsubscribe link in those emails.
  role:
    text: Controller. Zachary J Kietzman d/b/a AuthiChain (sole proprietor).
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal information, and we do not share it for cross-context behavioral advertising.
  subprocessors:
    text: 'Processors that handle it to run the service: Stripe — card checkout, the amount, and checkout recovery email. Supabase — database for accounts, checkout attempts, and product records we store. Cloudflare — hosting, delivery, and request security. Resend — email about an order you started or paid for'
    url: null
  transfers:
  - mechanism: DPF
    text: Zenleads Inc. (dba Apollo.io) is listed as active under the EU-U.S. Data Privacy Framework.
  - mechanism: SCC
    text: Supabase's data processing agreement provides Standard Contractual Clauses for transfers (Supabase DPA section 12.1).
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AuthiChain
provenance_date: '2026-11-09'
provider_name: AuthiChain
provider_slug: authichain-com
slug: authichain-com-privacy-policy
source_date: '2026-11-09'
source_filename: authichain-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://authichain.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AuthiChain\naid: authichain-com\nurl: https://authichain.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Controller. Zachary J Kietzman d/b/a AuthiChain (sole proprietor).\ndata_categories:\n- category: contact\n  text: Checkout email. Starting a card checkout requires a work email.\n- category: identifying\n  text: Your name, job title or role, work email address, company name, and company details (domain, headquarters\n    country, product category).\n- category: financial\n  text: We keep the result Stripe sends back (paid or not), the email, the amount, and the plan.\n- category:\
  \ device\n  text: Cloudflare serves the site and receives the IP address, browser type, and URL of each request in order to\n    deliver the page and block abuse.\n- category: communication\n  text: Messages to hello@authichain.com, support@authichain.com, or proposals@authichain.com, and our replies.\npurposes:\n- purpose: receipt and checkout follow-up\n  text: We use it for the receipt and to follow up if checkout does not finish.\n- purpose: operate and secure the service\n  text: We use those logs to operate and secure the service.\n- purpose: DPP readiness outreach\n  text: 'Legal basis: legitimate interest (GDPR Art. 6(1)(f)) in offering EU DPP readiness tools to businesses whose\n    products fall under the DPP rules.'\nretention:\n- scope: 1-to-1 business contact data\n  period: 12 months\n  text: We delete your contact data 12 months after our last contact with you if you have not replied.\n- scope: order and payment records\n  period: null\n  text: We keep order and payment\
  \ records for as long as we need them to deliver what you bought, to handle a dispute,\n    and to meet tax and accounting duties.\n- scope: IP hash for sign-ups\n  period: about a day\n  text: we also keep a salted hash of the IP address used to sign up for about a day\nresidency:\n- region: United States\n  text: Your data is processed in the United States.\ntransfers:\n- mechanism: DPF\n  text: Zenleads Inc. (dba Apollo.io) is listed as active under the EU-U.S. Data Privacy Framework.\n- mechanism: SCC\n  text: Supabase's data processing agreement provides Standard Contractual Clauses for transfers (Supabase DPA section\n    12.1).\nsubprocessors:\n  url: null\n  text: 'Processors that handle it to run the service: Stripe — card checkout, the amount, and checkout recovery\n    email. Supabase — database for accounts, checkout attempts, and product records we store. Cloudflare — hosting,\n    delivery, and request security. Resend — email about an order you started or paid for'\ndpa:\n\
  \  available: null\n  url: null\n  text: we have no data processing agreement with AgentMail (the reply-inbox provider) or with Apollo.io, and we\n    do not claim one is in place.\ndeletion:\n  route: email hello@authichain.com or authichain@mail.grokbot.com\n  text: Email hello@authichain.com to ask for a copy of the off-chain personal data we hold about you, to correct\n    it, or to delete it.\nrights:\n- right: access, correction, erasure, restriction, portability\n  text: You can ask for access to, correction, erasure, restriction, or a portable copy of your data (GDPR Arts.\n    15-20) by emailing authichain@mail.grokbot.com .\n- right: object to direct marketing\n  text: 'You can object at any time to the use of your data for direct marketing: reply ''stop'' (or tell us in\n    any words) to our email'\n- right: complain to supervisory authority\n  text: You can complain to a data protection supervisory authority, in particular in the EU member state where\n    you live or work\n\
  - right: withdraw consent\n  text: You will be able to withdraw consent at any time through the unsubscribe link in those emails.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell personal information, and we do not share it for cross-context behavioral advertising.\n"
source_yaml_url: https://artifacts.apis.io/authichain-com/privacy/authichain-com-privacy-policy.yml
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
summary_line: 23 quoted statements, read from AuthiChain's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Verification
- QR
- Digital Product Passport
- Supply Chain
---
