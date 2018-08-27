swagger: "2.0"
x-collection-name: Google Cloud Prediction
x-complete: 1
info:
  title: Prediction
  description: lets-you-access-a-cloud-hosted-machine-learning-service-that-makes-it-easy-to-build-smart-apps
  contact:
    name: Google
    url: https://google.com
  version: v1.6
host: www.googleapis.com
basePath: /prediction/v1.6/projects
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{project}/trainedmodels/{id}/analyze:
    get:
      summary: Analyze
      description: Get analysis of the model and the data the model was trained on.
      operationId: prediction.trainedmodels.analyze
      x-api-path-slug: projecttrainedmodelsidanalyze-get
      parameters:
      - in: path
        name: id
        description: The unique name for the predictive model
      - in: path
        name: project
        description: The project associated with the model
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Model
      - Analysis