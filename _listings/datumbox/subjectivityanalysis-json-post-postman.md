{
  "info": {
    "name": "Datumbox Classifies Document as Subjective or Objective",
    "_postman_id": "8bc144d1-c19a-4351-9c01-770d19c6fcb0",
    "description": "The Subjectivity Analysis function categorizes documents as subjective or objective based on their writing style. Texts that express personal opinions are labeled as subjective and the others as objective.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Sentiment",
      "item": [
        {
          "id": "0a4d3363-184c-4565-a30d-321fc54b189a",
          "name": "SentimentAnalysis",
          "request": {
            "url": "http://api.datumbox.com/1.0/SentimentAnalysis.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Sentiment Analysis function classifies documents as positive, negative or neutral (lack of sentiment) depending on whether they express a positive, negative or neutral opinion."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b4bf80c-a8d3-4b04-a7bc-bebcc34c9bb1"
            }
          ]
        }
      ]
    },
    {
      "name": "Subjectivity",
      "item": [
        {
          "id": "e3e2ade1-e862-4019-b6c3-59f74dc55c7f",
          "name": "SubjectivityAnalysis",
          "request": {
            "url": "http://api.datumbox.com/1.0/SubjectivityAnalysis.json",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "text",
                  "value": "{}",
                  "disabled": false,
                  "description": "The text that you want to analyze"
                }
              ]
            },
            "description": "The Subjectivity Analysis function categorizes documents as subjective or objective based on their writing style. Texts that express personal opinions are labeled as subjective and the others as objective."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e773903-e903-4a2d-b152-99cbe22bf7ca"
            }
          ]
        }
      ]
    }
  ]
}