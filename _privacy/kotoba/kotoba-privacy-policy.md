---
api_specs:
- filename: kotoba-transcriptionapi-api-openapi.yml
  format: yaml
  label: Kotoba Transcription API
  slug: kotoba-transcriptionapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kotoba/openapi/kotoba-transcriptionapi-api-openapi.yml
claim_count: 31
description: ''
doc:
  data_categories:
  - category: identifying
    text: We collect information by which you may be personally identified, such as your name and email address
  - category: contact
    text: name and email address, including when you choose to authenticate through third-party login services (such as Google or Apple)
  - category: financial
    text: Information relating to your subscription status, purchase history, or transaction confirmation received from third-party payment processors and subscription management providers.
  - category: device
    text: This includes device identifiers such as device ID and third-party identifiers including RevenueCat ID for non-enterprise users and AppsFlyer ID, as well as your Internet Protocol (IP) address.
  - category: behavioral
    text: It also includes information about your interactions with the Website, such as pages viewed, referring URLs, date and time of visits, browser type, and other usage data
  - category: location
    text: We may also derive general location information from your IP address.
  - category: communication
    text: When you sign up for our services or request information, we collect details about your requests and inquiries.
  - category: other
    text: We collect audio recordings or raw audio when you choose to use features that involve audio input.
  - category: health
    text: We do not intentionally collect sensitive personal information as defined under applicable law unless such information is incidentally included in audio recordings that you voluntarily submit.
  deletion:
    route: Contact us as set forth in Section IX, or in-app settings for opt-out of model training
    text: If you believe a child under 13 has provided us with personal information, please contact us as described in Section IX so we can delete it.
  dpa:
    available: null
    text: null
    url: null
  purposes:
  - purpose: Account management and service delivery
    text: We use this information to create and manage your account, authenticate your access to the Services, communicate with you regarding your account or the Services, provide customer support
  - purpose: Model training for non-enterprise users not opted out
    text: For non-enterprise paid users who have not opted out of data/model improvement use, and for free users, we may use Raw Audio Data and Audio-Derived Text/Data Outputs to provide the Services, conduct quality assurance, troubleshoot, improve service functionality and accuracy, perform analytics, and support ongoing training of our machine learning models
  - purpose: Cross-context behavioral advertising
    text: Through these technologies, such partners collect Internet or Other Electronic Network Activity Information (including identifiers such as IP address, device identifiers, and cookie identifiers) to show you Kotoba advertisements on other websites and applications based on your interactions with our Website.
  - purpose: Analytics and security
    text: We use this information to operate and maintain the Website and Services, monitor performance and errors (including through tools such as Firebase and Sentry), analyze usage trends and engagement
  residency:
  - region: Japan
    text: Personal information collected through the Services may be transferred to, stored, and processed in Japan, where our cloud infrastructure is located
  retention:
  - period: Duration of account + 6 months after deletion
    scope: Account and contact information, commercial information, communications data
    text: Account & Contact Information Duration of account + 6 months after deletion
  - period: Up to 24 months from collection
    scope: Internet/network activity logs
    text: Internet/Network Activity (log data, technical metadata, IP addresses) Up to 24 months from collection
  - period: Up to 12 months from last interaction with the Services for model training, unless you have opted out
    scope: Raw Audio Data (non-enterprise)
    text: 'Raw Audio Data: Limited period as reasonably necessary to provide the Services; Up to 12 months from last interaction with the Services for model training, unless you have opted out'
  - period: Not retained after processing is completed
    scope: Raw Audio Data (enterprise)
    text: 'Raw Audio Data: Retained only during transcription, translation, or related processing and not retained after processing is completed'
  - period: Not retained
    scope: Audio Outputs
    text: Audio Outputs are generated and played back in real time only and are not retained by us for any user category.
  - period: Indefinitely
    scope: De-identified/aggregated data
    text: De-Identified/ Aggregated Data Indefinitely Not reasonably capable of being linked to you.
  rights:
  - right: Access
    text: The right to confirm whether we process your personal information and to access such personal information.
  - right: Correction
    text: The right to request correction of inaccuracies in your personal information.
  - right: Deletion
    text: The right to request deletion of your personal information.
  - right: Opt out of sale or sharing
    text: The right to opt out of the sale or sharing of personal information, as defined under applicable law.
  - right: Appeal
    text: The right to appeal a decision regarding your privacy rights request, where required by applicable law.
  - right: Non-discrimination
    text: The right not to receive discriminatory treatment for exercising your privacy rights.
  role:
    text: We at Kotoba Technologies, Inc. (“Kotoba,” “we,” “us,” or “our”) have created this privacy policy
    value: controller
  sale_or_sharing:
    stance: conditional
    text: We do not sell personal information for monetary compensation.
  subprocessors:
    text: AI processing providers, including providers such as OpenAI, Google, and Microsoft
    url: null
  transfers:
  - mechanism: other
    text: By using the Services, you consent to such transfers.
