---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Capturespace Capturespace Action Clientupdates
  description: Returns latest version and URL
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/capturespace_capturespace/action/clientUpdates:
    get:
      summary: Get Service Capturespace Capturespace Action Clientupdates
      description: Returns latest version and URL
      operationId: captureSpace.clientUpdates
      x-api-path-slug: servicecapturespace-capturespaceactionclientupdates-get
      parameters:
      - in: query
        name: hashAlgorithm
        description: 'Enum Type: `KalturaCaptureSpaceHashAlgorithm`'
      - in: query
        name: No Name
      - in: query
        name: os
      - in: query
        name: version
      responses:
        200:
          description: OK
      tags:
      - Service
      - Capturespace
      - Capturespace
      - Action
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