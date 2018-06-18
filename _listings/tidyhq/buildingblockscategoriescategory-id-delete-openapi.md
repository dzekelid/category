---
swagger: "2.0"
x-collection-name: TidyHQ
x-complete: 0
info:
  title: API Evangelist Building Block API Delete Category for Building Block
  description: delete a building block category
  contact:
    name: Kin Lane
    url: http://kinlane.com
    email: info@kinlane.com
  version: v1
host: buildingblock.api.kinlane.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /buildingblocks/bycategory/{category}:
    get:
      summary: Get Building Blocks by Category
      description: building blocks by category
      operationId: getBuildingBlocksByCategory
      x-api-path-slug: buildingblocksbycategorycategory-get
      parameters:
      - in: query
        name: appid
        description: your appid for accessing the building block
      - in: query
        name: appkey
        description: your appkey for accessing the building block
      - in: path
        name: category
        description: the building block category to filter by
      responses:
        200:
          description: OK
      tags:
      - Building
      - Blocks
      - By
      - Category
  /buildingblocks/categories/:
    post:
      summary: Add Category for Building Block
      description: add building block category
      operationId: addBuildingBlockCategory
      x-api-path-slug: buildingblockscategories-post
      parameters:
      - in: formData
        name: appid
        description: your appid for accessing the building block
      - in: formData
        name: appkey
        description: your appkey for accessing the building block
      - in: formData
        name: name
        description: a name for the url
      - in: formData
        name: type
        description: type of url
      - in: formData
        name: url
        description: the url
      responses:
        200:
          description: OK
      tags:
      - CategoryBuilding
      - Block
  /buildingblocks/categories/{category_id}:
    delete:
      summary: Delete Category for Building Block
      description: delete a building block category
      operationId: deleteBuildingBlockCategory
      x-api-path-slug: buildingblockscategoriescategory-id-delete
      parameters:
      - in: query
        name: appid
        description: your appid for accessing the building block
      - in: query
        name: appkey
        description: your appkey for accessing the building block
      - in: path
        name: category_id
        description: id for the building block
      responses:
        200:
          description: OK
      tags:
      - CategoryBuilding
      - Block
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