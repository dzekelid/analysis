---
name: Pingdom
x-slug: pingdom
description: Pingdom is a service that tracks the uptime, downtime, and performance
  of websites. When problems happen with a site that Pingdom monitors, it immediately
  alerts the owner so the problem can be taken care of. Pingdom monitors websites
  from multiple locations globally so that it can distinguish genuine downtime from
  routing and access problems.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/456_logo.png
x-kinRank: "7"
x-alexaRank: ""
tags: Analysis
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/pingdom/apis.md
specificationVersion: "0.14"
apis:
- name: Analysis API Get Root Cause Analysis Results List
  x-api-slug: analysis-api
  description: Returns a list of the latest root cause analysis results for a specified
    check.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/456_logo.png
  humanURL: http://www.pingdom.com
  baseURL: |-
    :////
        /api/{version}/analysis/{checkid}
  tags: Analysis
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/pingdom/apiversionanalysischeckid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/pingdom/apiversionanalysischeckid-get-openapi.md
- name: Analysis API
  x-api-slug: analysis-api
  description: Pingdom is a service that tracks the uptime, downtime, and performance
    of websites. When problems happen with a site that Pingdom monitors, it immediately
    alerts the owner so the problem can be taken care of. Pingdom monitors websites
    from multiple locations globally so that it can distinguish genuine downtime from
    routing and access problems.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/456_logo.png
  humanURL: http://www.pingdom.com
  baseURL: :///
  tags: Analysis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/pingdom/openapi.md
x-common:
- type: x-base
  url: https://api.pingdom.com
- type: x-blog
  url: http://royal.pingdom.com/
- type: x-blog-rss
  url: http://royal.pingdom.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/pingdom
- type: x-developer
  url: https://www.pingdom.com/features/api/
- type: x-github
  url: https://github.com/Pingdom
- type: x-pricing
  url: https://www.pingdom.com/pricing
- type: x-twitter
  url: https://twitter.com/#!/pingdom
- type: x-website
  url: http://www.pingdom.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---