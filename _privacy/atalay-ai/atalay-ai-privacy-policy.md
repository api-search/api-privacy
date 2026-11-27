---
claim_count: 22
description: ''
doc:
  data_categories:
  - category: identifying
    text: 'Kimlik ve iletişim: ad, soyad, e-posta, isteğe bağlı telefon'
  - category: contact
    text: fatura unvanı, vergi bilgisi (gerekiyorsa) ve iletişim adresi
  - category: device
    text: IP adresi, tarayıcı ve cihaz türü, işletim sistemi, dil, ekran bilgisi, oturum tanımlayıcıları
  - category: financial
    text: 'Ödeme referansları: fatura, abonelik ve işlem kimlikleri (kart numarası saklanmaz)'
  - category: behavioral
    text: özellik kullanım kayıtları, hata ve performans logları, yönlendiren URL
  - category: communication
    text: destek e-postaları ve ekler
  deletion:
    route: hesap silme sayfası / destek@atalay.ai
    text: Ayrıntılı silme adımları için hesap silme sayfasına bakın.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: hesap yönetimi ve builder işletimi
    text: hesabı oluşturmak ve yönetmek; website builder’ı çalıştırmak, siteleri barındırmak/yayınlamak
  - purpose: ödeme ve abonelik
    text: abonelik ve ödemeyi yürütmek
  - purpose: güvenlik
    text: dolandırıcılık, kötüye kullanım ve güvenlik olaylarını önlemek
  - purpose: yasal uyum
    text: yasal saklama ve uyum yükümlülüklerini yerine getirmek
  residency:
  - region: Germany (AI model hosting via AWS)
    text: AWS'in Frankfurt (eu-central-1, Avrupa Birliği) bölgesinde çalışır.
  - region: United States (OpenAI voice features)
    text: Aktarım ABD'ye yapılır.
  retention:
  - period: hesap aktifken ve silme talebi işlenene kadar
    scope: hesap ve site verileri
    text: 'Hesap ve site verileri: hesap aktifken ve silme talebi işlenene kadar.'
  - period: aylık mertebede
    scope: güvenlik, erişim ve hata logları
    text: genelde kısa süreli (ör. güvenlik ve sorun giderme için aylık mertebede) tutulur
  - period: 1 yıl
    scope: AI tool call records (Atalay MCP)
    text: Çağrı kaydı güvenlik ve “hangi asistan neyi ne zaman okudu” sorusunu cevaplamak için 1 yıl tutulur ve sonra otomatik silinir.
  - period: en fazla 30 gün
    scope: MCP refresh tokens
    text: yenileme jetonu en fazla 30 gün geçerlidir
  rights:
  - right: erişim, düzeltme, silme, kısıtlama, itiraz, taşınabilirlik, rıza geri çekme
    text: kişisel verilerinize erişme, düzeltme, silme, işlemeyi kısıtlama, itiraz etme, veri taşınabilirliği (uygun olduğunda) ve rızayı geri çekme haklarına sahip olabilirsiniz.
  role:
    text: Bu Gizlilik Politikası (“Politika”), ATALAY YAZILIM LTD. ŞTİ. (“Şirket”, “biz”) tarafından sunulan Atalay AI web sitesi, website builder, ödeme alanları, ilgili istemciler ve dijital araçlarda (toplu “Hizmetler”) kişisel verilerin nasıl toplandığını, işlendiğini, aktarıldığını ve korunduğunu açıklar.
    value: controller
  sale_or_sharing:
    stance: prohibited
    text: Kişisel verilerinizi satmayız.
  subprocessors:
    text: null
    url: null
  transfers:
  - mechanism: other
    text: Üçüncü ülke sağlayıcılarının kendi gizlilik politikaları da geçerlidir; mümkün olduğunca asgari veri ilkesi uygulanır.
  - mechanism: other
    text: Aktarımlarda KVKK ve ilgili mevzuata uygun güvenceler (ör. sözleşmesel yükümlülükler, sağlayıcı güvenlik standartları, erişim kontrolü) gözetilir.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Atalay AI
