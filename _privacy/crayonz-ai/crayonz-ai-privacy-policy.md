---
api_specs:
- filename: crayonz-ai-design-pipeline-api-openapi.yml
  format: yaml
  label: Crayonz Design Pipeline API
  slug: crayonz-ai-design-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crayonz-ai/openapi/crayonz-ai-design-pipeline-api-openapi.yml
- filename: crayonz-ai-designs-api-openapi.yml
  format: yaml
  label: Crayonz Designs API
  slug: crayonz-ai-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crayonz-ai/openapi/crayonz-ai-designs-api-openapi.yml
- filename: crayonz-ai-photoshoot-api-openapi.yml
  format: yaml
  label: Crayonz Photoshoot API
  slug: crayonz-ai-photoshoot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crayonz-ai/openapi/crayonz-ai-photoshoot-api-openapi.yml
- filename: crayonz-ai-virtual-try-on-api-openapi.yml
  format: yaml
  label: Crayonz Virtual Try-On API
  slug: crayonz-ai-virtual-try-on-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/crayonz-ai/openapi/crayonz-ai-virtual-try-on-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name and last name
  - category: contact
    text: Email address and bcrypt-hashed password (or Google OAuth identifier if you sign in with Google)
  - category: financial
    text: Order amount in INR, discount applied, payment status, payment instrument category (UPI / card / wallet — never the card number itself)
  - category: location
    text: Shipping address (full name, address lines, city, state, pincode, country, phone) entered at checkout
  - category: behavioral
    text: Pages viewed, products viewed, items added to cart, checkouts started and orders completed — recorded as analytics events so we can see where the buying journey breaks
  - category: device
    text: User-agent string and device type for layout switching
  - category: communication
    text: Text prompts you write to generate designs
  deletion:
    route: Account page, or email hello@crayonz.ai with subject line "Data Rights Request"
    text: Request deletion of your account and associated data (subject to the order-record retention rules above)
  dpa:
    available: null
    text: Bound by a data processing agreement that prohibits any use beyond providing the service to us.
    url: null
  purposes:
  - purpose: Providing the service and customized experience
    text: We use this information to provide you with a safe, efficient, and customized experience, which includes displaying content such as recommended products and communicating with you about your orders, new products, and the latest promotional offers.
  - purpose: Analytics and advertising measurement
    text: 'Analytics and advertising: we do run analytics and advertising measurement on the Platform.'
  - purpose: Abuse prevention
    text: IP address (used for rate-limit enforcement and abuse prevention; not stored beyond 30 days)
  residency:
  - region: Singapore
    text: Cloud database and storage provider (Supabase, hosted in Singapore)
  retention:
  - period: Deleted within 90 days of an account-closure request
    scope: Account profile
    text: 'Account profile: retained while your account is active. Deleted within 90 days of an account-closure request.'
  - period: 7 years
    scope: Order records
    text: 'Order records: retained for 7 years to comply with Indian GST and consumer protection record-keeping rules.'
  - period: 30 days
    scope: Uploaded reference images
    text: 'Uploaded reference images: auto-purged after 30 days if not attached to a saved draft.'
  - period: 30 days
    scope: IP address and request logs
    text: 'IP address and request logs: rotated out of edge caches within 30 days; aggregated counters kept up to 90 days for abuse prevention.'
  - period: 90 days after last use
    scope: OAuth tokens issued to MCP clients
    text: 'OAuth tokens issued to MCP clients: revocable at any time; expire 90 days after last use.'
  rights:
  - right: Access
    text: Access the personal data we hold about you
  - right: Correction
    text: Request correction of inaccurate data
  - right: Deletion
    text: Request deletion of your account and associated data (subject to the order-record retention rules above)
  - right: Withdraw consent
    text: Withdraw consent for any optional processing
  - right: Object to direct marketing
    text: Object to direct marketing communications
  - right: Complain
    text: Lodge a complaint with India's Data Protection Board (or your local data protection authority in the EU/UK)
  role:
    text: This privacy policy ("Policy") sets out how Crayonz, a brand operated by Aivolvix Private Limited ("we", "us", or "our"), uses and protects any information that you provide
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: We do not sell your personal information, and we do not use your design prompts or uploaded reference images to target advertising.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Crayonz
provenance_date: '2026-11-09'
provider_name: Crayonz
provider_slug: crayonz-ai
slug: crayonz-ai-privacy-policy
source_date: '2026-11-09'
source_filename: crayonz-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://crayonz.ai/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Crayonz\naid: crayonz-ai\nurl: https://crayonz.ai/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: This privacy policy (\"Policy\") sets out how Crayonz, a brand operated by Aivolvix Private Limited (\"we\",\n    \"us\", or \"our\"), uses and protects any information that you provide\ndata_categories:\n- category: identifying\n  text: First name and last name\n- category: contact\n  text: Email address and bcrypt-hashed password (or Google OAuth identifier if you sign in with Google)\n- category: financial\n  text: Order amount in INR, discount applied, payment status, payment\
  \ instrument category (UPI / card / wallet\n    — never the card number itself)\n- category: location\n  text: Shipping address (full name, address lines, city, state, pincode, country, phone) entered at checkout\n- category: behavioral\n  text: Pages viewed, products viewed, items added to cart, checkouts started and orders completed — recorded as\n    analytics events so we can see where the buying journey breaks\n- category: device\n  text: User-agent string and device type for layout switching\n- category: communication\n  text: Text prompts you write to generate designs\npurposes:\n- purpose: Providing the service and customized experience\n  text: We use this information to provide you with a safe, efficient, and customized experience, which includes\n    displaying content such as recommended products and communicating with you about your orders, new products,\n    and the latest promotional offers.\n- purpose: Analytics and advertising measurement\n  text: 'Analytics and advertising:\
  \ we do run analytics and advertising measurement on the Platform.'\n- purpose: Abuse prevention\n  text: IP address (used for rate-limit enforcement and abuse prevention; not stored beyond 30 days)\nretention:\n- scope: Account profile\n  period: Deleted within 90 days of an account-closure request\n  text: 'Account profile: retained while your account is active. Deleted within 90 days of an account-closure request.'\n- scope: Order records\n  period: 7 years\n  text: 'Order records: retained for 7 years to comply with Indian GST and consumer protection record-keeping rules.'\n- scope: Uploaded reference images\n  period: 30 days\n  text: 'Uploaded reference images: auto-purged after 30 days if not attached to a saved draft.'\n- scope: IP address and request logs\n  period: 30 days\n  text: 'IP address and request logs: rotated out of edge caches within 30 days; aggregated counters kept up to\n    90 days for abuse prevention.'\n- scope: OAuth tokens issued to MCP clients\n  period: 90\
  \ days after last use\n  text: 'OAuth tokens issued to MCP clients: revocable at any time; expire 90 days after last use.'\nresidency:\n- region: Singapore\n  text: Cloud database and storage provider (Supabase, hosted in Singapore)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: Bound by a data processing agreement that prohibits any use beyond providing the service to us.\ndeletion:\n  route: Account page, or email hello@crayonz.ai with subject line \"Data Rights Request\"\n  text: Request deletion of your account and associated data (subject to the order-record retention rules above)\nrights:\n- right: Access\n  text: Access the personal data we hold about you\n- right: Correction\n  text: Request correction of inaccurate data\n- right: Deletion\n  text: Request deletion of your account and associated data (subject to the order-record retention rules above)\n- right: Withdraw consent\n  text: Withdraw consent for any optional\
  \ processing\n- right: Object to direct marketing\n  text: Object to direct marketing communications\n- right: Complain\n  text: Lodge a complaint with India's Data Protection Board (or your local data protection authority in the EU/UK)\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell your personal information, and we do not use your design prompts or uploaded reference images\n    to target advertising.\n"
source_yaml_url: https://artifacts.apis.io/crayonz-ai/privacy/crayonz-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- dpa
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from Crayonz's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Custom Apparel
- Print on Demand
- Merchandise
- AI Image Generation
- Design
- Marketplace
- E-Commerce
- India
---
