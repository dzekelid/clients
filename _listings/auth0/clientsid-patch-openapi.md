---
swagger: "2.0"
x-collection-name: Auth0
x-complete: 0
info:
  title: Auth0 API Patch Clients
  description: Patch clients.
  version: 1.0.0
host: login.auth0.com
basePath: api/v2/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /clients:
    get:
      summary: Get Clients
      description: Get clients.
      operationId: getClients
      x-api-path-slug: clients-get
      parameters:
      - in: query
        name: exclude_fields
        description: true if the fields specified are to be excluded from the result,
          false otherwise
      - in: query
        name: fields
        description: A comma separated list of fields to include or exclude (depending
          on exclude_fields) from the result
      responses:
        200:
          description: OK
      tags:
      - Clients
    post:
      summary: Post Clients
      description: Post clients.
      operationId: postClients
      x-api-path-slug: clients-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Clients
  /clients/{id}:
    delete:
      summary: Delete Clients
      description: Delete clients.
      operationId: deleteClients
      x-api-path-slug: clientsid-delete
      parameters:
      - in: path
        name: id
        description: The client_id of the client to delete
      responses:
        200:
          description: OK
      tags:
      - Clients
    get:
      summary: Get Clients
      description: Get clients.
      operationId: getClients
      x-api-path-slug: clientsid-get
      parameters:
      - in: query
        name: exclude_fields
        description: true if the fields specified are to be excluded from the result,
          false otherwise
      - in: query
        name: fields
        description: A comma separated list of fields to include or exclude (depending
          on exclude_fields) from the result
      - in: path
        name: id
        description: The client_id of the client to retrieve
      responses:
        200:
          description: OK
      tags:
      - Clients
    patch:
      summary: Patch Clients
      description: Patch clients.
      operationId: patchClients
      x-api-path-slug: clientsid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: id
        description: The client_id of the client to retrieve
      responses:
        200:
          description: OK
      tags:
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