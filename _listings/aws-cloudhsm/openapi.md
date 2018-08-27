swagger: "2.0"
x-collection-name: AWS CloudHSM
x-complete: 1
info:
  title: AWS CloudHSM API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=ListLunaClients:
    get:
      summary: List Luna Clients
      description: Lists all of the clients.
      operationId: listLunaClients
      x-api-path-slug: actionlistlunaclients-get
      parameters:
      - in: query
        name: NextToken
        description: The NextToken value from a previous call to ListLunaClients
        type: string
      responses:
        200:
          description: OK
      tags:
      - Luna Clients