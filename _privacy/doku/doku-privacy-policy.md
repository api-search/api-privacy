---
api_specs:
- filename: doku-access-token-api-openapi.yml
  format: yaml
  label: DOKU Access Token API
  slug: doku-access-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-access-token-api-openapi.yml
- filename: doku-checkout-api-openapi.yml
  format: yaml
  label: DOKU Checkout API
  slug: doku-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-checkout-api-openapi.yml
- filename: doku-direct-debit-e-wallet-api-openapi.yml
  format: yaml
  label: DOKU Direct Debit & e-Wallet API
  slug: doku-direct-debit-e-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-direct-debit-e-wallet-api-openapi.yml
- filename: doku-payout-api-openapi.yml
  format: yaml
  label: DOKU Payout API
  slug: doku-payout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-payout-api-openapi.yml
- filename: doku-qris-api-openapi.yml
  format: yaml
  label: DOKU QRIS API
  slug: doku-qris-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-qris-api-openapi.yml
- filename: doku-virtual-account-api-openapi.yml
  format: yaml
  label: DOKU Virtual Account API
  slug: doku-virtual-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/doku/openapi/doku-virtual-account-api-openapi.yml
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: nama, alamat kantor, alamat e-mail, dan nomor telepon Merchant
  - category: financial
    text: data rekening bank milik Merchant jika diperlukan
  - category: identifying
    text: kartu tanda penduduk (KTP) dari Direksi (jika badan usaha) atau KTP pemilik (jika non-badan usaha)
  - category: financial
    text: nama Pemegang Kartu, nomor kartu, masa berlaku dan service code dari kartu yang digunakan untuk melakukan pembayaran
  - category: device
    text: alamat protokol internet, aktivitas dihalaman web Kami, durasi setiap kunjungan/sesi, identitas perangkat internet
  - category: location
    text: informasi lokasi geografis anda dalam waktu sebenarnya
  deletion:
    route: null
    text: Kami akan berhenti menyimpan Informasi Pribadi, atau menghapus maksud dari dikaitkannya Informasi Pribadi tersebut dengan Anda sebagai Merchant atau Konsumen, segera setelah dianggap bahwa tujuan pengumpulan Informasi Pribadi tersebut tidak lagi dibutuhkan
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Provide requested services
    text: untuk menyediakan Layanan yang Anda minta termasuk melakukan komunikasi dan mengirimkan informasi sehubungan dengan transaksi yang dilakukan dengan menggunakan Layanan Kami
  - purpose: Fraud prevention
    text: untuk kepentingan pencegahan dan penindakan atas terjadinya penipuan (fraud prevention)
  - purpose: Anonymous statistics and analytics
    text: untuk menghasilkan informasi statistik dan data analitik anonim untuk tujuan pengujian, penelitian, analisis, pengembangan produk, kemitraan komersial, dan kerja sama
  residency:
  - region: Indonesia
    text: Informasi Pribadi Anda juga hanya disimpan di dalam negeri (Indonesia)
  retention:
  - period: null
    scope: Personal information
    text: Informasi Pribadi Anda hanya akan disimpan selama diperlukan untuk memenuhi tujuan dari pengumpulannya, atau selama penyimpanan tersebut diperlukan atau diperbolehkan oleh peraturan perundang-undangan yang berlaku
  rights:
  - right: Access and correction
    text: Anda dapat meminta Kami untuk mengakses, mengoreksi dan memperbaharui Informasi Pribadi Anda yang berada dalam penguasaan Kami
  - right: Withdraw consent
    text: Anda dapat menarik persetujuan Anda untuk setiap atau segala pengumpulan, penggunaan atau pengungkapan Informasi Pribadi Anda
  - right: Opt out of marketing
    text: Anda dapat memilih untuk tidak menerima komunikasi pemasaran tersebut kapan saja
  role:
    text: DOKU (PT Nusa Satu Inti Artha, "Kami") secara elektronis mengumpulkan, menggunakan, mengungkapkan, mengirimkan, menyimpan, dan melindungi informasi pribadi Anda
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Kami tidak akan menyebarluaskan dan/atau menjual Informasi Pribadi Anda kepada pihak lain atau perusahaan-perusahaan yang tidak terafiliasi dengan Kami, kecuali untuk pelaksanaan penyediaan produk dan jasa layanan yang Anda minta.
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: DOKU
provenance_date: '2026-11-09'
provider_name: DOKU
provider_slug: doku
slug: doku-privacy-policy
source_date: '2026-11-09'
source_filename: doku-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dashboard.doku.com/doku-agreement/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: DOKU\naid: doku\nurl: https://dashboard.doku.com/doku-agreement/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: DOKU (PT Nusa Satu Inti Artha, \"Kami\") secara elektronis mengumpulkan, menggunakan, mengungkapkan, mengirimkan,\n    menyimpan, dan melindungi informasi pribadi Anda\ndata_categories:\n- category: contact\n  text: nama, alamat kantor, alamat e-mail, dan nomor telepon Merchant\n- category: financial\n  text: data rekening bank milik Merchant jika diperlukan\n- category: identifying\n  text: kartu tanda penduduk (KTP) dari Direksi (jika badan usaha) atau KTP pemilik\
  \ (jika non-badan usaha)\n- category: financial\n  text: nama Pemegang Kartu, nomor kartu, masa berlaku dan service code dari kartu yang digunakan untuk melakukan\n    pembayaran\n- category: device\n  text: alamat protokol internet, aktivitas dihalaman web Kami, durasi setiap kunjungan/sesi, identitas perangkat\n    internet\n- category: location\n  text: informasi lokasi geografis anda dalam waktu sebenarnya\npurposes:\n- purpose: Provide requested services\n  text: untuk menyediakan Layanan yang Anda minta termasuk melakukan komunikasi dan mengirimkan informasi sehubungan\n    dengan transaksi yang dilakukan dengan menggunakan Layanan Kami\n- purpose: Fraud prevention\n  text: untuk kepentingan pencegahan dan penindakan atas terjadinya penipuan (fraud prevention)\n- purpose: Anonymous statistics and analytics\n  text: untuk menghasilkan informasi statistik dan data analitik anonim untuk tujuan pengujian, penelitian, analisis,\n    pengembangan produk, kemitraan komersial, dan kerja\
  \ sama\nretention:\n- scope: Personal information\n  period: null\n  text: Informasi Pribadi Anda hanya akan disimpan selama diperlukan untuk memenuhi tujuan dari pengumpulannya,\n    atau selama penyimpanan tersebut diperlukan atau diperbolehkan oleh peraturan perundang-undangan yang berlaku\nresidency:\n- region: Indonesia\n  text: Informasi Pribadi Anda juga hanya disimpan di dalam negeri (Indonesia)\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: Kami akan berhenti menyimpan Informasi Pribadi, atau menghapus maksud dari dikaitkannya Informasi Pribadi\n    tersebut dengan Anda sebagai Merchant atau Konsumen, segera setelah dianggap bahwa tujuan pengumpulan Informasi\n    Pribadi tersebut tidak lagi dibutuhkan\nrights:\n- right: Access and correction\n  text: Anda dapat meminta Kami untuk mengakses, mengoreksi dan memperbaharui Informasi Pribadi Anda yang berada\n    dalam penguasaan Kami\n\
  - right: Withdraw consent\n  text: Anda dapat menarik persetujuan Anda untuk setiap atau segala pengumpulan, penggunaan atau pengungkapan Informasi\n    Pribadi Anda\n- right: Opt out of marketing\n  text: Anda dapat memilih untuk tidak menerima komunikasi pemasaran tersebut kapan saja\nsale_or_sharing:\n  stance: prohibited\n  text: Kami tidak akan menyebarluaskan dan/atau menjual Informasi Pribadi Anda kepada pihak lain atau perusahaan-perusahaan\n    yang tidak terafiliasi dengan Kami, kecuali untuk pelaksanaan penyediaan produk dan jasa layanan yang Anda minta.\n"
source_yaml_url: https://artifacts.apis.io/doku/privacy/doku-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from DOKU's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Payment Gateway
- Fintech
- Indonesia
- SEA
- SNAP
- Virtual Accounts
- Digital Wallet
- QRIS
- Direct Debit
- Payouts
---
