---
name: Datumbox
x-slug: datumbox
description: 'Datumbox offers a powerful open-source Machine Learning Framework written
  in Java. Discover today its large collection of algorithms, models, statistical
  tests and tools. The Datumbox API offers a large number of off-the-shelf Classifiers
  and Natural Language Processing services which can be used in a broad spectrum of
  applications including: Sentiment Analysis, Topic Classification, Language Detection,
  Subjectivity Analysis, Spam Detection, Reading Assessment, Keyword and Text Extraction
  and more. All services are accessible via our powerful REST API which allows you
  to develop your own smart Applications in no time.'
image: http://www.datumbox.com/img/logo.png
x-kinRank: "9"
x-alexaRank: ""
tags: Analysis
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/apis.md
specificationVersion: "0.14"
apis:
- name: Datumbox Identifies the Sentiment of the Document
  x-api-slug: datumbox
  description: The Sentiment Analysis function classifies documents as positive, negative
    or neutral (lack of sentiment) depending on whether they express a positive, negative
    or neutral opinion.
  image: http://www.datumbox.com/img/logo.png
  humanURL: http://www.datumbox.com/
  baseURL: https://api.datumbox.com/1.0///SentimentAnalysis.json
  tags: Sentiment,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/sentimentanalysisjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/sentimentanalysisjson-post-openapi.md
- name: Datumbox Classifies Document as Subjective or Objective
  x-api-slug: datumbox
  description: The Subjectivity Analysis function categorizes documents as subjective
    or objective based on their writing style. Texts that express personal opinions
    are labeled as subjective and the others as objective.
  image: http://www.datumbox.com/img/logo.png
  humanURL: http://www.datumbox.com/
  baseURL: https://api.datumbox.com/1.0///SubjectivityAnalysis.json
  tags: Subjectivity,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/subjectivityanalysisjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/subjectivityanalysisjson-post-openapi.md
- name: Datumbox Identifies the Sentiment of Twitter Messages
  x-api-slug: datumbox
  description: The Twitter Sentiment Analysis function allows you to perform Sentiment
    Analysis on Twitter. It classifies the tweets as positive, negative or neutral
    depending on their context.
  image: http://www.datumbox.com/img/logo.png
  humanURL: http://www.datumbox.com/
  baseURL: https://api.datumbox.com/1.0///TwitterSentimentAnalysis.json
  tags: Twitter,Sentiment,Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/twittersentimentanalysisjson-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/twittersentimentanalysisjson-post-openapi.md
- name: Datumbox
  x-api-slug: datumbox
  description: 'Datumbox offers a powerful open-source Machine Learning Framework
    written in Java. Discover today its large collection of algorithms, models, statistical
    tests and tools. The Datumbox API offers a large number of off-the-shelf Classifiers
    and Natural Language Processing services which can be used in a broad spectrum
    of applications including: Sentiment Analysis, Topic Classification, Language
    Detection, Subjectivity Analysis, Spam Detection, Reading Assessment, Keyword
    and Text Extraction and more. All services are accessible via our powerful REST
    API which allows you to develop your own smart Applications in no time.'
  image: http://www.datumbox.com/img/logo.png
  humanURL: http://www.datumbox.com/
  baseURL: https://api.datumbox.com/1.0/
  tags: Analysis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/datumbox/openapi.md
x-common:
- type: x-apijson--authoritative
  url: http://apis.io/apisdef/legacy/datumbox.json
- type: x-blog
  url: http://blog.datumbox.com/
- type: x-blog-rss
  url: http://feeds.feedburner.com/Datumbox
- type: x-contact-form
  url: http://www.datumbox.com/contact/
- type: x-twitter
  url: https://twitter.com/datumbox
- type: x-developer
  url: http://www.datumbox.com/machine-learning-api/
- type: x-documentation
  url: http://www.datumbox.com/api-sandbox/
- type: x-email
  url: info@datumbox.com
- type: x-facebook
  url: https://www.facebook.com/Datumbox
- type: x-github
  url: https://github.com/datumbox
- type: x-google-plus
  url: https://plus.google.com/105921437813621882157/posts
- type: x-privacy
  url: http://www.datumbox.com/privacy-policy/
- type: x-terms-of-service
  url: http://www.datumbox.com/terms-of-use/
- type: x-website
  url: http://www.datumbox.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---