---
name: Bureau of Economic Analysis
x-slug: bureau-of-economic-analysis
description: Official Bureau of Economic Analysis website. Source of US economic statistics
  including national income and product accounts (NIPAs), gross domestic product (GDP)
  and related measures of national, regional, industry and international accounts.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11179-bureau-of-economic-analysis.jpg
x-kinRank: "9"
x-alexaRank: "64160"
tags: Bureau of Economic Analysis
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bureau-of-economic-analysis/master/_listings/bureau-of-economic-analysis/apis.md
specificationVersion: "0.14"
apis:
- name: The Bureau of Economic Analysis (BEA) API Economic Statistics
  x-api-slug: the-bureau-of-economic-analysis-bea-api
  description: Economic Statistics
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11179-bureau-of-economic-analysis.jpg
  humanURL: http://www.bea.gov
  baseURL: ://www.bea.gov/api/data?&UserID=Your-36CharacterKey&method=getparameterlist&datasetname=RegionalData&//api//data/
  tags: Economic,Statistics
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bureau-of-economic-analysis/master/_listings/bureau-of-economic-analysis/data-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bureau-of-economic-analysis/master/_listings/bureau-of-economic-analysis/data-get-openapi.md
- name: The Bureau of Economic Analysis (BEA) API
  x-api-slug: the-bureau-of-economic-analysis-bea-api
  description: The data API provides programmatic access to BEA published economic
    statistics using industry-standard methods and procedures. BEAs data API includes
    methods for retrieving a subset of our statistical data and the meta-data that
    describes it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/11179-bureau-of-economic-analysis.jpg
  humanURL: http://www.bea.gov
  baseURL: ://www.bea.gov/api/data?&UserID=Your-36CharacterKey&method=getparameterlist&datasetname=RegionalData&//api/
  tags: Bureau of Economic Analysis
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/bureau-of-economic-analysis/master/_listings/bureau-of-economic-analysis/openapi.md
x-common:
- type: x-base
  url: http://www.bea.gov/api/data/
- type: x-developer
  url: http://www.bea.gov/API/signup/index.cfm
- type: x-email
  url: privacy@bea.gov
- type: x-email
  url: webmaster@bea.gov
- type: x-email
  url: gianna.marrone@bea.gov
- type: x-email
  url: james.fetzer@bea.gov
- type: x-email
  url: william.jolliff@bea.gov
- type: x-email
  url: blaire.thomson@bea.gov
- type: x-email
  url: Ethan.Schein@bea.gov
- type: x-email
  url: chelsea.nelson@bea.gov
- type: x-email
  url: kevin.barefoot@bea.gov
- type: x-email
  url: peter.kuhbach@bea.gov
- type: x-email
  url: developers@bea.gov
- type: x-faq
  url: http://www.bea.gov/faq/index.cfm
- type: x-twitter
  url: https://twitter.com/BEA_News
- type: x-website
  url: http://www.bea.gov
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---