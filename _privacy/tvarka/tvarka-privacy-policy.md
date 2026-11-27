---
api_specs:
- filename: auth.json
  format: json
  label: Tvarka ATK API Tvarka ATK API
  slug: tvarka-atk-api-tvarka-atk-api-api
  spec_type: Postman
  url: https://atk.tvarka.pro/postman/auth.json
- filename: auth.json
  format: json
  label: Tvarka ATK API Tvarka ATK QES Signing API (paid Tier Addendum) API
  slug: tvarka-atk-api-tvarka-atk-qes-signing-api-paid-tier-addendum-api
  spec_type: Postman
  url: https://atk.tvarka.pro/postman/auth.json
- filename: tvarka-sign-api-openapi.yml
  format: yaml
  label: Tvarka Sign API
  slug: tvarka-sign-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-sign-api-openapi.yml
- filename: tvarka-auth-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Auth API
  slug: tvarka-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-auth-api-openapi.yml
- filename: tvarka-batches-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Batches API
  slug: tvarka-batches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-batches-api-openapi.yml
- filename: tvarka-erasure-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Erasure API
  slug: tvarka-erasure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-erasure-api-openapi.yml
- filename: tvarka-files-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Files API
  slug: tvarka-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-files-api-openapi.yml
- filename: tvarka-ltv-api-openapi.yml
  format: yaml
  label: Tvarka ATK API LTV API
  slug: tvarka-ltv-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-ltv-api-openapi.yml
- filename: tvarka-pairing-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Pairing API
  slug: tvarka-pairing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-pairing-api-openapi.yml
- filename: tvarka-signings-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Signings API
  slug: tvarka-signings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-signings-api-openapi.yml
- filename: tvarka-tvarka-atk-api-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Tvarka ATK API
  slug: tvarka-tvarka-atk-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-tvarka-atk-api-api-openapi.yml
- filename: tvarka-tvarka-sign-api-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Tvarka Sign API
  slug: tvarka-tvarka-sign-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-tvarka-sign-api-api-openapi.yml
- filename: tvarka-validation-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Validation API
  slug: tvarka-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-validation-api-openapi.yml
- filename: tvarka-well-known-api-openapi.yml
  format: yaml
  label: Tvarka ATK API Well Known API
  slug: tvarka-well-known-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tvarka/openapi/tvarka-well-known-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Galime gauti ir tvarkyti šiuos duomenis, kuriuos pateikia tapatybės patvirtinimo sprendimų teikėjai: asmens kodą, vardą, pavardę, šalies kodą, sertifikato duomenis audito pėdsakui.'
  - category: communication
    text: el. paštas, užklausos turinys
  - category: financial
    text: Tvarka gali gauti mokėjimo būsenos, balanso, sąskaitos ir apmokėjimo datos informaciją, reikalingą prieigai suteikti ir apskaitai.
  - category: device
    text: 'įrenginio registracijos duomenys: atsitiktinai sugeneruotas įrenginio identifikatorius ir prieigos raktas, techniniai žurnalai ir IP adresas'
  - category: professional
    text: juridinio asmens kodą (JA kodą), pavadinimą, tipą (pvz., UAB, MB)
  deletion:
    route: in-browser account deletion request
    text: Galite prašyti ištrinti paskyrą ir duomenis naršyklėje
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: account creation and authentication
    text: Paskyros sukūrimas ir autentifikavimas
  - purpose: usage analytics
    text: Paslaugos naudojimui vertinti PostHog ES regione skaičiuojame užbaigtas registracijas el. paštu, pirmą sėkmingą registruoto naudotojo pasirašymą ir pirmą įskaitytą balanso papildymą.
  residency:
  - region: European Union
    text: Paslaugos naudojimui vertinti PostHog ES regione skaičiuojame
  retention:
  - period: Iki paskyros ištrynimo
    scope: accounts
    text: Iki paskyros ištrynimo; audito įrašai – pagal teisėtą interesą ir saugumo poreikį.
  - period: 10 metų
    scope: accounting documents
    text: apskaitos dokumentai – 10 metų
  - period: Paprastai iki 12 mėn.
    scope: security logs
    text: Paprastai iki 12 mėn., jei nereikia ilgiau dėl incidento ar ginčo.
  - period: Paprastai iki 2 metų nuo paskutinio kontakto
    scope: communication and support
    text: Paprastai iki 2 metų nuo paskutinio kontakto, jei nereikia ilgiau dėl ginčo.
  rights:
  - right: access
    text: teisę susipažinti su duomenimis
  - right: portability
    text: teisę į duomenų perkeliamumą (kai taikoma)
  - right: complaint to supervisory authority
    text: teisę pateikti skundą priežiūros institucijai
  role:
    text: Asmens duomenų valdytojai pagal atitinkamas Tvarka.pro funkcijas yra Advokato M. Kiškio kontora INVENT (teisinių paslaugų teikėjas) ir Socialiniai algoritmai, UAB (platformos operatorius).
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: 'Pagrindinės gavėjų kategorijos: IT ir prieglobos paslaugų teikėjai (pvz., debesijos infrastruktūra)'
    url: null
  transfers:
  - mechanism: other
    text: Tvarka gali naudoti paslaugų teikėjus, kurie asmens duomenis tvarko už Europos ekonominės erdvės ribų.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Tvarka ATK API
