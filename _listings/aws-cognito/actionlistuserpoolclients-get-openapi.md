---
swagger: "2.0"
x-collection-name: AWS Cognito
x-complete: 0
info:
  title: AWS Cognito API List User Pool Clients
  version: 1.0.0
  description: Lists the clients that have been created for the specified user pool.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListUserPoolClients:
    get:
      summary: List User Pool Clients
      description: Lists the clients that have been created for the specified user
        pool.
      operationId: listUserPoolClients
      x-api-path-slug: actionlistuserpoolclients-get
      parameters:
      - in: query
        name: MaxResults
        description: The maximum number of results you want the request to return
          when listing the user            pool clients
        type: string
      - in: query
        name: NextToken
        description: An identifier that was returned from the previous call to this
          operation, which can            be used to return the next set of items
          in the list
        type: string
      - in: query
        name: UserPoolId
        description: The user pool ID for the user pool where you want to list user
          pool            clients
        type: string
      responses:
        200:
          description: OK
      tags:
      - user Pool Clients
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