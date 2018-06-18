---
name: Paylocity
x-slug: paylocity
description: ""
image: ""
x-kinRank: "7"
x-alexaRank: "0"
tags: Category
created: "2018-06-17"
modified: "2018-06-17"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/paylocity/apis.md
specificationVersion: "0.14"
apis:
- name: Paylocity Get All Custom Fields
  x-api-slug: paylocity
  description: Get All Custom Fields for the selected company
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api//v2/companies/{companyId}/customfields/{category}
  tags: V2,Companies,CompanyId,Customfields,Category
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/paylocity/v2companiescompanyidcustomfieldscategory-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/paylocity/v2companiescompanyidcustomfieldscategory-get-openapi.md
- name: Paylocity
  x-api-slug: paylocity
  description: ""
  image: ""
  humanURL: http://paylocity.com
  baseURL: https://api.paylocity.com//api
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/paylocity/openapi.md
x-common:
- type: x-blog
  url: https://www.paylocity.com/resources/blog/
- type: x-github
  url: https://github.com/Paylocity
- type: x-integrations
  url: https://www.paylocity.com/partnerships/integrations/
- type: x-twitter
  url: https://twitter.com/Paylocity
- type: x-website
  url: http://paylocity.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---