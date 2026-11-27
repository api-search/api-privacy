---
api_specs:
- filename: cenogram-pl-demographics-api-openapi.yml
  format: yaml
  label: Cenogram Demographics API
  slug: cenogram-pl-demographics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-demographics-api-openapi.yml
- filename: cenogram-pl-infrastructure-api-openapi.yml
  format: yaml
  label: Cenogram Infrastructure API
  slug: cenogram-pl-infrastructure-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-infrastructure-api-openapi.yml
- filename: cenogram-pl-locations-api-openapi.yml
  format: yaml
  label: Cenogram Locations API
  slug: cenogram-pl-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-locations-api-openapi.yml
- filename: cenogram-pl-parcels-api-openapi.yml
  format: yaml
  label: Cenogram Parcels API
  slug: cenogram-pl-parcels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-parcels-api-openapi.yml
- filename: cenogram-pl-spatial-api-openapi.yml
  format: yaml
  label: Cenogram Spatial API
  slug: cenogram-pl-spatial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-spatial-api-openapi.yml
- filename: cenogram-pl-statistics-api-openapi.yml
  format: yaml
  label: Cenogram Statistics API
  slug: cenogram-pl-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-statistics-api-openapi.yml
- filename: cenogram-pl-transactions-api-openapi.yml
  format: yaml
  label: Cenogram Transactions API
  slug: cenogram-pl-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cenogram-pl/openapi/cenogram-pl-transactions-api-openapi.yml
