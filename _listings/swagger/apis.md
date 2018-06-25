---
name: Swagger
x-slug: swagger
description: Swagger aides in development across the entire API lifecycle, from design
  and documentation, to test and deployment. Try it today!
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
x-kinRank: "8"
x-alexaRank: "23531"
tags: Clients
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/apis.md
specificationVersion: "0.14"
apis:
- name: Swagger Generator Gets languages supported by the client generator
  x-api-slug: swagger-generator
  description: Gets languages supported by the client generator.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api//gen/clients
  tags: Generate,Clients
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/genclients-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/genclients-get-openapi.md
- name: Swagger Generator Returns options for a client library
  x-api-slug: swagger-generator
  description: Returns options for a client library.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api//gen/clients/{language}
  tags: Generate,Clients,Language
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/genclientslanguage-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/genclientslanguage-get-openapi.md
- name: Swagger Generator Generates a client library
  x-api-slug: swagger-generator
  description: Accepts a `GeneratorInput` options map for spec location and generation
    options
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api//gen/clients/{language}
  tags: Generate,Clients,Language
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/genclientslanguage-post-openapi.md
- name: Swagger Generator
  x-api-slug: swagger-generator
  description: Swagger aides in development across the entire API lifecycle, from
    design and documentation, to test and deployment. Try it today!
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1684-swagger.jpg
  humanURL: http://swagger.io/
  baseURL: https://generator.swagger.io//api
  tags: Clients
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/clients/master/_listings/swagger/openapi.md
x-common:
- type: x-blog
  url: http://swagger.io/blog/
- type: x-crunchbase
  url: https://crunchbase.com/organization/swagger
- type: x-github
  url: https://github.com/swagger-api
- type: x-twitter
  url: https://twitter.com/SwaggerApi
- type: x-website
  url: http://swagger.io/
- type: x-website
  url: http://swagger.io
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---