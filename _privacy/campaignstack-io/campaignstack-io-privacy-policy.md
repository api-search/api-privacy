---
api_specs:
- filename: campaignstack-io-openapi-generated.yml
  format: yaml
  label: CampaignStack API
  slug: campaignstack-io-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/campaignstack-io/openapi/_ae-authored/campaignstack-io-openapi-generated.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: identifying
    text: Your email address and name.
  - category: contact
    text: a work email when one was found
  - category: professional
    text: name, title, seniority, location, employer, public headline, LinkedIn URL
  - category: behavioral
    text: dated professional events such as a job change or engagement with a public post
  - category: financial
    text: we hold the subscription state and never a card number
  - category: device
    text: your browser's user agent (its name and version, which Meta asks for)
  deletion:
    route: Settings account deletion, the privacy request form, or privacy@campaignstack.io
    text: You can delete your account from Settings; the workspaces you own go with it.
  dpa:
    available: true
    text: 'AI providers: profile text and message text used to draft outreach go to DeepSeek V4.1 Flash hosted by DeepInfra, with OpenAI and Anthropic as fallbacks, all under data processing agreements.'
    url: null
  purposes:
  - purpose: reaching business decision-makers
    text: reaching business decision-makers with relevant, capped, human-reviewed outreach
  - purpose: advertising measurement
    text: That is how they measure our ads and stop showing them to people who are already customers.
  - purpose: AI drafting of outreach
    text: profile text and message text used to draft outreach go to DeepSeek V4.1 Flash hosted by DeepInfra
  residency:
  - region: United States
    text: Convex (database and backend, United States)
  - region: Canada
    text: OVH (automation server, Canada)
  retention:
  - period: 18 months
    scope: unclaimed professional profiles
    text: A professional profile that no customer has attached to a workspace, a list or a conversation is deleted 18 months after it was last updated, by a daily sweep.
  - period: for as long as the account exists
    scope: customer accounts
    text: 'Customer accounts: for as long as the account exists.'
  - period: 90 days
    scope: workspace data after deletion
    text: the private leads, lists, imports and conversations it held are deleted 90 days later by a daily job.
  - period: 90 days
    scope: outbound attribution records
    text: 'Outbound attribution records: 90 days.'
  - period: 90 days
    scope: ad click id
    text: we also keep the ad click id from the link that brought you, for up to 90 days
  rights:
  - right: access, correction, deletion, copy
    text: you can ask what we hold, have it corrected or deleted, receive a copy, or object to the processing.
  - right: objection and erasure
    text: An objection or an erasure lands your email address and LinkedIn URL in a suppression register
  - right: complain to authority
    text: you can complain to your national data protection authority.
  role:
    text: For this database CampaignStack is the controller
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell data and no provider may train models on it under our agreements.
  subprocessors:
    text: The full list with what each one receives is on the security page
    url: null
  transfers:
  - mechanism: SCC
    text: Transfers outside the EEA rest on the provider's standard contractual clauses
  - mechanism: DPF
    text: or its EU-US Data Privacy Framework certification, as stated in each provider's agreement.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: CampaignStack
provenance_date: '2026-11-09'
provider_name: CampaignStack
provider_slug: campaignstack-io
slug: campaignstack-io-privacy-policy
source_date: '2026-11-09'
source_filename: campaignstack-io-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://campaignstack.io/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: CampaignStack\naid: campaignstack-io\nurl: https://campaignstack.io/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: For this database CampaignStack is the controller\ndata_categories:\n- category: identifying\n  text: Your email address and name.\n- category: contact\n  text: a work email when one was found\n- category: professional\n  text: name, title, seniority, location, employer, public headline, LinkedIn URL\n- category: behavioral\n  text: dated professional events such as a job change or engagement with a public post\n- category: financial\n  text: we hold the subscription state and\
  \ never a card number\n- category: device\n  text: your browser's user agent (its name and version, which Meta asks for)\npurposes:\n- purpose: reaching business decision-makers\n  text: reaching business decision-makers with relevant, capped, human-reviewed outreach\n- purpose: advertising measurement\n  text: That is how they measure our ads and stop showing them to people who are already customers.\n- purpose: AI drafting of outreach\n  text: profile text and message text used to draft outreach go to DeepSeek V4.1 Flash hosted by DeepInfra\nretention:\n- scope: unclaimed professional profiles\n  period: 18 months\n  text: A professional profile that no customer has attached to a workspace, a list or a conversation is deleted\n    18 months after it was last updated, by a daily sweep.\n- scope: customer accounts\n  period: for as long as the account exists\n  text: 'Customer accounts: for as long as the account exists.'\n- scope: workspace data after deletion\n  period: 90 days\n  text:\
  \ the private leads, lists, imports and conversations it held are deleted 90 days later by a daily job.\n- scope: outbound attribution records\n  period: 90 days\n  text: 'Outbound attribution records: 90 days.'\n- scope: ad click id\n  period: 90 days\n  text: we also keep the ad click id from the link that brought you, for up to 90 days\nresidency:\n- region: United States\n  text: Convex (database and backend, United States)\n- region: Canada\n  text: OVH (automation server, Canada)\ntransfers:\n- mechanism: SCC\n  text: Transfers outside the EEA rest on the provider's standard contractual clauses\n- mechanism: DPF\n  text: or its EU-US Data Privacy Framework certification, as stated in each provider's agreement.\nsubprocessors:\n  url: null\n  text: The full list with what each one receives is on the security page\ndpa:\n  available: true\n  url: null\n  text: 'AI providers: profile text and message text used to draft outreach go to DeepSeek V4.1 Flash hosted by\n    DeepInfra, with\
  \ OpenAI and Anthropic as fallbacks, all under data processing agreements.'\ndeletion:\n  route: Settings account deletion, the privacy request form, or privacy@campaignstack.io\n  text: You can delete your account from Settings; the workspaces you own go with it.\nrights:\n- right: access, correction, deletion, copy\n  text: you can ask what we hold, have it corrected or deleted, receive a copy, or object to the processing.\n- right: objection and erasure\n  text: An objection or an erasure lands your email address and LinkedIn URL in a suppression register\n- right: complain to authority\n  text: you can complain to your national data protection authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not sell data and no provider may train models on it under our agreements.\n"
source_yaml_url: https://artifacts.apis.io/campaignstack-io/privacy/campaignstack-io-privacy-policy.yml
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
summary_line: 26 quoted statements, read from CampaignStack's own page on 2026-11-09.
synthetic: false
tags:
- Outbound Outreach
- LinkedIn sourcing
- B2B SaaS
---
