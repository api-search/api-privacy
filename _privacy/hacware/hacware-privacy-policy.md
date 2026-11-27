---
api_specs:
- filename: hacware-admin-api-openapi.yml
  format: yaml
  label: Hacware Admin API
  slug: hacware-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-admin-api-openapi.yml
- filename: hacware-compliance-api-openapi.yml
  format: yaml
  label: Hacware Compliance API
  slug: hacware-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-compliance-api-openapi.yml
- filename: hacware-compliance-tenant-api-openapi.yml
  format: yaml
  label: Hacware Compliance-Tenant API
  slug: hacware-compliance-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-compliance-tenant-api-openapi.yml
- filename: hacware-customer-api-openapi.yml
  format: yaml
  label: Hacware Customer API
  slug: hacware-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-customer-api-openapi.yml
- filename: hacware-email-tenant-api-openapi.yml
  format: yaml
  label: Hacware Email-Tenant API
  slug: hacware-email-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-email-tenant-api-openapi.yml
- filename: hacware-group-api-openapi.yml
  format: yaml
  label: Hacware Group API
  slug: hacware-group-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-group-api-openapi.yml
- filename: hacware-multi-tenant-api-openapi.yml
  format: yaml
  label: Hacware Multi-Tenant API
  slug: hacware-multi-tenant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-multi-tenant-api-openapi.yml
- filename: hacware-phishing-api-openapi.yml
  format: yaml
  label: Hacware Phishing API
  slug: hacware-phishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-phishing-api-openapi.yml
- filename: hacware-report-api-openapi.yml
  format: yaml
  label: Hacware Report API
  slug: hacware-report-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-report-api-openapi.yml
- filename: hacware-training-api-openapi.yml
  format: yaml
  label: Hacware Training API
  slug: hacware-training-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-training-api-openapi.yml
- filename: hacware-user-api-openapi.yml
  format: yaml
  label: Hacware User API
  slug: hacware-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hacware/openapi/hacware-user-api-openapi.yml
claim_count: 14
description: ''
doc:
  data_categories:
  - category: contact
    text: BusinessContactinformation:firstname,lastname,employer,title,phonenumber,andbusinessemailaddresses
  - category: communication
    text: Automaticallycollectedinformation:informationcollectedviaemailagentincludingdomainname,dateofvisit,businessemailaddress,socialmediacontacts,employer,title,phonenumber,recipientemailaddresses,orothersimilarinformation
  deletion:
    route: null
    text: null
  dpa:
    available: true
    text: DataProcessingAgreementstoonlyprocessdataasauthorizedbytheagreement(s)andupontheinstructionofthecontroller
    url: null
  purposes:
  - purpose: Fraud detection and prevention
    text: Toensurefrauddetectionandprevention
  - purpose: Customer support
    text: Inordertoprovidesupportforourproductsandservices(youcanreachouttousbyphoneoremail)
  residency:
  - region: United States
    text: YourPersonalDatamaybecollected,transferredto,andstoredbyusintheUnitedStatesandbyouraffiliatesinothercountrieswhereweoperate.
  retention:
  - period: null
    scope: personal data
    text: HacWarewillretainyourPersonalDatafortheperiodnecessarytofulfillthepurposeoutlinedinthisProductDataProtectionNoticeunlessalongerretentionperiodisrequiredbyapplicabledataprivacylaw.
  rights:
  - right: Access, correct, amend, delete
    text: Accessing,correcting,amending,deletingyourPersonalData;
  - right: Object to processing based on legitimate interests
    text: ObjectingtoanyprocessingofyourPersonalDatacarriedoutonthebasisofourlegitimateinterests(righttoobject)
  - right: Withdraw consent
    text: withdrawingyourconsentatanytime,withoutaffectingthelawfulnessoftheprocessingbasedonsuchconsentbeforeitswithdrawal
  role:
    text: thisProductDataProtectionNoticeonlyappliestotheextentweprocessPersonalDataintheroleofaprocessoronbehalfofourcustomers.
    value: processor
  sale_or_sharing:
    stance: prohibited
    text: HacWarewillneversellyourPersonalData.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: SCC
    text: forinstancebyenteringintoanagreementtoabidebystandardcontractualclausesforthetransferofdataasapprovedbytheEuropeanCommission(Art.46GDPR)
  - mechanism: other
    text: HacWare,Inc.complieswiththeEU-U.S.PrivacyShieldFramework
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Hacware
provenance_date: '2026-11-09'
provider_name: Hacware
provider_slug: hacware
slug: hacware-privacy-policy
source_date: '2026-11-09'
source_filename: hacware-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://hacware.com/privacy.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Hacware\naid: hacware\nurl: https://hacware.com/privacy.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: processor\n  text: thisProductDataProtectionNoticeonlyappliestotheextentweprocessPersonalDataintheroleofaprocessoronbehalfofourcustomers.\ndata_categories:\n- category: contact\n  text: BusinessContactinformation:firstname,lastname,employer,title,phonenumber,andbusinessemailaddresses\n- category: communication\n  text: Automaticallycollectedinformation:informationcollectedviaemailagentincludingdomainname,dateofvisit,businessemailaddress,socialmediacontacts,employer,title,phonenumber,recipientemailaddresses,orothersimilarinformation\n\
  purposes:\n- purpose: Fraud detection and prevention\n  text: Toensurefrauddetectionandprevention\n- purpose: Customer support\n  text: Inordertoprovidesupportforourproductsandservices(youcanreachouttousbyphoneoremail)\nretention:\n- scope: personal data\n  period: null\n  text: HacWarewillretainyourPersonalDatafortheperiodnecessarytofulfillthepurposeoutlinedinthisProductDataProtectionNoticeunlessalongerretentionperiodisrequiredbyapplicabledataprivacylaw.\nresidency:\n- region: United States\n  text: YourPersonalDatamaybecollected,transferredto,andstoredbyusintheUnitedStatesandbyouraffiliatesinothercountrieswhereweoperate.\ntransfers:\n- mechanism: SCC\n  text: forinstancebyenteringintoanagreementtoabidebystandardcontractualclausesforthetransferofdataasapprovedbytheEuropeanCommission(Art.46GDPR)\n- mechanism: other\n  text: HacWare,Inc.complieswiththeEU-U.S.PrivacyShieldFramework\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: true\n  url: null\n  text: DataProcessingAgreementstoonlyprocessdataasauthorizedbytheagreement(s)andupontheinstructionofthecontroller\n\
  deletion:\n  route: null\n  text: null\nrights:\n- right: Access, correct, amend, delete\n  text: Accessing,correcting,amending,deletingyourPersonalData;\n- right: Object to processing based on legitimate interests\n  text: ObjectingtoanyprocessingofyourPersonalDatacarriedoutonthebasisofourlegitimateinterests(righttoobject)\n- right: Withdraw consent\n  text: withdrawingyourconsentatanytime,withoutaffectingthelawfulnessoftheprocessingbasedonsuchconsentbeforeitswithdrawal\nsale_or_sharing:\n  stance: prohibited\n  text: HacWarewillneversellyourPersonalData.\n"
source_yaml_url: https://artifacts.apis.io/hacware/privacy/hacware-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- dpa
- rights
- sale_or_sharing
summary_line: 14 quoted statements, read from Hacware's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Cybersecurity
- Security Awareness
- Phishing
- Training
- Compliance
- Email Security
- Artificial Intelligence
---
