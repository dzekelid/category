{
  "info": {
    "name": "Kaltura VPaaS Post Service Categoryuser Action Addfrombulkupload",
    "_postman_id": "62052640-7c17-4c90-8e1c-77b9729923d2",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "d840b2a9-1535-4118-9c50-12cba2d1e31d",
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
              "id": "26d2b7e8-2137-4be6-aa59-7863c336b49e"
            }
          ]
        },
        {
          "id": "d0eb9dd5-7cb6-44cb-9f1a-bcb1fdeb7cfe",
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
              "id": "23fefe52-8647-4606-b838-fa48d2884717"
            }
          ]
        },
        {
          "id": "e707e488-3d32-4fe2-afef-8056cb212232",
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
              "id": "e7bfda22-66b7-4ad4-905b-2748a7d5fd7f"
            }
          ]
        },
        {
          "id": "884c825a-0b3b-4159-a132-2cb6a7de0fc9",
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
              "id": "21a19feb-f52f-46cc-ad7c-a99e70dc75c9"
            }
          ]
        },
        {
          "id": "7d39708a-bc49-4111-8dd4-019b5745244c",
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
              "id": "99012ba1-782d-4b3d-a28b-6779967c86f8"
            }
          ]
        },
        {
          "id": "750a1ad4-a6fc-4e6c-b6c4-07613c955d22",
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
              "id": "0ccd4517-b7ce-45e4-a632-415b2f3b5c9f"
            }
          ]
        },
        {
          "id": "f445c94d-4a56-4b27-bb32-6076a2725cc5",
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
              "id": "03e65050-9beb-4165-836e-eab1bb894b7c"
            }
          ]
        },
        {
          "id": "d41a2d1d-7e0b-4edf-88b8-98bcd020eb40",
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
              "id": "18dd21b3-659e-4e0b-b15b-8380e11b88f3"
            }
          ]
        },
        {
          "id": "1d424aaf-45df-4933-8927-00b185c01fbc",
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
              "id": "d9ea3e57-3ada-496c-aed5-13dcad4622c7"
            }
          ]
        },
        {
          "id": "4130d5e2-8cf8-47f1-a618-194f7bd98f6a",
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
              "id": "d2f862fc-e644-4157-816d-3631978267e0"
            }
          ]
        },
        {
          "id": "629f2365-d4b7-4837-8a15-83329d6e8c69",
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
              "id": "b51abf2f-bdb9-40b3-9205-34254b348dfe"
            }
          ]
        },
        {
          "id": "673358f6-c855-4ddb-9305-e82d3032093a",
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
              "id": "3edc9e1d-295a-4c7d-9a20-24f6e76dad3c"
            }
          ]
        },
        {
          "id": "d49113e5-be85-4031-b5d6-489c758af890",
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
              "id": "a7cf5f84-a8ce-4000-8979-02bd1af823fa"
            }
          ]
        },
        {
          "id": "d4137d78-e942-4dbf-99e3-3b9b48a902c6",
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
              "id": "5da66f1b-fe2e-4606-b75f-7792e34326da"
            }
          ]
        },
        {
          "id": "8d9885be-6ca2-40dc-a0ce-7872094b450f",
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
              "id": "06f6d489-726a-41fa-8978-955bddd439a2"
            }
          ]
        },
        {
          "id": "d8f360b5-1df5-44aa-963b-ea043f87f083",
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
              "id": "1d63903d-41af-4ade-b2d1-1678c26d0f08"
            }
          ]
        },
        {
          "id": "6b6e923a-e0c5-469c-ab71-9356b93159ba",
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
              "id": "7c94d13b-54c7-4d27-8adb-969a5c153011"
            }
          ]
        },
        {
          "id": "0742fa04-6b09-47db-b2fd-2545a72b2a13",
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
              "id": "a780fd55-34e7-4a22-aeb5-8ba990cf4cba"
            }
          ]
        },
        {
          "id": "ee2edee3-966f-4ce1-99f2-75d71a32e726",
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
              "id": "30eff161-c537-403e-b580-a1f9c12d88db"
            }
          ]
        },
        {
          "id": "fdbb519d-b4c0-4d8b-9716-910aa0dd169a",
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
              "id": "a74bce83-a40e-42b1-a648-23c26d1824d8"
            }
          ]
        }
      ]
    }
  ]
}