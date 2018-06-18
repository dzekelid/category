---
swagger: "2.0"
x-collection-name: Google Doubleclick
x-complete: 0
info:
  title: Google Doubleclick API Update Content Category
  version: 1.0.0
  description: Updates an existing content category.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /userprofiles/{profileId}/contentCategories:
    get:
      summary: Get Content Categories
      description: Retrieves a list of content categories, possibly filtered. This
        method supports paging.
      operationId: dfareporting.contentCategories.list
      x-api-path-slug: userprofilesprofileidcontentcategories-get
      parameters:
      - in: query
        name: ids
        description: Select only content categories with these IDs
      - in: query
        name: maxResults
        description: Maximum number of results to return
      - in: query
        name: pageToken
        description: Value of the nextPageToken from the previous result page
      - in: path
        name: profileId
        description: User profile ID associated with this request
      - in: query
        name: searchString
        description: Allows searching for objects by name or ID
      - in: query
        name: sortField
        description: Field by which to sort the list
      - in: query
        name: sortOrder
        description: Order of sorted results, default is ASCENDING
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    patch:
      summary: Get Content Category
      description: Updates an existing content category. This method supports patch
        semantics.
      operationId: dfareporting.contentCategories.patch
      x-api-path-slug: userprofilesprofileidcontentcategories-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: id
        description: Content category ID
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    post:
      summary: Create Content Category
      description: Inserts a new content category.
      operationId: dfareporting.contentCategories.insert
      x-api-path-slug: userprofilesprofileidcontentcategories-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
    put:
      summary: Update Content Category
      description: Updates an existing content category.
      operationId: dfareporting.contentCategories.update
      x-api-path-slug: userprofilesprofileidcontentcategories-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: profileId
        description: User profile ID associated with this request
      responses:
        200:
          description: OK
      tags:
      - Advertising
      - Content Category
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