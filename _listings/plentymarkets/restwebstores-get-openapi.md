---
swagger: "2.0"
x-collection-name: Plentymarkets
x-complete: 0
info:
  title: Plentymarkets List clients (stores)
  description: List clients (stores).
  contact:
    name: plentymarkets
    url: https://forum.plentymarkets.com/c/rest-api
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /rest/items/sales_prices/{id}/online_stores:
    get:
      summary: List activated clients (stores)
      description: Lists all activated clients (stores) for a sales price. The ID
        of the sales price must be specified.
      operationId: getRestItemsSalesPricesOnlineStores
      x-api-path-slug: restitemssales-pricesidonline-stores-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - List
      - Activated
      - Clients
      - (stores)
  /rest/items/{id}/variations/{variationId}/variation_clients:
    get:
      summary: List clients linked to a variation
      description: Lists all clients (stores) linked to a variation. The ID of the
        variation must be specified.
      operationId: getRestItemsVariationsVariationVariationClients
      x-api-path-slug: restitemsidvariationsvariationidvariation-clients-get
      parameters:
      - in: path
        name: id
      - in: path
        name: variationId
      responses:
        200:
          description: OK
      tags:
      - List
      - Clients
      - Linked
      - To
      - Variation
  /rest/webstores:
    get:
      summary: List clients (stores)
      description: List clients (stores).
      operationId: getRestWebstores
      x-api-path-slug: restwebstores-get
      responses:
        200:
          description: OK
      tags:
      - List
      - Clients
      - (stores)
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