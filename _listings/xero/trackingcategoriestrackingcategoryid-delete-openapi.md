---
swagger: "2.0"
x-collection-name: Xero
x-complete: 0
info:
  title: Clarity Accounting Delete Tracking Categories Trackingcategory
  description: Delete trackingcategories trackingcategory.
  contact:
    name: Xero Developer Team
    url: https://developer.xero.com
  version: "2.0"
host: api.xero.com
basePath: /api.xro/2.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /TrackingCategories/{TrackingCategoryID}:
    delete:
      summary: Delete Tracking Categories Trackingcategory
      description: Delete trackingcategories trackingcategory.
      operationId: deleteTrackingcategoriesTrackingcategory
      x-api-path-slug: trackingcategoriestrackingcategoryid-delete
      parameters:
      - in: path
        name: TrackingCategoryID
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
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