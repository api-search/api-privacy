---
api_specs:
- filename: cermati-protect-openapi.json
  format: json
  label: Cermati Protect Generic Insurance API
  slug: cermati-protect-generic-insurance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/cermati/openapi/cermati-protect-openapi.json
claim_count: 17
description: ''
doc:
  data_categories:
  - category: contact
    text: nama pengguna (username), alamat email, nomor telepon, pin, password, alamat dan informasi lainnya yang dapat mengidentifikasi Pengguna
  - category: identifying
    text: nomor Kartu Tanda Penduduk (KTP), NPWP, pekerjaan, jumlah penghasilan/gaji, alamat
  - category: financial
    text: Mengisi data-data pembayaran pada saat Pengguna menggunakan layanan-layanan pada Situs, yaitu informasi kartu kredit
  - category: location
    text: data lokasi riil atau perkiraannya yaitu alamat IP dan geo-location
  - category: behavioral
    text: data penggunaan atau preferensi Pengguna, di antaranya interaksi Pengguna dalam menggunakan Situs, pilihan yang disimpan, serta pengaturan yang dipilih
  - category: demographic
    text: Pembelian asuransi jiwa dan kesehatan, yang terdiri dari jenis perlindungan, jenis kelamin, tanggal lahir, bulan lahir, tahun lahir, cara klaim
  - category: device
    text: data catatan (log), di antaranya yaitu alamat IP perangkat, tanggal dan waktu akses, fitur aplikasi atau laman yang dilihat, proses kerja aplikasi dan aktivitas sistem lainnya, jenis peramban (browser)
  deletion:
    route: close the account
    text: Pengguna dapat melakukan permohonan penghapusan informasi Pengguna dengan cara menutup akun Pengguna.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: process user requests and transactions
    text: Memproses segala bentuk permintaan, aktivitas maupun transaksi yang dilakukan oleh Pengguna melalui Situs
  - purpose: improve site and personalise experience
    text: Menyediakan dan memperbaiki Situs dan layanan kami, mengembangkan penawaran baru, meningkatkan dan personalisasikan pengalaman Pengguna di Situs
  - purpose: fraud monitoring and investigation
    text: Melakukan monitoring ataupun investigasi terhadap transaksi-transaksi mencurigakan atau transaksi yang terindikasi mengandung unsur kecurangan
  residency:
  - region: outside Indonesia
    text: Data Pribadi Pengguna juga dapat disimpan atau diproses di luar negara Republik Indonesia oleh pihak yang bekerja sama dengan kami
  retention:
  - period: selama akun Pengguna aktif
    scope: account data
    text: Kami akan menyimpan informasi selama akun Pengguna aktif sesuai dengan ketentuan peraturan hukum yang berlaku di Indonesia.
  rights:
  - right: access and correction
    text: Pengguna berhak untuk mengakses atau mengoreksi Data Pribadi Pengguna yang berada di bawah kendali kami
  - right: withdraw consent
    text: Hak untuk menarik kembali persetujuan pemrosesan Data Pribadi miliknya
  - right: erasure
    text: Hak untuk menghapus dan/atau memusnahkan Data Pribadi miliknya
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: conditional
    text: menjamin tidak ada pengungkapan, penjualan, pengalihan, distribusi dan/atau peminjaman Data Pribadi Pengguna kepada pihak ketiga lain, tanpa persetujuan terlebih dahulu dari Pengguna
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Cermati
provenance_date: '2026-11-09'
provider_name: Cermati
provider_slug: cermati
slug: cermati-privacy-policy
source_date: '2026-11-09'
source_filename: cermati-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://www.cermati.com/pages/privacy-policy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Cermati\naid: cermati\nurl: https://www.cermati.com/pages/privacy-policy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: nama pengguna (username), alamat email, nomor telepon, pin, password, alamat dan informasi lainnya yang\n    dapat mengidentifikasi Pengguna\n- category: identifying\n  text: nomor Kartu Tanda Penduduk (KTP), NPWP, pekerjaan, jumlah penghasilan/gaji, alamat\n- category: financial\n  text: Mengisi data-data pembayaran pada saat Pengguna menggunakan layanan-layanan pada Situs, yaitu informasi\n    kartu kredit\n- category:\
  \ location\n  text: data lokasi riil atau perkiraannya yaitu alamat IP dan geo-location\n- category: behavioral\n  text: data penggunaan atau preferensi Pengguna, di antaranya interaksi Pengguna dalam menggunakan Situs, pilihan\n    yang disimpan, serta pengaturan yang dipilih\n- category: demographic\n  text: Pembelian asuransi jiwa dan kesehatan, yang terdiri dari jenis perlindungan, jenis kelamin, tanggal lahir,\n    bulan lahir, tahun lahir, cara klaim\n- category: device\n  text: data catatan (log), di antaranya yaitu alamat IP perangkat, tanggal dan waktu akses, fitur aplikasi atau\n    laman yang dilihat, proses kerja aplikasi dan aktivitas sistem lainnya, jenis peramban (browser)\npurposes:\n- purpose: process user requests and transactions\n  text: Memproses segala bentuk permintaan, aktivitas maupun transaksi yang dilakukan oleh Pengguna melalui Situs\n- purpose: improve site and personalise experience\n  text: Menyediakan dan memperbaiki Situs dan layanan kami, mengembangkan\
  \ penawaran baru, meningkatkan dan personalisasikan\n    pengalaman Pengguna di Situs\n- purpose: fraud monitoring and investigation\n  text: Melakukan monitoring ataupun investigasi terhadap transaksi-transaksi mencurigakan atau transaksi yang terindikasi\n    mengandung unsur kecurangan\nretention:\n- scope: account data\n  period: selama akun Pengguna aktif\n  text: Kami akan menyimpan informasi selama akun Pengguna aktif sesuai dengan ketentuan peraturan hukum yang berlaku\n    di Indonesia.\nresidency:\n- region: outside Indonesia\n  text: Data Pribadi Pengguna juga dapat disimpan atau diproses di luar negara Republik Indonesia oleh pihak yang\n    bekerja sama dengan kami\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: close the account\n  text: Pengguna dapat melakukan permohonan penghapusan informasi Pengguna dengan cara menutup akun Pengguna.\nrights:\n- right: access and correction\n  text: Pengguna\
  \ berhak untuk mengakses atau mengoreksi Data Pribadi Pengguna yang berada di bawah kendali kami\n- right: withdraw consent\n  text: Hak untuk menarik kembali persetujuan pemrosesan Data Pribadi miliknya\n- right: erasure\n  text: Hak untuk menghapus dan/atau memusnahkan Data Pribadi miliknya\nsale_or_sharing:\n  stance: conditional\n  text: menjamin tidak ada pengungkapan, penjualan, pengalihan, distribusi dan/atau peminjaman Data Pribadi Pengguna\n    kepada pihak ketiga lain, tanpa persetujuan terlebih dahulu dari Pengguna\n"
source_yaml_url: https://artifacts.apis.io/cermati/privacy/cermati-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- residency
- deletion
- rights
- sale_or_sharing
summary_line: 17 quoted statements, read from Cermati's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Loans
- Credit Cards
- Insurance
- Investment
- Indonesia
---
