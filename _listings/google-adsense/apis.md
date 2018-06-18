---
name: Google Adsense
x-slug: google-adsense
description: AdSense is a free, simple way to make money online by placing ads on
  your website. Ads are reviewed to ensure they???re high quality and relevant to
  your content or audience, even when viewed on smartphones and tablets. The result?
  You can make more money online.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-adsense.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Clients
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/google-adsense/apis.md
specificationVersion: "0.14"
apis:
- name: Google Adsense API Get Ad Clients
  x-api-slug: google-adsense-api
  description: List all hosted ad clients in the specified hosted account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-adsense.png
  humanURL: https://developers.google.com/adsense/
  baseURL: https://///accounts/{accountId}/adclients
  tags: Advertising,Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/google-adsense/accountsaccountidadclients-get-openapi.md
- name: Google Adsense API Get Ad Client
  x-api-slug: google-adsense-api
  description: Get information about one of the ad clients in the specified publisher's
    AdSense account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-adsense.png
  humanURL: https://developers.google.com/adsense/
  baseURL: https://///accounts/{accountId}/adclients/{adClientId}
  tags: Advertising,Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/google-adsense/accountsaccountidadclientsadclientid-get-openapi.md
- name: Google Adsense API Get Ad Clients
  x-api-slug: google-adsense-api
  description: List all host ad clients in this AdSense account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-adsense.png
  humanURL: https://developers.google.com/adsense/
  baseURL: https://///adclients
  tags: Advertising,Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/google-adsense/adclients-get-openapi.md
- name: Google Adsense API Get Ad Client
  x-api-slug: google-adsense-api
  description: Get information about one of the ad clients in the Host AdSense account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-adsense.png
  humanURL: https://developers.google.com/adsense/
  baseURL: https://///adclients/{adClientId}
  tags: Advertising,Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/google-adsense/adclientsadclientid-get-openapi.md
- name: Google Adsense API
  x-api-slug: google-adsense-api
  description: AdSense is a free, simple way to make money online by placing ads on
    your website. Ads are reviewed to ensure they???re high quality and relevant to
    your content or audience, even when viewed on smartphones and tablets. The result?
    You can make more money online.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-adsense.png
  humanURL: https://developers.google.com/adsense/
  baseURL: https:///
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/google-adsense/openapi.md
x-common:
- type: x-blog
  url: http://googleadsdeveloper.blogspot.com/search/label/adsense_api
- type: x-blog-rss
  url: http://googleadsdeveloper.blogspot.com/feeds/posts/default?alt=rss
- type: x-developers
  url: https://developers.google.com/adsense/
- type: x-twitter
  url: https://twitter.com/AdSense
- type: x-website
  url: https://www.google.com/adsense/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---