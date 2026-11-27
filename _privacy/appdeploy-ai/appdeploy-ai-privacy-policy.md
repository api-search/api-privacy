---
api_specs:
- filename: appdeploy-ai-mcp-api-openapi.yml
  format: yaml
  label: appdeploy-ai MCP API
  slug: appdeploy-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdeploy-ai/openapi/appdeploy-ai-mcp-api-openapi.yml
- filename: appdeploy-ai-oauth-discovery-api-openapi.yml
  format: yaml
  label: appdeploy-ai OAuth discovery API
  slug: appdeploy-ai-oauth-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appdeploy-ai/openapi/appdeploy-ai-oauth-discovery-api-openapi.yml
claim_count: 24
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'User identifier : when you use the Integrations, we receive an identifier used to associate deployments with your account, such as a guest identifier or an authenticated user ID.'
  - category: contact
    text: Your email address may be present in the token; we do not require it to provide the core service.
  - category: financial
    text: Billing information may include your name, email, billing address, country, tax information and payment details provided through checkout.
  - category: device
    text: 'Device/browser data : standard HTTP logs, approximate location derived from IP at the infrastructure layer and diagnostic information for the Website.'
  - category: communication
    text: If you contact support, we collect the information you provide, such as your email address, message content and any attachments.
  - category: other
    text: project files, source code, configuration files, static assets, app names, app descriptions, app intent, acceptance criteria, deployment instructions, generated code, patches, corrected code, build logs, deployment logs, runtime logs, automated QA observations, browser observations, DOM observations, console logs, network logs, screenshots
  deletion:
    route: Deletion requests via AppDeploy tools, asking your AI platform or agent client to delete your app, or emailing support@appdeploy.ai; account deletion via Account menu
    text: You may request deletion of deployments and associated personal data through available AppDeploy tools, including by asking your AI platform or agent client to delete your app, or by contacting support@appdeploy.ai if you cannot use the tool flow.
  dpa:
    available: true
    text: The standard online DPA is available at appdeploy.ai/dpa .
    url: appdeploy.ai/dpa
  purposes:
  - purpose: Provide the Service
    text: create deployments, host your app, show deployment status and URLs, test deployments, troubleshoot failures and support Service operations.
  - purpose: Authenticate and prevent abuse
    text: secure the Service, validate requests, detect fraud or misuse and enforce our Terms.
  - purpose: Model improvement and evaluation
    text: we may use User Content, Deployment Data, Feedback Data and Derived Data to train, fine-tune, evaluate, benchmark and improve AppDeploy's QA, verification, repair, deployment, safety, abuse-detection and reliability models and related AI systems.
  - purpose: Commercial and cost improvement
    text: we may use User Content, Deployment Data, Feedback Data and Derived Data to improve deployment success, repair quality, safety, abuse detection, latency, reliability, cost efficiency, commercial licensing opportunities and related product development.
  residency:
  - region: United States (us-east-1)
    text: We process and store data in the United States (us-east-1).
  retention:
  - period: null
    scope: Deployment and Feedback Data for model improvement
    text: we may retain User Content, Deployment Data and Feedback Data for as long as reasonably necessary to operate, secure, develop, train, evaluate, benchmark, commercialize and improve AppDeploy's models, systems and services
  - period: 30 consecutive days with no visitors and no deployments
    scope: Free app hosted data
    text: we may delete Free apps and their associated hosted data after 30 consecutive days with no visitors and no deployments, without guaranteed advance notice except where required by law.
  - period: up to 30 days after deletion
    scope: Backups
    text: 'Backups : retained for up to 30 days after deletion for disaster recovery.'
  - period: null
    scope: Derived data and model outputs
    text: we may retain Derived Data, aggregated data, de-identified data, anonymized data, evaluation results, benchmarks, statistical outputs, technical learnings and trained model weights for longer periods
  rights:
  - right: Access
    text: Access, rectification, deletion, restriction, portability and objection.
  - right: Withdraw consent
    text: Withdraw consent at any time for processing based on consent
  - right: Complaint to supervisory authority
    text: If you are located in the EEA/UK, you also have the right to lodge a complaint with your local supervisory authority.
  role:
    text: FreeBraavos LTD may act as a data controller for account, billing, security, service operations, website analytics and data uses under the service data license, and as a data processor when hosting and processing data on your behalf in connection with deployed apps.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not use deployment content or Integration data to build advertising profiles, and we do not operate as a data broker.
  subprocessors:
    text: A current list is available at appdeploy.ai/subprocessors .
    url: appdeploy.ai/subprocessors
  transfers:
  - mechanism: SCC
    text: we rely on the European Commission's Standard Contractual Clauses (SCCs), the UK IDTA or UK Addendum to the EU SCCs, as applicable, or other valid transfer mechanisms.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: appdeploy-ai
