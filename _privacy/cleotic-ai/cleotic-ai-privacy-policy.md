---
claim_count: 58
description: ''
doc:
  data_categories:
  - category: identifying
    text: Name, email address, organisation, role, when you were last active, and sign-in records
  - category: contact
    text: Website address, email address, time zone, the page you arrived on, the referring page and campaign tags.
  - category: financial
    text: Name, email address, plan, subscription and invoices, and what you enter on Stripe’s payment page. We never see card details.
  - category: location
    text: approximate location from your IP address
  - category: behavioral
    text: Pages you open and what you click or do, linked to your name, email address and organisation
  - category: device
    text: Pages viewed, clicks and scrolls, the referring page, device and browser, and approximate location from your IP address.
  - category: other
    text: Prompts, brand facts, drafts, AI answers and Search Console queries can name people, such as a company’s founder.
  - category: identifying
    source: https://cleotic.ai/subprocessors
    text: Names and email addresses of authorised users, sign-in records, and access to connected Google accounts
  - category: contact
    source: https://cleotic.ai/subprocessors
    text: Recipients’ email addresses and names, and the email contents
  - category: behavioral
    source: https://cleotic.ai/subprocessors
    text: Usage events and page addresses; the name and email address of each signed-in user, and their organisation’s name and plan; errors; and session recordings that mask all text and inputs
  - category: device
    source: https://cleotic.ai/subprocessors
    text: Each request it carries, including the sender’s IP address, user agent and other headers, and what the request contains
  deletion:
    route: Email privacy@cleotic.ai
    text: To see, correct or delete your data, email privacy@cleotic.ai.
  dpa:
    available: true
    text: We use it only to provide Cleotic to them, under our Data Processing Agreement.
    url: null
  purposes:
  - purpose: Run account and provide features
    text: Run your account
  - purpose: Import Google Search Console data
    text: Import Google Search Console data, if an admin connects a Google account
  - purpose: Take payment
    text: Take payment and keep accounts
  - purpose: Send account emails
    text: Send emails about your account and the service
  - purpose: Marketing emails with consent
    text: Send marketing emails, if you turned them on
  - purpose: Product analytics and error finding
    text: Understand how the app is used, and find and fix problems
  - purpose: Keep Cleotic secure
    text: Keep Cleotic secure and prevent abuse
  - purpose: Hosting the application and its data
    source: https://cleotic.ai/subprocessors
    text: Hosts the application and its data
  - purpose: Routing requests to AI models
    source: https://cleotic.ai/subprocessors
    text: Routes requests to AI models from OpenAI, Anthropic, Google, Perplexity, xAI and others
  - purpose: Product analytics
    source: https://cleotic.ai/subprocessors
    text: Product analytics and session recordings in the web app
  - purpose: Sending emails
    source: https://cleotic.ai/subprocessors
    text: Sends weekly emails, scan results, account emails and the reports customers send
  residency:
  - region: Netherlands
    text: Our application and database are hosted in the Netherlands.
  - region: UAE
    text: We are based in the UAE.
  - region: Netherlands
    source: https://cleotic.ai/subprocessors
    text: Netherlands (Amsterdam)
  - region: US, UK, India
    source: https://cleotic.ai/subprocessors
    text: US, UK and India. Each request runs in the region nearest the user.
  - region: US
    source: https://cleotic.ai/subprocessors
    text: US. Each request passes through its data centre nearest the sender, worldwide.
  - region: Estonia
    source: https://cleotic.ai/subprocessors
    text: Estonia (an EU company; it does not publish where its servers are)
  - region: France
    source: https://cleotic.ai/subprocessors
    text: France (Paris), with some of its own sub-processors in the US
  - region: Germany
    source: https://cleotic.ai/subprocessors
    text: EU (Frankfurt, Germany)
  retention:
  - period: null
    scope: Account and organisation data
    text: Until the organisation’s owner deletes it, or 60 days after its subscription or trial ends.
  - period: The last 16 months of daily totals and the last 90 days of search queries
    scope: Google Search Console data
    text: The last 16 months of daily totals and the last 90 days of search queries. Older days are deleted every day.
  - period: 90 days
    scope: IP address on customer visit data
    text: We clear it 90 days after we receive it.
  - period: 7 years
    scope: Billing records
    text: Billing records 7 years, as UAE tax law requires
  - period: 12 months
    scope: Free tool checks
    text: Free tool checks, with the email and IP address given 12 months, then the check, email address and IP address are deleted
  - period: 2 years after our last contact
    scope: Demo requests (HubSpot)
    text: Demo requests (HubSpot) 2 years after our last contact
  - period: 7 years after the last message
    scope: Support emails
    text: Support emails 7 years after the last message
  - period: 30 days
    scope: Server logs
    text: Server logs 30 days
  - period: null
    scope: DataForSEO prompt text
    source: https://cleotic.ai/subprocessors
    text: DataForSEO’s terms set no time limit for deleting the prompt text we send it.
  - period: null
    scope: TypeSafe derived data
    source: https://cleotic.ai/subprocessors
    text: TypeSafe may keep and reuse what it derives from them; see below.
  rights:
  - right: access
    text: get a copy of the personal data we hold about you
  - right: correction
    text: have it corrected
  - right: deletion
    text: have it deleted
  - right: restriction
    text: have its use restricted
  - right: portability
    text: get it in a machine-readable format, or have it sent to another company
  - right: objection
    text: object to how we use it when we rely on legitimate interests, and to direct marketing at any time
  - right: withdraw consent
    text: withdraw your consent at any time, without affecting what we did before
  - right: complain
    text: complain to a data protection authority
  role:
    text: For data about our customers and their users, visitors to our website, people who use our free tools, and people we talk to about sales, we decide how the data is used. We are its controller, and this policy applies in full.
    value: both
  sale_or_sharing:
    stance: prohibited
    text: We do not sell personal data.
  subprocessors:
    text: Our sub-processors page lists them, with what each receives.
    url: https://cleotic.ai/subprocessors
  transfers:
  - mechanism: DPF
    text: 'Stripe, HubSpot, Google, Reddit, X and GitHub : the Data Privacy Framework, and the Standard Contractual Clauses with the UK Addendum.'
  - mechanism: SCC
    text: 'Microsoft : the Data Privacy Framework with its UK Extension, and the Standard Contractual Clauses.'
  - mechanism: other
    text: 'ClickTerm : none needed. It is an EU company and keeps the data in the EU.'
  - mechanism: DPF
    source: https://cleotic.ai/subprocessors
    text: the EU-US Data Privacy Framework (DPF)
  - mechanism: SCC
    source: https://cleotic.ai/subprocessors
    text: the European Commission’s Standard Contractual Clauses (SCCs) with the UK Addendum or the UK International Data Transfer Agreement (IDTA)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cleotic
