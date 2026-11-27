---
api_specs:
- filename: biver-id-openapi-generated.yml
  format: yaml
  label: Biver API
  slug: biver-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/biver-id/openapi/_ae-authored/biver-id-openapi-generated.yml
claim_count: 28
description: ''
doc:
  data_categories:
  - category: identifying
    text: Nama lengkap, alamat email, kata sandi (terenkripsi), nomor telepon (opsional).
  - category: financial
    text: Data kartu kredit/debit diproses oleh payment processor (DOKU dan integrasi pembayaran lama yang masih aktif). Kami tidak menyimpan nomor kartu lengkap.
  - category: device
    text: Identifier perangkat, resolusi layar, pengaturan bahasa.
  - category: behavioral
    text: Fitur yang digunakan, halaman yang dibuat, waktu sesi.
  - category: communication
    text: Pesan yang Anda kirimkan kepada tim support kami.
  - category: location
    text: Alamat IP, jenis browser, sistem operasi, URL referral, halaman yang dikunjungi, waktu dan durasi kunjungan.
  deletion:
    route: Email legal@biver.id
    text: Untuk mengajukan permintaan hak data, kirimkan email ke legal@biver.id .
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Penyediaan layanan
    text: Membuat dan mengelola akun Anda, menyediakan fitur platform, memproses pembayaran.
  - purpose: Peningkatan layanan
    text: Menganalisis penggunaan platform untuk meningkatkan fitur dan pengalaman pengguna.
  - purpose: Keamanan
    text: Mendeteksi, mencegah, dan menangani penipuan, penyalahgunaan, dan ancaman keamanan.
  - purpose: Kepatuhan hukum
    text: Memenuhi kewajiban hukum yang berlaku.
  residency:
  - region: Outside Indonesia
    text: Sebagian penyedia layanan kami berlokasi di luar Indonesia.
  retention:
  - period: Selama akun aktif + 30 hari setelah penghapusan
    scope: Data akun aktif
    text: Selama akun aktif + 30 hari setelah penghapusan
  - period: 10 tahun
    scope: Data transaksi
    text: 10 tahun (kewajiban pajak Indonesia)
  - period: 12 bulan
    scope: Log akses dan keamanan
    text: Log akses dan keamanan 12 bulan
  - period: 26 bulan
    scope: Data analitik (anonim)
    text: Data analitik (anonim) 26 bulan
  - period: 3 tahun
    scope: Data komunikasi support
    text: Data komunikasi support 3 tahun
  - period: 90 hari
    scope: Data backup
    text: Data backup 90 hari
  rights:
  - right: Akses
    text: Mendapatkan salinan data pribadi yang kami simpan tentang Anda.
  - right: Perbaikan
    text: Meminta perbaikan data yang tidak akurat atau tidak lengkap.
  - right: Penghapusan
    text: Meminta penghapusan data pribadi Anda dalam kondisi tertentu.
  - right: Pembatasan pemrosesan
    text: Meminta pembatasan pemrosesan data Anda dalam kondisi tertentu.
  - right: Portabilitas
    text: Menerima data Anda dalam format yang dapat dibaca mesin.
  - right: Keberatan
    text: Mengajukan keberatan terhadap pemrosesan berdasarkan kepentingan sah.
  - right: Penarikan persetujuan
    text: Menarik persetujuan yang telah diberikan kapan saja.
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: Kami tidak menjual data pribadi Anda.
  subprocessors:
    text: Cloudflare — compute, database, storage, CDN, keamanan, dan DNS
    url: null
  transfers:
  - mechanism: SCC
    text: Standard Contractual Clauses (SCC) yang disetujui oleh Komisi Eropa untuk transfer ke negara di luar EEA.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Biver
