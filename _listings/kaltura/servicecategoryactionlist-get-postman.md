{
  "info": {
    "name": "Kaltura VPaaS Get Service Category Action List",
    "_postman_id": "bdcad6be-03ab-4e77-8e7e-c8c1ca551279",
    "description": "List all categories",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "7f18b0a0-c2c6-46e3-b846-d6407c757fc0",
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
              "id": "9de3df73-9dfe-4c8a-a516-d7cd1edfce87"
            }
          ]
        },
        {
          "id": "03a458b9-6e65-4088-8bdd-c68f23030608",
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
              "id": "e2725e54-e5b8-44c2-afb0-d6f47345c86c"
            }
          ]
        },
        {
          "id": "40a3c893-d1b0-47c0-9025-eec6b0466ad5",
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
              "id": "03ac24ec-7572-4f63-a3a0-ab9833d187c5"
            }
          ]
        },
        {
          "id": "bfb57e39-f8f2-4988-9a88-46e186136430",
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
              "id": "96ba2a5b-d8ec-42d2-8e76-a4579ad9e411"
            }
          ]
        },
        {
          "id": "91946e13-a9f2-4922-9c3b-b1fcb34b1edb",
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
              "id": "737e2234-865d-4ab4-b151-c681018e4f08"
            }
          ]
        },
        {
          "id": "f386a33c-2d6d-4900-8a01-48ecdba8310f",
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
              "id": "4ef819c7-ce15-473c-8e9f-40ab20af35df"
            }
          ]
        }
      ]
    }
  ]
}