layer: privacy_policy
layer_version: 0.1.0
layout: privacy
method: harvested
model: claude-haiku-5-5
name: Kotoba
provenance_date: '2026-11-09'
provider_name: Kotoba
provider_slug: kotoba
slug: kotoba-privacy-policy
source_date: '2026-11-09'
source_filename: kotoba-privacy-policy.yml
source_heading: Privacy Policy
source_page: https://dashboard.kotobatech.ai/privacy_en.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\nprivacy_policy: 0.1.0\nprovider: Kotoba\naid: kotoba\nurl: https://dashboard.kotobatech.ai/privacy_en.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\nrole:\n  value: controller\n  text: We at Kotoba Technologies, Inc. (“Kotoba,” “we,” “us,” or “our”) have created this privacy policy\ndata_categories:\n- category: identifying\n  text: We collect information by which you may be personally identified, such as your name and email address\n- category: contact\n  text: name and email address, including when you choose to authenticate through third-party login services (such\n    as Google or Apple)\n- category: financial\n  text: Information relating to your\
  \ subscription status, purchase history, or transaction confirmation received\n    from third-party payment processors and subscription management providers.\n- category: device\n  text: This includes device identifiers such as device ID and third-party identifiers including RevenueCat ID for\n    non-enterprise users and AppsFlyer ID, as well as your Internet Protocol (IP) address.\n- category: behavioral\n  text: It also includes information about your interactions with the Website, such as pages viewed, referring URLs,\n    date and time of visits, browser type, and other usage data\n- category: location\n  text: We may also derive general location information from your IP address.\n- category: communication\n  text: When you sign up for our services or request information, we collect details about your requests and inquiries.\n- category: other\n  text: We collect audio recordings or raw audio when you choose to use features that involve audio input.\n- category: health\n  text: We\
  \ do not intentionally collect sensitive personal information as defined under applicable law unless such\n    information is incidentally included in audio recordings that you voluntarily submit.\npurposes:\n- purpose: Account management and service delivery\n  text: We use this information to create and manage your account, authenticate your access to the Services, communicate\n    with you regarding your account or the Services, provide customer support\n- purpose: Model training for non-enterprise users not opted out\n  text: For non-enterprise paid users who have not opted out of data/model improvement use, and for free users,\n    we may use Raw Audio Data and Audio-Derived Text/Data Outputs to provide the Services, conduct quality assurance,\n    troubleshoot, improve service functionality and accuracy, perform analytics, and support ongoing training of\n    our machine learning models\n- purpose: Cross-context behavioral advertising\n  text: Through these technologies, such partners\
  \ collect Internet or Other Electronic Network Activity Information\n    (including identifiers such as IP address, device identifiers, and cookie identifiers) to show you Kotoba advertisements\n    on other websites and applications based on your interactions with our Website.\n- purpose: Analytics and security\n  text: We use this information to operate and maintain the Website and Services, monitor performance and errors\n    (including through tools such as Firebase and Sentry), analyze usage trends and engagement\nretention:\n- scope: Account and contact information, commercial information, communications data\n  period: Duration of account + 6 months after deletion\n  text: Account & Contact Information Duration of account + 6 months after deletion\n- scope: Internet/network activity logs\n  period: Up to 24 months from collection\n  text: Internet/Network Activity (log data, technical metadata, IP addresses) Up to 24 months from collection\n- scope: Raw Audio Data (non-enterprise)\n\
  \  period: Up to 12 months from last interaction with the Services for model training, unless you have opted out\n  text: 'Raw Audio Data: Limited period as reasonably necessary to provide the Services; Up to 12 months from last\n    interaction with the Services for model training, unless you have opted out'\n- scope: Raw Audio Data (enterprise)\n  period: Not retained after processing is completed\n  text: 'Raw Audio Data: Retained only during transcription, translation, or related processing and not retained\n    after processing is completed'\n- scope: Audio Outputs\n  period: Not retained\n  text: Audio Outputs are generated and played back in real time only and are not retained by us for any user category.\n- scope: De-identified/aggregated data\n  period: Indefinitely\n  text: De-Identified/ Aggregated Data Indefinitely Not reasonably capable of being linked to you.\nresidency:\n- region: Japan\n  text: Personal information collected through the Services may be transferred to, stored,\
  \ and processed in Japan,\n    where our cloud infrastructure is located\ntransfers:\n- mechanism: other\n  text: By using the Services, you consent to such transfers.\nsubprocessors:\n  url: null\n  text: AI processing providers, including providers such as OpenAI, Google, and Microsoft\ndpa:\n  available: null\n  url: null\n  text: null\ndeletion:\n  route: Contact us as set forth in Section IX, or in-app settings for opt-out of model training\n  text: If you believe a child under 13 has provided us with personal information, please contact us as described\n    in Section IX so we can delete it.\nrights:\n- right: Access\n  text: The right to confirm whether we process your personal information and to access such personal information.\n- right: Correction\n  text: The right to request correction of inaccuracies in your personal information.\n- right: Deletion\n  text: The right to request deletion of your personal information.\n- right: Opt out of sale or sharing\n  text: The right to\
  \ opt out of the sale or sharing of personal information, as defined under applicable law.\n- right: Appeal\n  text: The right to appeal a decision regarding your privacy rights request, where required by applicable law.\n- right: Non-discrimination\n  text: The right not to receive discriminatory treatment for exercising your privacy rights.\nsale_or_sharing:\n  stance: conditional\n  text: We do not sell personal information for monetary compensation.\n"
source_yaml_url: https://artifacts.apis.io/kotoba/privacy/kotoba-privacy-policy.yml
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
- sale_or_sharing
summary_line: 31 quoted statements, read from Kotoba's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Voice
- Speech Recognition
- Speech-to-Text
- Text-to-Speech
- Translation
- Real-Time
- WebSocket
- Audio
- Transcription
---
