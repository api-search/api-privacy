---
api_specs:
- filename: przypominamy-com-czarna-lista-api-openapi.yml
  format: yaml
  label: przypominamy-com Czarna lista API
  slug: przypominamy-com-czarna-lista-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-czarna-lista-api-openapi.yml
- filename: przypominamy-com-kontakty-i-grupy-api-openapi.yml
  format: yaml
  label: przypominamy-com Kontakty i grupy API
  slug: przypominamy-com-kontakty-i-grupy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-kontakty-i-grupy-api-openapi.yml
- filename: przypominamy-com-konto-api-openapi.yml
  format: yaml
  label: przypominamy-com Konto API
  slug: przypominamy-com-konto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-konto-api-openapi.yml
- filename: przypominamy-com-linki-api-openapi.yml
  format: yaml
  label: przypominamy-com Linki API
  slug: przypominamy-com-linki-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-linki-api-openapi.yml
- filename: przypominamy-com-numery-api-openapi.yml
  format: yaml
  label: przypominamy-com Numery API
  slug: przypominamy-com-numery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-numery-api-openapi.yml
- filename: przypominamy-com-odpowiedzi-2-way-api-openapi.yml
  format: yaml
  label: przypominamy-com Odpowiedzi (2-way) API
  slug: przypominamy-com-odpowiedzi-2-way-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-odpowiedzi-2-way-api-openapi.yml
- filename: przypominamy-com-status-api-openapi.yml
  format: yaml
  label: przypominamy-com Status API
  slug: przypominamy-com-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-status-api-openapi.yml
- filename: przypominamy-com-szablony-api-openapi.yml
  format: yaml
  label: przypominamy-com Szablony API
  slug: przypominamy-com-szablony-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-szablony-api-openapi.yml
- filename: przypominamy-com-wiadomo-ci-api-openapi.yml
  format: yaml
  label: przypominamy-com Wiadomości API
  slug: przypominamy-com-wiadomo-ci-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/przypominamy-com/openapi/przypominamy-com-wiadomo-ci-api-openapi.yml
claim_count: 27
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Dane rejestracyjne: imię i nazwisko, nazwa firmy, NIP, adres e-mail, numer telefonu'
  - category: financial
    text: 'Dane transakcyjne: historia doładowań, faktury, wolumen wysyłek'
  - category: device
    text: 'Dane techniczne: adres IP, typ przeglądarki, informacje o urządzeniu (zbierane automatycznie)'
  - category: communication
    text: 'Dane z czatu: treść rozmów z asystentem AI (przechowywane tymczasowo w sesji przeglądarki)'
  - category: professional
    text: 'Dane z formularza zamówienia: branża, szacowany wolumen, opis przypadku użycia'
  deletion:
    route: email request to the privacy contact
    text: Aby skorzystać z powyższych praw, skontaktuj się z nami
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: service delivery
    text: 'Realizacja usług masowej wysyłki SMS, MMS i IVR (podstawa: umowa)'
  - purpose: invoicing
    text: 'Wystawianie faktur i rozliczenia (podstawa: obowiązek prawny)'
  - purpose: AI offer
    text: 'Przygotowanie spersonalizowanej oferty przez asystenta AI (podstawa: prawnie uzasadniony interes)'
  - purpose: support
    text: 'Obsługa zapytań i wsparcie techniczne (podstawa: prawnie uzasadniony interes)'
  - purpose: security
    text: 'Zapewnienie bezpieczeństwa Platformy (podstawa: prawnie uzasadniony interes)'
  retention:
  - period: przez czas trwania umowy + 5 lat
    scope: customer account data
    text: 'Dane konta klienta: przez czas trwania umowy + 5 lat (obowiązek podatkowy)'
  - period: 5 lat od końca roku podatkowego
    scope: transaction data and invoices
    text: 'Dane transakcyjne i faktury: 5 lat od końca roku podatkowego'
  - period: 90 dni
    scope: order form data
    text: 'Dane z formularza zamówienia: 90 dni od złożenia zapytania'
  - period: wyłącznie w sesji przeglądarki
    scope: AI chat data
    text: 'Dane z czatu AI: wyłącznie w sesji przeglądarki, nie są przechowywane na serwerze'
  - period: maksymalnie 30 dni
    scope: technical logs
    text: 'Logi techniczne: maksymalnie 30 dni'
  - period: 14 miesięcy
    scope: GA4 data
    text: Dane w GA4 przechowujemy 14 miesięcy
  rights:
  - right: access
    text: Dostępu do swoich danych
  - right: rectification
    text: Sprostowania nieprawidłowych danych
  - right: restriction
    text: Ograniczenia przetwarzania
  - right: portability
    text: Przenoszenia danych
  - right: objection
    text: Sprzeciwu wobec przetwarzania
  - right: complaint to supervisory authority
    text: Wniesienia skargi do Prezesa Urzędu Ochrony Danych Osobowych
  role:
    text: Administratorem danych osobowych jest Doradztwo Paweł Mamcarz
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Nie sprzedajemy danych osobowych podmiotom trzecim.
  subprocessors:
    text: 'Dostawcom infrastruktury: Cloudflare (hosting), Anthropic (AI asystent)'
    url: null
  transfers:
  - mechanism: SCC
    text: Przekazanie poza EOG, jeśli nastąpi, opiera się na standardowych klauzulach umownych Komisji Europejskiej.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: przypominamy-com
