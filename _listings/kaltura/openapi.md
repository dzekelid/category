---
swagger: "2.0"
x-collection-name: Kaltura
x-complete: 1
info:
  title: Kaltura VPaaS
  description: building-video-experiences-consists-of-ingesting-media-files-playing-back-videos-and-reviewing-usage-and-engagement-analytics--in-between-there-is-a-world-of-nuances-required-for-your-unique-usecase-and-application--kaltura-vpaas-is-built-on-the-principles-of-atomic-services-sdks-and-tools-that-allow-you-full-control-and-flexibility-over-every-element-and-process-in-your-medias-life-cycle-
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
  /service/category/action/unlockCategories:
    get:
      summary: Get Service Category Action Unlockcategories
      description: Unlock categories
      operationId: category.unlockCategories
      x-api-path-slug: servicecategoryactionunlockcategories-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Category
      - Action
      - UnlockCategories
  /service/category/action/update:
    get:
      summary: Get Service Category Action Update
      description: Update Category
      operationId: category.update
      x-api-path-slug: servicecategoryactionupdate-get
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
      - Update
  /service/categoryentry/action/activate:
    get:
      summary: Get Service Categoryentry Action Activate
      description: activate CategoryEntry when it is pending moderation
      operationId: categoryEntry.activate
      x-api-path-slug: servicecategoryentryactionactivate-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - Activate
  /service/categoryentry/action/add:
    get:
      summary: Get Service Categoryentry Action Add
      description: Add new CategoryEntry
      operationId: categoryEntry.add
      x-api-path-slug: servicecategoryentryactionadd-get
      parameters:
      - in: query
        name: categoryEntry[categoryId]
      - in: query
        name: categoryEntry[entryId]
        description: entry id
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - Add
  /service/categoryentry/action/addFromBulkUpload:
    get:
      summary: Get Service Categoryentry Action Addfrombulkupload
      description: ""
      operationId: categoryEntry.addFromBulkUpload
      x-api-path-slug: servicecategoryentryactionaddfrombulkupload-get
      parameters:
      - in: query
        name: bulkUploadData[filter][advancedSearch][attribute]
        description: 'Enum Type: `KalturaBaseEntryCompareAttribute`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][categoriesMatchOr]
      - in: query
        name: bulkUploadData[filter][advancedSearch][categoryEntryStatusIn]
      - in: query
        name: bulkUploadData[filter][advancedSearch][categoryIdEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][comparison]
        description: 'Enum Type: `KalturaSearchConditionComparison`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][contentLike]
      - in: query
        name: bulkUploadData[filter][advancedSearch][contentMultiLikeAnd]
      - in: query
        name: bulkUploadData[filter][advancedSearch][contentMultiLikeOr]
      - in: query
        name: bulkUploadData[filter][advancedSearch][cuePointsFreeText]
      - in: query
        name: bulkUploadData[filter][advancedSearch][cuePointSubTypeEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][cuePointTypeIn]
      - in: query
        name: bulkUploadData[filter][advancedSearch][depthGreaterThanEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][distributionProfileId]
      - in: query
        name: bulkUploadData[filter][advancedSearch][distributionSunStatus]
        description: 'Enum Type: `KalturaEntryDistributionSunStatus`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][entryDistributionFlag]
        description: 'Enum Type: `KalturaEntryDistributionFlag`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][entryDistributionStatus]
        description: 'Enum Type: `KalturaEntryDistributionStatus`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][entryDistributionValidationErrors]
        description: Comma seperated validation error types
      - in: query
        name: bulkUploadData[filter][advancedSearch][extendedStatusEqual]
        description: 'Enum Type: `KalturaUserEntryExtendedStatus`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][extendedStatusIn]
      - in: query
        name: bulkUploadData[filter][advancedSearch][field]
      - in: query
        name: bulkUploadData[filter][advancedSearch][hasEntryDistributionValidationErrors]
      - in: query
        name: bulkUploadData[filter][advancedSearch][idEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][idIn]
      - in: query
        name: bulkUploadData[filter][advancedSearch][indexIdGreaterThan]
      - in: query
        name: bulkUploadData[filter][advancedSearch][isQuiz]
        description: 'Enum Type: `KalturaNullableBoolean`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][items]
      - in: query
        name: bulkUploadData[filter][advancedSearch][memberIdEq]
      - in: query
        name: bulkUploadData[filter][advancedSearch][memberIdIn]
      - in: query
        name: bulkUploadData[filter][advancedSearch][memberPermissionsMatchAnd]
      - in: query
        name: bulkUploadData[filter][advancedSearch][memberPermissionsMatchOr]
      - in: query
        name: bulkUploadData[filter][advancedSearch][metadataProfileId]
      - in: query
        name: bulkUploadData[filter][advancedSearch][noDistributionProfiles]
      - in: query
        name: bulkUploadData[filter][advancedSearch][not]
      - in: query
        name: bulkUploadData[filter][advancedSearch][objectType]
      - in: query
        name: bulkUploadData[filter][advancedSearch][orderBy]
        description: 'Enum Type: `KalturaCategoryEntryAdvancedOrderBy`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][type]
        description: 'Enum Type: `KalturaSearchOperatorType`'
      - in: query
        name: bulkUploadData[filter][advancedSearch][updatedAtGreaterThanOrEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][updatedAtLessThanOrEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][userIdEqual]
      - in: query
        name: bulkUploadData[filter][advancedSearch][userIdIn]
      - in: query
        name: bulkUploadData[filter][advancedSearch][value]
      - in: query
        name: bulkUploadData[filter][advancedSearch][watermarkId]
      - in: query
        name: bulkUploadData[filter][orderBy]
      - in: query
        name: bulkUploadData[objectType]
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - AddFromBulkUpload
  /service/categoryentry/action/delete:
    get:
      summary: Get Service Categoryentry Action Delete
      description: Delete CategoryEntry
      operationId: categoryEntry.delete
      x-api-path-slug: servicecategoryentryactiondelete-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - Delete
  /service/categoryentry/action/index:
    get:
      summary: Get Service Categoryentry Action Index
      description: Index CategoryEntry by Id
      operationId: categoryEntry.index
      x-api-path-slug: servicecategoryentryactionindex-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: entryId
      - in: query
        name: No Name
      - in: query
        name: shouldUpdate
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - Index
  /service/categoryentry/action/list:
    get:
      summary: Get Service Categoryentry Action List
      description: List all categoryEntry
      operationId: categoryEntry.list
      x-api-path-slug: servicecategoryentryactionlist-get
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
        name: filter[categoryFullIdsStartsWith]
      - in: query
        name: filter[categoryIdEqual]
      - in: query
        name: filter[categoryIdIn]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[creatorUserIdEqual]
      - in: query
        name: filter[creatorUserIdIn]
      - in: query
        name: filter[entryIdEqual]
      - in: query
        name: filter[entryIdIn]
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCategoryEntryStatus`'
      - in: query
        name: filter[statusIn]
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
      - Categoryentry
      - Action
      - List
  /service/categoryentry/action/reject:
    get:
      summary: Get Service Categoryentry Action Reject
      description: activate CategoryEntry when it is pending moderation
      operationId: categoryEntry.reject
      x-api-path-slug: servicecategoryentryactionreject-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - Reject
  /service/categoryentry/action/syncPrivacyContext:
    get:
      summary: Get Service Categoryentry Action Syncprivacycontext
      description: update privacy context from the category
      operationId: categoryEntry.syncPrivacyContext
      x-api-path-slug: servicecategoryentryactionsyncprivacycontext-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: entryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryentry
      - Action
      - SyncPrivacyContext
  /service/categoryuser/action/activate:
    get:
      summary: Get Service Categoryuser Action Activate
      description: activate CategoryUser
      operationId: categoryUser.activate
      x-api-path-slug: servicecategoryuseractionactivate-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Activate
  /service/categoryuser/action/add:
    get:
      summary: Get Service Categoryuser Action Add
      description: Add new CategoryUser
      operationId: categoryUser.add
      x-api-path-slug: servicecategoryuseractionadd-get
      parameters:
      - in: query
        name: categoryUser[categoryId]
        description: '`insertOnly`'
      - in: query
        name: categoryUser[permissionLevel]
        description: 'Enum Type: `KalturaCategoryUserPermissionLevel`Permission level'
      - in: query
        name: categoryUser[permissionNames]
        description: Set of category-related permissions for the current category
          user
      - in: query
        name: categoryUser[updateMethod]
        description: 'Enum Type: `KalturaUpdateMethodType`Update method can be either
          manual or automatic to distinguish between manual operations (for example
          in KMC) on automatic - using bulk upload'
      - in: query
        name: categoryUser[userId]
        description: '`insertOnly`User id'
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Add
  /service/categoryuser/action/addFromBulkUpload:
    post:
      summary: Post Service Categoryuser Action Addfrombulkupload
      description: ""
      operationId: categoryUser.addFromBulkUpload
      x-api-path-slug: servicecategoryuseractionaddfrombulkupload-post
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
      - Categoryuser
      - Action
      - AddFromBulkUpload
  /service/categoryuser/action/copyFromCategory:
    get:
      summary: Get Service Categoryuser Action Copyfromcategory
      description: Copy all memeber from parent category
      operationId: categoryUser.copyFromCategory
      x-api-path-slug: servicecategoryuseractioncopyfromcategory-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - CopyFromCategory
  /service/categoryuser/action/deactivate:
    get:
      summary: Get Service Categoryuser Action Deactivate
      description: reject CategoryUser
      operationId: categoryUser.deactivate
      x-api-path-slug: servicecategoryuseractiondeactivate-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Deactivate
  /service/categoryuser/action/delete:
    get:
      summary: Get Service Categoryuser Action Delete
      description: Delete a CategoryUser
      operationId: categoryUser.delete
      x-api-path-slug: servicecategoryuseractiondelete-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Delete
  /service/categoryuser/action/get:
    get:
      summary: Get Service Categoryuser Action Get
      description: Get CategoryUser by id
      operationId: categoryUser.get
      x-api-path-slug: servicecategoryuseractionget-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Get
  /service/categoryuser/action/index:
    get:
      summary: Get Service Categoryuser Action Index
      description: Index CategoryUser by userid and category id
      operationId: categoryUser.index
      x-api-path-slug: servicecategoryuseractionindex-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: No Name
      - in: query
        name: shouldUpdate
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Index
  /service/categoryuser/action/list:
    get:
      summary: Get Service Categoryuser Action List
      description: List all categories
      operationId: categoryUser.list
      x-api-path-slug: servicecategoryuseractionlist-get
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
        name: filter[categoryDirectMembers]
        description: Return the list of categoryUser that are not inherited from parent
          category - only the direct categoryUsers
      - in: query
        name: filter[categoryFullIdsEqual]
      - in: query
        name: filter[categoryFullIdsStartsWith]
      - in: query
        name: filter[categoryIdEqual]
      - in: query
        name: filter[categoryIdIn]
      - in: query
        name: filter[createdAtGreaterThanOrEqual]
      - in: query
        name: filter[createdAtLessThanOrEqual]
      - in: query
        name: filter[freeText]
        description: Free text search on user id or screen name
      - in: query
        name: filter[orderBy]
      - in: query
        name: filter[permissionLevelEqual]
        description: 'Enum Type: `KalturaCategoryUserPermissionLevel`'
      - in: query
        name: filter[permissionLevelIn]
      - in: query
        name: filter[permissionNamesMatchAnd]
      - in: query
        name: filter[permissionNamesMatchOr]
      - in: query
        name: filter[permissionNamesNotContains]
      - in: query
        name: filter[relatedGroupsByUserId]
        description: Return a list of categoryUser that related to the userId in this
          field by groups
      - in: query
        name: filter[statusEqual]
        description: 'Enum Type: `KalturaCategoryUserStatus`'
      - in: query
        name: filter[statusIn]
      - in: query
        name: filter[updatedAtGreaterThanOrEqual]
      - in: query
        name: filter[updatedAtLessThanOrEqual]
      - in: query
        name: filter[updateMethodEqual]
        description: 'Enum Type: `KalturaUpdateMethodType`'
      - in: query
        name: filter[updateMethodIn]
      - in: query
        name: filter[userIdEqual]
      - in: query
        name: filter[userIdIn]
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
      - Categoryuser
      - Action
      - List
  /service/categoryuser/action/update:
    get:
      summary: Get Service Categoryuser Action Update
      description: Update CategoryUser by id
      operationId: categoryUser.update
      x-api-path-slug: servicecategoryuseractionupdate-get
      parameters:
      - in: query
        name: categoryId
      - in: query
        name: categoryUser[categoryId]
        description: '`insertOnly`'
      - in: query
        name: categoryUser[permissionLevel]
        description: 'Enum Type: `KalturaCategoryUserPermissionLevel`Permission level'
      - in: query
        name: categoryUser[permissionNames]
        description: Set of category-related permissions for the current category
          user
      - in: query
        name: categoryUser[updateMethod]
        description: 'Enum Type: `KalturaUpdateMethodType`Update method can be either
          manual or automatic to distinguish between manual operations (for example
          in KMC) on automatic - using bulk upload'
      - in: query
        name: categoryUser[userId]
        description: '`insertOnly`User id'
      - in: query
        name: No Name
      - in: query
        name: override
        description: '- to override manual changes'
      - in: query
        name: userId
      responses:
        200:
          description: OK
      tags:
      - Service
      - Categoryuser
      - Action
      - Update
---