provenance_date: '2026-11-09'
provider_name: Biver
provider_slug: biver-id
slug: biver-id-privacy-policy
source_date: '2026-11-09'
source_filename: biver-id-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://biver.id/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Biver\naid: biver-id\nurl: https://biver.id/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: identifying\n  text: Nama lengkap, alamat email, kata sandi (terenkripsi), nomor telepon (opsional).\n- category: financial\n  text: Data kartu kredit/debit diproses oleh payment processor (DOKU dan integrasi pembayaran lama yang masih aktif).\n    Kami tidak menyimpan nomor kartu lengkap.\n- category: device\n  text: Identifier perangkat, resolusi layar, pengaturan bahasa.\n- category: behavioral\n  text: Fitur yang digunakan, halaman yang dibuat, waktu sesi.\n\
  - category: communication\n  text: Pesan yang Anda kirimkan kepada tim support kami.\n- category: location\n  text: Alamat IP, jenis browser, sistem operasi, URL referral, halaman yang dikunjungi, waktu dan durasi kunjungan.\npurposes:\n- purpose: Penyediaan layanan\n  text: Membuat dan mengelola akun Anda, menyediakan fitur platform, memproses pembayaran.\n- purpose: Peningkatan layanan\n  text: Menganalisis penggunaan platform untuk meningkatkan fitur dan pengalaman pengguna.\n- purpose: Keamanan\n  text: Mendeteksi, mencegah, dan menangani penipuan, penyalahgunaan, dan ancaman keamanan.\n- purpose: Kepatuhan hukum\n  text: Memenuhi kewajiban hukum yang berlaku.\nretention:\n- scope: Data akun aktif\n  period: Selama akun aktif + 30 hari setelah penghapusan\n  text: Selama akun aktif + 30 hari setelah penghapusan\n- scope: Data transaksi\n  period: 10 tahun\n  text: 10 tahun (kewajiban pajak Indonesia)\n- scope: Log akses dan keamanan\n  period: 12 bulan\n  text: Log akses dan keamanan\
  \ 12 bulan\n- scope: Data analitik (anonim)\n  period: 26 bulan\n  text: Data analitik (anonim) 26 bulan\n- scope: Data komunikasi support\n  period: 3 tahun\n  text: Data komunikasi support 3 tahun\n- scope: Data backup\n  period: 90 hari\n  text: Data backup 90 hari\nresidency:\n- region: Outside Indonesia\n  text: Sebagian penyedia layanan kami berlokasi di luar Indonesia.\ntransfers:\n- mechanism: SCC\n  text: Standard Contractual Clauses (SCC) yang disetujui oleh Komisi Eropa untuk transfer ke negara di luar EEA.\nsubprocessors:\n  url: null\n  text: Cloudflare — compute, database, storage, CDN, keamanan, dan DNS\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Email legal@biver.id\n  text: Untuk mengajukan permintaan hak data, kirimkan email ke legal@biver.id .\nrights:\n- right: Akses\n  text: Mendapatkan salinan data pribadi yang kami simpan tentang Anda.\n- right: Perbaikan\n  text: Meminta perbaikan data yang tidak akurat atau tidak lengkap.\n- right:\
  \ Penghapusan\n  text: Meminta penghapusan data pribadi Anda dalam kondisi tertentu.\n- right: Pembatasan pemrosesan\n  text: Meminta pembatasan pemrosesan data Anda dalam kondisi tertentu.\n- right: Portabilitas\n  text: Menerima data Anda dalam format yang dapat dibaca mesin.\n- right: Keberatan\n  text: Mengajukan keberatan terhadap pemrosesan berdasarkan kepentingan sah.\n- right: Penarikan persetujuan\n  text: Menarik persetujuan yang telah diberikan kapan saja.\nsale_or_sharing:\n  stance: prohibited\n  text: Kami tidak menjual data pribadi Anda.\n"
source_yaml_url: https://artifacts.apis.io/biver-id/privacy/biver-id-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- transfers
- subprocessors
- deletion
- rights
- sale_or_sharing
summary_line: 28 quoted statements, read from Biver's own page on 2026-11-09.
synthetic: false
tags:
- E-Commerce
- Artificial Intelligence
- Landing Page Builder
- Indonesia
- UMKM
---
