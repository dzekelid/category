{
  "info": {
    "name": "Kaltura VPaaS Get Service Categoryentry Action Addfrombulkupload",
    "_postman_id": "c1c9f1ce-bf9e-4970-a283-3926be5f6d63",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "4413bc9b-b1b4-4b38-b764-0d789f139d8a",
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
              "id": "dbd0148f-2244-4f2b-a637-f1b820424854"
            }
          ]
        },
        {
          "id": "3642c93c-7234-4cd1-afa0-088b07e8165e",
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
              "id": "b7d3ad4e-35ac-4e9b-b274-af5cd9f48ab7"
            }
          ]
        },
        {
          "id": "29c0d2cf-ae62-4ef0-a6d6-8c9f87ae7a0b",
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
              "id": "1f794156-1f13-4ebd-8b9c-6da9fc7bd466"
            }
          ]
        },
        {
          "id": "2133618f-652a-484d-a4ad-1efa64337b78",
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
              "id": "b74577a0-ecd2-4111-8f54-fc8ceb77a25a"
            }
          ]
        },
        {
          "id": "dc93ca5e-4a0a-45bc-8e39-ecb0755ca4bf",
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
              "id": "32a36253-2a75-4a70-8fcd-c30932bdf0c0"
            }
          ]
        },
        {
          "id": "161b2d55-a119-4a78-a096-dcdd50b42481",
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
              "id": "728a2cbb-b28c-4027-87cf-128a066d4fe1"
            }
          ]
        },
        {
          "id": "a39f09aa-4857-476f-8f9b-4364b364289d",
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
              "id": "dc6ee19a-752a-438e-b77d-7067f5e31ad3"
            }
          ]
        },
        {
          "id": "54885662-3912-46e6-ac49-4a86cd9088ce",
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
              "id": "ed9079bb-087a-4a55-b213-202b4d07409c"
            }
          ]
        },
        {
          "id": "f0a335ba-258e-4d12-9bee-b4dc2b6fbce4",
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
              "id": "242ef4e3-5cdc-4ef6-baee-eddab75c221d"
            }
          ]
        },
        {
          "id": "f39b72d0-f445-49ac-9d04-a95bf8be3ceb",
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
              "id": "36d37c93-6487-4d6a-acc3-5b44d7ff3cbb"
            }
          ]
        },
        {
          "id": "b737e608-9d24-4e3b-830c-e6ba29c1ed45",
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
              "id": "5595c72d-22fb-4126-855f-7924126f335d"
            }
          ]
        },
        {
          "id": "11fd7034-e29a-4b8a-8fad-e57aa625494b",
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
              "id": "f98d79f8-cac1-4a02-868c-c87e17c604bd"
            }
          ]
        },
        {
          "id": "b2c65909-4f41-426d-bbf9-b277f02dbea6",
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
              "id": "ea053844-5099-4627-926d-ce9e4061a502"
            }
          ]
        },
        {
          "id": "a6a714b4-4b25-4330-97b8-d37b2e886b08",
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
              "id": "e8b6725d-b441-4f3d-ac99-cf04d554ddd2"
            }
          ]
        },
        {
          "id": "b4d02adc-55b5-4125-987e-aa7b447e4690",
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
              "id": "844ca456-e749-4845-ac1b-a7f0c1439591"
            }
          ]
        },
        {
          "id": "356b0fa2-0ca1-47b1-b8a3-6252593aa231",
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
              "id": "e8ce7c20-832e-4309-90f5-f4357812d9f2"
            }
          ]
        },
        {
          "id": "ef58e5be-c09e-4ecf-8ea4-ee6ecf5961aa",
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
              "id": "2c5bb14c-ff79-4cd0-bbda-887983099560"
            }
          ]
        },
        {
          "id": "f9fe2e56-6bca-4306-8721-8a4ad87ab121",
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
              "id": "82ec71cd-9cd1-4ce3-bfcf-62f6b42fdab8"
            }
          ]
        },
        {
          "id": "368f24a4-c12f-4e58-9a7b-6b24328e6078",
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
              "id": "89110278-9801-47a9-bfb7-ec900a3b454b"
            }
          ]
        }
      ]
    }
  ]
}