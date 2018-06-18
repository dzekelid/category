{
  "info": {
    "name": "Kaltura VPaaS Get Service Categoryentry Action List",
    "_postman_id": "803fe674-4c39-4c66-b3a4-210297e3436b",
    "description": "List all categoryEntry",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "dfa0ea1c-ba05-4d2d-8642-f5d0b8ba6703",
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
              "id": "e88e9d44-dfcd-4c4a-a747-5e885ef1f469"
            }
          ]
        },
        {
          "id": "a4bb8669-7f5e-41d0-a306-3e68c9f46a59",
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
              "id": "2b612599-521c-4418-ad36-2fcbc4fe0654"
            }
          ]
        },
        {
          "id": "d19ef904-2d19-410e-9071-726247ae52d8",
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
              "id": "011e294d-588b-4e96-b61f-3e5991d1d0b3"
            }
          ]
        },
        {
          "id": "0c68a6e5-48c7-459b-a2dc-07209d5e65de",
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
              "id": "081d5cf7-d584-431b-b2a7-76aae33cd382"
            }
          ]
        },
        {
          "id": "aa9eb820-7abb-499a-94b8-01ba8daeca11",
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
              "id": "926248d1-9d77-4579-ae7e-5fe6509a043a"
            }
          ]
        },
        {
          "id": "6be89b31-0cde-49c7-8cd5-67f2f71623be",
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
              "id": "19c175a4-cbb3-442d-9b25-3c0819172c05"
            }
          ]
        },
        {
          "id": "5047bcc2-e1d1-422b-9142-2f838719ebcc",
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
              "id": "1a018a6f-f632-4ee1-af8e-e6b343415c9a"
            }
          ]
        },
        {
          "id": "70b0004b-a646-4247-af7c-2e7188a57897",
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
              "id": "03ba5d62-ed21-49b5-b94b-1c3ce4b8a929"
            }
          ]
        },
        {
          "id": "9ae29680-15e6-40c4-9025-00828ce37cf5",
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
              "id": "03b842f1-559b-4d08-9d27-fc2428b79d7a"
            }
          ]
        },
        {
          "id": "135a62bf-7a50-471e-9743-9152564bd309",
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
              "id": "2781ffb4-5c24-4969-b726-1573bb12f630"
            }
          ]
        },
        {
          "id": "53f5108b-7aac-47dd-894c-9bd219ff4500",
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
              "id": "5bb522b7-8159-4448-97e4-ac4080e5fa61"
            }
          ]
        },
        {
          "id": "833e4001-0364-49ae-ba9a-9e4453cdbf45",
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
              "id": "3ebd205e-fcec-45a8-acb2-774722f8ea54"
            }
          ]
        },
        {
          "id": "822d5400-4aac-4588-8018-6691780d1d92",
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
              "id": "28fba9d3-a6a3-4549-a4f0-e22033730084"
            }
          ]
        },
        {
          "id": "b873868d-fde9-4aec-a73f-cdeff16bf0e2",
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
              "id": "572fb45b-519c-47a5-a87e-b1472f1b3a46"
            }
          ]
        },
        {
          "id": "1d6d1f7e-d223-4926-a76b-7ec979dd953a",
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
              "id": "bedd67ce-e790-4385-b79d-79f90146357d"
            }
          ]
        }
      ]
    }
  ]
}