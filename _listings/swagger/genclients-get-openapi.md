---
swagger: "2.0"
x-collection-name: Swagger
x-complete: 0
info:
  title: Swagger Generator Gets languages supported by the client generator
  description: Gets languages supported by the client generator.
  termsOfService: http://swagger.io/terms/
  contact:
    name: apiteam@swagger.io
  version: 2.2.3
host: generator.swagger.io
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /gen/clients:
    get:
      summary: Gets languages supported by the client generator
      description: Gets languages supported by the client generator.
      operationId: clientOptions
      x-api-path-slug: genclients-get
      responses:
        200:
          description: OK
      tags:
      - Generate
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