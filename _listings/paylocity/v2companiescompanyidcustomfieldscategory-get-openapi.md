---
swagger: "2.0"
x-collection-name: Paylocity
x-complete: 0
info:
  title: Paylocity Get All Custom Fields
  description: Get All Custom Fields for the selected company
  termsOfService: WebLink.OpenApiDoc.TermsOfService
  version: "2"
host: api.paylocity.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v2/companies/{companyId}/customfields/{category}:
    get:
      summary: Get All Custom Fields
      description: Get All Custom Fields for the selected company
      operationId: v2.companies.companyId.customfields.category.get
      x-api-path-slug: v2companiescompanyidcustomfieldscategory-get
      parameters:
      - in: header
        name: Authorization
        description: Bearer + JWT
      - in: path
        name: category
        description: Custom Fields Category
      - in: path
        name: companyId
        description: Company Id
      responses:
        200:
          description: OK
      tags:
      - V2
      - Companies
      - CompanyId
      - Customfields
      - Category
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