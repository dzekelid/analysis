---
swagger: "2.0"
x-collection-name: SAP
x-complete: 0
info:
  title: SAP Manufacturing Network Partner APIs Retrieves a parts analysis worklist
  description: "Retrieves a parts analysis worklist.  \nThe analysis is made to identify
    parts that are suitable for additive manufacturing."
  version: 1.0.0
host: hostname
basePath: /dim/api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /partsAnalysis/worklists/{worklistId}:
    get:
      summary: Retrieves a parts analysis worklist
      description: "Retrieves a parts analysis worklist.  \nThe analysis is made to
        identify parts that are suitable for additive manufacturing."
      operationId: retrieves-a-parts-analysis-worklist--the-analysis-is-made-to-identify-parts-that-are-suitable-for-ad
      x-api-path-slug: partsanalysisworklistsworklistid-get
      parameters:
      - in: query
        name: $format
        description: Specifies the response format
      - in: path
        name: worklistId
        description: The UUID for a published worklist
      responses:
        200:
          description: Successful response
      tags:
      - Retrieves
      - Parts
      - Analysis
      - Worklist
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