provenance_date: '2026-11-09'
provider_name: appdeploy-ai
provider_slug: appdeploy-ai
slug: appdeploy-ai-privacy-policy
source_date: '2026-11-09'
source_filename: appdeploy-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://appdeploy.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: appdeploy-ai\naid: appdeploy-ai\nurl: https://appdeploy.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: FreeBraavos LTD may act as a data controller for account, billing, security, service operations, website\n    analytics and data uses under the service data license, and as a data processor when hosting and processing\n    data on your behalf in connection with deployed apps.\ndata_categories:\n- category: identifying\n  text: 'User identifier : when you use the Integrations, we receive an identifier used to associate deployments\n    with your account, such as a guest identifier or\
  \ an authenticated user ID.'\n- category: contact\n  text: Your email address may be present in the token; we do not require it to provide the core service.\n- category: financial\n  text: Billing information may include your name, email, billing address, country, tax information and payment\n    details provided through checkout.\n- category: device\n  text: 'Device/browser data : standard HTTP logs, approximate location derived from IP at the infrastructure layer\n    and diagnostic information for the Website.'\n- category: communication\n  text: If you contact support, we collect the information you provide, such as your email address, message content\n    and any attachments.\n- category: other\n  text: project files, source code, configuration files, static assets, app names, app descriptions, app intent,\n    acceptance criteria, deployment instructions, generated code, patches, corrected code, build logs, deployment\n    logs, runtime logs, automated QA observations, browser observations,\
  \ DOM observations, console logs, network\n    logs, screenshots\npurposes:\n- purpose: Provide the Service\n  text: create deployments, host your app, show deployment status and URLs, test deployments, troubleshoot failures\n    and support Service operations.\n- purpose: Authenticate and prevent abuse\n  text: secure the Service, validate requests, detect fraud or misuse and enforce our Terms.\n- purpose: Model improvement and evaluation\n  text: we may use User Content, Deployment Data, Feedback Data and Derived Data to train, fine-tune, evaluate,\n    benchmark and improve AppDeploy's QA, verification, repair, deployment, safety, abuse-detection and reliability\n    models and related AI systems.\n- purpose: Commercial and cost improvement\n  text: we may use User Content, Deployment Data, Feedback Data and Derived Data to improve deployment success,\n    repair quality, safety, abuse detection, latency, reliability, cost efficiency, commercial licensing opportunities\n    and related\
  \ product development.\nretention:\n- scope: Deployment and Feedback Data for model improvement\n  period: null\n  text: we may retain User Content, Deployment Data and Feedback Data for as long as reasonably necessary to operate,\n    secure, develop, train, evaluate, benchmark, commercialize and improve AppDeploy's models, systems and services\n- scope: Free app hosted data\n  period: 30 consecutive days with no visitors and no deployments\n  text: we may delete Free apps and their associated hosted data after 30 consecutive days with no visitors and\n    no deployments, without guaranteed advance notice except where required by law.\n- scope: Backups\n  period: up to 30 days after deletion\n  text: 'Backups : retained for up to 30 days after deletion for disaster recovery.'\n- scope: Derived data and model outputs\n  period: null\n  text: we may retain Derived Data, aggregated data, de-identified data, anonymized data, evaluation results, benchmarks,\n    statistical outputs, technical\
  \ learnings and trained model weights for longer periods\nresidency:\n- region: United States (us-east-1)\n  text: We process and store data in the United States (us-east-1).\ntransfers:\n- mechanism: SCC\n  text: we rely on the European Commission's Standard Contractual Clauses (SCCs), the UK IDTA or UK Addendum to\n    the EU SCCs, as applicable, or other valid transfer mechanisms.\nsubprocessors:\n  url: appdeploy.ai/subprocessors\n  text: A current list is available at appdeploy.ai/subprocessors .\ndpa:\n  available: true\n  url: appdeploy.ai/dpa\n  text: The standard online DPA is available at appdeploy.ai/dpa .\ndeletion:\n  route: Deletion requests via AppDeploy tools, asking your AI platform or agent client to delete your app, or emailing\n    support@appdeploy.ai; account deletion via Account menu\n  text: You may request deletion of deployments and associated personal data through available AppDeploy tools,\n    including by asking your AI platform or agent client to delete your\
  \ app, or by contacting support@appdeploy.ai\n    if you cannot use the tool flow.\nrights:\n- right: Access\n  text: Access, rectification, deletion, restriction, portability and objection.\n- right: Withdraw consent\n  text: Withdraw consent at any time for processing based on consent\n- right: Complaint to supervisory authority\n  text: If you are located in the EEA/UK, you also have the right to lodge a complaint with your local supervisory\n    authority.\nsale_or_sharing:\n  stance: prohibited\n  text: We do not use deployment content or Integration data to build advertising profiles, and we do not operate\n    as a data broker.\n"
source_yaml_url: https://artifacts.apis.io/appdeploy-ai/privacy/appdeploy-ai-privacy-policy.yml
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
summary_line: 24 quoted statements, read from appdeploy-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Deployment
- Platform
- Low-Code
- Automation
---
