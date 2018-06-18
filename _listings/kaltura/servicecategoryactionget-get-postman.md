{
  "info": {
    "name": "Kaltura VPaaS Get Service Category Action Get",
    "_postman_id": "39be5cd6-62c7-49ce-899d-4bd401ab8a17",
    "description": "Get Category by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "ac34eacb-a3cf-4cd1-8b8c-e753eb68e0ea",
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
              "id": "3b85b051-1f1f-4def-8928-8ae36e3471dc"
            }
          ]
        },
        {
          "id": "4fa954c0-c98e-43a8-ac64-e0de4baaa94e",
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
              "id": "fadc37f7-2af0-454e-9c82-1c6ea34d8395"
            }
          ]
        },
        {
          "id": "ae865162-0c47-4c00-9055-a992f3bc21c0",
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
              "id": "89c1f182-36cf-414f-a413-d31367bffe0a"
            }
          ]
        },
        {
          "id": "7e08faae-1b0b-44c2-a5c8-f169d18c8474",
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
              "id": "30eb7200-a071-4abe-bba9-30bc53f0d3d0"
            }
          ]
        }
      ]
    }
  ]
}