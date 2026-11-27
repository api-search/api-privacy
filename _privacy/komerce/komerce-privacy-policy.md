---
api_specs:
- filename: komerce-cost-api-openapi.yml
  format: yaml
  label: Komerce Cost API
  slug: komerce-cost-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-cost-api-openapi.yml
- filename: komerce-destinations-api-openapi.yml
  format: yaml
  label: Komerce Destinations API
  slug: komerce-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-destinations-api-openapi.yml
- filename: komerce-orders-api-openapi.yml
  format: yaml
  label: Komerce Orders API
  slug: komerce-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-orders-api-openapi.yml
- filename: komerce-payments-api-openapi.yml
  format: yaml
  label: Komerce Payments API
  slug: komerce-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-payments-api-openapi.yml
- filename: komerce-pickup-api-openapi.yml
  format: yaml
  label: Komerce Pickup API
  slug: komerce-pickup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-pickup-api-openapi.yml
- filename: komerce-qris-api-openapi.yml
  format: yaml
  label: Komerce QRIS API
  slug: komerce-qris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-qris-api-openapi.yml
- filename: komerce-tracking-api-openapi.yml
  format: yaml
  label: Komerce Tracking API
  slug: komerce-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/komerce/openapi/komerce-tracking-api-openapi.yml
claim_count: 19
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nama Lengkap
  - category: contact
    text: Nomor HP
  - category: location
    text: Lokasi Bisnis
  - category: behavioral
    text: Data pencarian, riwayat penelusuran (termasuk tanggal dan waktu yang terekam)
  - category: device
    text: Informasi mengenai tipe perangkat yang Anda gunakan, seperti ID unik perangkat
  - category: biometric
    text: Data wajah yang disimpan hanya untuk keperluan internal kantor seperti, presensi masuk dan pulang
  - category: communication
    text: Foto, suara, kontak, daftar panggilan ataupun interaksi lainnya dalam Layanan
  - category: financial
    text: invoice pembayaran
  deletion:
    route: Users can access, update or delete data
    text: 'Pengguna dapat: Mengakses, memperbarui, atau menghapus data.'
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: communication, KYC and personalisation
    text: Untuk berkomunikasi, menjalankan prinsip Know Your Customer (KYC) dan memberikan personalisasi kepada Anda
  - purpose: diagnosis and troubleshooting
    text: Untuk melakukan diagnosa dan penyelesaian masalah terkait kesulitan dalam menggunakan Layanan.
  - purpose: payment processing
    text: Untuk memproses maupun memfasilitasi pembayaran Anda.
  - purpose: advertising and promotion
    text: Untuk menawarkan iklan/promosi maupun penawaran dari pihak lain yang bekerja sama.
  - purpose: broadcast service support
    text: Mendukung layanan broadcast.
  retention:
  - period: sekitar 3 bulan
    scope: face data on internal office server
    text: Data yang di simpan di server internal kantor hanya akan bertahan sekitar 3 bulan dan kemudian akan dihapus dari server.
  - period: null
    scope: general
    text: Data disimpan sesuai kebutuhan layanan dan hukum.
  rights:
  - right: access, update or delete
    text: Mengakses, memperbarui, atau menghapus data.
  - right: withdraw consent
    text: Menarik persetujuan kapan saja.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Kami tidak menjual data.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Komerce
provenance_date: '2026-11-09'
provider_name: Komerce
provider_slug: komerce
slug: komerce-privacy-policy
source_date: '2026-11-09'
source_filename: komerce-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://komerce.id/kebijakan-privasi/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Komerce\naid: komerce\nurl: https://komerce.id/kebijakan-privasi/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Nama Lengkap\n- category: contact\n  text: Nomor HP\n- category: location\n  text: Lokasi Bisnis\n- category: behavioral\n  text: Data pencarian, riwayat penelusuran (termasuk tanggal dan waktu yang terekam)\n- category: device\n  text: Informasi mengenai tipe perangkat yang Anda gunakan, seperti ID unik perangkat\n- category: biometric\n  text: Data wajah yang disimpan hanya untuk keperluan internal kantor seperti, presensi\
  \ masuk dan pulang\n- category: communication\n  text: Foto, suara, kontak, daftar panggilan ataupun interaksi lainnya dalam Layanan\n- category: financial\n  text: invoice pembayaran\npurposes:\n- purpose: communication, KYC and personalisation\n  text: Untuk berkomunikasi, menjalankan prinsip Know Your Customer (KYC) dan memberikan personalisasi kepada Anda\n- purpose: diagnosis and troubleshooting\n  text: Untuk melakukan diagnosa dan penyelesaian masalah terkait kesulitan dalam menggunakan Layanan.\n- purpose: payment processing\n  text: Untuk memproses maupun memfasilitasi pembayaran Anda.\n- purpose: advertising and promotion\n  text: Untuk menawarkan iklan/promosi maupun penawaran dari pihak lain yang bekerja sama.\n- purpose: broadcast service support\n  text: Mendukung layanan broadcast.\nretention:\n- scope: face data on internal office server\n  period: sekitar 3 bulan\n  text: Data yang di simpan di server internal kantor hanya akan bertahan sekitar 3 bulan dan kemudian akan\
  \ dihapus\n    dari server.\n- scope: general\n  period: null\n  text: Data disimpan sesuai kebutuhan layanan dan hukum.\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Users can access, update or delete data\n  text: 'Pengguna dapat: Mengakses, memperbarui, atau menghapus data.'\nrights:\n- right: access, update or delete\n  text: Mengakses, memperbarui, atau menghapus data.\n- right: withdraw consent\n  text: Menarik persetujuan kapan saja.\nsale_or_sharing:\n  stance: prohibited\n  text: Kami tidak menjual data.\n"
source_yaml_url: https://artifacts.apis.io/komerce/privacy/komerce-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 19 quoted statements, read from Komerce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Shipping
- Logistics
- E-Commerce
- Payments
- QRIS
- Indonesia
- Couriers
- Tracking
- Fulfillment
---