provenance_date: '2026-11-09'
provider_name: Cleotic
provider_slug: cleotic-ai
slug: cleotic-ai-privacy-policy
source_date: '2026-11-09'
source_filename: cleotic-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cleotic.ai/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cleotic\naid: cleotic-ai\nurl: https://cleotic.ai/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://cleotic.ai/privacy\n  - https://cleotic.ai/subprocessors\nrole:\n  value: both\n  text: For data about our customers and their users, visitors to our website, people who use our free tools, and\n    people we talk to about sales, we decide how the data is used. We are its controller, and this policy applies\n    in full.\ndata_categories:\n- category: identifying\n  text: Name, email address, organisation, role, when you were last active, and sign-in records\n- category: contact\n  text: Website address,\
  \ email address, time zone, the page you arrived on, the referring page and campaign tags.\n- category: financial\n  text: Name, email address, plan, subscription and invoices, and what you enter on Stripe’s payment page. We never\n    see card details.\n- category: location\n  text: approximate location from your IP address\n- category: behavioral\n  text: Pages you open and what you click or do, linked to your name, email address and organisation\n- category: device\n  text: Pages viewed, clicks and scrolls, the referring page, device and browser, and approximate location from\n    your IP address.\n- category: other\n  text: Prompts, brand facts, drafts, AI answers and Search Console queries can name people, such as a company’s\n    founder.\n- category: identifying\n  text: Names and email addresses of authorised users, sign-in records, and access to connected Google accounts\n  source: https://cleotic.ai/subprocessors\n- category: contact\n  text: Recipients’ email addresses and names,\
  \ and the email contents\n  source: https://cleotic.ai/subprocessors\n- category: behavioral\n  text: Usage events and page addresses; the name and email address of each signed-in user, and their organisation’s\n    name and plan; errors; and session recordings that mask all text and inputs\n  source: https://cleotic.ai/subprocessors\n- category: device\n  text: Each request it carries, including the sender’s IP address, user agent and other headers, and what the request\n    contains\n  source: https://cleotic.ai/subprocessors\npurposes:\n- purpose: Run account and provide features\n  text: Run your account\n- purpose: Import Google Search Console data\n  text: Import Google Search Console data, if an admin connects a Google account\n- purpose: Take payment\n  text: Take payment and keep accounts\n- purpose: Send account emails\n  text: Send emails about your account and the service\n- purpose: Marketing emails with consent\n  text: Send marketing emails, if you turned them on\n- purpose:\
  \ Product analytics and error finding\n  text: Understand how the app is used, and find and fix problems\n- purpose: Keep Cleotic secure\n  text: Keep Cleotic secure and prevent abuse\n- purpose: Hosting the application and its data\n  text: Hosts the application and its data\n  source: https://cleotic.ai/subprocessors\n- purpose: Routing requests to AI models\n  text: Routes requests to AI models from OpenAI, Anthropic, Google, Perplexity, xAI and others\n  source: https://cleotic.ai/subprocessors\n- purpose: Product analytics\n  text: Product analytics and session recordings in the web app\n  source: https://cleotic.ai/subprocessors\n- purpose: Sending emails\n  text: Sends weekly emails, scan results, account emails and the reports customers send\n  source: https://cleotic.ai/subprocessors\nretention:\n- scope: Account and organisation data\n  period: null\n  text: Until the organisation’s owner deletes it, or 60 days after its subscription or trial ends.\n- scope: Google Search Console\
  \ data\n  period: The last 16 months of daily totals and the last 90 days of search queries\n  text: The last 16 months of daily totals and the last 90 days of search queries. Older days are deleted every\n    day.\n- scope: IP address on customer visit data\n  period: 90 days\n  text: We clear it 90 days after we receive it.\n- scope: Billing records\n  period: 7 years\n  text: Billing records 7 years, as UAE tax law requires\n- scope: Free tool checks\n  period: 12 months\n  text: Free tool checks, with the email and IP address given 12 months, then the check, email address and IP address\n    are deleted\n- scope: Demo requests (HubSpot)\n  period: 2 years after our last contact\n  text: Demo requests (HubSpot) 2 years after our last contact\n- scope: Support emails\n  period: 7 years after the last message\n  text: Support emails 7 years after the last message\n- scope: Server logs\n  period: 30 days\n  text: Server logs 30 days\n- scope: DataForSEO prompt text\n  period: null\n  text:\
  \ DataForSEO’s terms set no time limit for deleting the prompt text we send it.\n  source: https://cleotic.ai/subprocessors\n- scope: TypeSafe derived data\n  period: null\n  text: TypeSafe may keep and reuse what it derives from them; see below.\n  source: https://cleotic.ai/subprocessors\nresidency:\n- region: Netherlands\n  text: Our application and database are hosted in the Netherlands.\n- region: UAE\n  text: We are based in the UAE.\n- region: Netherlands\n  text: Netherlands (Amsterdam)\n  source: https://cleotic.ai/subprocessors\n- region: US, UK, India\n  text: US, UK and India. Each request runs in the region nearest the user.\n  source: https://cleotic.ai/subprocessors\n- region: US\n  text: US. Each request passes through its data centre nearest the sender, worldwide.\n  source: https://cleotic.ai/subprocessors\n- region: Estonia\n  text: Estonia (an EU company; it does not publish where its servers are)\n  source: https://cleotic.ai/subprocessors\n- region: France\n  text:\
  \ France (Paris), with some of its own sub-processors in the US\n  source: https://cleotic.ai/subprocessors\n- region: Germany\n  text: EU (Frankfurt, Germany)\n  source: https://cleotic.ai/subprocessors\ntransfers:\n- mechanism: DPF\n  text: 'Stripe, HubSpot, Google, Reddit, X and GitHub : the Data Privacy Framework, and the Standard Contractual\n    Clauses with the UK Addendum.'\n- mechanism: SCC\n  text: 'Microsoft : the Data Privacy Framework with its UK Extension, and the Standard Contractual Clauses.'\n- mechanism: other\n  text: 'ClickTerm : none needed. It is an EU company and keeps the data in the EU.'\n- mechanism: DPF\n  text: the EU-US Data Privacy Framework (DPF)\n  source: https://cleotic.ai/subprocessors\n- mechanism: SCC\n  text: the European Commission’s Standard Contractual Clauses (SCCs) with the UK Addendum or the UK International\n    Data Transfer Agreement (IDTA)\n  source: https://cleotic.ai/subprocessors\nsubprocessors:\n  url: https://cleotic.ai/subprocessors\n\
  \  text: Our sub-processors page lists them, with what each receives.\ndpa:\n  available: true\n  url: null\n  text: We use it only to provide Cleotic to them, under our Data Processing Agreement.\ndeletion:\n  route: Email privacy@cleotic.ai\n  text: To see, correct or delete your data, email privacy@cleotic.ai.\nrights:\n- right: access\n  text: get a copy of the personal data we hold about you\n- right: correction\n  text: have it corrected\n- right: deletion\n  text: have it deleted\n- right: restriction\n  text: have its use restricted\n- right: portability\n  text: get it in a machine-readable format, or have it sent to another company\n- right: objection\n  text: object to how we use it when we rely on legitimate interests, and to direct marketing at any time\n- right: withdraw consent\n  text: withdraw your consent at any time, without affecting what we did before\n- right: complain\n  text: complain to a data protection authority\nsale_or_sharing:\n  stance: prohibited\n  text:\
  \ We do not sell personal data.\n"
source_yaml_url: https://artifacts.apis.io/cleotic-ai/privacy/cleotic-ai-privacy-policy.yml
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
summary_line: 58 quoted statements, read from Cleotic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Visibility
- Answer Engine Optimization
- Generative Engine Optimization
- SEO
- Brand Monitoring
- Content Management
- MCP
- CLI
---
