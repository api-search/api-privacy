---
api_specs:
- filename: conversion-audiences-api-openapi.yml
  format: yaml
  label: Conversion Audiences API
  slug: conversion-audiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-audiences-api-openapi.yml
- filename: conversion-campaigns-api-openapi.yml
  format: yaml
  label: Conversion Campaigns API
  slug: conversion-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-campaigns-api-openapi.yml
- filename: conversion-contacts-api-openapi.yml
  format: yaml
  label: Conversion Contacts API
  slug: conversion-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-contacts-api-openapi.yml
- filename: conversion-custom-objects-api-openapi.yml
  format: yaml
  label: Conversion Custom Objects API
  slug: conversion-custom-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-custom-objects-api-openapi.yml
- filename: conversion-events-api-openapi.yml
  format: yaml
  label: Conversion Events API
  slug: conversion-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-events-api-openapi.yml
- filename: conversion-exports-api-openapi.yml
  format: yaml
  label: Conversion Exports API
  slug: conversion-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-exports-api-openapi.yml
- filename: conversion-fields-api-openapi.yml
  format: yaml
  label: Conversion Fields API
  slug: conversion-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-fields-api-openapi.yml
- filename: conversion-forms-api-openapi.yml
  format: yaml
  label: Conversion Forms API
  slug: conversion-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-forms-api-openapi.yml
- filename: conversion-full-delete-api-openapi.yml
  format: yaml
  label: Conversion Full Delete API
  slug: conversion-full-delete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-full-delete-api-openapi.yml
