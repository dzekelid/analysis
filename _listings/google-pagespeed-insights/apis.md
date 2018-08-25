---
name: Google PageSpeed Insights
x-slug: google-pagespeed-insights
description: Page Speed Insights measures the performance of a page for mobile devices
  and desktop devices. It fetches the url twice, once with a mobile user-agent, and
  once with a desktop-user agent. The PageSpeed Score ranges from 0 to 100 points.
  A higher score is better and a score of 85 or above indicates that the page is performing
  well. Please note that PageSpeed Insights is being continually improved and so the
  score will change as we add new rules or improve our analysis.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/54de5c09d56ec853cc9310e1.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Analysis
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-pagespeed-insights/apis.md
specificationVersion: "0.14"
apis:
- name: Google PageSpeed Insights API
  x-api-slug: google-pagespeed-insights-api
  description: analyzes-the-performance-of-a-web-page-and-provides-tailored-suggestions-to-make-that-page-faster-
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/54de5c09d56ec853cc9310e1.png
  humanURL: https://developers.google.com/speed/docs/insights/about
  baseURL: ://www.googleapis.com//pagespeedonline/v2
  tags: Performance, Websites, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-pagespeed-insights/runpagespeed-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-pagespeed-insights/runpagespeed-get-openapi.md
- name: Google PageSpeed Insights API
  x-api-slug: google-pagespeed-insights-api
  description: Page Speed Insights measures the performance of a page for mobile devices
    and desktop devices. It fetches the url twice, once with a mobile user-agent,
    and once with a desktop-user agent. The PageSpeed Score ranges from 0 to 100 points.
    A higher score is better and a score of 85 or above indicates that the page is
    performing well. Please note that PageSpeed Insights is being continually improved
    and so the score will change as we add new rules or improve our analysis.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/54de5c09d56ec853cc9310e1.png
  humanURL: https://developers.google.com/speed/docs/insights/about
  baseURL: ://www.googleapis.com//pagespeedonline/v2
  tags: Analysis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/analysis/master/_listings/google-pagespeed-insights/openapi.md
x-common:
- type: x-api-gallery
  url: http://google.oauth2.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.pagespeed.insights.stack.network
- type: x-change-logs
  url: https://developers.google.com/speed/docs/insights/release_notes
- type: x-getting-started
  url: https://developers.google.com/speed/docs/insights/v2/getting-started
- type: x-website
  url: https://developers.google.com/speed/docs/insights/about
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---