provenance_date: '2026-11-10'
provider_name: przypominamy-com
provider_slug: przypominamy-com
slug: przypominamy-com-privacy-policy
source_date: '2026-11-10'
source_filename: przypominamy-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://przypominamy.com/polityka-prywatnosci
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: przypominamy-com\naid: przypominamy-com\nurl: https://przypominamy.com/polityka-prywatnosci\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Administratorem danych osobowych jest Doradztwo Paweł Mamcarz\ndata_categories:\n- category: identifying\n  text: 'Dane rejestracyjne: imię i nazwisko, nazwa firmy, NIP, adres e-mail, numer telefonu'\n- category: financial\n  text: 'Dane transakcyjne: historia doładowań, faktury, wolumen wysyłek'\n- category: device\n  text: 'Dane techniczne: adres IP, typ przeglądarki, informacje o urządzeniu (zbierane automatycznie)'\n- category: communication\n  text:\
  \ 'Dane z czatu: treść rozmów z asystentem AI (przechowywane tymczasowo w sesji przeglądarki)'\n- category: professional\n  text: 'Dane z formularza zamówienia: branża, szacowany wolumen, opis przypadku użycia'\npurposes:\n- purpose: service delivery\n  text: 'Realizacja usług masowej wysyłki SMS, MMS i IVR (podstawa: umowa)'\n- purpose: invoicing\n  text: 'Wystawianie faktur i rozliczenia (podstawa: obowiązek prawny)'\n- purpose: AI offer\n  text: 'Przygotowanie spersonalizowanej oferty przez asystenta AI (podstawa: prawnie uzasadniony interes)'\n- purpose: support\n  text: 'Obsługa zapytań i wsparcie techniczne (podstawa: prawnie uzasadniony interes)'\n- purpose: security\n  text: 'Zapewnienie bezpieczeństwa Platformy (podstawa: prawnie uzasadniony interes)'\nretention:\n- scope: customer account data\n  period: przez czas trwania umowy + 5 lat\n  text: 'Dane konta klienta: przez czas trwania umowy + 5 lat (obowiązek podatkowy)'\n- scope: transaction data and invoices\n  period: 5 lat\
  \ od końca roku podatkowego\n  text: 'Dane transakcyjne i faktury: 5 lat od końca roku podatkowego'\n- scope: order form data\n  period: 90 dni\n  text: 'Dane z formularza zamówienia: 90 dni od złożenia zapytania'\n- scope: AI chat data\n  period: wyłącznie w sesji przeglądarki\n  text: 'Dane z czatu AI: wyłącznie w sesji przeglądarki, nie są przechowywane na serwerze'\n- scope: technical logs\n  period: maksymalnie 30 dni\n  text: 'Logi techniczne: maksymalnie 30 dni'\n- scope: GA4 data\n  period: 14 miesięcy\n  text: Dane w GA4 przechowujemy 14 miesięcy\nresidency: []\ntransfers:\n- mechanism: SCC\n  text: Przekazanie poza EOG, jeśli nastąpi, opiera się na standardowych klauzulach umownych Komisji Europejskiej.\nsubprocessors:\n  url: null\n  text: 'Dostawcom infrastruktury: Cloudflare (hosting), Anthropic (AI asystent)'\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: email request to the privacy contact\n  text: Aby skorzystać z powyższych praw, skontaktuj się\
  \ z nami\nrights:\n- right: access\n  text: Dostępu do swoich danych\n- right: rectification\n  text: Sprostowania nieprawidłowych danych\n- right: restriction\n  text: Ograniczenia przetwarzania\n- right: portability\n  text: Przenoszenia danych\n- right: objection\n  text: Sprzeciwu wobec przetwarzania\n- right: complaint to supervisory authority\n  text: Wniesienia skargi do Prezesa Urzędu Ochrony Danych Osobowych\nsale_or_sharing:\n  stance: prohibited\n  text: Nie sprzedajemy danych osobowych podmiotom trzecim.\n"
source_yaml_url: https://artifacts.apis.io/przypominamy-com/privacy/przypominamy-com-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 27 quoted statements, read from przypominamy-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- SMS
- Communications
- Poland
- Messaging
---
