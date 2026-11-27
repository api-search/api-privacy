---
claim_count: 32
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nazwa użytkownika (opcjonalnie)
  - category: contact
    text: Adres e-mail
  - category: financial
    text: Dane płatności (przetwarzane przez zewnętrznego operatora płatności)
  - category: behavioral
    text: Dane dotyczące aktywności w systemie (logi, historia użycia API)
  - category: communication
    text: Głos - strumień dźwięku z mikrofonu przetwarzany w czasie rzeczywistym podczas rozmowy (nagrania audio nie są zapisywane)
  - category: financial
    text: Dane księgowe odczytywane z Twojego systemu księgowego (wFirma / Fakturownia) na Twoje polecenie w trakcie rozmowy
  - category: other
    text: Dane dostępowe do Twojego systemu księgowego - zapisywane wyłącznie za Twoją zgodą, w postaci zaszyfrowanej (AES-256-GCM)
  - category: behavioral
    text: Metadane sesji głosowych (data, czas trwania, wybrany system księgowy)
  deletion:
    route: In-app panel for accounting access credentials; account deletion by user
    text: możesz je usunąć jednym kliknięciem w panelu
  dpa:
    available: true
    text: transfer danych odbywa się na podstawie standardowych klauzul umownych (SCC) oraz umowy powierzenia przetwarzania danych (DPA)
    url: null
  purposes:
  - purpose: Provision of service
    text: Świadczenia usług systemu wFirma MCP
  - purpose: Account management
    text: Zarządzania kontem użytkownika
  - purpose: Payments and subscriptions
    text: Realizacji płatności i subskrypcji
  - purpose: User communication
    text: Komunikacji z użytkownikiem
  - purpose: Legal obligations
    text: Wypełnienia obowiązków prawnych
  residency:
  - region: European Union
    text: Dostawca infrastruktury serwerowej (OVH, Unia Europejska) - hosting serwisu
  retention:
  - period: do momentu usunięcia konta przez użytkownika
    scope: Account data
    text: Dane konta - do momentu usunięcia konta przez użytkownika
  - period: do 12 miesięcy
    scope: Logs and API usage history
    text: Logi i historia użycia API - do 12 miesięcy
  - period: nie jest przechowywana
    scope: Voice conversation transcripts
    text: Treść rozmów głosowych (transkrypcje) - nie jest przechowywana
  - period: do 55 dni
    scope: Google security logs
    text: wyłącznie techniczne logi bezpieczeństwa podprocesora (Google) do 55 dni
  - period: przez okres trwania subskrypcji oraz okres przedawnienia ewentualnych roszczeń
    scope: Voice session metadata
    text: Metadane sesji głosowych (czas trwania, rozliczenie minut) - przez okres trwania subskrypcji oraz okres przedawnienia ewentualnych roszczeń
  - period: 5 lat
    scope: Billing data
    text: Dane rozliczeniowe (faktury, płatności) - 5 lat, zgodnie z przepisami podatkowymi
  rights:
  - right: Access
    text: Dostępu do swoich danych osobowych
  - right: Rectification
    text: Sprostowania (poprawiania) danych
  - right: Erasure
    text: Usunięcia danych ("prawo do bycia zapomnianym")
  - right: Restriction
    text: Ograniczenia przetwarzania
  - right: Portability
    text: Przenoszenia danych
  - right: Objection
    text: Wniesienia sprzeciwu wobec przetwarzania
  - right: Withdraw consent
    text: Cofnięcia zgody w dowolnym momencie
  role:
    text: 'Administratorem danych osobowych jest: NULLINE Krzysztof Gródek'
    value: controller
  sale_or_sharing:
    stance: unstated
    text: null
  subprocessors:
    text: Aktualną listę podmiotów przetwarzających udostępniamy na żądanie - napisz na contact@nulline.com
    url: null
  transfers:
  - mechanism: SCC
    text: transfer danych odbywa się na podstawie standardowych klauzul umownych (SCC) oraz umowy powierzenia przetwarzania danych (DPA)
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: fakto-app
provenance_date: '2026-11-09'
provider_name: fakto-app
provider_slug: fakto-app
slug: fakto-app-privacy-policy
source_date: '2026-11-09'
source_filename: fakto-app-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://fakto.app/mcp/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: fakto-app\naid: fakto-app\nurl: https://fakto.app/mcp/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: 'Administratorem danych osobowych jest: NULLINE Krzysztof Gródek'\ndata_categories:\n- category: identifying\n  text: Nazwa użytkownika (opcjonalnie)\n- category: contact\n  text: Adres e-mail\n- category: financial\n  text: Dane płatności (przetwarzane przez zewnętrznego operatora płatności)\n- category: behavioral\n  text: Dane dotyczące aktywności w systemie (logi, historia użycia API)\n- category: communication\n  text: Głos - strumień dźwięku z mikrofonu przetwarzany w czasie\
  \ rzeczywistym podczas rozmowy (nagrania audio nie\n    są zapisywane)\n- category: financial\n  text: Dane księgowe odczytywane z Twojego systemu księgowego (wFirma / Fakturownia) na Twoje polecenie w trakcie\n    rozmowy\n- category: other\n  text: Dane dostępowe do Twojego systemu księgowego - zapisywane wyłącznie za Twoją zgodą, w postaci zaszyfrowanej\n    (AES-256-GCM)\n- category: behavioral\n  text: Metadane sesji głosowych (data, czas trwania, wybrany system księgowy)\npurposes:\n- purpose: Provision of service\n  text: Świadczenia usług systemu wFirma MCP\n- purpose: Account management\n  text: Zarządzania kontem użytkownika\n- purpose: Payments and subscriptions\n  text: Realizacji płatności i subskrypcji\n- purpose: User communication\n  text: Komunikacji z użytkownikiem\n- purpose: Legal obligations\n  text: Wypełnienia obowiązków prawnych\nretention:\n- scope: Account data\n  period: do momentu usunięcia konta przez użytkownika\n  text: Dane konta - do momentu usunięcia konta\
  \ przez użytkownika\n- scope: Logs and API usage history\n  period: do 12 miesięcy\n  text: Logi i historia użycia API - do 12 miesięcy\n- scope: Voice conversation transcripts\n  period: nie jest przechowywana\n  text: Treść rozmów głosowych (transkrypcje) - nie jest przechowywana\n- scope: Google security logs\n  period: do 55 dni\n  text: wyłącznie techniczne logi bezpieczeństwa podprocesora (Google) do 55 dni\n- scope: Voice session metadata\n  period: przez okres trwania subskrypcji oraz okres przedawnienia ewentualnych roszczeń\n  text: Metadane sesji głosowych (czas trwania, rozliczenie minut) - przez okres trwania subskrypcji oraz okres\n    przedawnienia ewentualnych roszczeń\n- scope: Billing data\n  period: 5 lat\n  text: Dane rozliczeniowe (faktury, płatności) - 5 lat, zgodnie z przepisami podatkowymi\nresidency:\n- region: European Union\n  text: Dostawca infrastruktury serwerowej (OVH, Unia Europejska) - hosting serwisu\ntransfers:\n- mechanism: SCC\n  text: transfer danych\
  \ odbywa się na podstawie standardowych klauzul umownych (SCC) oraz umowy powierzenia przetwarzania\n    danych (DPA)\nsubprocessors:\n  url: null\n  text: Aktualną listę podmiotów przetwarzających udostępniamy na żądanie - napisz na contact@nulline.com\ndpa:\n  available: true\n  url: null\n  text: transfer danych odbywa się na podstawie standardowych klauzul umownych (SCC) oraz umowy powierzenia przetwarzania\n    danych (DPA)\ndeletion:\n  route: In-app panel for accounting access credentials; account deletion by user\n  text: możesz je usunąć jednym kliknięciem w panelu\nrights:\n- right: Access\n  text: Dostępu do swoich danych osobowych\n- right: Rectification\n  text: Sprostowania (poprawiania) danych\n- right: Erasure\n  text: Usunięcia danych (\"prawo do bycia zapomnianym\")\n- right: Restriction\n  text: Ograniczenia przetwarzania\n- right: Portability\n  text: Przenoszenia danych\n- right: Objection\n  text: Wniesienia sprzeciwu wobec przetwarzania\n- right: Withdraw consent\n\
  \  text: Cofnięcia zgody w dowolnym momencie\nsale_or_sharing:\n  stance: unstated\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fakto-app/privacy/fakto-app-privacy-policy.yml
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
summary_line: 32 quoted statements, read from fakto-app's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Accounting
- Integration
- Poland
- Automation
---
