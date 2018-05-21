---
name: Auth0
x-slug: auth0
description: Authenticate and authorize apps and APIs with any popular identity provider
  (enterprise, social or custom) running on any popular software stack on any popular
  device or cloud with Auth0s identity-as-a-service. Run from the Auth0 public cloud
  service, from a private cloud instance, or on-prem. Auth0 allows developers to replace
  painfully brittle in-app auth code with a call to an easy-to-use cloud service.
  Auth0 is particularly useful in eliminating the pain of dealing with a complex identity
  environment. Auth0 further allows IT to quickly set up SSO for any SAML-compliant
  3rd party app (SaaS or on-prem).
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Clients
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/apis.md
specificationVersion: "0.14"
apis:
- name: Auth0 API Get Clients
  x-api-slug: auth0-api
  description: Get clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com/api/v2///clients
  tags: Clients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/clients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/clients-get-openapi.md
- name: Auth0 API Post Clients
  x-api-slug: auth0-api
  description: Post clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com/api/v2///clients
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/clients-post-openapi.md
- name: Auth0 API Delete Clients
  x-api-slug: auth0-api
  description: Delete clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com/api/v2///clients/{id}
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/clientsid-delete-openapi.md
- name: Auth0 API Get Clients
  x-api-slug: auth0-api
  description: Get clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com/api/v2///clients/{id}
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/clientsid-get-openapi.md
- name: Auth0 API Patch Clients
  x-api-slug: auth0-api
  description: Patch clients.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com/api/v2///clients/{id}
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/clientsid-patch-openapi.md
- name: Auth0 API
  x-api-slug: auth0-api
  description: Authenticate and authorize apps and APIs with any popular identity
    provider (enterprise, social or custom) running on any popular software stack
    on any popular device or cloud with Auth0s identity-as-a-service. Run from the
    Auth0 public cloud service, from a private cloud instance, or on-prem. Auth0 allows
    developers to replace painfully brittle in-app auth code with a call to an easy-to-use
    cloud service. Auth0 is particularly useful in eliminating the pain of dealing
    with a complex identity environment. Auth0 further allows IT to quickly set up
    SSO for any SAML-compliant 3rd party app (SaaS or on-prem).
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/auth0-logo.png
  humanURL: https://auth0.com/
  baseURL: https://login.auth0.com/api/v2/
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/auth0/openapi.md
x-common:
- type: x-blog
  url: https://auth0.com/blog/
- type: x-blog-rss
  url: http://feeds.feedburner.com/auth0
- type: x-developer
  url: https://auth0.com/docs/apiv2
- type: x-github
  url: https://github.com/auth0
- type: x-pricing
  url: https://auth0.com/pricing
- type: x-service-level-agreement
  url: https://auth0.com/docs/sla
- type: x-twitter
  url: https://twitter.com/authzero
- type: x-website
  url: https://auth0.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---