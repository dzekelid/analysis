---
name: Google Cloud Prediction
x-slug: google-cloud-prediction
description: Google Cloud Prediction API provides a RESTful API to build Machine Learning
  models. Predictions cloud-based machine learning tools can help analyze your data
  to add various features to your applications, such as customer sentiment analysis,
  spam detection, recommendation systems, and more.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Analysis
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-cloud-prediction/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud Prediction API Analyze
  x-api-slug: google-cloud-prediction-api
  description: Get analysis of the model and the data the model was trained on.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects//{project}/trainedmodels/{id}/analyze
  tags: Model,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-cloud-prediction/projecttrainedmodelsidanalyze-get-openapi.md
- name: Google Cloud Prediction API
  x-api-slug: google-cloud-prediction-api
  description: Google Cloud Prediction API provides a RESTful API to build Machine
    Learning models. Predictions cloud-based machine learning tools can help analyze
    your data to add various features to your applications, such as customer sentiment
    analysis, spam detection, recommendation systems, and more.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-prediction-api-500x500.jpg
  humanURL: https://cloud.google.com/prediction/docs/developer-guide
  baseURL: ://www.googleapis.com//prediction/v1.6/projects
  tags: Analysis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-cloud-prediction/openapi.md
x-common:
- type: x-bugs
  url: https://cloud.google.com/prediction/docs/feedback_and_discuss
- type: x-change-log
  url: https://cloud.google.com/prediction/docs/release-notes
- type: x-code
  url: https://cloud.google.com/prediction/docs/libraries
- type: x-website
  url: https://cloud.google.com/prediction/docs/developer-guide
- type: x-documentation
  url: https://cloud.google.com/prediction/docs/
- type: x-faq
  url: https://cloud.google.com/prediction/docs/faq
- type: x-forum
  url: https://cloud.google.com/prediction/docs/general_discussion_forum
- type: x-getting-started
  url: https://cloud.google.com/prediction/docs/quickstart
- type: x-glossary
  url: https://cloud.google.com/prediction/docs/glossary
- type: x-pricing
  url: https://cloud.google.com/prediction/pricing
- type: x-sla
  url: https://cloud.google.com/prediction/sla
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---