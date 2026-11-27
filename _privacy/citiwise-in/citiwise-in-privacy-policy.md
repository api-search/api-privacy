---
api_specs:
- filename: citiwise-in-check-api-openapi.yml
  format: yaml
  label: Citiwise Check API
  slug: citiwise-in-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-check-api-openapi.yml
- filename: citiwise-in-clause-api-openapi.yml
  format: yaml
  label: Citiwise Clause API
  slug: citiwise-in-clause-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-clause-api-openapi.yml
- filename: citiwise-in-compare-api-openapi.yml
  format: yaml
  label: Citiwise Compare API
  slug: citiwise-in-compare-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-compare-api-openapi.yml
- filename: citiwise-in-dxf-api-openapi.yml
  format: yaml
  label: Citiwise Dxf API
  slug: citiwise-in-dxf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-dxf-api-openapi.yml
- filename: citiwise-in-feasibility-api-openapi.yml
  format: yaml
  label: Citiwise Feasibility API
  slug: citiwise-in-feasibility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-feasibility-api-openapi.yml
- filename: citiwise-in-find-api-openapi.yml
  format: yaml
  label: Citiwise Find API
  slug: citiwise-in-find-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-find-api-openapi.yml
- filename: citiwise-in-pdf-api-openapi.yml
  format: yaml
  label: Citiwise PDF API
  slug: citiwise-in-pdf-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-pdf-api-openapi.yml
- filename: citiwise-in-plot-api-openapi.yml
  format: yaml
  label: Citiwise Plot API
  slug: citiwise-in-plot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-plot-api-openapi.yml
- filename: citiwise-in-regulation-api-openapi.yml
  format: yaml
  label: Citiwise Regulation API
  slug: citiwise-in-regulation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-regulation-api-openapi.yml
- filename: citiwise-in-search-api-openapi.yml
  format: yaml
  label: Citiwise Search API
  slug: citiwise-in-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-search-api-openapi.yml
- filename: citiwise-in-towns-api-openapi.yml
  format: yaml
  label: Citiwise Towns API
  slug: citiwise-in-towns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/citiwise-in/openapi/citiwise-in-towns-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: location
    text: The town or village, the plot's area, sides and roads, the use, the flats and any rates you enter.
  - category: identifying
    text: If you put a name on a study's cover (prepared for, prepared by), that name is part of the study.
  - category: contact
    text: If you write to us by email or WhatsApp, we receive your message, your email address or phone number, and anything you attach.
  - category: device
    text: Our hosting provider keeps standard request logs (time, IP address, the address requested)
  deletion:
    route: Write to hello@citiwise.in
    text: By using Citiwise you agree to these uses; you can withdraw by writing to us, and we will delete what we hold.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Work out answer and prepare study
    text: We use plot details only to work out the answer and prepare the study you asked for.
  - purpose: Keep study so link opens
    text: We keep a study under its code only so its link opens.
  - purpose: Understand usefulness
    text: We use counts to understand whether Citiwise is useful and where to improve it.
  - purpose: Reply to messages
    text: We use messages only to reply to you and to fix what you report.
  residency:
  - region: Mumbai, India
    text: Our hosting provider (Vercel) runs the website and the service in Mumbai and keeps the request logs.
  - region: Mumbai, India
    text: Our database provider (Supabase) stores studies under their codes and the usage counts, in Mumbai.
  retention:
  - period: until you ask us to delete it
    scope: Studies kept under a code
    text: A study kept under a code stays until you ask us to delete it, so that a printed study's QR code keeps working.
  - period: a few days
    scope: Request logs
    text: Request logs are kept by our host for a short period, normally a few days, and then deleted.
  - period: null
    scope: Messages
    text: Messages are kept for as long as we need to answer and resolve them, and are deleted when you ask.
  rights:
  - right: Access, correction, deletion, nominate
    text: you may ask what we hold about you, ask us to correct or delete it, and name someone to act for you.
  - right: Complain to regulator
    text: If you are not satisfied with our answer, you may complain to the Data Protection Board of India.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: We do not sell any data, and we do not use it for advertising or to build profiles.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Citiwise
provenance_date: '2026-11-09'
provider_name: Citiwise
provider_slug: citiwise-in
slug: citiwise-in-privacy-policy
source_date: '2026-11-09'
source_filename: citiwise-in-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://citiwise.in/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Citiwise\naid: citiwise-in\nurl: https://citiwise.in/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: location\n  text: The town or village, the plot's area, sides and roads, the use, the flats and any rates you enter.\n- category: identifying\n  text: If you put a name on a study's cover (prepared for, prepared by), that name is part of the study.\n- category: contact\n  text: If you write to us by email or WhatsApp, we receive your message, your email address or phone number, and\n    anything you attach.\n- category: device\n  text: Our hosting provider\
  \ keeps standard request logs (time, IP address, the address requested)\npurposes:\n- purpose: Work out answer and prepare study\n  text: We use plot details only to work out the answer and prepare the study you asked for.\n- purpose: Keep study so link opens\n  text: We keep a study under its code only so its link opens.\n- purpose: Understand usefulness\n  text: We use counts to understand whether Citiwise is useful and where to improve it.\n- purpose: Reply to messages\n  text: We use messages only to reply to you and to fix what you report.\nretention:\n- scope: Studies kept under a code\n  period: until you ask us to delete it\n  text: A study kept under a code stays until you ask us to delete it, so that a printed study's QR code keeps working.\n- scope: Request logs\n  period: a few days\n  text: Request logs are kept by our host for a short period, normally a few days, and then deleted.\n- scope: Messages\n  period: null\n  text: Messages are kept for as long as we need to answer\
  \ and resolve them, and are deleted when you ask.\nresidency:\n- region: Mumbai, India\n  text: Our hosting provider (Vercel) runs the website and the service in Mumbai and keeps the request logs.\n- region: Mumbai, India\n  text: Our database provider (Supabase) stores studies under their codes and the usage counts, in Mumbai.\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Write to hello@citiwise.in\n  text: By using Citiwise you agree to these uses; you can withdraw by writing to us, and we will delete what we\n    hold.\nrights:\n- right: Access, correction, deletion, nominate\n  text: you may ask what we hold about you, ask us to correct or delete it, and name someone to act for you.\n- right: Complain to regulator\n  text: If you are not satisfied with our answer, you may complain to the Data Protection Board of India.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell any data, and we\
  \ do not use it for advertising or to build profiles.\n"
source_yaml_url: https://artifacts.apis.io/citiwise-in/privacy/citiwise-in-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Citiwise's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- India
- Urban Planning
- Land Use
- Mapping
---
