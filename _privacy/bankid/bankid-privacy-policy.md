---
api_specs:
- filename: bankid-auth-api-openapi.yml
  format: yaml
  label: BankID Auth API
  slug: bankid-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-auth-api-openapi.yml
- filename: bankid-cancel-api-openapi.yml
  format: yaml
  label: BankID Cancel API
  slug: bankid-cancel-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-cancel-api-openapi.yml
- filename: bankid-collect-api-openapi.yml
  format: yaml
  label: BankID Collect API
  slug: bankid-collect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-collect-api-openapi.yml
- filename: bankid-other-api-openapi.yml
  format: yaml
  label: BankID Other API
  slug: bankid-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-other-api-openapi.yml
- filename: bankid-payment-api-openapi.yml
  format: yaml
  label: BankID Payment API
  slug: bankid-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-payment-api-openapi.yml
- filename: bankid-phone-api-openapi.yml
  format: yaml
  label: BankID Phone API
  slug: bankid-phone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-phone-api-openapi.yml
- filename: bankid-sign-api-openapi.yml
  format: yaml
  label: BankID Sign API
  slug: bankid-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bankid/openapi/bankid-sign-api-openapi.yml
claim_count: 25
description: ''
doc:
  data_categories:
  - category: identifying
    text: Namn, ålder och personnummer.
  - category: biometric
    text: Ursprungsbild (bild från ID-handlingen), en jämförelsebild (nytagen bild av dig) och resultatet av matchningen.
  - category: location
    text: Om du väljer att dela din platsinformation med BankID-appen behandlar vi även uppgifter om geografisk platsinformation
  - category: device
    text: Teknisk information som genereras vid utgivning eller användning, exempelvis tidpunkt för användning, IP-adress, loggar, modell av mobiltelefon eller dator, operativsystem
  - category: behavioral
    text: Utförda identifieringar och underskrifter mot tillhandahållare av e-tjänster
  - category: health
    text: uppgifter om hälsa eller sexualitet
  deletion:
    route: Request to the bank or the data protection officer
    text: 'Du har i vissa fall rätt att begära att dina personuppgifter utan dröjsmål raderas om:'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide BankID
    text: Dina personuppgifter behandlas för att Banken ska kunna tillhandahålla dig BankID
  - purpose: Prevent unauthorised use
    text: Dina personuppgifter behandlas för att utföra en förstärkningsåtgärd
  - purpose: Transaction monitoring
    text: för att kunna analysera uppgifter om ditt användarbeteende för att förhindra att BankID missbrukas
  - purpose: Support
    text: Dina personuppgifter behandlas när du söker support för ditt BankID.
  - purpose: Improve and maintain services
    text: för att ta fram aggregerad/anonym information för att förbättra BankID och relaterade tjänster
  residency:
  - region: EU/EES
    text: Banken och vi lagrar och behandlar dina uppgifter enbart inom EU/EES
  retention:
  - period: 11 år
    scope: Basic data
    text: Grundläggande uppgifter sparas i 11 år
  - period: 6 år
    scope: Usage data
    text: Uppgifter om användning sparas i 6 år
  - period: 72 timmar
    scope: Biometric comparison image
    text: Jämförelsebilden lagras endast under 72 timmar
  - period: 1 år efter att ärendet avslutats
    scope: Support case information
    text: Information som du själv lämnar i ditt supportärende sparas i 1 år efter att ärendet avslutats
  - period: 6 månader
    scope: Improvement data
    text: Dina personuppgifter sparas i 6 månader.
  rights:
  - right: Access
    text: Du har rätt att få besked och information om vilka av dina personuppgifter som behandlas
  - right: Rectification
    text: Du har alltid möjlighet att utan dröjsmål rätta dina personuppgifter om de är felaktiga
  - right: Restriction
    text: Du har rätt att begära att behandlingen av dina personuppgifter begränsas om
  - right: Objection
    text: Du har rätt att när som helst invända mot Bankens eller vår behandling av dina personuppgifter
  - right: Complaint
    text: Om du anser att Banken eller vi inte behandlar dina uppgifter i enlighet med gällande personuppgiftslagstiftning har du möjlighet att klaga till Integritetsskyddsmyndigheten
  role:
    text: Finansiell ID-Teknik BID AB (”vi” eller ”vår”) är personuppgiftsbiträde till Banken avseende behandlingen av dina personuppgifter inom ramen för BankID.
    value: both
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Vi delar alla dina uppgifter med vår driftsleverantör.
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: BankID
provenance_date: '2026-11-09'
provider_name: BankID
provider_slug: bankid
slug: bankid-privacy-policy
source_date: '2026-11-09'
source_filename: bankid-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.bankid.com/juridik/integritetspolicy-bankid
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: BankID\naid: bankid\nurl: https://www.bankid.com/juridik/integritetspolicy-bankid\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: both\n  text: Finansiell ID-Teknik BID AB (”vi” eller ”vår”) är personuppgiftsbiträde till Banken avseende behandlingen\n    av dina personuppgifter inom ramen för BankID.\ndata_categories:\n- category: identifying\n  text: Namn, ålder och personnummer.\n- category: biometric\n  text: Ursprungsbild (bild från ID-handlingen), en jämförelsebild (nytagen bild av dig) och resultatet av matchningen.\n- category: location\n  text: Om du väljer att dela din platsinformation med BankID-appen\
  \ behandlar vi även uppgifter om geografisk platsinformation\n- category: device\n  text: Teknisk information som genereras vid utgivning eller användning, exempelvis tidpunkt för användning, IP-adress,\n    loggar, modell av mobiltelefon eller dator, operativsystem\n- category: behavioral\n  text: Utförda identifieringar och underskrifter mot tillhandahållare av e-tjänster\n- category: health\n  text: uppgifter om hälsa eller sexualitet\npurposes:\n- purpose: Provide BankID\n  text: Dina personuppgifter behandlas för att Banken ska kunna tillhandahålla dig BankID\n- purpose: Prevent unauthorised use\n  text: Dina personuppgifter behandlas för att utföra en förstärkningsåtgärd\n- purpose: Transaction monitoring\n  text: för att kunna analysera uppgifter om ditt användarbeteende för att förhindra att BankID missbrukas\n- purpose: Support\n  text: Dina personuppgifter behandlas när du söker support för ditt BankID.\n- purpose: Improve and maintain services\n  text: för att ta fram aggregerad/anonym\
  \ information för att förbättra BankID och relaterade tjänster\nretention:\n- scope: Basic data\n  period: 11 år\n  text: Grundläggande uppgifter sparas i 11 år\n- scope: Usage data\n  period: 6 år\n  text: Uppgifter om användning sparas i 6 år\n- scope: Biometric comparison image\n  period: 72 timmar\n  text: Jämförelsebilden lagras endast under 72 timmar\n- scope: Support case information\n  period: 1 år efter att ärendet avslutats\n  text: Information som du själv lämnar i ditt supportärende sparas i 1 år efter att ärendet avslutats\n- scope: Improvement data\n  period: 6 månader\n  text: Dina personuppgifter sparas i 6 månader.\nresidency:\n- region: EU/EES\n  text: Banken och vi lagrar och behandlar dina uppgifter enbart inom EU/EES\ntransfers: []\nsubprocessors:\n  url: null\n  text: Vi delar alla dina uppgifter med vår driftsleverantör.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Request to the bank or the data protection officer\n  text: 'Du har i vissa\
  \ fall rätt att begära att dina personuppgifter utan dröjsmål raderas om:'\nrights:\n- right: Access\n  text: Du har rätt att få besked och information om vilka av dina personuppgifter som behandlas\n- right: Rectification\n  text: Du har alltid möjlighet att utan dröjsmål rätta dina personuppgifter om de är felaktiga\n- right: Restriction\n  text: Du har rätt att begära att behandlingen av dina personuppgifter begränsas om\n- right: Objection\n  text: Du har rätt att när som helst invända mot Bankens eller vår behandling av dina personuppgifter\n- right: Complaint\n  text: Om du anser att Banken eller vi inte behandlar dina uppgifter i enlighet med gällande personuppgiftslagstiftning\n    har du möjlighet att klaga till Integritetsskyddsmyndigheten\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bankid/privacy/bankid-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- subprocessors
- deletion
- rights
summary_line: 25 quoted statements, read from BankID's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Authentication
- eIDAS
- Digital Identity
- Sweden
---
