swagger: "2.0"
x-collection-name: SAP
x-complete: 1
info:
  title: SAP Translation Hub
  description: to-provide-users-of-software-in-a-global-market-with-texts-in-their-own-language-translations-are-required--sap-translation-hub-enables-you-to-draw-on-saps-translation-experience-across-multiple-products-and-languages-to-propose-translations-for-short-texts-
  contact:
    name: SAP Translation Hub team
    email: translationhub@sap.com
  version: 1.0.0
host: sandbox.api.sap.com
basePath: /translationhub/api/v1
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