provenance_date: '2026-11-09'
provider_name: Atalay AI
provider_slug: atalay-ai
slug: atalay-ai-privacy-policy
source_date: '2026-11-09'
source_filename: atalay-ai-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://app.atalay.ai/gizlilik-politikasi
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Atalay AI\naid: atalay-ai\nurl: https://app.atalay.ai/gizlilik-politikasi\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: Bu Gizlilik Politikası (“Politika”), ATALAY YAZILIM LTD. ŞTİ. (“Şirket”, “biz”) tarafından sunulan Atalay\n    AI web sitesi, website builder, ödeme alanları, ilgili istemciler ve dijital araçlarda (toplu “Hizmetler”) kişisel\n    verilerin nasıl toplandığını, işlendiğini, aktarıldığını ve korunduğunu açıklar.\ndata_categories:\n- category: identifying\n  text: 'Kimlik ve iletişim: ad, soyad, e-posta, isteğe bağlı telefon'\n- category: contact\n  text: fatura unvanı, vergi\
  \ bilgisi (gerekiyorsa) ve iletişim adresi\n- category: device\n  text: IP adresi, tarayıcı ve cihaz türü, işletim sistemi, dil, ekran bilgisi, oturum tanımlayıcıları\n- category: financial\n  text: 'Ödeme referansları: fatura, abonelik ve işlem kimlikleri (kart numarası saklanmaz)'\n- category: behavioral\n  text: özellik kullanım kayıtları, hata ve performans logları, yönlendiren URL\n- category: communication\n  text: destek e-postaları ve ekler\npurposes:\n- purpose: hesap yönetimi ve builder işletimi\n  text: hesabı oluşturmak ve yönetmek; website builder’ı çalıştırmak, siteleri barındırmak/yayınlamak\n- purpose: ödeme ve abonelik\n  text: abonelik ve ödemeyi yürütmek\n- purpose: güvenlik\n  text: dolandırıcılık, kötüye kullanım ve güvenlik olaylarını önlemek\n- purpose: yasal uyum\n  text: yasal saklama ve uyum yükümlülüklerini yerine getirmek\nretention:\n- scope: hesap ve site verileri\n  period: hesap aktifken ve silme talebi işlenene kadar\n  text: 'Hesap ve site verileri: hesap\
  \ aktifken ve silme talebi işlenene kadar.'\n- scope: güvenlik, erişim ve hata logları\n  period: aylık mertebede\n  text: genelde kısa süreli (ör. güvenlik ve sorun giderme için aylık mertebede) tutulur\n- scope: AI tool call records (Atalay MCP)\n  period: 1 yıl\n  text: Çağrı kaydı güvenlik ve “hangi asistan neyi ne zaman okudu” sorusunu cevaplamak için 1 yıl tutulur ve sonra\n    otomatik silinir.\n- scope: MCP refresh tokens\n  period: en fazla 30 gün\n  text: yenileme jetonu en fazla 30 gün geçerlidir\nresidency:\n- region: Germany (AI model hosting via AWS)\n  text: AWS'in Frankfurt (eu-central-1, Avrupa Birliği) bölgesinde çalışır.\n- region: United States (OpenAI voice features)\n  text: Aktarım ABD'ye yapılır.\ntransfers:\n- mechanism: other\n  text: Üçüncü ülke sağlayıcılarının kendi gizlilik politikaları da geçerlidir; mümkün olduğunca asgari veri ilkesi\n    uygulanır.\n- mechanism: other\n  text: Aktarımlarda KVKK ve ilgili mevzuata uygun güvenceler (ör. sözleşmesel yükümlülükler,\
  \ sağlayıcı güvenlik\n    standartları, erişim kontrolü) gözetilir.\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: hesap silme sayfası / destek@atalay.ai\n  text: Ayrıntılı silme adımları için hesap silme sayfasına bakın.\nrights:\n- right: erişim, düzeltme, silme, kısıtlama, itiraz, taşınabilirlik, rıza geri çekme\n  text: kişisel verilerinize erişme, düzeltme, silme, işlemeyi kısıtlama, itiraz etme, veri taşınabilirliği (uygun\n    olduğunda) ve rızayı geri çekme haklarına sahip olabilirsiniz.\nsale_or_sharing:\n  stance: prohibited\n  text: Kişisel verilerinizi satmayız.\n"
source_yaml_url: https://artifacts.apis.io/atalay-ai/privacy/atalay-ai-privacy-policy.yml
stated_fields:
- role
- data_categories
- purposes
- retention
- residency
- transfers
- deletion
- rights
- sale_or_sharing
summary_line: 22 quoted statements, read from Atalay AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Business
- Software-as-a-Service
- Turkish
---
