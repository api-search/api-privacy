---
claim_count: 14
description: ''
doc:
  data_categories:
  - category: other
    text: ユーザーがアップロードした画像は AI による顔認識処理にのみ使用され、判定処理が完了した直後に破棄します。
  - category: identifying
    text: LINE から通知される利用者識別子 (ユーザーID) を一時的に利用します。
  - category: identifying
    text: Telegram から通知される利用者識別子 (ユーザーID) と、重複処理を防ぐためのメッセージ (Update) 識別子を一時的に利用します。
  - category: behavioral
    text: クリック・スクロール・マウス操作といった行動データを収集して、ヒートマップやセッションの再生 (画面操作の記録) として当サイトの運営者に提供します。
  - category: device
    text: 端末・ブラウザの種別、IPアドレスから推定するおおまかな地域など
  deletion:
    route: null
    text: null
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Image face recognition for actress judgment
    text: 送信された画像は AI による顔認識処理にのみ使用し、判定処理が完了した直後に破棄します。
  - purpose: Rate limiting and abuse prevention
    text: 同一利用者による短時間の大量送信を防止し 1 日あたりの判定回数を管理する目的で
  - purpose: Anonymous statistics
    text: 「よく判定されている女優」といった、当サイト全体の傾向を把握・表示する目的にのみ利用し
  - purpose: Site analytics
    text: 利用状況把握のため Google 社の提供する Google Analytics 4 (GA4) を利用しています。
  - purpose: Site improvement analytics
    text: ページの使われ方を把握しサイトの改善に役立てるため、Microsoft 社の提供する Microsoft Clarity を利用しています。
  retention:
  - period: null
    scope: Uploaded images
    text: 判定処理が完了した直後に破棄します。
  - period: null
    scope: Image URL for URL-based judgment
    text: 画像 URL は、判定のための画像取得に使用するほかは、当サイトのサーバーおよびデータベースに保存しません。
  - period: null
    scope: LINE and Telegram user identifiers
    text: 一定期間経過後に自動的に削除します。
  role:
    text: null
    value: unstated
  sale_or_sharing:
    stance: prohibited
    text: 第三者への提供・販売は行いません。
  subprocessors:
    text: null
    url: null
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: AV女優判定AI
provenance_date: '2026-11-09'
provider_name: AV女優判定AI
provider_slug: ai-for-av-com
slug: ai-for-av-com-privacy-policy
source_date: '2026-11-09'
source_filename: ai-for-av-com-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://ai-for-av.com/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: AV女優判定AI\naid: ai-for-av-com\nurl: https://ai-for-av.com/privacy\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: unstated\n  text: null\ndata_categories:\n- category: other\n  text: ユーザーがアップロードした画像は AI による顔認識処理にのみ使用され、判定処理が完了した直後に破棄します。\n- category: identifying\n  text: LINE から通知される利用者識別子 (ユーザーID) を一時的に利用します。\n- category: identifying\n  text: Telegram から通知される利用者識別子 (ユーザーID) と、重複処理を防ぐためのメッセージ (Update) 識別子を一時的に利用します。\n- category: behavioral\n  text: クリック・スクロール・マウス操作といった行動データを収集して、ヒートマップやセッションの再生 (画面操作の記録) として当サイトの運営者に提供します。\n- category: device\n  text: 端末・ブラウザの種別、IPアドレスから推定するおおまかな地域など\npurposes:\n- purpose: Image\
  \ face recognition for actress judgment\n  text: 送信された画像は AI による顔認識処理にのみ使用し、判定処理が完了した直後に破棄します。\n- purpose: Rate limiting and abuse prevention\n  text: 同一利用者による短時間の大量送信を防止し 1 日あたりの判定回数を管理する目的で\n- purpose: Anonymous statistics\n  text: 「よく判定されている女優」といった、当サイト全体の傾向を把握・表示する目的にのみ利用し\n- purpose: Site analytics\n  text: 利用状況把握のため Google 社の提供する Google Analytics 4 (GA4) を利用しています。\n- purpose: Site improvement analytics\n  text: ページの使われ方を把握しサイトの改善に役立てるため、Microsoft 社の提供する Microsoft Clarity を利用しています。\nretention:\n- scope: Uploaded images\n  period: null\n  text: 判定処理が完了した直後に破棄します。\n- scope: Image URL for URL-based judgment\n  period: null\n  text: 画像 URL は、判定のための画像取得に使用するほかは、当サイトのサーバーおよびデータベースに保存しません。\n- scope: LINE and Telegram user identifiers\n  period: null\n  text: 一定期間経過後に自動的に削除します。\nresidency: []\ntransfers: []\nsubprocessors:\n  url: null\n  text: null\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: null\n  text: null\nrights: []\nsale_or_sharing:\n  stance: prohibited\n\
  \  text: 第三者への提供・販売は行いません。\n"
source_yaml_url: https://artifacts.apis.io/ai-for-av-com/privacy/ai-for-av-com-privacy-policy.yml
stated_fields:
- data_categories
- purposes
- retention
- sale_or_sharing
summary_line: 14 quoted statements, read from AV女優判定AI's own page on 2026-11-09.
synthetic: false
tags:
- Adult
- Artificial Intelligence
- Video
- Japanese
- Entertainment
---
