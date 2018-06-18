---
swagger: "2.0"
x-collection-name: MySpace Developers
x-complete: 1
info:
  title: My Space
  description: create-apps-and-games-within-the-myspace-platform--monetize-through-advertising-and-virtual-goods-
  version: 1.0.0
host: api.myspace.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /1.0/mediaItems/{personId}/@videos/@supportedcategories/{categoryId}:
    get:
      summary: Get Mediaitems Personid Videos Supported Categories Categoryid
      description: Retrieves videos for Category.
      operationId: 1.0.mediaItems.personId._videos._supportedcategories.categoryId.get
      x-api-path-slug: 1-0mediaitemspersonidvideossupportedcategoriescategoryid-get
      parameters:
      - in: path
        name: categoryId
        description: Indicates the video category about which you want to retrieve
          data
      - in: query
        name: count
        description: Only returns the nearest multiple of 3 compared to the original
          value
      - in: query
        name: fields
        description: The following field names are supported
      - in: query
        name: format
        description: Determines the format of the response
      - in: query
        name: msPrivacyLevel
        description: MySpace specific field
      - in: path
        name: personId
        description: The persons identifier
      - in: query
        name: startIndex
        description: Indicates the index of the first item to retrieve from the query
          set
      responses:
        200:
          description: OK
      tags:
      - MediaItems
      - People
      - '@videos'
      - Supported
      - categories
      - CategoryId
---