---
swagger: "2.0"
x-collection-name: Google Books
x-complete: 1
info:
  title: Books
  description: searches-for-books-and-manages-your-google-books-library-
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
---