- filename: conversion-workflows-api-openapi.yml
  format: yaml
  label: Conversion Workflows API
  slug: conversion-workflows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/conversion/openapi/conversion-workflows-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: contact
    text: Names, business email addresses, work phone numbers, job titles, and company information
  - category: identifying
    text: User identifiers, usernames, authentication credentials, and login metadata
  - category: device
    text: Internet Protocol (IP) addresses, device identifiers, and unique browser identifiers
  - category: behavioral
    text: Usage and telemetry logs, event logs, activity logs, and feature usage data
  - category: communication
    text: Communications with our support team and sales representatives
  deletion:
    route: Upon reasonable written request, Conversion will provide written certification that Customer Data has been deleted
    text: Upon reasonable written request, Conversion will provide written certification that Customer Data has been deleted in accordance with this Section.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide and operate Services
    text: To provide, operate, maintain, and support the Services, including storing data, executing campaigns, and managing integrations
  - purpose: Security and fraud prevention
    text: To detect, prevent, and investigate fraud, abuse, or security incidents
  - purpose: Process payments and billing
    text: To process payments and manage billing and subscription renewals
  - purpose: Improve platform
    text: To analyze usage patterns and improve platform functionality, reliability, and security
  residency:
  - region: United States
    text: Conversion stores and processes Personal Data and Customer Data primarily in the United States (Google Cloud Platform, US-Central-1 region).
  retention:
  - period: sixty (60) days
    scope: Customer Data after termination
    text: Within sixty (60) days after termination (or longer as required by applicable law), Conversion will delete or anonymize all Customer Data in its possession
  - period: one hundred eighty (180) days
    scope: Backup copies
    text: Copies in backup systems, which will be deleted or overwritten within one hundred eighty (180) days in accordance with standard backup retention schedules
  - period: 13 months
    scope: Analytics cookie identifiers
    text: no longer than 13 months for analytics cookies
  - period: 90-day
    scope: Security access logs
    text: Comprehensive logging of access to Personal Data with 90-day retention for security monitoring
  rights:
  - right: Access
    text: 'Right of Access: Request disclosure of Personal Data we hold about you'
  - right: Correction
    text: 'Right of Correction: Request correction of inaccurate or incomplete Personal Data'
  - right: Deletion
    text: 'Right of Deletion: Request deletion of Personal Data, subject to legal exceptions'
  - right: Portability
    text: 'Right of Portability: Request your Personal Data in a structured, commonly-used format'
  - right: Object
    text: 'Right to Object: Object to processing of your Personal Data on certain grounds'
  - right: Restrict processing
    text: 'Right to Restrict Processing: Request limitation of processing for specified purposes'
  role:
    text: Conversion acts as a Processor with respect to Customer Data processed on behalf of customers.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: 'Conversion does not: Sell, rent, or trade Personal Data or Customer Data for compensation'
  subprocessors:
    text: A current list of authorized sub-processors is available at trust.conversion.ai or upon written request.
    url: trust.conversion.ai
  transfers:
  - mechanism: SCC
    text: 'Standard Contractual Clauses (SCCs): Module Two (Controller-to-Processor) per Commission Decision 2021/914, incorporated into applicable DPAs'
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Conversion
provenance_date: '2026-11-09'
provider_name: Conversion
provider_slug: conversion
slug: conversion-privacy-policy
source_date: '2026-11-09'
source_filename: conversion-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://conversion.ai/privacy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Conversion\naid: conversion\nurl: https://conversion.ai/privacy/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: Conversion acts as a Processor with respect to Customer Data processed on behalf of customers.\ndata_categories:\n- category: contact\n  text: Names, business email addresses, work phone numbers, job titles, and company information\n- category: identifying\n  text: User identifiers, usernames, authentication credentials, and login metadata\n- category: device\n  text: Internet Protocol (IP) addresses, device identifiers, and unique browser identifiers\n- category: behavioral\n  text:\
  \ Usage and telemetry logs, event logs, activity logs, and feature usage data\n- category: communication\n  text: Communications with our support team and sales representatives\npurposes:\n- purpose: Provide and operate Services\n  text: To provide, operate, maintain, and support the Services, including storing data, executing campaigns, and\n    managing integrations\n- purpose: Security and fraud prevention\n  text: To detect, prevent, and investigate fraud, abuse, or security incidents\n- purpose: Process payments and billing\n  text: To process payments and manage billing and subscription renewals\n- purpose: Improve platform\n  text: To analyze usage patterns and improve platform functionality, reliability, and security\nretention:\n- scope: Customer Data after termination\n  period: sixty (60) days\n  text: Within sixty (60) days after termination (or longer as required by applicable law), Conversion will delete\n    or anonymize all Customer Data in its possession\n- scope: Backup\
  \ copies\n  period: one hundred eighty (180) days\n  text: Copies in backup systems, which will be deleted or overwritten within one hundred eighty (180) days in accordance\n    with standard backup retention schedules\n- scope: Analytics cookie identifiers\n  period: 13 months\n  text: no longer than 13 months for analytics cookies\n- scope: Security access logs\n  period: 90-day\n  text: Comprehensive logging of access to Personal Data with 90-day retention for security monitoring\nresidency:\n- region: United States\n  text: Conversion stores and processes Personal Data and Customer Data primarily in the United States (Google Cloud\n    Platform, US-Central-1 region).\ntransfers:\n- mechanism: SCC\n  text: 'Standard Contractual Clauses (SCCs): Module Two (Controller-to-Processor) per Commission Decision 2021/914,\n    incorporated into applicable DPAs'\nsubprocessors:\n  url: trust.conversion.ai\n  text: A current list of authorized sub-processors is available at trust.conversion.ai\
  \ or upon written request.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Upon reasonable written request, Conversion will provide written certification that Customer Data has been\n    deleted\n  text: Upon reasonable written request, Conversion will provide written certification that Customer Data has been\n    deleted in accordance with this Section.\nrights:\n- right: Access\n  text: 'Right of Access: Request disclosure of Personal Data we hold about you'\n- right: Correction\n  text: 'Right of Correction: Request correction of inaccurate or incomplete Personal Data'\n- right: Deletion\n  text: 'Right of Deletion: Request deletion of Personal Data, subject to legal exceptions'\n- right: Portability\n  text: 'Right of Portability: Request your Personal Data in a structured, commonly-used format'\n- right: Object\n  text: 'Right to Object: Object to processing of your Personal Data on certain grounds'\n- right: Restrict processing\n  text: 'Right to Restrict\
  \ Processing: Request limitation of processing for specified purposes'\nsale_or_sharing:\n  stance: prohibited\n  text: 'Conversion does not: Sell, rent, or trade Personal Data or Customer Data for compensation'\n"
source_yaml_url: https://artifacts.apis.io/conversion/privacy/conversion-privacy-policy.yml
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
summary_line: 25 quoted statements, read from Conversion's own page on 2026-11-09.
synthetic: false
tags:
- Marketing
- Automation
- Artificial Intelligence
- B2B
- Software-as-a-Service
- Platform
---
