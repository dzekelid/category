{
  "info": {
    "name": "Kaltura VPaaS Get Service Categoryuser Action Update",
    "_postman_id": "2b16c958-4028-423d-aac9-8175937439c2",
    "description": "Update CategoryUser by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "b6719f65-0689-4df1-a1ca-9777a9dd4c56",
          "name": "category.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/add?category[aggregationCategories]=%7B%7D&category[appearInList]=%7B%7D&category[contributionPolicy]=%7B%7D&category[defaultOrderBy]=%7B%7D&category[defaultPermissionLevel]=%7B%7D&category[description]=%7B%7D&category[inheritanceType]=%7B%7D&category[isAggregationCategory]=%7B%7D&category[moderation]=%7B%7D&category[name]=%7B%7D&category[owner]=%7B%7D&category[parentId]=%7B%7D&category[partnerData]=%7B%7D&category[partnerSortValue]=%7B%7D&category[privacyContext]=%7B%7D&category[privacy]=%7B%7D&category[referenceId]=%7B%7D&category[tags]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eecd53aa-ef91-4e57-94bd-3387a3212cf6"
            }
          ]
        },
        {
          "id": "e2ce47a5-cb96-4ab1-9343-6f082b35af01",
          "name": "category.addFromBulkUpload",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/addFromBulkUpload?bulkUploadData[fileName]=%7B%7D&bulkUploadData[objectData][conversionProfileId]=%7B%7D&bulkUploadData[objectData][objectType]=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "fileData",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Post Service Category Action Addfrombulkupload"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31c03562-1b24-4bab-98bc-3058a65495d7"
            }
          ]
        },
        {
          "id": "021b47fa-249f-4eb1-a19f-424fb509db00",
          "name": "category.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/delete?id=%7B%7D&moveEntriesToParentCategory=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a Category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "35f8b14c-ac21-46b5-ba9d-fde447f90fc7"
            }
          ]
        },
        {
          "id": "8080904c-190e-41fe-a6dd-452e274b6658",
          "name": "category.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Category by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5ce9d864-7c0b-4658-a920-448bb4174ffb"
            }
          ]
        },
        {
          "id": "07240c95-48f6-48cf-8170-fd2d64db0fae",
          "name": "category.index",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/index?id=%7B%7D&No Name=%7B%7D&shouldUpdate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Index Category by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a5a19b5e-b293-4964-b62e-13c1cdf82ed3"
            }
          ]
        },
        {
          "id": "e7cfbbf0-6379-4502-8019-cf7af4ba594c",
          "name": "category.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[aggregationCategoriesMultiLikeAnd]=%7B%7D&filter[aggregationCategoriesMultiLikeOr]=%7B%7D&filter[ancestorIdIn]=%7B%7D&filter[appearInListEqual]=%7B%7D&filter[contributionPolicyEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[depthEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[fullIdsEqual]=%7B%7D&filter[fullIdsMatchOr]=%7B%7D&filter[fullIdsStartsWith]=%7B%7D&filter[fullNameEqual]=%7B%7D&filter[fullNameIn]=%7B%7D&filter[fullNameStartsWithIn]=%7B%7D&filter[fullNameStartsWith]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[idNotIn]=%7B%7D&filter[idOrInheritedParentIdIn]=%7B%7D&filter[inheritanceTypeEqual]=%7B%7D&filter[inheritanceTypeIn]=%7B%7D&filter[inheritedParentIdEqual]=%7B%7D&filter[inheritedParentIdIn]=%7B%7D&filter[managerEqual]=%7B%7D&filter[memberEqual]=%7B%7D&filter[membersCountGreaterThanOrEqual]=%7B%7D&filter[membersCountLessThanOrEqual]=%7B%7D&filter[membersIn]=%7B%7D&filter[nameOrReferenceIdStartsWith]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[pendingMembersCountGreaterThanOrEqual]=%7B%7D&filter[pendingMembersCountLessThanOrEqual]=%7B%7D&filter[privacyContextEqual]=%7B%7D&filter[privacyEqual]=%7B%7D&filter[privacyIn]=%7B%7D&filter[referenceIdEmpty]=%7B%7D&filter[referenceIdEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3717de77-03bb-41d5-93c5-c5a255bda440"
            }
          ]
        },
        {
          "id": "cc879a35-f6a3-4a20-af8c-9672476f8fcb",
          "name": "category.move",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/move?categoryIds=%7B%7D&No Name=%7B%7D&targetCategoryParentId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Move categories that belong to the same parent category to a target categroy - enabled only for ks with disable entitlement"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "947ab7d1-2926-4676-a9b9-e1a9d0f67864"
            }
          ]
        },
        {
          "id": "afdc1a9e-9ba4-49a5-a634-da659603051d",
          "name": "category.unlockCategories",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/unlockCategories?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Unlock categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c3d3198a-4ad5-4096-b36b-0aad7c327f3e"
            }
          ]
        },
        {
          "id": "0c52af52-1264-47d6-a392-15cb3a4ca858",
          "name": "category.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/category/action/update?category[aggregationCategories]=%7B%7D&category[appearInList]=%7B%7D&category[contributionPolicy]=%7B%7D&category[defaultOrderBy]=%7B%7D&category[defaultPermissionLevel]=%7B%7D&category[description]=%7B%7D&category[inheritanceType]=%7B%7D&category[isAggregationCategory]=%7B%7D&category[moderation]=%7B%7D&category[name]=%7B%7D&category[owner]=%7B%7D&category[parentId]=%7B%7D&category[partnerData]=%7B%7D&category[partnerSortValue]=%7B%7D&category[privacyContext]=%7B%7D&category[privacy]=%7B%7D&category[referenceId]=%7B%7D&category[tags]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84f245dd-e656-443d-ab3e-a193dde425f2"
            }
          ]
        },
        {
          "id": "173f2d2d-35fe-4660-886d-4fe7b030e343",
          "name": "categoryEntry.activate",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/activate?categoryId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "activate CategoryEntry when it is pending moderation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e7e664b2-3fa2-4d78-9ca3-3106cebe4b13"
            }
          ]
        },
        {
          "id": "40052a4e-d61f-4a4c-aa40-4059ee99bd45",
          "name": "categoryEntry.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/add?categoryEntry[categoryId]=%7B%7D&categoryEntry[entryId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new CategoryEntry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26bc83a5-eb0d-4056-bddf-e19d1a2cf420"
            }
          ]
        },
        {
          "id": "406dc39d-4c12-4110-9cf6-d4794a5e5edb",
          "name": "categoryEntry.addFromBulkUpload",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/addFromBulkUpload?bulkUploadData[filter][advancedSearch][attribute]=%7B%7D&bulkUploadData[filter][advancedSearch][categoriesMatchOr]=%7B%7D&bulkUploadData[filter][advancedSearch][categoryEntryStatusIn]=%7B%7D&bulkUploadData[filter][advancedSearch][categoryIdEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][comparison]=%7B%7D&bulkUploadData[filter][advancedSearch][contentLike]=%7B%7D&bulkUploadData[filter][advancedSearch][contentMultiLikeAnd]=%7B%7D&bulkUploadData[filter][advancedSearch][contentMultiLikeOr]=%7B%7D&bulkUploadData[filter][advancedSearch][cuePointsFreeText]=%7B%7D&bulkUploadData[filter][advancedSearch][cuePointSubTypeEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][cuePointTypeIn]=%7B%7D&bulkUploadData[filter][advancedSearch][depthGreaterThanEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][distributionProfileId]=%7B%7D&bulkUploadData[filter][advancedSearch][distributionSunStatus]=%7B%7D&bulkUploadData[filter][advancedSearch][entryDistributionFlag]=%7B%7D&bulkUploadData[filter][advancedSearch][entryDistributionStatus]=%7B%7D&bulkUploadData[filter][advancedSearch][entryDistributionValidationErrors]=%7B%7D&bulkUploadData[filter][advancedSearch][extendedStatusEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][extendedStatusIn]=%7B%7D&bulkUploadData[filter][advancedSearch][field]=%7B%7D&bulkUploadData[filter][advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&bulkUploadData[filter][advancedSearch][idEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][idIn]=%7B%7D&bulkUploadData[filter][advancedSearch][indexIdGreaterThan]=%7B%7D&bulkUploadData[filter][advancedSearch][isQuiz]=%7B%7D&bulkUploadData[filter][advancedSearch][items]=%7B%7D&bulkUploadData[filter][advancedSearch][memberIdEq]=%7B%7D&bulkUploadData[filter][advancedSearch][memberIdIn]=%7B%7D&bulkUploadData[filter][advancedSearch][memberPermissionsMatchAnd]=%7B%7D&bulkUploadData[filter][advancedSearch][memberPermissionsMatchOr]=%7B%7D&bulkUploadData[filter][advancedSearch][metadataProfileId]=%7B%7D&bulkUploadData[filter][advancedSearch][noDistributionProfiles]=%7B%7D&bulkUploadData[filter][advancedSearch][not]=%7B%7D&bulkUploadData[filter][advancedSearch][objectType]=%7B%7D&bulkUploadData[filter][advancedSearch][orderBy]=%7B%7D&bulkUploadData[filter][advancedSearch][type]=%7B%7D&bulkUploadData[filter][advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][userIdEqual]=%7B%7D&bulkUploadData[filter][advancedSearch][userIdIn]=%7B%7D&bulkUploadData[filter][advancedSearch][value]=%7B%7D&bulkUploadData[filter][advancedSearch][watermarkId]=%7B%7D&bulkUploadData[filter][orderBy]=%7B%7D&bulkUploadData[objectType]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Categoryentry Action Addfrombulkupload"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9669ed8b-2e1d-4c96-8881-53daf2f5f244"
            }
          ]
        },
        {
          "id": "41cac5ce-2425-45b6-b02a-14ffe129ef1f",
          "name": "categoryEntry.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/delete?categoryId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete CategoryEntry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "293eef01-c7e5-44dc-91ed-c64983f2478d"
            }
          ]
        },
        {
          "id": "bc4c97c6-9cfe-4ae7-87b1-eb741361087c",
          "name": "categoryEntry.index",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/index?categoryId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D&shouldUpdate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Index CategoryEntry by Id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fa508886-1f86-41e2-9467-2cb693a4e8d5"
            }
          ]
        },
        {
          "id": "facc9a86-1b0a-44d5-bb2c-84bb7ba3b1f4",
          "name": "categoryEntry.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[categoryFullIdsStartsWith]=%7B%7D&filter[categoryIdEqual]=%7B%7D&filter[categoryIdIn]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[creatorUserIdEqual]=%7B%7D&filter[creatorUserIdIn]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all categoryEntry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9f0f868a-ebe9-4f0b-8c61-e0d4b8a87e29"
            }
          ]
        },
        {
          "id": "de794aa5-81a9-46eb-821d-057218be28cf",
          "name": "categoryEntry.reject",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/reject?categoryId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "activate CategoryEntry when it is pending moderation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa9f7cde-61c4-4dff-8cf8-2d69202f55a8"
            }
          ]
        },
        {
          "id": "883cd30d-07d8-49d7-be50-3e1a6f2ec99d",
          "name": "categoryEntry.syncPrivacyContext",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryentry/action/syncPrivacyContext?categoryId=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "update privacy context from the category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec47d2c7-b564-46c9-94ea-b8f55c1f2902"
            }
          ]
        },
        {
          "id": "c3ac1061-88b5-4d57-98fa-e224134a727c",
          "name": "categoryUser.activate",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/activate?categoryId=%7B%7D&No Name=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "activate CategoryUser"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f1da145a-6232-4abe-957d-e7c9a33a60ff"
            }
          ]
        },
        {
          "id": "0a2eb326-e5af-42a0-a308-f3f5ab406e3c",
          "name": "categoryUser.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/add?categoryUser[categoryId]=%7B%7D&categoryUser[permissionLevel]=%7B%7D&categoryUser[permissionNames]=%7B%7D&categoryUser[updateMethod]=%7B%7D&categoryUser[userId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new CategoryUser"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36980bba-0c3e-42df-af9f-38cd10e813b1"
            }
          ]
        },
        {
          "id": "7d7861f6-fda9-40cd-b032-3dd08e58945d",
          "name": "categoryUser.addFromBulkUpload",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/addFromBulkUpload?bulkUploadData[fileName]=%7B%7D&bulkUploadData[objectData][conversionProfileId]=%7B%7D&bulkUploadData[objectData][objectType]=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "fileData",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Post Service Categoryuser Action Addfrombulkupload"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e8a3703f-b139-44a8-af20-b7e2ef10efb7"
            }
          ]
        },
        {
          "id": "be2ba0ba-06e1-4b1f-9b77-d76427d22662",
          "name": "categoryUser.copyFromCategory",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/copyFromCategory?categoryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Copy all memeber from parent category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7843d1fe-f06d-4000-9512-f80792997ed1"
            }
          ]
        },
        {
          "id": "3769c017-3036-4d71-a444-56c4b43e64af",
          "name": "categoryUser.deactivate",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/deactivate?categoryId=%7B%7D&No Name=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "reject CategoryUser"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a61ae914-0b9d-4729-8a25-91853a32c464"
            }
          ]
        },
        {
          "id": "e8145a06-30d7-4929-84af-75ed3e26cae8",
          "name": "categoryUser.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/delete?categoryId=%7B%7D&No Name=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete a CategoryUser"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38404398-d295-4069-ac09-1cbd8c3851ef"
            }
          ]
        },
        {
          "id": "dfc7296e-c32d-42e1-a906-c3f2660d142b",
          "name": "categoryUser.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/get?categoryId=%7B%7D&No Name=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get CategoryUser by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "734f5184-8dce-4a67-811c-b44b734f4866"
            }
          ]
        },
        {
          "id": "62c96037-6138-4928-b6a6-aa9c24cf613c",
          "name": "categoryUser.index",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/index?categoryId=%7B%7D&No Name=%7B%7D&shouldUpdate=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Index CategoryUser by userid and category id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "51af9e1e-db9e-4498-bd3c-ef1bf6ea2d9f"
            }
          ]
        },
        {
          "id": "44d2ca09-6340-453f-ba96-cc13cf573cd9",
          "name": "categoryUser.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[categoryDirectMembers]=%7B%7D&filter[categoryFullIdsEqual]=%7B%7D&filter[categoryFullIdsStartsWith]=%7B%7D&filter[categoryIdEqual]=%7B%7D&filter[categoryIdIn]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[orderBy]=%7B%7D&filter[permissionLevelEqual]=%7B%7D&filter[permissionLevelIn]=%7B%7D&filter[permissionNamesMatchAnd]=%7B%7D&filter[permissionNamesMatchOr]=%7B%7D&filter[permissionNamesNotContains]=%7B%7D&filter[relatedGroupsByUserId]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[updateMethodEqual]=%7B%7D&filter[updateMethodIn]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List all categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e77fbb1f-6897-4f82-9b80-f48633fe4373"
            }
          ]
        },
        {
          "id": "c721dd90-e899-4126-a014-a5596103b0a7",
          "name": "categoryUser.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/categoryuser/action/update?categoryId=%7B%7D&categoryUser[categoryId]=%7B%7D&categoryUser[permissionLevel]=%7B%7D&categoryUser[permissionNames]=%7B%7D&categoryUser[updateMethod]=%7B%7D&categoryUser[userId]=%7B%7D&No Name=%7B%7D&override=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update CategoryUser by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fb05ad34-79b2-4673-b6f8-7d4d1b73da9b"
            }
          ]
        }
      ]
    }
  ]
}