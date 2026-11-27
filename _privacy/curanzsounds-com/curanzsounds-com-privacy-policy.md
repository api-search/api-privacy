---
api_specs:
- filename: curanzsounds-com-answer-api-openapi.yml
  format: yaml
  label: Curanz Sounds Answer API
  slug: curanzsounds-com-answer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/curanzsounds-com/openapi/curanzsounds-com-answer-api-openapi.yml
claim_count: 16
description: ''
doc:
  data_categories:
  - category: contact
    text: メールアドレス (会員登録・ログイン・お問い合わせの返信用)
  - category: identifying
    text: 呼び名・表示名 (Müri があなたを呼ぶ際の名前)
  - category: demographic
    text: 性別 (任意、鑑定の精度向上のため)
  - category: location
    text: 生まれた場所 (都道府県)
  - category: behavioral
    text: 生年月日 (西暦年・月・日)
  - category: communication
    text: お問い合わせフォームへの入力情報 (お名前・お問い合わせ内容)
  - category: financial
    text: サブスクリプション決済情報 (決済代行会社により処理され、当サイトはカード情報を保持しません)
  - category: contact
    text: 電話番号 (任意、数秘術の応用機能のため)
  deletion:
    route: アカウント設定から削除、または お問い合わせ窓口より個別にご請求
    text: アカウント設定からお客様自身でいつでもご削除いただけます
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: 占術鑑定機能の提供
    text: 占術鑑定機能のご提供のため、お客様からお預けいただいた情報を Müri がお預かりします。
  - purpose: 会員登録・ログイン・問い合わせ対応
    text: メールアドレス (会員登録・ログイン・お問い合わせの返信用)
  - purpose: 電話番号の数霊計算
    text: '利用目的: 電話番号の数霊計算、ライフパス数との相性診断、日常の数字判断'
  retention:
  - period: null
    scope: 登録解除後の内部情報
    text: 過去の鑑定結果等の内部情報は、 法令上の保管義務に基づき、 暗号化された状態でお預かりを続けます。
  rights:
  - right: 開示・訂正・利用停止・削除の請求
    text: 開示・訂正・利用停止・削除をご請求いただく権利を有します。
  - right: 電話番号の削除
    text: '削除請求: アカウント設定からお客様自身でいつでもご削除いただけます'
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 第三者への提供・販売は一切行いません。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Curanz Sounds
provenance_date: '2026-11-09'
provider_name: Curanz Sounds
provider_slug: curanzsounds-com
slug: curanzsounds-com-privacy-policy
source_date: '2026-11-09'
source_filename: curanzsounds-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://curanzsounds.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Curanz Sounds\naid: curanzsounds-com\nurl: https://curanzsounds.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: contact\n  text: メールアドレス (会員登録・ログイン・お問い合わせの返信用)\n- category: identifying\n  text: 呼び名・表示名 (Müri があなたを呼ぶ際の名前)\n- category: demographic\n  text: 性別 (任意、鑑定の精度向上のため)\n- category: location\n  text: 生まれた場所 (都道府県)\n- category: behavioral\n  text: 生年月日 (西暦年・月・日)\n- category: communication\n  text: お問い合わせフォームへの入力情報 (お名前・お問い合わせ内容)\n- category: financial\n  text: サブスクリプション決済情報 (決済代行会社により処理され、当サイトはカード情報を保持しません)\n- category: contact\n  text: 電話番号 (任意、数秘術の応用機能のため)\n\
  purposes:\n- purpose: 占術鑑定機能の提供\n  text: 占術鑑定機能のご提供のため、お客様からお預けいただいた情報を Müri がお預かりします。\n- purpose: 会員登録・ログイン・問い合わせ対応\n  text: メールアドレス (会員登録・ログイン・お問い合わせの返信用)\n- purpose: 電話番号の数霊計算\n  text: '利用目的: 電話番号の数霊計算、ライフパス数との相性診断、日常の数字判断'\nretention:\n- scope: 登録解除後の内部情報\n  period: null\n  text: 過去の鑑定結果等の内部情報は、 法令上の保管義務に基づき、 暗号化された状態でお預かりを続けます。\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: アカウント設定から削除、または お問い合わせ窓口より個別にご請求\n  text: アカウント設定からお客様自身でいつでもご削除いただけます\nrights:\n- right: 開示・訂正・利用停止・削除の請求\n  text: 開示・訂正・利用停止・削除をご請求いただく権利を有します。\n- right: 電話番号の削除\n  text: '削除請求: アカウント設定からお客様自身でいつでもご削除いただけます'\nsale_or_sharing:\n  stance: prohibited\n  text: 第三者への提供・販売は一切行いません。\n"
source_yaml_url: https://artifacts.apis.io/curanzsounds-com/privacy/curanzsounds-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- deletion
- rights
- sale_or_sharing
summary_line: 16 quoted statements, read from Curanz Sounds's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fortune Telling
- Astrology
- Artificial Intelligence
- Numerology
- Tarot
- Japan
- Consumer
---
