{
  "info": {
    "name": "Kaltura VPaaS Post Service Category Action Addfrombulkupload",
    "_postman_id": "413015a5-5aef-4a8f-8880-29fa1ab878ab",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "b4a756e0-f845-40d7-836f-c8b4b4133b42",
          "name": "annotation.addFromBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/addFromBulk?No Name=%7B%7D",
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
            "description": "Allows you to add multiple cue points objects by uploading XML that contains multiple cue point definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f08d8b62-a289-40dd-9bef-c61db96ce245"
            }
          ]
        },
        {
          "id": "93aec4c9-410f-45c1-b2f4-250b8175a490",
          "name": "annotation.serveBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/serveBulk?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download multiple cue points objects as XML definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cabd9087-4ad3-4269-bcdf-861a795e2034"
            }
          ]
        },
        {
          "id": "4a10f171-f1c0-4ff8-83c2-c4e14da596f4",
          "name": "batch.addBulkUploadResult",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/addBulkUploadResult?bulkUploadResult[accessControlProfileId]=%7B%7D&bulkUploadResult[action]=%7B%7D&bulkUploadResult[appearInList]=%7B%7D&bulkUploadResult[bulkUploadJobId]=%7B%7D&bulkUploadResult[bulkUploadResultObjectType]=%7B%7D&bulkUploadResult[categoryId]=%7B%7D&bulkUploadResult[categoryReferenceId]=%7B%7D&bulkUploadResult[category]=%7B%7D&bulkUploadResult[city]=%7B%7D&bulkUploadResult[contentType]=%7B%7D&bulkUploadResult[contributionPolicy]=%7B%7D&bulkUploadResult[conversionProfileId]=%7B%7D&bulkUploadResult[country]=%7B%7D&bulkUploadResult[creatorId]=%7B%7D&bulkUploadResult[dateOfBirth]=%7B%7D&bulkUploadResult[defaultPermissionLevel]=%7B%7D&bulkUploadResult[description]=%7B%7D&bulkUploadResult[email]=%7B%7D&bulkUploadResult[entitledUsersEdit]=%7B%7D&bulkUploadResult[entitledUsersPublish]=%7B%7D&bulkUploadResult[entryId]=%7B%7D&bulkUploadResult[entryStatus]=%7B%7D&bulkUploadResult[errorCode]=%7B%7D&bulkUploadResult[errorDescription]=%7B%7D&bulkUploadResult[errorType]=%7B%7D&bulkUploadResult[firstName]=%7B%7D&bulkUploadResult[gender]=%7B%7D&bulkUploadResult[group]=%7B%7D&bulkUploadResult[inheritanceType]=%7B%7D&bulkUploadResult[lastName]=%7B%7D&bulkUploadResult[lineIndex]=%7B%7D&bulkUploadResult[moderation]=%7B%7D&bulkUploadResult[name]=%7B%7D&bulkUploadResult[objectErrorDescription]=%7B%7D&bulkUploadResult[objectId]=%7B%7D&bulkUploadResult[objectStatus]=%7B%7D&bulkUploadResult[objectType]=%7B%7D&bulkUploadResult[ownerId]=%7B%7D&bulkUploadResult[owner]=%7B%7D&bulkUploadResult[parentSystemName]=%7B%7D&bulkUploadResult[parentType]=%7B%7D&bulkUploadResult[partnerData]=%7B%7D&bulkUploadResult[partnerId]=%7B%7D&bulkUploadResult[partnerSortValue]=%7B%7D&bulkUploadResult[permissionLevel]=%7B%7D&bulkUploadResult[pluginsData]=%7B%7D&bulkUploadResult[privacy]=%7B%7D&bulkUploadResult[referenceId]=%7B%7D&bulkUploadResult[relativePath]=%7B%7D&bulkUploadResult[requiredObjectStatus]=%7B%7D&bulkUploadResult[resourceId]=%7B%7D&bulkUploadResult[rowData]=%7B%7D&bulkUploadResult[scheduleEndDate]=%7B%7D&bulkUploadResult[scheduleStartDate]=%7B%7D&bulkUploadResult[screenName]=%7B%7D&bulkUploadResult[sshKeyPassphrase]=%7B%7D&bulkUploadResult[sshPrivateKey]=%7B%7D&bulkUploadResult[sshPublicKey]=%7B%7D&bulkUploadResult[state]=%7B%7D&bulkUploadResult[status]=%7B%7D&bulkUploadResult[systemName]=%7B%7D&bulkUploadResult[tags]=%7B%7D&bulkUploadResult[templateEntryId]=%7B%7D&bulkUploadResult[thumbnailSaved]=%7B%7D&bulkUploadResult[thumbnailUrl]=%7B%7D&bulkUploadResult[title]=%7B%7D&bulkUploadResult[type]=%7B%7D&bulkUploadResult[updateMethod]=%7B%7D&bulkUploadResult[url]=%7B%7D&bulkUploadResult[userId]=%7B%7D&bulkUploadResult[userJoinPolicy]=%7B%7D&bulkUploadResult[zip]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch addBulkUploadResultAction action adds KalturaBulkUploadResult to the DB"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7bda5796-08bd-4794-b4dc-72e7d7db74ef"
            }
          ]
        },
        {
          "id": "16690209-e730-46b6-afbf-1a2a4238c8dc",
          "name": "batch.countBulkUploadEntries",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/countBulkUploadEntries?bulkUploadJobId=%7B%7D&bulkUploadObjectType=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns total created entries count and total error entries count"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6946eab7-5412-46a6-803d-584d3aac4487"
            }
          ]
        },
        {
          "id": "2331ea9a-e707-4e14-aa42-b878f96ae4b5",
          "name": "batch.getBulkUploadLastResult",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getBulkUploadLastResult?bulkUploadJobId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getBulkUploadLastResultAction action returns the last result of the bulk upload"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3d6060de-d985-4f5b-92c1-b63edee7439d"
            }
          ]
        },
        {
          "id": "65a19254-e4a2-4b13-91bb-257eacb9c6cd",
          "name": "batch.updateBulkUploadResults",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/updateBulkUploadResults?bulkUploadJobId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch updateBulkUploadResults action adds KalturaBulkUploadResult to the DB"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4ed4923f-b151-46f5-9318-397b9a51c446"
            }
          ]
        },
        {
          "id": "4ea0e7bc-f79c-4836-b626-3e58b0328d85",
          "name": "bulkUpload.abort",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload/action/abort?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Aborts the bulk upload and all its child jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f79a7cff-cfdf-4ee6-b601-f5ab467ece20"
            }
          ]
        },
        {
          "id": "6b4adc9e-15ba-4c69-80eb-11cf1a1b0f53",
          "name": "bulkUpload.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload/action/add?bulkUploadType=%7B%7D&conversionProfileId=%7B%7D&fileName=%7B%7D&No Name=%7B%7D&uploadedBy=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "csvFileData",
                  "value": "{}",
                  "disabled": false,
                  "description": "bulk upload file"
                }
              ]
            },
            "description": "Add new bulk upload batch job\n\nConversion profile id can be specified in the API or in the CSV file, the one in the CSV file will be stronger.\n\nIf no conversion profile was specified, partner's default will be used"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd80da05-ffd6-4d1c-bff6-72b994a1a174"
            }
          ]
        },
        {
          "id": "318fad70-2f4c-41d1-9479-e7ba4a5ba341",
          "name": "bulkUpload.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get bulk upload batch job by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11e7fcf4-cd4b-47be-bb01-d1a74cb20f1e"
            }
          ]
        },
        {
          "id": "c10eae5b-d7e5-4e20-8fd3-7c963f432757",
          "name": "bulkUpload.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload/action/list?No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List bulk upload batch jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3029d669-e253-4794-9511-d4ce684af0bb"
            }
          ]
        },
        {
          "id": "e115dece-a6dd-47e7-a2db-d957b4203cf9",
          "name": "bulkUpload.serve",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload/action/serve?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "serve action returan the original file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "98918a10-573b-492f-b148-b958dda080a5"
            }
          ]
        },
        {
          "id": "b4c45ac5-e169-4f18-ba29-ae12069db219",
          "name": "bulkUpload.serveLog",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload/action/serveLog?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "serveLog action returan the original file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fec60cf-9719-4bc9-8f86-e82bd4accdea"
            }
          ]
        },
        {
          "id": "a346c6b6-4b56-4aa7-9ee9-ce7d57910c92",
          "name": "bulk.abort",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload_bulk/action/abort?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Aborts the bulk upload and all its child jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09745db9-5411-46c7-b476-b32397360c68"
            }
          ]
        },
        {
          "id": "2f01ae86-75f1-4996-b414-c5cede7bbc6d",
          "name": "bulk.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload_bulk/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get bulk upload batch job by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "95adf9cc-dfcb-4007-8736-dbc1ba688ad4"
            }
          ]
        },
        {
          "id": "1fbff5a0-2760-48e1-a1d3-b9fc89d53648",
          "name": "bulk.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload_bulk/action/list?bulkUploadFilter[advancedSearch][attribute]=%7B%7D&bulkUploadFilter[advancedSearch][categoriesMatchOr]=%7B%7D&bulkUploadFilter[advancedSearch][categoryEntryStatusIn]=%7B%7D&bulkUploadFilter[advancedSearch][categoryIdEqual]=%7B%7D&bulkUploadFilter[advancedSearch][comparison]=%7B%7D&bulkUploadFilter[advancedSearch][contentLike]=%7B%7D&bulkUploadFilter[advancedSearch][contentMultiLikeAnd]=%7B%7D&bulkUploadFilter[advancedSearch][contentMultiLikeOr]=%7B%7D&bulkUploadFilter[advancedSearch][cuePointsFreeText]=%7B%7D&bulkUploadFilter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&bulkUploadFilter[advancedSearch][cuePointTypeIn]=%7B%7D&bulkUploadFilter[advancedSearch][depthGreaterThanEqual]=%7B%7D&bulkUploadFilter[advancedSearch][distributionProfileId]=%7B%7D&bulkUploadFilter[advancedSearch][distributionSunStatus]=%7B%7D&bulkUploadFilter[advancedSearch][entryDistributionFlag]=%7B%7D&bulkUploadFilter[advancedSearch][entryDistributionStatus]=%7B%7D&bulkUploadFilter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&bulkUploadFilter[advancedSearch][extendedStatusEqual]=%7B%7D&bulkUploadFilter[advancedSearch][extendedStatusIn]=%7B%7D&bulkUploadFilter[advancedSearch][field]=%7B%7D&bulkUploadFilter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&bulkUploadFilter[advancedSearch][idEqual]=%7B%7D&bulkUploadFilter[advancedSearch][idIn]=%7B%7D&bulkUploadFilter[advancedSearch][indexIdGreaterThan]=%7B%7D&bulkUploadFilter[advancedSearch][isQuiz]=%7B%7D&bulkUploadFilter[advancedSearch][items]=%7B%7D&bulkUploadFilter[advancedSearch][memberIdEq]=%7B%7D&bulkUploadFilter[advancedSearch][memberIdIn]=%7B%7D&bulkUploadFilter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&bulkUploadFilter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&bulkUploadFilter[advancedSearch][metadataProfileId]=%7B%7D&bulkUploadFilter[advancedSearch][noDistributionProfiles]=%7B%7D&bulkUploadFilter[advancedSearch][not]=%7B%7D&bulkUploadFilter[advancedSearch][objectType]=%7B%7D&bulkUploadFilter[advancedSearch][orderBy]=%7B%7D&bulkUploadFilter[advancedSearch][type]=%7B%7D&bulkUploadFilter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&bulkUploadFilter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&bulkUploadFilter[advancedSearch][userIdEqual]=%7B%7D&bulkUploadFilter[advancedSearch][userIdIn]=%7B%7D&bulkUploadFilter[advancedSearch][value]=%7B%7D&bulkUploadFilter[advancedSearch][watermarkId]=%7B%7D&bulkUploadFilter[bulkUploadObjectTypeEqual]=%7B%7D&bulkUploadFilter[bulkUploadObjectTypeIn]=%7B%7D&bulkUploadFilter[orderBy]=%7B%7D&bulkUploadFilter[statusEqual]=%7B%7D&bulkUploadFilter[statusIn]=%7B%7D&bulkUploadFilter[uploadedOnEqual]=%7B%7D&bulkUploadFilter[uploadedOnGreaterThanOrEqual]=%7B%7D&bulkUploadFilter[uploadedOnLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List bulk upload batch jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8dbb36b3-6dae-4c56-85c2-6cd3af6d4c4f"
            }
          ]
        },
        {
          "id": "c8eacdca-72cf-413b-a0c3-4d704a280833",
          "name": "bulk.serve",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload_bulk/action/serve?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "serve action returns the original file."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b825354-c6c0-417a-abc6-1b9d8ebaf3aa"
            }
          ]
        },
        {
          "id": "adc859fa-f091-4396-8c8d-c9b0bdadb89d",
          "name": "bulk.serveLog",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/bulkupload_bulk/action/serveLog?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "serveLog action returns the log file for the bulk-upload job."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c81a89dd-98c6-433c-8035-8b1e70733839"
            }
          ]
        },
        {
          "id": "1f04d1d4-cc3b-4a9a-89ab-1c0936fd3290",
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
              "id": "7dd9a4ec-3699-4569-8a8b-28c3f46bcc55"
            }
          ]
        }
      ]
    }
  ]
}