---
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: GitHub user identifiers associated with the installation
  - category: contact
    text: Email address if you voluntarily subscribe to our newsletter
  - category: professional
    text: Job title and company name
  - category: location
    text: Location (city, country)
  - category: device
    text: Standard web analytics data via Google Analytics (page views, country, browser type, device info)
  - category: other
    text: Repository metadata (repository ID, installation ID, organization name)
  deletion:
    route: Uninstall the GitHub App or contact security@coderifts.com
    text: Uninstalling the CodeRifts GitHub App automatically removes all associated installation data.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Operating the GitHub App analysis
    text: Comparing configured specification files between the base and head of a pull request
  - purpose: Risk scoring and governance reports
    text: Calculating risk scores and generating governance reports
  - purpose: Posting PR comments and check status
    text: Posting Pull Request comments with analysis results
  - purpose: Newsletter
    text: Sending newsletter emails (only if you subscribed)
  - purpose: Service reliability
    text: Improving service reliability (operational logs)
  retention:
  - period: until the key is revoked or a deletion request is completed
    scope: API key hashes
    text: 'API key hashes: retained until the key is revoked or a deletion request is completed.'
  - period: null
    scope: Schema content read for a pull request
    text: Not retained after processing. Processed in memory only.
  - period: 90 days
    scope: Usage logs (request metadata)
    text: 'Usage logs (request metadata): Retained for 90 days, then deleted automatically.'
  - period: until you unsubscribe
    scope: Newsletter email addresses
    text: 'Newsletter email addresses: Retained until you unsubscribe.'
  - period: while the app is installed
    scope: GitHub installation metadata
    text: 'GitHub installation metadata: Retained while the app is installed. Deleted upon uninstall.'
  - period: null
    scope: Stored tool schemas via registry route
    text: A stored schema has no retention period and no deletion path.
  rights:
  - right: Access
    text: 'Right of access: Request a copy of the personal data we hold about you'
  - right: Rectification
    text: 'Right to rectification: Request correction of inaccurate or incomplete data'
  - right: Restriction
    text: 'Right to restriction of processing: Request that we limit how we use your data while a concern is being resolved'
  - right: Erasure
    text: 'Right to erasure: Request deletion of your personal data when it is no longer necessary for the purposes for which it was collected'
  - right: Portability
    text: 'Right to data portability: Request your data in a structured, commonly used, machine-readable format and transmit it to another controller'
  - right: Withdraw consent
    text: 'Right to withdraw consent: Where processing is based on consent (e.g., newsletter subscription), you may withdraw consent at any time without affecting the lawfulness of processing carried out before withdrawal'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: We do not sell, rent, or share your data with third parties for marketing purposes.
  subprocessors:
    text: 'Your data may be processed by the following service providers (sub-processors) solely for operating the CodeRifts service: Railway (app.railway.com) — Application hosting.'
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CodeRifts
provenance_date: '2026-11-09'
provider_name: CodeRifts
provider_slug: coderifts
slug: coderifts-privacy-policy
source_date: '2026-11-09'
source_filename: coderifts-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://coderifts.com/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CodeRifts\naid: coderifts\nurl: https://coderifts.com/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: GitHub user identifiers associated with the installation\n- category: contact\n  text: Email address if you voluntarily subscribe to our newsletter\n- category: professional\n  text: Job title and company name\n- category: location\n  text: Location (city, country)\n- category: device\n  text: Standard web analytics data via Google Analytics (page views, country, browser type, device info)\n- category: other\n  text: Repository\
  \ metadata (repository ID, installation ID, organization name)\npurposes:\n- purpose: Operating the GitHub App analysis\n  text: Comparing configured specification files between the base and head of a pull request\n- purpose: Risk scoring and governance reports\n  text: Calculating risk scores and generating governance reports\n- purpose: Posting PR comments and check status\n  text: Posting Pull Request comments with analysis results\n- purpose: Newsletter\n  text: Sending newsletter emails (only if you subscribed)\n- purpose: Service reliability\n  text: Improving service reliability (operational logs)\nretention:\n- scope: API key hashes\n  period: until the key is revoked or a deletion request is completed\n  text: 'API key hashes: retained until the key is revoked or a deletion request is completed.'\n- scope: Schema content read for a pull request\n  period: null\n  text: Not retained after processing. Processed in memory only.\n- scope: Usage logs (request metadata)\n  period: 90\
  \ days\n  text: 'Usage logs (request metadata): Retained for 90 days, then deleted automatically.'\n- scope: Newsletter email addresses\n  period: until you unsubscribe\n  text: 'Newsletter email addresses: Retained until you unsubscribe.'\n- scope: GitHub installation metadata\n  period: while the app is installed\n  text: 'GitHub installation metadata: Retained while the app is installed. Deleted upon uninstall.'\n- scope: Stored tool schemas via registry route\n  period: null\n  text: A stored schema has no retention period and no deletion path.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: 'Your data may be processed by the following service providers (sub-processors) solely for operating the\n    CodeRifts service: Railway (app.railway.com) — Application hosting.'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Uninstall the GitHub App or contact security@coderifts.com\n  text: Uninstalling the CodeRifts GitHub App automatically removes\
  \ all associated installation data.\nrights:\n- right: Access\n  text: 'Right of access: Request a copy of the personal data we hold about you'\n- right: Rectification\n  text: 'Right to rectification: Request correction of inaccurate or incomplete data'\n- right: Restriction\n  text: 'Right to restriction of processing: Request that we limit how we use your data while a concern is being\n    resolved'\n- right: Erasure\n  text: 'Right to erasure: Request deletion of your personal data when it is no longer necessary for the purposes\n    for which it was collected'\n- right: Portability\n  text: 'Right to data portability: Request your data in a structured, commonly used, machine-readable format and\n    transmit it to another controller'\n- right: Withdraw consent\n  text: 'Right to withdraw consent: Where processing is based on consent (e.g., newsletter subscription), you may\n    withdraw consent at any time without affecting the lawfulness of processing carried out before withdrawal'\n\
  sale_or_sharing:\n  stance: conditional\n  text: We do not sell, rent, or share your data with third parties for marketing purposes.\n"
source_yaml_url: https://artifacts.apis.io/coderifts/privacy/coderifts-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 26 quoted statements, read from CodeRifts's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Verification
- Compliance
- Platform
---
