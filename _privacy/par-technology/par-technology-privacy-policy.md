---
api_specs:
- filename: par-technology-auth-api-openapi.yml
  format: yaml
  label: PAR Technology Auth API
  slug: par-technology-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-auth-api-openapi.yml
- filename: par-technology-discounts-api-openapi.yml
  format: yaml
  label: PAR Technology Discounts API
  slug: par-technology-discounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-discounts-api-openapi.yml
- filename: par-technology-pos-api-openapi.yml
  format: yaml
  label: PAR Technology Pos API
  slug: par-technology-pos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-pos-api-openapi.yml
- filename: par-technology-redemptions-api-openapi.yml
  format: yaml
  label: PAR Technology Redemptions API
  slug: par-technology-redemptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/par-technology/openapi/par-technology-redemptions-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: identifying
    text: First name, last name, social security number, username or similar identifier, password, date of birth, title, address, email address and telephone numbers.
  - category: financial
    text: Account information, payment preference and payment and gift card details.
  - category: location
    text: Information such as longitude and latitude from your IP address or mobile device when using our mobile apps
  - category: biometric
    text: Biometric information used for uniquely identifying a consumer or employee of our Business Customer through the use of our Products and Services.
  - category: behavioral
    text: Inferences from PI Collected Information drawn from any of the above-referenced personal information to create a profile about a consumer reflecting the consumer’s preferences, characteristics, psychological trends, predispositions, behavior, attitudes, intelligence, abilities, and aptitudes.
  - category: device
    text: Information such as internet protocol (IP) address, your login information, browser type and version, time zone setting, browser plug-in types and versions, operating system and platform
  deletion:
    route: Contact privacy@partech.com or the Business Customer
    text: When our Business Customer provides notice that the user should be deleted from the subscription software services, our policy is to delete the user’s information, including the token, promptly upon receipt of that notice.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide Products and Services and administer accounts
    text: Provide the Products and Services and to register and administer accounts for Business Customers for use of our Sites and our Products and Services;
  - purpose: Marketing
    text: For marketing, such as for contextual ad customization or to market the Products and Services or the services of our affiliates, Business Customers, or other third parties.
  - purpose: Fraud prevention and security
    text: To prevent fraud, such as using personal information about you obtained through our Products and Services and from our Business Customers
  retention:
  - period: null
    scope: Personal information generally
    text: We keep your personal information for no longer than reasonably necessary to achieve the purposes for which it was collected or processed
  - period: null
    scope: Biometric token
    text: 'In no event will the token be kept beyond the earlier of: (a) one (1) month from our receipt of notice from the Business Customer that the user should be deleted from the subscription software services; and (b) three (3) years since the user’s last use of the token.'
  rights:
  - right: Exercise privacy rights under U.S. Privacy Laws
    text: 'If you are seeking to exercise your privacy rights under U.S. Privacy Laws, you may call us at 1-800-448-6505, option #5 or by visiting the Your Privacy Choices webpage.'
  - right: Withdraw consent to marketing
    text: You have the right to withdraw consent to marketing at any time by contacting us.
  - right: Opt out of marketing messages
    text: You can ask us or third parties to stop sending you marketing messages at any time by following the opt-out links
  role:
    text: In most cases, we collect and process personal information solely in our capacity as a service provider (or “processor” for purposes of the GDPR and certain U.S. Privacy Laws) to our Business Customers.
    value: both
  sale_or_sharing:
    stance: unstated
    text: we do not knowingly sell or share (as “share” is defined by the CCPA) any information, including personal information, from children under 16 years of age.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: PAR Technology
provenance_date: '2026-11-10'
provider_name: PAR Technology
provider_slug: par-technology
slug: par-technology-privacy-policy
source_date: '2026-11-10'
source_filename: par-technology-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://partech.com/privacy-policy/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: PAR Technology\naid: par-technology\nurl: https://partech.com/privacy-policy/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: In most cases, we collect and process personal information solely in our capacity as a service provider\n    (or “processor” for purposes of the GDPR and certain U.S. Privacy Laws) to our Business Customers.\ndata_categories:\n- category: identifying\n  text: First name, last name, social security number, username or similar identifier, password, date of birth,\n    title, address, email address and telephone numbers.\n- category: financial\n  text: Account information, payment\
  \ preference and payment and gift card details.\n- category: location\n  text: Information such as longitude and latitude from your IP address or mobile device when using our mobile apps\n- category: biometric\n  text: Biometric information used for uniquely identifying a consumer or employee of our Business Customer through\n    the use of our Products and Services.\n- category: behavioral\n  text: Inferences from PI Collected Information drawn from any of the above-referenced personal information to\n    create a profile about a consumer reflecting the consumer’s preferences, characteristics, psychological trends,\n    predispositions, behavior, attitudes, intelligence, abilities, and aptitudes.\n- category: device\n  text: Information such as internet protocol (IP) address, your login information, browser type and version, time\n    zone setting, browser plug-in types and versions, operating system and platform\npurposes:\n- purpose: Provide Products and Services and administer accounts\n\
  \  text: Provide the Products and Services and to register and administer accounts for Business Customers for use\n    of our Sites and our Products and Services;\n- purpose: Marketing\n  text: For marketing, such as for contextual ad customization or to market the Products and Services or the services\n    of our affiliates, Business Customers, or other third parties.\n- purpose: Fraud prevention and security\n  text: To prevent fraud, such as using personal information about you obtained through our Products and Services\n    and from our Business Customers\nretention:\n- scope: Personal information generally\n  period: null\n  text: We keep your personal information for no longer than reasonably necessary to achieve the purposes for which\n    it was collected or processed\n- scope: Biometric token\n  period: null\n  text: 'In no event will the token be kept beyond the earlier of: (a) one (1) month from our receipt of notice\n    from the Business Customer that the user should be deleted\
  \ from the subscription software services; and (b)\n    three (3) years since the user’s last use of the token.'\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact privacy@partech.com or the Business Customer\n  text: When our Business Customer provides notice that the user should be deleted from the subscription software\n    services, our policy is to delete the user’s information, including the token, promptly upon receipt of that\n    notice.\nrights:\n- right: Exercise privacy rights under U.S. Privacy Laws\n  text: 'If you are seeking to exercise your privacy rights under U.S. Privacy Laws, you may call us at 1-800-448-6505,\n    option #5 or by visiting the Your Privacy Choices webpage.'\n- right: Withdraw consent to marketing\n  text: You have the right to withdraw consent to marketing at any time by contacting us.\n- right: Opt out of marketing messages\n  text: You can ask us\
  \ or third parties to stop sending you marketing messages at any time by following the opt-out\n    links\nsale_or_sharing:\n  stance: unstated\n  text: we do not knowingly sell or share (as “share” is defined by the CCPA) any information, including personal\n    information, from children under 16 years of age.\n"
source_yaml_url: https://artifacts.apis.io/par-technology/privacy/par-technology-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- deletion
- rights
summary_line: 16 quoted statements, read from PAR Technology's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Hospitality
- Point-of-Sale
- Loyalty
- Retail
---
