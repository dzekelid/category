---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 0
info:
  title: Kaltura VPaaS Get Service Category Action Move
  description: Move categories that belong to the same parent category to a target
    categroy - enabled only for ks with disable entitlement
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
  /service/category/action/get:
    get:
      summary: Get Service Category Action Get
      description: Get Category by id
      operationId: category.get
      x-api-path-slug: servicecategoryactionget-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - Get
  /service/category/action/index:
    get:
      summary: Get Service Category Action Index
      description: Index Category by id
      operationId: category.index
      x-api-path-slug: servicecategoryactionindex-get
      parameters:
      - in: query
        name: id
      - in: query
        name: No Name
      - in: query
        name: shouldUpdate
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - Index
  /service/category/action/list:
    get:
      summary: Get Service Category Action List
      description: List all categories
      operationId: category.list
      x-api-path-slug: servicecategoryactionlist-get
      parameters:
      - in: query
        name: filter[advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: filter[advancedSearch][categoriesMatchOr]
      - in: query
        name: filter[advancedSearch][categoryEntryStatusIn]
      - in: query
        name: filter[advancedSearch][categoryIdEqual]
      - in: query
        name: filter[advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: filter[advancedSearch][contentLike]
      - in: query
        name: filter[advancedSearch][contentMultiLikeAnd]
      - in: query
        name: filter[advancedSearch][contentMultiLikeOr]
      - in: query
        name: filter[advancedSearch][cuePointsFreeText]
      - in: query
        name: filter[advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: filter[advancedSearch][cuePointTypeIn]
      - in: query
        name: filter[advancedSearch][depthGreaterThanEqual]
      - in: query
        name: filter[advancedSearch][distributionProfileId]
      - in: query
        name: filter[advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: filter[advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: filter[advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: filter[advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: filter[advancedSearch][extendedStatusIn]
      - in: query
        name: filter[advancedSearch][field]
      - in: query
        name: filter[advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: filter[advancedSearch][idEqual]
      - in: query
        name: filter[advancedSearch][idIn]
      - in: query
        name: filter[advancedSearch][indexIdGreaterThan]
      - in: query
        name: filter[advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[advancedSearch][items]
      - in: query
        name: filter[advancedSearch][memberIdEq]
      - in: query
        name: filter[advancedSearch][memberIdIn]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: filter[advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: filter[advancedSearch][metadataProfileId]
      - in: query
        name: filter[advancedSearch][noDistributionProfiles]
      - in: query
        name: filter[advancedSearch][not]
      - in: query
        name: filter[advancedSearch][objectType]
      - in: query
        name: filter[advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: filter[advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: filter[advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: filter[advancedSearch][userIdEqual]
      - in: query
        name: filter[advancedSearch][userIdIn]
      - in: query
        name: filter[advancedSearch][value]
      - in: query
        name: filter[advancedSearch][watermarkId]
      - in: query
        name: filter[aggregationCategoriesMultiLikeAnd]
      - in: query
        name: filter[aggregationCategoriesMultiLikeOr]
      - in: query
        name: filter[ancestorIdIn]
        description: not includes the category itself (only sub categories)
      - in: query
        name: filter[appearInListEqual]
        description: 'Enum Type: `KalturaAppearInListType`'
      - in: query
        name: filter[contributionPolicyEqual]
        description: 'Enum Type: `KalturaContributionPolicyType`'
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[depthEqual]
      - in: query
        name: filter[freeText]
      - in: query
        name: filter[fullIdsEqual]
      - in: query
        name: filter[fullIdsMatchOr]
      - in: query
        name: filter[fullIdsStartsWith]
      - in: query
        name: filter[fullNameEqual]
      - in: query
        name: filter[fullNameIn]
      - in: query
        name: filter[fullNameStartsWithIn]
      - in: query
        name: filter[fullNameStartsWith]
      - in: query
        name: filter[idEqual]
      - in: query
        name: filter[idIn]
      - in: query
        name: filter[idNotIn]
      - in: query
        name: filter[idOrInheritedParentIdIn]
      - in: query
        name: filter[inheritanceTypeEqual]
        description: 'Enum Type: `KalturaInheritanceType`'
      - in: query
        name: filter[inheritanceTypeIn]
      - in: query
        name: filter[inheritedParentIdEqual]
      - in: query
        name: filter[inheritedParentIdIn]
      - in: query
        name: filter[managerEqual]
      - in: query
        name: filter[memberEqual]
      - in: query
        name: filter[membersCountGreaterThanOrEqual]
      - in: query
        name: filter[membersCountLessThanOrEqual]
      - in: query
        name: filter[membersIn]
      - in: query
        name: filter[nameOrReferenceIdStartsWith]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[parentIdEqual]
      - in: query
        name: filter[parentIdIn]
      - in: query
        name: filter[partnerSortValueGreaterThanOrEqual]
      - in: query
        name: filter[partnerSortValueLessThanOrEqual]
      - in: query
        name: filter[pendingMembersCountGreaterThanOrEqual]
      - in: query
        name: filter[pendingMembersCountLessThanOrEqual]
      - in: query
        name: filter[privacyContextEqual]
      - in: query
        name: filter[privacyEqual]
        description: 'Enum Type: `KalturaPrivacyType`'
      - in: query
        name: filter[privacyIn]
      - in: query
        name: filter[referenceIdEmpty]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: filter[referenceIdEqual]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCategoryStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[tagsLike]
      - in: query
        name: filter[tagsMultiLikeAnd]
      - in: query
        name: filter[tagsMultiLikeOr]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: No Name
      - in: query
        name: pager[pageIndex]
        description: The page number for which {pageSize} of objects should be retrieved
          (Default is 1)
      - in: query
        name: pager[pageSize]
        description: The number of objects to retrieve
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - List
  /service/category/action/move:
    get:
      summary: Get Service Category Action Move
      description: Move categories that belong to the same parent category to a target
        categroy - enabled only for ks with disable entitlement
      operationId: category.move
      x-api-path-slug: servicecategoryactionmove-get
      parameters:
      - in: query
        name: categoryIds
      - in: query
        name: No Name
      - in: query
        name: targetCategoryParentId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - Move
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