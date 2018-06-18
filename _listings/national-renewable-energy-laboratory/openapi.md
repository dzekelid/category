---
swagger: "2.0"
x-collection-name: National Renewable Energy Laboratory
x-complete: 1
info:
  title: Transportation Laws and Incentives
  description: query-our-database-of-state-and-federal-laws-and-incentives-for-alternative-fuels
  version: 0.1.0
host: developer.nrel.gov
basePath: /api/transportation-incentives-laws
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /v1/category-list.{output_format}:
    get:
      summary: Return the law categories for a given category type.
      description: Return the law categories for a given category type..
      operationId: v1.category_list.output_format.get
      x-api-path-slug: v1categorylist-output-format-get
      parameters:
      - in: path
        name: output_format
        description: Response format
      - in: query
        name: type
        description: Search by the category type
      responses:
        200:
          description: OK
      tags:
      - Return
      - Law
      - Categoriesa
      - Given
      - Category
      - Type
---