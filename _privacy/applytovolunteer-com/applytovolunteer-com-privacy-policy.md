---
api_specs:
- filename: applytovolunteer-com-applications-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Applications API
  slug: applytovolunteer-com-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-applications-api-openapi.yml
- filename: applytovolunteer-com-auth-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Auth API
  slug: applytovolunteer-com-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-auth-api-openapi.yml
- filename: applytovolunteer-com-conversions-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Conversions API
  slug: applytovolunteer-com-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-conversions-api-openapi.yml
- filename: applytovolunteer-com-demos-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Demos API
  slug: applytovolunteer-com-demos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-demos-api-openapi.yml
- filename: applytovolunteer-com-forms-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Forms API
  slug: applytovolunteer-com-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-forms-api-openapi.yml
- filename: applytovolunteer-com-me-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Me API
  slug: applytovolunteer-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-me-api-openapi.yml
- filename: applytovolunteer-com-public-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Public API
  slug: applytovolunteer-com-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-public-api-openapi.yml
- filename: applytovolunteer-com-tools-api-openapi.yml
  format: yaml
  label: ApplyToVolunteer Tools API
  slug: applytovolunteer-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/applytovolunteer-com/openapi/applytovolunteer-com-tools-api-openapi.yml
claim_count: 12
description: ''
doc:
  data_categories:
  - category: contact
    text: Hosted volunteer forms collect contact details (name, email, phone) so an organization can process an application.
  - category: identifying
    text: When you sign in, we store the raw IP address and the browser user agent on the session row.
  - category: device
    text: When you sign in, we store the raw IP address and the browser user agent on the session row.
  deletion:
    route: Organization admins email help@apply2volunteer.com to request deletion of records kept until requested
    text: Organization admins can email help@apply2volunteer.com to ask us to delete records this page says we keep until you ask
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Process volunteer applications
    text: so an organization can process an application
  - purpose: Account sign-in
    text: Sign-in uses a magic link sent to the address you enter.
  retention:
  - period: 30 days
    scope: Session row
    text: The sign-in cookie lasts 30 days, and the session row expires then.
  - period: 24 hours
    scope: Anonymous MCP preview
    text: An anonymous MCP preview stores the parsed form for 24 hours and is deleted in the next daily cleanup after it expires.
  - period: 30 days
    scope: Form Grader reports
    text: Form Grader reports, including reports created while signed in and reports that are not public, are deleted in the next daily cleanup after 30 days.
  - period: 24 × 30 days
    scope: Hosted application IP hash
    text: The default retention period is 24 × 30 days.
  - period: no expiry
    scope: In-app conversion
    text: An in-app conversion keeps the imported file, the parsed form, the field labels, and the file hash, with no expiry.
  rights:
  - right: Deletion request
    text: Organization admins can email help@apply2volunteer.com to ask us to delete records this page says we keep until you ask
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
name: ApplyToVolunteer
provenance_date: '2026-11-09'
provider_name: ApplyToVolunteer
provider_slug: applytovolunteer-com
slug: applytovolunteer-com-privacy-policy
source_date: '2026-11-09'
source_filename: applytovolunteer-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://applytovolunteer.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: ApplyToVolunteer\naid: applytovolunteer-com\nurl: https://applytovolunteer.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: Hosted volunteer forms collect contact details (name, email, phone) so an organization can process an application.\n- category: identifying\n  text: When you sign in, we store the raw IP address and the browser user agent on the session row.\n- category: device\n  text: When you sign in, we store the raw IP address and the browser user agent on the session row.\npurposes:\n- purpose: Process volunteer applications\n\
  \  text: so an organization can process an application\n- purpose: Account sign-in\n  text: Sign-in uses a magic link sent to the address you enter.\nretention:\n- scope: Session row\n  period: 30 days\n  text: The sign-in cookie lasts 30 days, and the session row expires then.\n- scope: Anonymous MCP preview\n  period: 24 hours\n  text: An anonymous MCP preview stores the parsed form for 24 hours and is deleted in the next daily cleanup after\n    it expires.\n- scope: Form Grader reports\n  period: 30 days\n  text: Form Grader reports, including reports created while signed in and reports that are not public, are deleted\n    in the next daily cleanup after 30 days.\n- scope: Hosted application IP hash\n  period: 24 × 30 days\n  text: The default retention period is 24 × 30 days.\n- scope: In-app conversion\n  period: no expiry\n  text: An in-app conversion keeps the imported file, the parsed form, the field labels, and the file hash, with\n    no expiry.\nresidency: []\ntransfers: []\n\
  subprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Organization admins email help@apply2volunteer.com to request deletion of records kept until requested\n  text: Organization admins can email help@apply2volunteer.com to ask us to delete records this page says we keep\n    until you ask\nrights:\n- right: Deletion request\n  text: Organization admins can email help@apply2volunteer.com to ask us to delete records this page says we keep\n    until you ask\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/applytovolunteer-com/privacy/applytovolunteer-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 12 quoted statements, read from ApplyToVolunteer's own page on 2026-11-09.
synthetic: false
tags:
- Volunteer
- Forms
- Software-as-a-Service
- Non-Profit
- Platform
---
