---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 0
info:
  title: Google Books API List Categoies
  description: List categories for onboarding experience.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /books/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /onboarding/listCategories:
    get:
      summary: List Categoies
      description: List categories for onboarding experience.
      operationId: books.onboarding.listCategories
      x-api-path-slug: onboardinglistcategories-get
      parameters:
      - in: query
        name: locale
        description: ISO-639-1 language and ISO-3166-1 country code
      responses:
        200:
          description: OK
      tags:
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