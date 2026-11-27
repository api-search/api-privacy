---
api_specs:
- filename: freestyle-sh-auth-api-openapi.yml
  format: yaml
  label: Freestyle Auth API
  slug: freestyle-sh-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-auth-api-openapi.yml
- filename: freestyle-sh-certs-api-openapi.yml
  format: yaml
  label: Freestyle Certs API
  slug: freestyle-sh-certs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-certs-api-openapi.yml
- filename: freestyle-sh-cron-api-openapi.yml
  format: yaml
  label: Freestyle Cron API
  slug: freestyle-sh-cron-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-cron-api-openapi.yml
- filename: freestyle-sh-dns-api-openapi.yml
  format: yaml
  label: Freestyle DNS API
  slug: freestyle-sh-dns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-dns-api-openapi.yml
- filename: freestyle-sh-domains-api-openapi.yml
  format: yaml
  label: Freestyle Domains API
  slug: freestyle-sh-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-domains-api-openapi.yml
- filename: freestyle-sh-execute-api-openapi.yml
  format: yaml
  label: Freestyle Execute API
  slug: freestyle-sh-execute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-execute-api-openapi.yml
- filename: freestyle-sh-git-api-openapi.yml
  format: yaml
  label: Freestyle Git API
  slug: freestyle-sh-git-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-git-api-openapi.yml
- filename: freestyle-sh-identity-api-openapi.yml
  format: yaml
  label: Freestyle Identity API
  slug: freestyle-sh-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-identity-api-openapi.yml
- filename: freestyle-sh-observability-api-openapi.yml
  format: yaml
  label: Freestyle Observability API
  slug: freestyle-sh-observability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-observability-api-openapi.yml
- filename: freestyle-sh-web-api-openapi.yml
  format: yaml
  label: Freestyle Web API
  slug: freestyle-sh-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-web-api-openapi.yml
- filename: freestyle-sh-background-requests-api-openapi.yml
  format: yaml
  label: Freestyle Background requests API
  slug: freestyle-sh-background-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-background-requests-api-openapi.yml
- filename: freestyle-sh-filesystem-api-openapi.yml
  format: yaml
  label: Freestyle Filesystem API
  slug: freestyle-sh-filesystem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-filesystem-api-openapi.yml
- filename: freestyle-sh-firewall-api-openapi.yml
  format: yaml
  label: Freestyle Firewall API
  slug: freestyle-sh-firewall-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-firewall-api-openapi.yml
- filename: freestyle-sh-hardware-api-openapi.yml
  format: yaml
  label: Freestyle Hardware API
  slug: freestyle-sh-hardware-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-hardware-api-openapi.yml
- filename: freestyle-sh-identities-api-openapi.yml
  format: yaml
  label: Freestyle Identities API
  slug: freestyle-sh-identities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-identities-api-openapi.yml
- filename: freestyle-sh-snapshots-api-openapi.yml
  format: yaml
  label: Freestyle Snapshots API
  slug: freestyle-sh-snapshots-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-snapshots-api-openapi.yml
- filename: freestyle-sh-tls-api-openapi.yml
  format: yaml
  label: Freestyle TLS API
  slug: freestyle-sh-tls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-tls-api-openapi.yml
- filename: freestyle-sh-tunnels-api-openapi.yml
  format: yaml
  label: Freestyle Tunnels API
  slug: freestyle-sh-tunnels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-tunnels-api-openapi.yml
- filename: freestyle-sh-vms-api-openapi.yml
  format: yaml
  label: Freestyle VMs API
  slug: freestyle-sh-vms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-vms-api-openapi.yml
- filename: freestyle-sh-vpcs-api-openapi.yml
  format: yaml
  label: Freestyle VPCs API
  slug: freestyle-sh-vpcs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/freestyle-sh/openapi/freestyle-sh-vpcs-api-openapi.yml
claim_count: 15
description: ''
doc:
  data_categories:
  - category: identifying
    text: account and team information
  - category: device
    text: the hardware model, operating system and version, and unique device identifiers
  - category: behavioral
    text: the tools you use, the actions you take, and the time, frequency, and duration of your activities
  - category: communication
    text: commands and their results, files and their contents
  - category: location
    text: your IP address
  deletion:
    route: email support@freestyle.sh
    text: To request deletion of content retained by Freestyle, email support@freestyle.sh .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: provide, maintain and improve site and services
    text: Provide, maintain, and improve our Site and services
  - purpose: analytics of usage and trends
    text: Monitor and analyze trends, usage, and activities in connection with our Site
  - purpose: detect and address technical issues
    text: Detect, prevent, and address technical issues
  - purpose: develop new products
    text: Develop new products and services
  retention:
  - period: one month
    scope: logs
    text: We retain logs for one month.
  - period: null
    scope: deleted VM backup copies
    text: Backup copies of deleted VM data are removed asynchronously through a cleanup queue; removal is not immediate and its timing depends on queue processing.
  - period: until you delete them
    scope: snapshots
    text: Separately created snapshots remain until you delete them.
  rights:
  - right: opt out of Google Analytics
    text: You can opt-out of Google Analytics by installing the Google Analytics opt-out browser add-on
  - right: cookie control
    text: Most web browsers are set to accept cookies by default. If you prefer, you can usually choose to set your browser to remove or reject cookies.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Freestyle
provenance_date: '2026-11-09'
provider_name: Freestyle
provider_slug: freestyle-sh
slug: freestyle-sh-privacy-policy
source_date: '2026-11-09'
source_filename: freestyle-sh-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.freestyle.sh/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Freestyle\naid: freestyle-sh\nurl: https://www.freestyle.sh/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: account and team information\n- category: device\n  text: the hardware model, operating system and version, and unique device identifiers\n- category: behavioral\n  text: the tools you use, the actions you take, and the time, frequency, and duration of your activities\n- category: communication\n  text: commands and their results, files and their contents\n- category: location\n  text: your IP address\npurposes:\n- purpose:\
  \ provide, maintain and improve site and services\n  text: Provide, maintain, and improve our Site and services\n- purpose: analytics of usage and trends\n  text: Monitor and analyze trends, usage, and activities in connection with our Site\n- purpose: detect and address technical issues\n  text: Detect, prevent, and address technical issues\n- purpose: develop new products\n  text: Develop new products and services\nretention:\n- scope: logs\n  period: one month\n  text: We retain logs for one month.\n- scope: deleted VM backup copies\n  period: null\n  text: Backup copies of deleted VM data are removed asynchronously through a cleanup queue; removal is not immediate\n    and its timing depends on queue processing.\n- scope: snapshots\n  period: until you delete them\n  text: Separately created snapshots remain until you delete them.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email support@freestyle.sh\n\
  \  text: To request deletion of content retained by Freestyle, email support@freestyle.sh .\nrights:\n- right: opt out of Google Analytics\n  text: You can opt-out of Google Analytics by installing the Google Analytics opt-out browser add-on\n- right: cookie control\n  text: Most web browsers are set to accept cookies by default. If you prefer, you can usually choose to set your\n    browser to remove or reject cookies.\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/freestyle-sh/privacy/freestyle-sh-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 15 quoted statements, read from Freestyle's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Sandbox
- VMs
- MicroVM
- Version Control
- Code Execution
- JavaScript
- TypeScript
- Serverless
- Hosting
- Developer Tools
- Infrastructure
---
