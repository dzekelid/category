{
  "info": {
    "name": "Kaltura VPaaS Get Service Categoryuser Action Deactivate",
    "_postman_id": "88150d6c-d982-43a9-86b9-8cbd9ad8d5fc",
    "description": "reject CategoryUser",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "252f55bf-da8c-48ab-bd26-45dfbbfbe8b5",
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
              "id": "ad3706ab-ef72-486f-9a4b-18779cf1837d"
            }
          ]
        },
        {
          "id": "e306b21f-84a9-4a11-bb3c-367191265895",
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
              "id": "df06510e-c8f7-4d0c-96ff-9a22442917c8"
            }
          ]
        },
        {
          "id": "981dd6a3-66c3-449d-a547-f4db4ba73af6",
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
              "id": "f0bbebe4-59d9-4f65-be92-4b0c236cd277"
            }
          ]
        },
        {
          "id": "e163051e-39ec-4656-8096-f7f2dc4e946c",
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
              "id": "94f88e82-13cb-4f97-a763-0457e255abef"
            }
          ]
        },
        {
          "id": "b992e558-22e5-4481-b182-3fecb75f6736",
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
              "id": "912eccd9-810c-4bb3-8498-db3cb61d6e7f"
            }
          ]
        },
        {
          "id": "a21705cb-d81b-4e58-a96a-41a6795c0f21",
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
              "id": "d88728a9-3bfd-403e-9887-cfe7367e7d2b"
            }
          ]
        },
        {
          "id": "a67ae4a4-e5ed-4165-b1cb-eeb655dd1a83",
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
              "id": "d3526ffb-71ed-4f26-8e81-f91100a27de6"
            }
          ]
        },
        {
          "id": "39c586f5-a5d9-4518-ae91-e067d6ec0bd6",
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
              "id": "c2d317e0-674a-40dd-8f5b-cb8059196d8a"
            }
          ]
        },
        {
          "id": "18bebb71-0b2a-486b-9fa5-967986155bec",
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
              "id": "4297e712-9a0d-4332-a0f2-6792294ff7f3"
            }
          ]
        },
        {
          "id": "fef18e5a-c772-4356-89e7-69597dd05d07",
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
              "id": "8e7e8b84-919f-4cca-82fa-7fbecba19380"
            }
          ]
        },
        {
          "id": "c357a9ff-335e-40ab-b623-23de2811b49e",
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
              "id": "6d686389-8312-47b8-b0a7-6d02d20540cb"
            }
          ]
        },
        {
          "id": "5462ccfc-d124-4e62-85dc-47cf6993b698",
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
              "id": "e298ad18-be72-4a9d-85a5-37de9c546e4a"
            }
          ]
        },
        {
          "id": "e803d8fa-2c1e-4240-96b2-a4698986b04a",
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
              "id": "a2bb9e33-6090-4c36-a5d2-ec1070bc8d06"
            }
          ]
        },
        {
          "id": "fce4e166-848c-462f-a382-11869f3b19ff",
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
              "id": "cb6ffc52-eeda-45f1-854c-f44cede29f3b"
            }
          ]
        },
        {
          "id": "35ddd922-8839-496d-abc2-a4dcef8cbab6",
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
              "id": "ae3e4e9c-1436-4b64-a10f-831cee2dc1ef"
            }
          ]
        },
        {
          "id": "a4b45dc9-bf64-4ff4-a547-561f3999cc30",
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
              "id": "c27834fe-e740-4105-9fbf-f9399fc8ae76"
            }
          ]
        },
        {
          "id": "ac5a0fd8-532e-4851-84d3-1d9916ddcee5",
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
              "id": "30b14789-206f-41e5-9b1e-c8220129b3cf"
            }
          ]
        },
        {
          "id": "53b517ca-8745-4a73-8681-1a13c5df7ad6",
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
              "id": "4cdc923c-77e4-4bd0-a6da-22931d3344ca"
            }
          ]
        },
        {
          "id": "c35c0bdf-e67a-4137-9c43-d35d6ee799e1",
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
              "id": "a1ce05d9-62a0-4839-af3f-a80b7b31dd78"
            }
          ]
        },
        {
          "id": "0cc00e1e-a7f2-4a05-a234-13b443239aed",
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
              "id": "31b207f6-3ec5-4774-8159-7374b964415b"
            }
          ]
        },
        {
          "id": "f4ff561e-490e-4dcf-acf0-007c63399a64",
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
              "id": "99cf26ed-73dc-4768-95be-3570fdc82172"
            }
          ]
        },
        {
          "id": "3bdc094d-b183-4c59-8c2a-de9adf581d38",
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
              "id": "e45953e6-7a2c-4d2e-8a8b-9005391de9f1"
            }
          ]
        }
      ]
    }
  ]
}