---
swagger: "2.0"
x-collection-name: Google Adsense
x-complete: 0
info:
  title: Google Adsense API Get Ad Client
  version: 1.0.0
  description: Get information about one of the ad clients in the Host AdSense account.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /accounts/{accountId}/adclients:
    get:
      summary: Get Ad Clients
      description: List all hosted ad clients in the specified hosted account.
      operationId: adsensehost.accounts.adclients.list
      x-api-path-slug: accountsaccountidadclients-get
      parameters:
      - in: path
        name: accountId
        description: Account for which to list ad clients
      - in: query
        name: maxResults
        description: The maximum number of ad clients to include in the response,
          used for paging
      - in: query
        name: pageToken
        description: A continuation token, used to page through ad clients
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Clients
  /accounts/{accountId}/adclients/{adClientId}:
    get:
      summary: Get Ad Client
      description: Get information about one of the ad clients in the specified publisher's
        AdSense account.
      operationId: adsensehost.accounts.adclients.get
      x-api-path-slug: accountsaccountidadclientsadclientid-get
      parameters:
      - in: path
        name: accountId
        description: Account which contains the ad client
      - in: path
        name: adClientId
        description: Ad client to get
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Clients
  /adclients:
    get:
      summary: Get Ad Clients
      description: List all host ad clients in this AdSense account.
      operationId: adsensehost.adclients.list
      x-api-path-slug: adclients-get
      parameters:
      - in: query
        name: maxResults
        description: The maximum number of ad clients to include in the response,
          used for paging
      - in: query
        name: pageToken
        description: A continuation token, used to page through ad clients
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Clients
  /adclients/{adClientId}:
    get:
      summary: Get Ad Client
      description: Get information about one of the ad clients in the Host AdSense
        account.
      operationId: adsensehost.adclients.get
      x-api-path-slug: adclientsadclientid-get
      parameters:
      - in: path
        name: adClientId
        description: Ad client to get
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Clients
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---