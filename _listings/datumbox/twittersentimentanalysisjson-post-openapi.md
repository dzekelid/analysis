---
swagger: "2.0"
x-collection-name: Datumbox
x-complete: 0
info:
  title: Datumbox Identifies the Sentiment of Twitter Messages
  description: The Twitter Sentiment Analysis function allows you to perform Sentiment
    Analysis on Twitter. It classifies the tweets as positive, negative or neutral
    depending on their context.
  version: 1.0.0
host: api.datumbox.com
basePath: 1.0/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /SentimentAnalysis.json:
    post:
      summary: Identifies the Sentiment of the Document
      description: The Sentiment Analysis function classifies documents as positive,
        negative or neutral (lack of sentiment) depending on whether they express
        a positive, negative or neutral opinion.
      operationId: SentimentAnalysis
      x-api-path-slug: sentimentanalysisjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Sentiment
      - Analysis
  /SubjectivityAnalysis.json:
    post:
      summary: Classifies Document as Subjective or Objective
      description: The Subjectivity Analysis function categorizes documents as subjective
        or objective based on their writing style. Texts that express personal opinions
        are labeled as subjective and the others as objective.
      operationId: SubjectivityAnalysis
      x-api-path-slug: subjectivityanalysisjson-post
      parameters:
      - in: formData
        name: text
        description: The text that you want to analyze
      responses:
        200:
          description: OK
      tags:
      - Subjectivity
      - Analysis
  /TwitterSentimentAnalysis.json:
    post:
      summary: Identifies the Sentiment of Twitter Messages
      description: The Twitter Sentiment Analysis function allows you to perform Sentiment
        Analysis on Twitter. It classifies the tweets as positive, negative or neutral
        depending on their context.
      operationId: TwitterSentimentAnalysis
      x-api-path-slug: twittersentimentanalysisjson-post
      parameters:
      - in: formData
        name: text
        description: The text of the tweet that we evaluate
      responses:
        200:
          description: OK
      tags:
      - Twitter
      - Sentiment
      - Analysis
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