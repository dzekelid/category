{
  "info": {
    "name": "Kaltura VPaaS Get Service Categoryuser Action List",
    "_postman_id": "edef1012-2e02-4452-8209-2cc33633e223",
    "description": "List all categories",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "c2864891-4931-48d9-9205-1f458c410e22",
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
              "id": "547ac445-2844-455a-bbe1-8cd3cc5044a1"
            }
          ]
        },
        {
          "id": "b7041531-1d43-4f83-bf5d-ed14894d6a1d",
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
              "id": "4e71ac10-11e5-45ad-ae86-a35580f53524"
            }
          ]
        },
        {
          "id": "208d7b7b-7a85-4ab8-9d0a-94c049ea70e2",
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
              "id": "786efa8a-a841-4fdc-a896-506e7aa3a8e4"
            }
          ]
        },
        {
          "id": "75ffc0b0-723c-4d02-881f-4af0b6786b4a",
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
              "id": "5b0f32e1-7c73-415f-8c4f-fff46f3ea28d"
            }
          ]
        },
        {
          "id": "e306109b-c59f-44b8-a874-4425cee25245",
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
              "id": "aa7870fe-c4a3-468d-bd63-954392527ad1"
            }
          ]
        },
        {
          "id": "92094718-0121-462e-912e-984f259aa01b",
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
              "id": "57143656-f8a6-45e7-8f98-afd8325c2851"
            }
          ]
        },
        {
          "id": "c9a2804c-b306-42c5-a377-1e7063cf3d1d",
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
              "id": "1d4ee869-98ed-47f2-9a06-d4aa88cc802f"
            }
          ]
        },
        {
          "id": "ec352714-69c1-471a-86e6-eb9f98158adb",
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
              "id": "aba613f5-442d-467f-9591-576ef4ae75d7"
            }
          ]
        },
        {
          "id": "76572fc3-5383-49c2-a8bd-f46347a94385",
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
              "id": "dbb41c0f-4a9c-45c5-8b75-ddf8a6c72b6d"
            }
          ]
        },
        {
          "id": "9506f924-28b6-410e-b826-3101383bbdbe",
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
              "id": "e47014c9-fe89-4e1e-83e4-4bfcf68f4991"
            }
          ]
        },
        {
          "id": "9df555cb-bfaf-4658-b575-9144369c226d",
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
              "id": "179f212f-0179-4079-b4d3-c166e7b74b2d"
            }
          ]
        },
        {
          "id": "86f2c4f5-d563-4334-a20e-e423c035885a",
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
              "id": "1e85c7ea-1ff2-43e2-a8c5-aef26d973415"
            }
          ]
        },
        {
          "id": "0e8f57e6-83be-43a8-bb49-5da0c91c7683",
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
              "id": "dc1e9338-cccd-4a4c-87bb-8004f62b6fbe"
            }
          ]
        },
        {
          "id": "2449e96f-a716-4392-b37c-55a929166386",
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
              "id": "bc9766b4-2ec7-4b11-b8a3-4e5c6b1318c3"
            }
          ]
        },
        {
          "id": "bcf948ce-59d3-4270-bec9-0e6900a9cafa",
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
              "id": "0aa2a1a3-68ee-4e89-b5ba-30d9ed6e079c"
            }
          ]
        },
        {
          "id": "c7de49e0-2e36-4093-9860-9c3c4ae2db74",
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
              "id": "01e9dfc2-fdb5-442c-a2e9-57ec3aafe688"
            }
          ]
        },
        {
          "id": "c3a4187d-cc4c-4867-b77b-f3982b8149a9",
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
              "id": "492fe155-2198-44e4-8ba8-9f0066f4aee3"
            }
          ]
        },
        {
          "id": "f6e400b7-abaa-4090-b255-58341c3d0426",
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
              "id": "0b424f8c-1892-4bf2-85b3-3d2d9cf96c58"
            }
          ]
        },
        {
          "id": "76ffe4bb-2227-4a57-8d9d-4f674c1e62c1",
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
              "id": "12cb32dd-0a18-43a5-ae05-1671ba6c6a17"
            }
          ]
        },
        {
          "id": "4f785a4e-934f-427a-b386-f4c387a4ac52",
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
              "id": "7aae6ffc-fc68-4d18-a6d1-1a018b59015b"
            }
          ]
        },
        {
          "id": "e4d6f810-d6cb-44af-bc61-6e56bdd5ba9f",
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
              "id": "d59be90c-4ce1-41ff-be5e-ba67eb83ba76"
            }
          ]
        },
        {
          "id": "b3c224be-fecd-435e-95c2-633d2a7aca28",
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
              "id": "2ea9429e-e08d-47df-b9c0-0ece6f50b586"
            }
          ]
        },
        {
          "id": "14f0eaf7-8cad-44b6-a6a4-d5c2cd5e9a71",
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
              "id": "95719a87-0199-4365-afe1-58ba5792c3f7"
            }
          ]
        },
        {
          "id": "47af964d-e509-4ce5-92e6-a03b36639eaa",
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
              "id": "26caf19b-537e-4c5d-8f7e-bd839df5bc1d"
            }
          ]
        },
        {
          "id": "7b30c843-1320-4093-a09c-21fdf72cb86c",
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
              "id": "f24a6a0c-d542-4842-b4bb-0db182d21d58"
            }
          ]
        },
        {
          "id": "99c696e0-0afa-46e3-be55-1faf948f4f78",
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
              "id": "842749a4-d3c6-411a-9abc-d27779556587"
            }
          ]
        }
      ]
    }
  ]
}