claim_count: 26
description: ''
doc:
  data_categories:
  - category: contact
    text: Adresy email zbierane przez formularze kontaktowe i zapisy na powiadomienia
  - category: identifying
    text: 'Dane konta: adres email (login), zaszyfrowane hasło, status weryfikacji email'
  - category: behavioral
    text: 'Logi użycia API: identyfikator klucza API (powiązany z kontem), wywoływany endpoint wraz z parametrami zapytania, adres IP, znacznik czasu'
  - category: device
    text: dane przeglądarki (user agent)
  - category: financial
    text: 'Saldo i historia tokenów: stan kredytów oraz zapis ich wykorzystania'
  - category: other
    text: 'Zdarzenia przycisku „Zapytaj AI o te wyniki”: gdy korzystasz z tego przycisku w wyszukiwarce, zapisujemy, co zrobiono'
  deletion:
    route: email request
    text: Usunięcie konta i powiązanych danych można zlecić, kontaktując się pod adresem [email protected]
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: contract performance
    text: Art. 6 ust. 1 lit. b RODO - wykonanie umowy o świadczenie usługi (prowadzenie konta, dostęp do API i serwera MCP, rozliczenie wykorzystania tokenów)
  - purpose: legitimate interest, security and fraud prevention
    text: bezpieczeństwo usługi, diagnostyka techniczna oraz zapobieganie nadużyciom (logi i zdarzenia uwierzytelniania)
  - purpose: transparency of the property market
    text: prawnie uzasadniony interes administratora, polegający na analizie i udostępnianiu danych z publicznego rejestru w celu wspierania transparentności rynku nieruchomości
  - purpose: report preparation
    text: 'Cel: przygotowanie raportu i wysłanie go na podany adres e-mail'
  residency:
  - region: EU
    text: dostawcy hostingu (serwery w UE)
  retention:
  - period: bezterminowo
    scope: public registry transaction data
    text: Dane przechowywane bezterminowo - stanowią informacje o charakterze historycznym i statystycznym
  - period: do czasu usunięcia konta przez użytkownika
    scope: account data
    text: Dane konta, w tym dane o źródle rejestracji - do czasu usunięcia konta przez użytkownika
  - period: 90 dni
    scope: assistant button events
    text: Zdarzenia przycisku „Zapytaj AI o te wyniki” - 90 dni
  - period: do 60 dni lub do odłączenia konektora
    scope: connector OAuth refresh token
    text: token odświeżania do 60 dni lub do odłączenia konektora
  - period: 12 miesięcy
    scope: competition report form
    text: 'Okres przechowywania: 12 miesięcy od wysłania raportu albo do czasu wycofania zgody, jeśli nastąpi wcześniej'
  rights:
  - right: access
    text: Prawo dostępu do danych (art. 15 RODO)
  - right: rectification
    text: Prawo do sprostowania (art. 16 RODO)
  - right: erasure
    text: Prawo do usunięcia (art. 17 RODO)
  - right: restriction
    text: Prawo do ograniczenia przetwarzania (art. 18 RODO)
  - right: portability
    text: Prawo do przenoszenia danych (art. 20 RODO)
  - right: objection
    text: Prawo do sprzeciwu (art. 21 RODO)
  role:
    text: 'Administratorem danych osobowych jest: Arena Paweł Nguyen'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Dane konta, API i MCP przetwarzają na nasze zlecenie dostawcy hostingu (serwery w UE), sieci i ochrony ruchu, płatności oraz wysyłki e-maili.
    url: null
  transfers:
  - mechanism: other
    text: przekazuje je do Meta Platforms, Inc. w Stanach Zjednoczonych
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cenogram
provenance_date: '2026-11-09'
provider_name: Cenogram
provider_slug: cenogram-pl
slug: cenogram-pl-privacy-policy
source_date: '2026-11-09'
source_filename: cenogram-pl-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://cenogram.pl/polityka-prywatnosci
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cenogram\naid: cenogram-pl\nurl: https://cenogram.pl/polityka-prywatnosci\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Administratorem danych osobowych jest: Arena Paweł Nguyen'\ndata_categories:\n- category: contact\n  text: Adresy email zbierane przez formularze kontaktowe i zapisy na powiadomienia\n- category: identifying\n  text: 'Dane konta: adres email (login), zaszyfrowane hasło, status weryfikacji email'\n- category: behavioral\n  text: 'Logi użycia API: identyfikator klucza API (powiązany z kontem), wywoływany endpoint wraz z parametrami\n    zapytania, adres IP, znacznik czasu'\n\
  - category: device\n  text: dane przeglądarki (user agent)\n- category: financial\n  text: 'Saldo i historia tokenów: stan kredytów oraz zapis ich wykorzystania'\n- category: other\n  text: 'Zdarzenia przycisku „Zapytaj AI o te wyniki”: gdy korzystasz z tego przycisku w wyszukiwarce, zapisujemy,\n    co zrobiono'\npurposes:\n- purpose: contract performance\n  text: Art. 6 ust. 1 lit. b RODO - wykonanie umowy o świadczenie usługi (prowadzenie konta, dostęp do API i serwera\n    MCP, rozliczenie wykorzystania tokenów)\n- purpose: legitimate interest, security and fraud prevention\n  text: bezpieczeństwo usługi, diagnostyka techniczna oraz zapobieganie nadużyciom (logi i zdarzenia uwierzytelniania)\n- purpose: transparency of the property market\n  text: prawnie uzasadniony interes administratora, polegający na analizie i udostępnianiu danych z publicznego\n    rejestru w celu wspierania transparentności rynku nieruchomości\n- purpose: report preparation\n  text: 'Cel: przygotowanie raportu\
  \ i wysłanie go na podany adres e-mail'\nretention:\n- scope: public registry transaction data\n  period: bezterminowo\n  text: Dane przechowywane bezterminowo - stanowią informacje o charakterze historycznym i statystycznym\n- scope: account data\n  period: do czasu usunięcia konta przez użytkownika\n  text: Dane konta, w tym dane o źródle rejestracji - do czasu usunięcia konta przez użytkownika\n- scope: assistant button events\n  period: 90 dni\n  text: Zdarzenia przycisku „Zapytaj AI o te wyniki” - 90 dni\n- scope: connector OAuth refresh token\n  period: do 60 dni lub do odłączenia konektora\n  text: token odświeżania do 60 dni lub do odłączenia konektora\n- scope: competition report form\n  period: 12 miesięcy\n  text: 'Okres przechowywania: 12 miesięcy od wysłania raportu albo do czasu wycofania zgody, jeśli nastąpi wcześniej'\nresidency:\n- region: EU\n  text: dostawcy hostingu (serwery w UE)\ntransfers:\n- mechanism: other\n  text: przekazuje je do Meta Platforms, Inc. w Stanach\
  \ Zjednoczonych\nsubprocessors:\n  url: null\n  text: Dane konta, API i MCP przetwarzają na nasze zlecenie dostawcy hostingu (serwery w UE), sieci i ochrony ruchu,\n    płatności oraz wysyłki e-maili.\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request\n  text: Usunięcie konta i powiązanych danych można zlecić, kontaktując się pod adresem [email protected]\nrights:\n- right: access\n  text: Prawo dostępu do danych (art. 15 RODO)\n- right: rectification\n  text: Prawo do sprostowania (art. 16 RODO)\n- right: erasure\n  text: Prawo do usunięcia (art. 17 RODO)\n- right: restriction\n  text: Prawo do ograniczenia przetwarzania (art. 18 RODO)\n- right: portability\n  text: Prawo do przenoszenia danych (art. 20 RODO)\n- right: objection\n  text: Prawo do sprzeciwu (art. 21 RODO)\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cenogram-pl/privacy/cenogram-pl-privacy-policy.yml
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
summary_line: 26 quoted statements, read from Cenogram's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Data
- Analytics
- Poland
---
