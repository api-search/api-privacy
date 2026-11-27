---
claim_count: 11
description: ''
doc:
  data_categories:
  - category: communication
    text: The service receives the requested tool and its arguments, such as a state, bill identifier, search keywords, or an optional question for an evidence brief.
  - category: device
    text: Hosting and application logs can contain network and request information such as an IP address, user agent, path, time, response status, and operational error details.
  deletion:
    route: email request
    text: For a privacy question or request, email alberto@gdacs.net
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: answer legislative-research requests
    text: Tool arguments are used to answer the legislative-research request.
  - purpose: service availability
    text: IP-based limits protect service availability.
  - purpose: reliability and diagnosis
    text: Operational usage and logs support reliability, error diagnosis, and an aggregate view of which tools are used.
  retention:
  - period: null
    scope: generated evidence packets
    text: Bill Commons does not archive generated evidence packets.
  - period: until the service restarts or entries are evicted
    scope: IP-based request-limit entries
    text: IP-based request-limit entries remain in process memory until the service restarts or entries are evicted to keep the limiter within its size cap.
  - period: no fixed expiry
    scope: operational-usage records
    text: Operational-usage records have no fixed expiry and the application has no automatic deletion job for them.
  rights:
  - right: privacy question or request
    text: For a privacy question or request, email alberto@gdacs.net
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: The service is hosted on Railway and reads indexed public records from its configured PostgreSQL database.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: billcommons-org
provenance_date: '2026-11-09'
provider_name: billcommons-org
provider_slug: billcommons-org
slug: billcommons-org-privacy-policy
source_date: '2026-11-09'
source_filename: billcommons-org-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://billcommons.org/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: billcommons-org\naid: billcommons-org\nurl: https://billcommons.org/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: communication\n  text: The service receives the requested tool and its arguments, such as a state, bill identifier, search keywords,\n    or an optional question for an evidence brief.\n- category: device\n  text: Hosting and application logs can contain network and request information such as an IP address, user agent,\n    path, time, response status, and operational error details.\npurposes:\n- purpose: answer legislative-research requests\n\
  \  text: Tool arguments are used to answer the legislative-research request.\n- purpose: service availability\n  text: IP-based limits protect service availability.\n- purpose: reliability and diagnosis\n  text: Operational usage and logs support reliability, error diagnosis, and an aggregate view of which tools are\n    used.\nretention:\n- scope: generated evidence packets\n  period: null\n  text: Bill Commons does not archive generated evidence packets.\n- scope: IP-based request-limit entries\n  period: until the service restarts or entries are evicted\n  text: IP-based request-limit entries remain in process memory until the service restarts or entries are evicted\n    to keep the limiter within its size cap.\n- scope: operational-usage records\n  period: no fixed expiry\n  text: Operational-usage records have no fixed expiry and the application has no automatic deletion job for them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: The service is hosted on Railway\
  \ and reads indexed public records from its configured PostgreSQL database.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: For a privacy question or request, email alberto@gdacs.net\nrights:\n- right: privacy question or request\n  text: For a privacy question or request, email alberto@gdacs.net\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/billcommons-org/privacy/billcommons-org-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
summary_line: 11 quoted statements, read from billcommons-org's own page on 2026-11-09.
synthetic: false
tags:
- Legislative
- State bills
- Open Source
- Research Tools
---
