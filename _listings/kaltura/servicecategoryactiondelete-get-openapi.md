---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Category Action Delete
  description: Delete a Category
  version: 3.3.0
host: www.kaltura.com
basePath: /api_v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /service/category/action/add:
    get:
      summary: Get Service Category Action Add
      description: Add new Category
      operationId: category.add
      x-api-path-slug: servicecategoryactionadd-get
      parameters:
      - in: query
        name: category[aggregationCategories]
        description: List of aggregation channels the category belongs to
      - in: query
        name: category[appearInList]
        description: 'Enum Type: `KalturaAppearInListType`If category will be returned
          for list action'
      - in: query
        name: category[contributionPolicy]
        description: 'Enum Type: `KalturaContributionPolicyType`who can assign entries
          to this category'
      - in: query
        name: category[defaultOrderBy]
        description: 'Enum Type: `KalturaCategoryOrderBy`Enable client side applications
          to define how to sort the category child categories'
      - in: query
        name: category[defaultPermissionLevel]
        description: 'Enum Type: `KalturaCategoryUserPermissionLevel`Default permissionLevel
          for new users'
      - in: query
        name: category[description]
        description: Category description
      - in: query
        name: category[inheritanceType]
        description: 'Enum Type: `KalturaInheritanceType`If Category members are inherited
          from parent category or set manualy'
      - in: query
        name: category[isAggregationCategory]
        description: 'Enum Type: `KalturaNullableBoolean`Flag indicating that the
          category is an aggregation category'
      - in: query
        name: category[moderation]
        description: 'Enum Type: `KalturaNullableBoolean`Moderation to add entries
          to this category by users that are not of permission level Manager or Moderator'
      - in: query
        name: category[name]
        description: The name of the Category
      - in: query
        name: category[owner]
        description: Category Owner (User id)
      - in: query
        name: category[parentId]
      - in: query
        name: category[partnerData]
        description: Can be used to store various partner related data as a string
      - in: query
        name: category[partnerSortValue]
        description: Can be used to store various partner related data as a numeric
          value
      - in: query
        name: category[privacyContext]
        description: Set privacy context for search entries that assiged to private
          and public categories
      - in: query
        name: category[privacy]
        description: 'Enum Type: `KalturaPrivacyType`defines the privacy of the entries
          that assigned to this category'
      - in: query
        name: category[referenceId]
        description: Category external id, controlled and managed by the partner
      - in: query
        name: category[tags]
        description: Category tags
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - Add
  /service/category/action/addFromBulkUpload:
    post:
      summary: Post Service Category Action Addfrombulkupload
      description: ""
      operationId: category.addFromBulkUpload
      x-api-path-slug: servicecategoryactionaddfrombulkupload-post
      parameters:
      - in: query
        name: bulkUploadData[fileName]
        description: Friendly name of the file, used to be recognized later in the
          logs
      - in: query
        name: bulkUploadData[objectData][conversionProfileId]
        description: Selected profile id for all bulk entries
      - in: query
        name: bulkUploadData[objectData][objectType]
      - in: formData
        name: fileData
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - AddFromBulkUpload
  /service/category/action/delete:
    get:
      summary: Get Service Category Action Delete
      description: Delete a Category
      operationId: category.delete
      x-api-path-slug: servicecategoryactiondelete-get
      parameters:
      - in: query
        name: id
      - in: query
        name: moveEntriesToParentCategory
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - Delete
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