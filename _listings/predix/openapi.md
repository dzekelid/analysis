swagger: "2.0"
x-collection-name: Predix
x-complete: 1
info:
  title: VIEWS
  version: 1.0.0
host: thetaray-anomaly-service.run.aws-usw02-pr.ice.predix.io
basePath: /v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/proxy/analyses:
    get:
      summary: Analyses List
      description: Get list of Analyses
      operationId: retrieveNewUsingGET
      x-api-path-slug: v1proxyanalyses-get
      responses:
        200:
          description: OK
      tags:
      - Proxy
      - Analyses