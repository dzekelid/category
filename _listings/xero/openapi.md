---
swagger: "2.0"
x-collection-name: Xero
x-complete: 1
info:
  title: Accounting
  description: -introductionthe-xero-accounting-api-is-a-restful-web-service-and-uses-the-oauth-v1-0a-protocol-to-authenticate-3rd-party-applications--the-accounting-api-exposes-accounting-and-related-functions-of-the-main-xero-application-and-can-be-used-for-a-variety-of-purposes-such-as-creating-transactions-like-invoices-and-credit-notes-right-through-to-extracting-accounting-data-via-our-reports-endpoint-
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
    get:
      summary: Get Tracking Categories Trackingcategory
      description: Get trackingcategories trackingcategory.
      operationId: getTrackingcategoriesTrackingcategory
      x-api-path-slug: trackingcategoriestrackingcategoryid-get
      parameters:
      - in: path
        name: TrackingCategoryID
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
    post:
      summary: Post Tracking Categories Trackingcategory
      description: Post trackingcategories trackingcategory.
      operationId: postTrackingcategoriesTrackingcategory
      x-api-path-slug: trackingcategoriestrackingcategoryid-post
      parameters:
      - in: body
        name: TrackingCategories
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: TrackingCategoryID
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
    x-related-model:
      summary: X-related-model Tracking Categories Trackingcategory
      description: X-related-model trackingcategories trackingcategory.
      operationId: x-related-modelTrackingcategoriesTrackingcategory
      x-api-path-slug: trackingcategoriestrackingcategoryid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
  /TrackingCategories/{TrackingCategoryID}/Options:
    put:
      summary: Put Tracking Categories Trackingcategory Options
      description: Put trackingcategories trackingcategory options.
      operationId: putTrackingcategoriesTrackingcategoryOptions
      x-api-path-slug: trackingcategoriestrackingcategoryidoptions-put
      parameters:
      - in: query
        name: No Name
      - in: path
        name: TrackingCategoryID
      - in: body
        name: TrackingOptions
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
      - Options
    x-related-model:
      summary: X-related-model Tracking Categories Trackingcategory Options
      description: X-related-model trackingcategories trackingcategory options.
      operationId: x-related-modelTrackingcategoriesTrackingcategoryOptions
      x-api-path-slug: trackingcategoriestrackingcategoryidoptions-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
      - Options
  /TrackingCategories/{TrackingCategoryID}/Options/{TrackingOptionID}:
    delete:
      summary: Delete Tracking Categories Trackingcategory Options Trackingoption
      description: Delete trackingcategories trackingcategory options trackingoption.
      operationId: deleteTrackingcategoriesTrackingcategoryOptionsTrackingoption
      x-api-path-slug: trackingcategoriestrackingcategoryidoptionstrackingoptionid-delete
      parameters:
      - in: path
        name: TrackingCategoryID
      - in: path
        name: TrackingOptionID
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
      - Options
      - TrackingOptionID
    x-related-model:
      summary: X-related-model Tracking Categories Trackingcategory Options Trackingoption
      description: X-related-model trackingcategories trackingcategory options trackingoption.
      operationId: x-related-modelTrackingcategoriesTrackingcategoryOptionsTrackingoption
      x-api-path-slug: trackingcategoriestrackingcategoryidoptionstrackingoptionid-xrelatedmodel
      responses:
        200:
          description: OK
      tags:
      - TrackingCategories
      - TrackingCategoryID
      - Options
      - TrackingOptionID
---