provenance_date: '2026-11-10'
provider_name: Tvarka ATK API
provider_slug: tvarka
slug: tvarka-privacy-policy
source_date: '2026-11-10'
source_filename: tvarka-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://tvarka.pro/privatumas/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Tvarka ATK API\naid: tvarka\nurl: https://tvarka.pro/privatumas/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Asmens duomenų valdytojai pagal atitinkamas Tvarka.pro funkcijas yra Advokato M. Kiškio kontora INVENT (teisinių\n    paslaugų teikėjas) ir Socialiniai algoritmai, UAB (platformos operatorius).\ndata_categories:\n- category: identifying\n  text: 'Galime gauti ir tvarkyti šiuos duomenis, kuriuos pateikia tapatybės patvirtinimo sprendimų teikėjai: asmens\n    kodą, vardą, pavardę, šalies kodą, sertifikato duomenis audito pėdsakui.'\n- category: communication\n  text: el. paštas, užklausos\
  \ turinys\n- category: financial\n  text: Tvarka gali gauti mokėjimo būsenos, balanso, sąskaitos ir apmokėjimo datos informaciją, reikalingą prieigai\n    suteikti ir apskaitai.\n- category: device\n  text: 'įrenginio registracijos duomenys: atsitiktinai sugeneruotas įrenginio identifikatorius ir prieigos raktas,\n    techniniai žurnalai ir IP adresas'\n- category: professional\n  text: juridinio asmens kodą (JA kodą), pavadinimą, tipą (pvz., UAB, MB)\npurposes:\n- purpose: account creation and authentication\n  text: Paskyros sukūrimas ir autentifikavimas\n- purpose: usage analytics\n  text: Paslaugos naudojimui vertinti PostHog ES regione skaičiuojame užbaigtas registracijas el. paštu, pirmą sėkmingą\n    registruoto naudotojo pasirašymą ir pirmą įskaitytą balanso papildymą.\nretention:\n- scope: accounts\n  period: Iki paskyros ištrynimo\n  text: Iki paskyros ištrynimo; audito įrašai – pagal teisėtą interesą ir saugumo poreikį.\n- scope: accounting documents\n  period: 10 metų\n  text:\
  \ apskaitos dokumentai – 10 metų\n- scope: security logs\n  period: Paprastai iki 12 mėn.\n  text: Paprastai iki 12 mėn., jei nereikia ilgiau dėl incidento ar ginčo.\n- scope: communication and support\n  period: Paprastai iki 2 metų nuo paskutinio kontakto\n  text: Paprastai iki 2 metų nuo paskutinio kontakto, jei nereikia ilgiau dėl ginčo.\nresidency:\n- region: European Union\n  text: Paslaugos naudojimui vertinti PostHog ES regione skaičiuojame\ntransfers:\n- mechanism: other\n  text: Tvarka gali naudoti paslaugų teikėjus, kurie asmens duomenis tvarko už Europos ekonominės erdvės ribų.\nsubprocessors:\n  url: null\n  text: 'Pagrindinės gavėjų kategorijos: IT ir prieglobos paslaugų teikėjai (pvz., debesijos infrastruktūra)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: in-browser account deletion request\n  text: Galite prašyti ištrinti paskyrą ir duomenis naršyklėje\nrights:\n- right: access\n  text: teisę susipažinti su duomenimis\n- right: portability\n\
  \  text: teisę į duomenų perkeliamumą (kai taikoma)\n- right: complaint to supervisory authority\n  text: teisę pateikti skundą priežiūros institucijai\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tvarka/privacy/tvarka-privacy-policy.yml
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
summary_line: 19 quoted statements, read from Tvarka ATK API's own page on 2026-11-10.
synthetic: false
tags:
- Authentication
- Digital Signature
- eIDAS
- QES
- Lithuania
- OpenAPI
- eID
- Smart-ID
- Mobile-ID
- NFC
- Timestamping
- LTV
- Webhook
- Identity
- Trust Services
- GDPR
---
