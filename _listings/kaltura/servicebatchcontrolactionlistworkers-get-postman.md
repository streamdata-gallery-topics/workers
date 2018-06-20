{
  "info": {
    "name": "Kaltura VPaaS Get Service Batchcontrol Action Listworkers",
    "_postman_id": "c75c17e6-13ff-4708-8e96-1b05736b3ef3",
    "description": "list all Workers",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "a45b6e78-1a23-4073-876d-c20a34e4ae99",
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
              "id": "eb8237a5-33de-4167-88c4-2ab4d34133e3"
            }
          ]
        },
        {
          "id": "7affe1b7-aea6-440b-a1eb-971c3f6e82f4",
          "name": "batch.addMediaInfo",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/addMediaInfo?mediaInfo[audioBitRateMode]=%7B%7D&mediaInfo[audioBitRate]=%7B%7D&mediaInfo[audioChannels]=%7B%7D&mediaInfo[audioCodecId]=%7B%7D&mediaInfo[audioDuration]=%7B%7D&mediaInfo[audioFormat]=%7B%7D&mediaInfo[audioResolution]=%7B%7D&mediaInfo[audioSamplingRate]=%7B%7D&mediaInfo[complexityValue]=%7B%7D&mediaInfo[containerBitRate]=%7B%7D&mediaInfo[containerDuration]=%7B%7D&mediaInfo[containerFormat]=%7B%7D&mediaInfo[containerId]=%7B%7D&mediaInfo[containerProfile]=%7B%7D&mediaInfo[contentStreams]=%7B%7D&mediaInfo[fileSize]=%7B%7D&mediaInfo[flavorAssetId]=%7B%7D&mediaInfo[isFastStart]=%7B%7D&mediaInfo[maxGOP]=%7B%7D&mediaInfo[multiStreamInfo]=%7B%7D&mediaInfo[multiStream]=%7B%7D&mediaInfo[rawData]=%7B%7D&mediaInfo[scanType]=%7B%7D&mediaInfo[videoBitRateMode]=%7B%7D&mediaInfo[videoBitRate]=%7B%7D&mediaInfo[videoCodecId]=%7B%7D&mediaInfo[videoDar]=%7B%7D&mediaInfo[videoDuration]=%7B%7D&mediaInfo[videoFormat]=%7B%7D&mediaInfo[videoFrameRate]=%7B%7D&mediaInfo[videoHeight]=%7B%7D&mediaInfo[videoRotation]=%7B%7D&mediaInfo[videoWidth]=%7B%7D&mediaInfo[writingLib]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch addMediaInfoAction action saves a media info object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0b99c0f0-801b-4214-9e9b-4a0a7245f1ff"
            }
          ]
        },
        {
          "id": "8ada4d1a-9611-43c9-8884-e48a70b8671f",
          "name": "batch.checkEntryIsDone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/checkEntryIsDone?batchJobId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch checkEntryIsDone Check weather a specified entry is done converting and changes it to ready."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3469054f-639e-49ff-94ac-434f44ba8097"
            }
          ]
        },
        {
          "id": "6843f5ad-b7c5-4b3d-96a0-f153960da74f",
          "name": "batch.checkFileExists",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/checkFileExists?localPath=%7B%7D&No Name=%7B%7D&size=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch checkFileExists action check if the file exists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5c1c7f76-2001-4397-88bc-99b5830ac6c6"
            }
          ]
        },
        {
          "id": "a92ec87b-eb3a-4e6b-a42d-ebee1931b613",
          "name": "batch.cleanExclusiveJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/cleanExclusiveJobs?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch cleanExclusiveJobs action mark as fatal error all expired jobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "25fa190c-0541-44d1-9861-f031c0334599"
            }
          ]
        },
        {
          "id": "e56d46a7-b6f2-4417-a18f-e28abf3b4796",
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
              "id": "a50b7852-e263-44b6-b6aa-a301bb561495"
            }
          ]
        },
        {
          "id": "afe495d5-d5a4-438c-b566-a9fe563c2c1e",
          "name": "batch.freeExclusiveJob",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/freeExclusiveJob?id=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&No Name=%7B%7D&resetExecutionAttempts=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch freeExclusiveJobAction action allows to get a generic BatchJob"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "45e9b324-fbeb-4167-bb94-79381c44af17"
            }
          ]
        },
        {
          "id": "498e058b-95aa-44f6-af5b-5f3195f5060c",
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
              "id": "1bbb51ed-dcb2-4600-b4ab-f47df0fe0de0"
            }
          ]
        },
        {
          "id": "ee9f981f-2629-47e7-8d91-2386685d4943",
          "name": "batch.getExclusiveAlmostDone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getExclusiveAlmostDone?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[batchVersionEqual]=%7B%7D&filter[batchVersionGreaterThanOrEqual]=%7B%7D&filter[batchVersionLessThanOrEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[errNumberEqual]=%7B%7D&filter[errNumberIn]=%7B%7D&filter[errNumberNotIn]=%7B%7D&filter[errTypeEqual]=%7B%7D&filter[errTypeIn]=%7B%7D&filter[errTypeNotIn]=%7B%7D&filter[estimatedEffortGreaterThan]=%7B%7D&filter[estimatedEffortLessThan]=%7B%7D&filter[executionAttemptsGreaterThanOrEqual]=%7B%7D&filter[executionAttemptsLessThanOrEqual]=%7B%7D&filter[finishTimeGreaterThanOrEqual]=%7B%7D&filter[finishTimeLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idGreaterThanOrEqual]=%7B%7D&filter[jobSubTypeEqual]=%7B%7D&filter[jobSubTypeIn]=%7B%7D&filter[jobSubTypeNotIn]=%7B%7D&filter[jobTypeAndSubTypeIn]=%7B%7D&filter[jobTypeEqual]=%7B%7D&filter[jobTypeIn]=%7B%7D&filter[jobTypeNotIn]=%7B%7D&filter[lockVersionGreaterThanOrEqual]=%7B%7D&filter[lockVersionLessThanOrEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[partnerIdNotIn]=%7B%7D&filter[priorityEqual]=%7B%7D&filter[priorityGreaterThanOrEqual]=%7B%7D&filter[priorityIn]=%7B%7D&filter[priorityLessThanOrEqual]=%7B%7D&filter[priorityNotIn]=%7B%7D&filter[queueTimeGreaterThanOrEqual]=%7B%7D&filter[queueTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[urgencyGreaterThanOrEqual]=%7B%7D&filter[urgencyLessThanOrEqual]=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&maxExecutionTime=%7B%7D&No Name=%7B%7D&numberOfJobs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getExclusiveAlmostDone action allows to get a BatchJob that wait for remote closure"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0aaad1f7-a4ff-46c4-a640-42ba653805ca"
            }
          ]
        },
        {
          "id": "725611c8-0077-4d91-a272-8726dfa2a9dd",
          "name": "batch.getExclusiveJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getExclusiveJobs?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[batchVersionEqual]=%7B%7D&filter[batchVersionGreaterThanOrEqual]=%7B%7D&filter[batchVersionLessThanOrEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[errNumberEqual]=%7B%7D&filter[errNumberIn]=%7B%7D&filter[errNumberNotIn]=%7B%7D&filter[errTypeEqual]=%7B%7D&filter[errTypeIn]=%7B%7D&filter[errTypeNotIn]=%7B%7D&filter[estimatedEffortGreaterThan]=%7B%7D&filter[estimatedEffortLessThan]=%7B%7D&filter[executionAttemptsGreaterThanOrEqual]=%7B%7D&filter[executionAttemptsLessThanOrEqual]=%7B%7D&filter[finishTimeGreaterThanOrEqual]=%7B%7D&filter[finishTimeLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idGreaterThanOrEqual]=%7B%7D&filter[jobSubTypeEqual]=%7B%7D&filter[jobSubTypeIn]=%7B%7D&filter[jobSubTypeNotIn]=%7B%7D&filter[jobTypeAndSubTypeIn]=%7B%7D&filter[jobTypeEqual]=%7B%7D&filter[jobTypeIn]=%7B%7D&filter[jobTypeNotIn]=%7B%7D&filter[lockVersionGreaterThanOrEqual]=%7B%7D&filter[lockVersionLessThanOrEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[partnerIdNotIn]=%7B%7D&filter[priorityEqual]=%7B%7D&filter[priorityGreaterThanOrEqual]=%7B%7D&filter[priorityIn]=%7B%7D&filter[priorityLessThanOrEqual]=%7B%7D&filter[priorityNotIn]=%7B%7D&filter[queueTimeGreaterThanOrEqual]=%7B%7D&filter[queueTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[urgencyGreaterThanOrEqual]=%7B%7D&filter[urgencyLessThanOrEqual]=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&maxExecutionTime=%7B%7D&maxJobToPullForCache=%7B%7D&No Name=%7B%7D&numberOfJobs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getExclusiveJobsAction action allows to get a BatchJob"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "18153749-486f-44d6-81ff-7b36fef50cd4"
            }
          ]
        },
        {
          "id": "adf06580-5dde-47ab-aca3-0245ba5113e9",
          "name": "batch.getExclusiveNotificationJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getExclusiveNotificationJobs?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[batchVersionEqual]=%7B%7D&filter[batchVersionGreaterThanOrEqual]=%7B%7D&filter[batchVersionLessThanOrEqual]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[errNumberEqual]=%7B%7D&filter[errNumberIn]=%7B%7D&filter[errNumberNotIn]=%7B%7D&filter[errTypeEqual]=%7B%7D&filter[errTypeIn]=%7B%7D&filter[errTypeNotIn]=%7B%7D&filter[estimatedEffortGreaterThan]=%7B%7D&filter[estimatedEffortLessThan]=%7B%7D&filter[executionAttemptsGreaterThanOrEqual]=%7B%7D&filter[executionAttemptsLessThanOrEqual]=%7B%7D&filter[finishTimeGreaterThanOrEqual]=%7B%7D&filter[finishTimeLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idGreaterThanOrEqual]=%7B%7D&filter[jobSubTypeEqual]=%7B%7D&filter[jobSubTypeIn]=%7B%7D&filter[jobSubTypeNotIn]=%7B%7D&filter[jobTypeAndSubTypeIn]=%7B%7D&filter[jobTypeEqual]=%7B%7D&filter[jobTypeIn]=%7B%7D&filter[jobTypeNotIn]=%7B%7D&filter[lockVersionGreaterThanOrEqual]=%7B%7D&filter[lockVersionLessThanOrEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[partnerIdNotIn]=%7B%7D&filter[priorityEqual]=%7B%7D&filter[priorityGreaterThanOrEqual]=%7B%7D&filter[priorityIn]=%7B%7D&filter[priorityLessThanOrEqual]=%7B%7D&filter[priorityNotIn]=%7B%7D&filter[queueTimeGreaterThanOrEqual]=%7B%7D&filter[queueTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[urgencyGreaterThanOrEqual]=%7B%7D&filter[urgencyLessThanOrEqual]=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&maxExecutionTime=%7B%7D&No Name=%7B%7D&numberOfJobs=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getExclusiveNotificationJob action allows to get a BatchJob of type NOTIFICATION"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4b71c5c6-538f-4001-b31a-2175e05e7f9f"
            }
          ]
        },
        {
          "id": "f6aafbe2-6eda-4bea-a903-c89a3ce14ebc",
          "name": "batch.getQueueSize",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/getQueueSize?No Name=%7B%7D&workerQueueFilter[filter][advancedSearch][attribute]=%7B%7D&workerQueueFilter[filter][advancedSearch][categoriesMatchOr]=%7B%7D&workerQueueFilter[filter][advancedSearch][categoryEntryStatusIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][categoryIdEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][comparison]=%7B%7D&workerQueueFilter[filter][advancedSearch][contentLike]=%7B%7D&workerQueueFilter[filter][advancedSearch][contentMultiLikeAnd]=%7B%7D&workerQueueFilter[filter][advancedSearch][contentMultiLikeOr]=%7B%7D&workerQueueFilter[filter][advancedSearch][cuePointsFreeText]=%7B%7D&workerQueueFilter[filter][advancedSearch][cuePointSubTypeEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][cuePointTypeIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][depthGreaterThanEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][distributionProfileId]=%7B%7D&workerQueueFilter[filter][advancedSearch][distributionSunStatus]=%7B%7D&workerQueueFilter[filter][advancedSearch][entryDistributionFlag]=%7B%7D&workerQueueFilter[filter][advancedSearch][entryDistributionStatus]=%7B%7D&workerQueueFilter[filter][advancedSearch][entryDistributionValidationErrors]=%7B%7D&workerQueueFilter[filter][advancedSearch][extendedStatusEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][extendedStatusIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][field]=%7B%7D&workerQueueFilter[filter][advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&workerQueueFilter[filter][advancedSearch][idEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][idIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][indexIdGreaterThan]=%7B%7D&workerQueueFilter[filter][advancedSearch][isQuiz]=%7B%7D&workerQueueFilter[filter][advancedSearch][items]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberIdEq]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberIdIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberPermissionsMatchAnd]=%7B%7D&workerQueueFilter[filter][advancedSearch][memberPermissionsMatchOr]=%7B%7D&workerQueueFilter[filter][advancedSearch][metadataProfileId]=%7B%7D&workerQueueFilter[filter][advancedSearch][noDistributionProfiles]=%7B%7D&workerQueueFilter[filter][advancedSearch][not]=%7B%7D&workerQueueFilter[filter][advancedSearch][objectType]=%7B%7D&workerQueueFilter[filter][advancedSearch][orderBy]=%7B%7D&workerQueueFilter[filter][advancedSearch][type]=%7B%7D&workerQueueFilter[filter][advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][userIdEqual]=%7B%7D&workerQueueFilter[filter][advancedSearch][userIdIn]=%7B%7D&workerQueueFilter[filter][advancedSearch][value]=%7B%7D&workerQueueFilter[filter][advancedSearch][watermarkId]=%7B%7D&workerQueueFilter[filter][batchVersionEqual]=%7B%7D&workerQueueFilter[filter][batchVersionGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][batchVersionLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][createdAtGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][createdAtLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][entryIdEqual]=%7B%7D&workerQueueFilter[filter][errNumberEqual]=%7B%7D&workerQueueFilter[filter][errNumberIn]=%7B%7D&workerQueueFilter[filter][errNumberNotIn]=%7B%7D&workerQueueFilter[filter][errTypeEqual]=%7B%7D&workerQueueFilter[filter][errTypeIn]=%7B%7D&workerQueueFilter[filter][errTypeNotIn]=%7B%7D&workerQueueFilter[filter][estimatedEffortGreaterThan]=%7B%7D&workerQueueFilter[filter][estimatedEffortLessThan]=%7B%7D&workerQueueFilter[filter][executionAttemptsGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][executionAttemptsLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][finishTimeGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][finishTimeLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][idEqual]=%7B%7D&workerQueueFilter[filter][idGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][jobSubTypeEqual]=%7B%7D&workerQueueFilter[filter][jobSubTypeIn]=%7B%7D&workerQueueFilter[filter][jobSubTypeNotIn]=%7B%7D&workerQueueFilter[filter][jobTypeAndSubTypeIn]=%7B%7D&workerQueueFilter[filter][jobTypeEqual]=%7B%7D&workerQueueFilter[filter][jobTypeIn]=%7B%7D&workerQueueFilter[filter][jobTypeNotIn]=%7B%7D&workerQueueFilter[filter][lockVersionGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][lockVersionLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][objectType]=%7B%7D&workerQueueFilter[filter][orderBy]=%7B%7D&workerQueueFilter[filter][partnerIdEqual]=%7B%7D&workerQueueFilter[filter][partnerIdIn]=%7B%7D&workerQueueFilter[filter][partnerIdNotIn]=%7B%7D&workerQueueFilter[filter][priorityEqual]=%7B%7D&workerQueueFilter[filter][priorityGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][priorityIn]=%7B%7D&workerQueueFilter[filter][priorityLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][priorityNotIn]=%7B%7D&workerQueueFilter[filter][queueTimeGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][queueTimeLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][statusEqual]=%7B%7D&workerQueueFilter[filter][statusIn]=%7B%7D&workerQueueFilter[filter][statusNotIn]=%7B%7D&workerQueueFilter[filter][updatedAtGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][updatedAtLessThanOrEqual]=%7B%7D&workerQueueFilter[filter][urgencyGreaterThanOrEqual]=%7B%7D&workerQueueFilter[filter][urgencyLessThanOrEqual]=%7B%7D&workerQueueFilter[jobType]=%7B%7D&workerQueueFilter[schedulerId]=%7B%7D&workerQueueFilter[workerId]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch getQueueSize action get the queue size for job type"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "94c466c8-2296-4bd9-8643-e3a4331ba6f8"
            }
          ]
        },
        {
          "id": "fa56a2d2-9b96-4b8a-8f04-7ce0f090003f",
          "name": "batch.logConversion",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/logConversion?data=%7B%7D&flavorAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add the data to the flavor asset conversion log, creates it if doesn't exists"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c0991145-4144-40c5-a1c8-e3217a410a08"
            }
          ]
        },
        {
          "id": "5387539f-ab96-415c-b5ab-c82b4b19232c",
          "name": "batch.resetJobExecutionAttempts",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/resetJobExecutionAttempts?id=%7B%7D&jobType=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch resetJobExecutionAttempts action resets the execution attempts of the job"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ca95b52c-46e3-4c2b-b933-a2526685bbf0"
            }
          ]
        },
        {
          "id": "0dd63d09-6d8b-4988-8399-b6d4839af254",
          "name": "batch.suspendJobs",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/suspendJobs?No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch suspendJobs action suspends jobs from running."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa1a7ae4-dc3c-4a09-a800-ad7eafe84e36"
            }
          ]
        },
        {
          "id": "5e0acd95-02bd-4b14-a939-780ef5615806",
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
              "id": "042a574a-3a7c-4700-99f0-e593f9cb8758"
            }
          ]
        },
        {
          "id": "109b699e-39f8-4943-85b9-a25d572d4841",
          "name": "batch.updateExclusiveConvertCollectionJob",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/updateExclusiveConvertCollectionJob?id=%7B%7D&job[data][actualSrcFileSyncLocalPath]=%7B%7D&job[data][addedPrivacyContexts]=%7B%7D&job[data][amfArray]=%7B%7D&job[data][assetId]=%7B%7D&job[data][authenticationMethod]=%7B%7D&job[data][backupEncoderIP]=%7B%7D&job[data][backupStreamID]=%7B%7D&job[data][bodyParams]=%7B%7D&job[data][cachedObjectType]=%7B%7D&job[data][calculateComplexity]=%7B%7D&job[data][campaignId]=%7B%7D&job[data][captionAssetId]=%7B%7D&job[data][categoryId]=%7B%7D&job[data][changedCategoryId]=%7B%7D&job[data][columns]=%7B%7D&job[data][commandLinesStr]=%7B%7D&job[data][concatenatedDuration]=%7B%7D&job[data][connectTimeout]=%7B%7D&job[data][contentMatchPolicy]=%7B%7D&job[data][contentMoid]=%7B%7D&job[data][contentParameters]=%7B%7D&job[data][conversionProfileId]=%7B%7D&job[data][cpcode]=%7B%7D&job[data][createLink]=%7B%7D&job[data][createThumb]=%7B%7D&job[data][customData]=%7B%7D&job[data][customHeaders]=%7B%7D&job[data][data]=%7B%7D&job[data][deletedPrivacyContexts]=%7B%7D&job[data][description]=%7B%7D&job[data][destCategoryFullIds]=%7B%7D&job[data][destCategoryId]=%7B%7D&job[data][destDataFilePath]=%7B%7D&job[data][destDirLocalPath]=%7B%7D&job[data][destDirRemoteUrl]=%7B%7D&job[data][destFileLocalPath]=%7B%7D&job[data][destFileName]=%7B%7D&job[data][destFilePath]=%7B%7D&job[data][destFileSyncLocalPath]=%7B%7D&job[data][destFileSyncRemoteUrl]=%7B%7D&job[data][destFileSyncStoredPath]=%7B%7D&job[data][destVersion]=%7B%7D&job[data][destXsdPath]=%7B%7D&job[data][detectGOP]=%7B%7D&job[data][distributionProfileId]=%7B%7D&job[data][distributionProfile][accountId]=%7B%7D&job[data][distributionProfile][adFreeApplicationGuid]=%7B%7D&job[data][distributionProfile][adServerPartnerId]=%7B%7D&job[data][distributionProfile][allowAdsenseForVideo]=%7B%7D&job[data][distributionProfile][allowComments]=%7B%7D&job[data][distributionProfile][allowDownload]=%7B%7D&job[data][distributionProfile][allowEmbedding]=%7B%7D&job[data][distributionProfile][allowInvideo]=%7B%7D&job[data][distributionProfile][allowMidRollAds]=%7B%7D&job[data][distributionProfile][allowPostRollAds]=%7B%7D&job[data][distributionProfile][allowPreRollAds]=%7B%7D&job[data][distributionProfile][allowRatings]=%7B%7D&job[data][distributionProfile][allowResponses]=%7B%7D&job[data][distributionProfile][allowStreaming]=%7B%7D&job[data][distributionProfile][allowSyndication]=%7B%7D&job[data][distributionProfile][apiAuthorizeUrl]=%7B%7D&job[data][distributionProfile][apiHostUrl]=%7B%7D&job[data][distributionProfile][apikey]=%7B%7D&job[data][distributionProfile][asperaHost]=%7B%7D&job[data][distributionProfile][asperaLogin]=%7B%7D&job[data][distributionProfile][asperaPass]=%7B%7D&job[data][distributionProfile][asperaPrivateKey]=%7B%7D&job[data][distributionProfile][asperaPublicKey]=%7B%7D&job[data][distributionProfile][assetFilenameXslt]=%7B%7D&job[data][distributionProfile][assumeSuccess]=%7B%7D&job[data][distributionProfile][autoCreateFlavors]=%7B%7D&job[data][distributionProfile][autoCreateThumb]=%7B%7D&job[data][distributionProfile][backgroundImageStandard]=%7B%7D&job[data][distributionProfile][backgroundImageWide]=%7B%7D&job[data][distributionProfile][basePath]=%7B%7D&job[data][distributionProfile][blockOutsideOwnership]=%7B%7D&job[data][distributionProfile][bodyXslt]=%7B%7D&job[data][distributionProfile][captionAutosync]=%7B%7D&job[data][distributionProfile][categoryId]=%7B%7D&job[data][distributionProfile][certificateKey]=%7B%7D&job[data][distributionProfile][channelCopyright]=%7B%7D&job[data][distributionProfile][channelDescription]=%7B%7D&job[data][distributionProfile][channelGenerator]=%7B%7D&job[data][distributionProfile][channelGuid]=%7B%7D&job[data][distributionProfile][channelImageHeight]=%7B%7D&job[data][distributionProfile][channelImageLink]=%7B%7D&job[data][distributionProfile][channelImageTitle]=%7B%7D&job[data][distributionProfile][channelImageUrl]=%7B%7D&job[data][distributionProfile][channelImageWidth]=%7B%7D&job[data][distributionProfile][channelLanguage]=%7B%7D&job[data][distributionProfile][channelLink]=%7B%7D&job[data][distributionProfile][channelManagingEditor]=%7B%7D&job[data][distributionProfile][channelRating]=%7B%7D&job[data][distributionProfile][channelTitle]=%7B%7D&job[data][distributionProfile][claimType]=%7B%7D&job[data][distributionProfile][commercialPolicy]=%7B%7D&job[data][distributionProfile][contactEmail]=%7B%7D&job[data][distributionProfile][contactTelephone]=%7B%7D&job[data][distributionProfile][contentOwner]=%7B%7D&job[data][distributionProfile][copyright]=%7B%7D&job[data][distributionProfile][cPlatformTvSeriesField]=%7B%7D&job[data][distributionProfile][cPlatformTvSeries]=%7B%7D&job[data][distributionProfile][csId]=%7B%7D&job[data][distributionProfile][cuePointsProvider]=%7B%7D&job[data][distributionProfile][defaultCategory]=%7B%7D&job[data][distributionProfile][deleteEnabled]=%7B%7D&job[data][distributionProfile][deleteReference]=%7B%7D&job[data][distributionProfile][disableEpisodeNumberCustomValidation]=%7B%7D&job[data][distributionProfile][disableMetadata]=%7B%7D&job[data][distributionProfile][distributeCaptions]=%7B%7D&job[data][distributionProfile][distributeCuePoints]=%7B%7D&job[data][distributionProfile][distributeRemoteCaptionAssetContent]=%7B%7D&job[data][distributionProfile][distributeRemoteFlavorAssetContent]=%7B%7D&job[data][distributionProfile][distributeRemoteThumbAssetContent]=%7B%7D&job[data][distributionProfile][domainGuid]=%7B%7D&job[data][distributionProfile][domainName]=%7B%7D&job[data][distributionProfile][domain]=%7B%7D&job[data][distributionProfile][downloadPriceCode]=%7B%7D&job[data][distributionProfile][email]=%7B%7D&job[data][distributionProfile][enableAdServer]=%7B%7D&job[data][distributionProfile][entitlements]=%7B%7D&job[data][distributionProfile][entitlement]=%7B%7D&job[data][distributionProfile][feedAuthorName]=%7B%7D&job[data][distributionProfile][feedCopyright]=%7B%7D&job[data][distributionProfile][feedDescription]=%7B%7D&job[data][distributionProfile][feedImageHeight]=%7B%7D&job[data][distributionProfile][feedImageLink]=%7B%7D&job[data][distributionProfile][feedImageTitle]=%7B%7D&job[data][distributionProfile][feedImageUrl]=%7B%7D&job[data][distributionProfile][feedImageWidth]=%7B%7D&job[data][distributionProfile][feedLanguage]=%7B%7D&job[data][distributionProfile][feedLastBuildDate]=%7B%7D&job[data][distributionProfile][feedLink]=%7B%7D&job[data][distributionProfile][feedSpecVersion]=%7B%7D&job[data][distributionProfile][feedSubtitle]=%7B%7D&job[data][distributionProfile][feedTitle]=%7B%7D&job[data][distributionProfile][fieldConfigArray]=%7B%7D&job[data][distributionProfile][flavorAssetFilenameXslt]=%7B%7D&job[data][distributionProfile][flvFlavorParamsId]=%7B%7D&job[data][distributionProfile][ftpHost]=%7B%7D&job[data][distributionProfile][ftpLogin]=%7B%7D&job[data][distributionProfile][ftpPassword]=%7B%7D&job[data][distributionProfile][ftpPass]=%7B%7D&job[data][distributionProfile][ftpPath]=%7B%7D&job[data][distributionProfile][ftpUsername]=%7B%7D&job[data][distributionProfile][genericProviderId]=%7B%7D&job[data][distributionProfile][geoBlockingMapping]=%7B%7D&job[data][distributionProfile][googleClientId]=%7B%7D&job[data][distributionProfile][googleClientSecret]=%7B%7D&job[data][distributionProfile][googleTokenData]=%7B%7D&job[data][distributionProfile][hideViewCount]=%7B%7D&job[data][distributionProfile][host]=%7B%7D&job[data][distributionProfile][ignoreSchedulingInFeed]=%7B%7D&job[data][distributionProfile][ingestUrl]=%7B%7D&job[data][distributionProfile][instreamStandard]=%7B%7D&job[data][distributionProfile][instreamTrueview]=%7B%7D&job[data][distributionProfile][ips]=%7B%7D&job[data][distributionProfile][itemLink]=%7B%7D&job[data][distributionProfile][itemMediaRating]=%7B%7D&job[data][distributionProfile][itemsPerPage]=%7B%7D&job[data][distributionProfile][itemType]=%7B%7D&job[data][distributionProfile][itemXpathsToExtend]=%7B%7D&job[data][distributionProfile][mapAccessControlProfileIds]=%7B%7D&job[data][distributionProfile][mapCaptionParamsIds]=%7B%7D&job[data][distributionProfile][mapConversionProfileIds]=%7B%7D&job[data][distributionProfile][mapFlavorParamsIds]=%7B%7D&job[data][distributionProfile][mapMetadataProfileIds]=%7B%7D&job[data][distributionProfile][mapStorageProfileIds]=%7B%7D&job[data][distributionProfile][mapThumbParamsIds]=%7B%7D&job[data][distributionProfile][metadataFilenameXslt]=%7B%7D&job[data][distributionProfile][metadataProfileId]=%7B%7D&job[data][distributionProfile][metadataXpathsTriggerUpdate]=%7B%7D&job[data][distributionProfile][metadataXslt]=%7B%7D&job[data][distributionProfile][msnvideoCat]=%7B%7D&job[data][distributionProfile][msnvideoTopCat]=%7B%7D&job[data][distributionProfile][msnvideoTop]=%7B%7D&job[data][distributionProfile][name]=%7B%7D&job[data][distributionProfile][notificationEmail]=%7B%7D&job[data][distributionProfile][objectType]=%7B%7D&job[data][distributionProfile][optionalAssetDistributionRules]=%7B%7D&job[data][distributionProfile][optionalFlavorParamsIds]=%7B%7D&job[data][distributionProfile][optionalThumbDimensions]=%7B%7D&job[data][distributionProfile][overrideManualEdits]=%7B%7D&job[data][distributionProfile][ownerName]=%7B%7D&job[data][distributionProfile][pageAccessToken]=%7B%7D&job[data][distributionProfile][pageGroup]=%7B%7D&job[data][distributionProfile][pageId]=%7B%7D&job[data][distributionProfile][passphrase]=%7B%7D&job[data][distributionProfile][password]=%7B%7D&job[data][distributionProfile][permissions]=%7B%7D&job[data][distributionProfile][port]=%7B%7D&job[data][distributionProfile][priority]=%7B%7D&job[data][distributionProfile][privacyStatus]=%7B%7D&job[data][distributionProfile][processFeed]=%7B%7D&job[data][distributionProfile][protocol]=%7B%7D&job[data][distributionProfile][providerId]=%7B%7D&job[data][distributionProfile][providerName]=%7B%7D&job[data][distributionProfile][providerType]=%7B%7D&job[data][distributionProfile][rating]=%7B%7D&job[data][distributionProfile][recommendedDcForDownload]=%7B%7D&job[data][distributionProfile][recommendedDcForExecute]=%7B%7D&job[data][distributionProfile][recommendedStorageProfileForDownload]=%7B%7D&job[data][distributionProfile][releaseClaims]=%7B%7D&job[data][distributionProfile][remoteAssetParamsId]=%7B%7D&job[data][distributionProfile][replaceAirDates]=%7B%7D&job[data][distributionProfile][replaceGroup]=%7B%7D&job[data][distributionProfile][reportEnabled]=%7B%7D&job[data][distributionProfile][requiredAssetDistributionRules]=%7B%7D&job[data][distributionProfile][requiredFlavorParamsIds]=%7B%7D&job[data][distributionProfile][requiredThumbDimensions]=%7B%7D&job[data][distributionProfile][reRequestPermissions]=%7B%7D&job[data][distributionProfile][seasonNumber]=%7B%7D&job[data][distributionProfile][seasonSynopsis]=%7B%7D&job[data][distributionProfile][seasonTuneInInformation]=%7B%7D&job[data][distributionProfile][sendMetadataAfterAssets]=%7B%7D&job[data][distributionProfile][seriesAdditionalCategories]=%7B%7D&job[data][distributionProfile][seriesChannel]=%7B%7D&job[data][distributionProfile][seriesPrimaryCategory]=%7B%7D&job[data][distributionProfile][sftpBaseDir]=%7B%7D&job[data][distributionProfile][sftpBasePath]=%7B%7D&job[data][distributionProfile][sftpHost]=%7B%7D&job[data][distributionProfile][sftpLogin]=%7B%7D&job[data][distributionProfile][sftpPass]=%7B%7D&job[data][distributionProfile][sftpPort]=%7B%7D&job[data][distributionProfile][sftpPrivateKey]=%7B%7D&job[data][distributionProfile][sftpPublicKey]=%7B%7D&job[data][distributionProfile][shouldAddThumbExtension]=%7B%7D&job[data][distributionProfile][shouldIncludeCaptions]=%7B%7D&job[data][distributionProfile][shouldIncludeCuePoints]=%7B%7D&job[data][distributionProfile][slFlavorParamsId]=%7B%7D&job[data][distributionProfile][slHdFlavorParamsId]=%7B%7D&job[data][distributionProfile][sourceFlavorParamsId]=%7B%7D&job[data][distributionProfile][sourceFriendlyName]=%7B%7D&job[data][distributionProfile][source]=%7B%7D&job[data][distributionProfile][state]=%7B%7D&job[data][distributionProfile][status]=%7B%7D&job[data][distributionProfile][storageProfileId]=%7B%7D&job[data][distributionProfile][streamingPriceCode]=%7B%7D&job[data][distributionProfile][strict]=%7B%7D&job[data][distributionProfile][submitAction][ftpPassiveMode]=%7B%7D&job[data][distributionProfile][submitAction][httpFieldName]=%7B%7D&job[data][distributionProfile][submitAction][httpFileName]=%7B%7D&job[data][distributionProfile][submitAction][password]=%7B%7D&job[data][distributionProfile][submitAction][protocol]=%7B%7D&job[data][distributionProfile][submitAction][serverPath]=%7B%7D&job[data][distributionProfile][submitAction][serverUrl]=%7B%7D&job[data][distributionProfile][submitAction][username]=%7B%7D&job[data][distributionProfile][submitEnabled]=%7B%7D&job[data][distributionProfile][sunriseDefaultOffset]=%7B%7D&job[data][distributionProfile][sunsetDefaultOffset]=%7B%7D&job[data][distributionProfile][tags]=%7B%7D&job[data][distributionProfile][targetAccountId]=%7B%7D&job[data][distributionProfile][targetLoginId]=%7B%7D&job[data][distributionProfile][targetLoginPassword]=%7B%7D&job[data][distributionProfile][targetServiceUrl]=%7B%7D&job[data][distributionProfile][target]=%7B%7D&job[data][distributionProfile][thumbnailAssetFilenameXslt]=%7B%7D&job[data][distributionProfile][ugcPolicy]=%7B%7D&job[data][distributionProfile][updateEnabled]=%7B%7D&job[data][distributionProfile][upstreamNetworkId]=%7B%7D&job[data][distributionProfile][upstreamNetworkName]=%7B%7D&job[data][distributionProfile][upstreamVideoId]=%7B%7D&job[data][distributionProfile][urgentReference]=%7B%7D&job[data][distributionProfile][useCategoryEntries]=%7B%7D&job[data][distributionProfile][userAccessToken]=%7B%7D&job[data][distributionProfile][username]=%7B%7D&job[data][distributionProfile][user]=%7B%7D&job[data][distributionProfile][videoMediaType]=%7B%7D&job[data][distributionProfile][wmvFlavorParamsId]=%7B%7D&job[data][distributionProfile][xsltFile]=%7B%7D&job[data][distributionProfile][xsl]=%7B%7D&job[data][domainName]=%7B%7D&job[data][dropFolderFileIds]=%7B%7D&job[data][dropFolderFileId]=%7B%7D&job[data][dropFolderId]=%7B%7D&job[data][duration]=%7B%7D&job[data][dvrEnabled]=%7B%7D&job[data][dvrWindow]=%7B%7D&job[data][emailId]=%7B%7D&job[data][encoderIP]=%7B%7D&job[data][encoderPassword]=%7B%7D&job[data][encoderUsername]=%7B%7D&job[data][endDate]=%7B%7D&job[data][endObjectKey]=%7B%7D&job[data][endPoint]=%7B%7D&job[data][endTime]=%7B%7D&job[data][engineMessage]=%7B%7D&job[data][engineVersion]=%7B%7D&job[data][entryIds]=%7B%7D&job[data][entryId]=%7B%7D&job[data][eventsType]=%7B%7D&job[data][extractId3Tags]=%7B%7D&job[data][extraDestFileSyncs]=%7B%7D&job[data][fileIndex]=%7B%7D&job[data][fileLocation]=%7B%7D&job[data][fileName]=%7B%7D&job[data][fileSize]=%7B%7D&job[data][filesPermissionInS3]=%7B%7D&job[data][filter][advancedSearch][attribute]=%7B%7D&job[data][filter][advancedSearch][categoriesMatchOr]=%7B%7D&job[data][filter][advancedSearch][categoryEntryStatusIn]=%7B%7D&job[data][filter][advancedSearch][categoryIdEqual]=%7B%7D&job[data][filter][advancedSearch][comparison]=%7B%7D&job[data][filter][advancedSearch][contentLike]=%7B%7D&job[data][filter][advancedSearch][contentMultiLikeAnd]=%7B%7D&job[data][filter][advancedSearch][contentMultiLikeOr]=%7B%7D&job[data][filter][advancedSearch][cuePointsFreeText]=%7B%7D&job[data][filter][advancedSearch][cuePointSubTypeEqual]=%7B%7D&job[data][filter][advancedSearch][cuePointTypeIn]=%7B%7D&job[data][filter][advancedSearch][depthGreaterThanEqual]=%7B%7D&job[data][filter][advancedSearch][distributionProfileId]=%7B%7D&job[data][filter][advancedSearch][distributionSunStatus]=%7B%7D&job[data][filter][advancedSearch][entryDistributionFlag]=%7B%7D&job[data][filter][advancedSearch][entryDistributionStatus]=%7B%7D&job[data][filter][advancedSearch][entryDistributionValidationErrors]=%7B%7D&job[data][filter][advancedSearch][extendedStatusEqual]=%7B%7D&job[data][filter][advancedSearch][extendedStatusIn]=%7B%7D&job[data][filter][advancedSearch][field]=%7B%7D&job[data][filter][advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&job[data][filter][advancedSearch][idEqual]=%7B%7D&job[data][filter][advancedSearch][idIn]=%7B%7D&job[data][filter][advancedSearch][indexIdGreaterThan]=%7B%7D&job[data][filter][advancedSearch][isQuiz]=%7B%7D&job[data][filter][advancedSearch][items]=%7B%7D&job[data][filter][advancedSearch][memberIdEq]=%7B%7D&job[data][filter][advancedSearch][memberIdIn]=%7B%7D&job[data][filter][advancedSearch][memberPermissionsMatchAnd]=%7B%7D&job[data][filter][advancedSearch][memberPermissionsMatchOr]=%7B%7D&job[data][filter][advancedSearch][metadataProfileId]=%7B%7D&job[data][filter][advancedSearch][noDistributionProfiles]=%7B%7D&job[data][filter][advancedSearch][not]=%7B%7D&job[data][filter][advancedSearch][objectType]=%7B%7D&job[data][filter][advancedSearch][orderBy]=%7B%7D&job[data][filter][advancedSearch][type]=%7B%7D&job[data][filter][advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&job[data][filter][advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&job[data][filter][advancedSearch][userIdEqual]=%7B%7D&job[data][filter][advancedSearch][userIdIn]=%7B%7D&job[data][filter][advancedSearch][value]=%7B%7D&job[data][filter][advancedSearch][watermarkId]=%7B%7D&job[data][filter][orderBy]=%7B%7D&job[data][flavorAssetId]=%7B%7D&job[data][flavorParamsId]=%7B%7D&job[data][flavorParamsOutputId]=%7B%7D&job[data][flavorParamsOutput][anamorphicPixels]=%7B%7D&job[data][flavorParamsOutput][aspectRatioProcessingMode]=%7B%7D&job[data][flavorParamsOutput][audioBitrate]=%7B%7D&job[data][flavorParamsOutput][audioChannels]=%7B%7D&job[data][flavorParamsOutput][audioCodec]=%7B%7D&job[data][flavorParamsOutput][audioSampleRate]=%7B%7D&job[data][flavorParamsOutput][clipDuration]=%7B%7D&job[data][flavorParamsOutput][clipOffset]=%7B%7D&job[data][flavorParamsOutput][commandLinesStr]=%7B%7D&job[data][flavorParamsOutput][contentAwareness]=%7B%7D&job[data][flavorParamsOutput][conversionEnginesExtraParams]=%7B%7D&job[data][flavorParamsOutput][conversionEngines]=%7B%7D&job[data][flavorParamsOutput][deinterlice]=%7B%7D&job[data][flavorParamsOutput][densityHeight]=%7B%7D&job[data][flavorParamsOutput][densityWidth]=%7B%7D&job[data][flavorParamsOutput][depth]=%7B%7D&job[data][flavorParamsOutput][description]=%7B%7D&job[data][flavorParamsOutput][engineVersion]=%7B%7D&job[data][flavorParamsOutput][flashVersion]=%7B%7D&job[data][flavorParamsOutput][flavorAssetId]=%7B%7D&job[data][flavorParamsOutput][flavorAssetVersion]=%7B%7D&job[data][flavorParamsOutput][flavorParamsId]=%7B%7D&job[data][flavorParamsOutput][flavorParamsVersion]=%7B%7D&job[data][flavorParamsOutput][forcedKeyFramesMode]=%7B%7D&job[data][flavorParamsOutput][forceFrameToMultiplication16]=%7B%7D&job[data][flavorParamsOutput][format]=%7B%7D&job[data][flavorParamsOutput][frameRate]=%7B%7D&job[data][flavorParamsOutput][gopSize]=%7B%7D&job[data][flavorParamsOutput][height]=%7B%7D&job[data][flavorParamsOutput][isAvoidForcedKeyFrames]=%7B%7D&job[data][flavorParamsOutput][isAvoidVideoShrinkBitrateToSource]=%7B%7D&job[data][flavorParamsOutput][isAvoidVideoShrinkFramesizeToSource]=%7B%7D&job[data][flavorParamsOutput][isCropIMX]=%7B%7D&job[data][flavorParamsOutput][isEncrypted]=%7B%7D&job[data][flavorParamsOutput][isGopInSec]=%7B%7D&job[data][flavorParamsOutput][isVideoFrameRateForLowBrAppleHls]=%7B%7D&job[data][flavorParamsOutput][maxFrameRate]=%7B%7D&job[data][flavorParamsOutput][mediaParserType]=%7B%7D&job[data][flavorParamsOutput][multiStream]=%7B%7D&job[data][flavorParamsOutput][name]=%7B%7D&job[data][flavorParamsOutput][objectType]=%7B%7D&job[data][flavorParamsOutput][operators]=%7B%7D&job[data][flavorParamsOutput][optimizationPolicy]=%7B%7D&job[data][flavorParamsOutput][partnerId]=%7B%7D&job[data][flavorParamsOutput][poly2Bitmap]=%7B%7D&job[data][flavorParamsOutput][readonly]=%7B%7D&job[data][flavorParamsOutput][readyBehavior]=%7B%7D&job[data][flavorParamsOutput][remoteStorageProfileIds]=%7B%7D&job[data][flavorParamsOutput][requiredPermissions]=%7B%7D&job[data][flavorParamsOutput][rotate]=%7B%7D&job[data][flavorParamsOutput][sizeHeight]=%7B%7D&job[data][flavorParamsOutput][sizeWidth]=%7B%7D&job[data][flavorParamsOutput][sourceAssetParamsIds]=%7B%7D&job[data][flavorParamsOutput][sourceRemoteStorageProfileId]=%7B%7D&job[data][flavorParamsOutput][subtitlesData]=%7B%7D&job[data][flavorParamsOutput][systemName]=%7B%7D&job[data][flavorParamsOutput][tags]=%7B%7D&job[data][flavorParamsOutput][twoPass]=%7B%7D&job[data][flavorParamsOutput][videoBitrateTolerance]=%7B%7D&job[data][flavorParamsOutput][videoBitrate]=%7B%7D&job[data][flavorParamsOutput][videoCodec]=%7B%7D&job[data][flavorParamsOutput][videoConstantBitrate]=%7B%7D&job[data][flavorParamsOutput][watermarkData]=%7B%7D&job[data][flavorParamsOutput][widevineDistributionEndDate]=%7B%7D&job[data][flavorParamsOutput][widevineDistributionStartDate]=%7B%7D&job[data][flavorParamsOutput][width]=%7B%7D&job[data][flavors]=%7B%7D&job[data][force]=%7B%7D&job[data][fromEmail]=%7B%7D&job[data][fromName]=%7B%7D&job[data][fromPartnerId]=%7B%7D&job[data][ftpPassiveMode]=%7B%7D&job[data][inputFileSyncLocalPath]=%7B%7D&job[data][inputXmlLocalPath]=%7B%7D&job[data][inputXmlRemoteUrl]=%7B%7D&job[data][isHtml]=%7B%7D&job[data][keepDistributionItem]=%7B%7D&job[data][ksType]=%7B%7D&job[data][language]=%7B%7D&job[data][lastCuePointSyncTime]=%7B%7D&job[data][lastMovedCategoryEntryPageIndex]=%7B%7D&job[data][lastMovedCategoryId]=%7B%7D&job[data][lastMovedCategoryPageIndex]=%7B%7D&job[data][lastSegmentDrift]=%7B%7D&job[data][lastSegmentDuration]=%7B%7D&job[data][lastUpdatedCategoryCreatedAt]=%7B%7D&job[data][lastUpdatedCategoryEntryCreatedAt]=%7B%7D&job[data][liveEntryId]=%7B%7D&job[data][localFileSyncPath]=%7B%7D&job[data][logFileSyncLocalPath]=%7B%7D&job[data][logFileSyncRemoteUrl]=%7B%7D&job[data][mailPriority]=%7B%7D&job[data][mailType]=%7B%7D&job[data][maxResults]=%7B%7D&job[data][mediaServerIndex]=%7B%7D&job[data][mediaType]=%7B%7D&job[data][metadataId]=%7B%7D&job[data][metadataProfileId]=%7B%7D&job[data][method]=%7B%7D&job[data][minSendDate]=%7B%7D&job[data][modifiedAttributes]=%7B%7D&job[data][monitorSyncCompletion]=%7B%7D&job[data][moveFromChildren]=%7B%7D&job[data][multiLanaguageCaptionAssetId]=%7B%7D&job[data][notificationEmail]=%7B%7D&job[data][notificationResult]=%7B%7D&job[data][numberOfAttempts]=%7B%7D&job[data][objectData][conversionProfileId]=%7B%7D&job[data][objectData][objectType]=%7B%7D&job[data][objectId]=%7B%7D&job[data][objectType]=%7B%7D&job[data][objType]=%7B%7D&job[data][offset]=%7B%7D&job[data][outputPath]=%7B%7D&job[data][parsedSlug]=%7B%7D&job[data][parsedUserId]=%7B%7D&job[data][passPhrase]=%7B%7D&job[data][password]=%7B%7D&job[data][plays]=%7B%7D&job[data][primaryBroadcastingUrl]=%7B%7D&job[data][primaryContact]=%7B%7D&job[data][privateKey]=%7B%7D&job[data][protocol]=%7B%7D&job[data][providerData][additionalParameters]=%7B%7D&job[data][providerData][captionAssetFormats]=%7B%7D&job[data][providerData][entryId]=%7B%7D&job[data][providerData][exampleUrl]=%7B%7D&job[data][providerData][fidelity]=%7B%7D&job[data][providerData][flavorAssetId]=%7B%7D&job[data][providerData][metadataProfileId]=%7B%7D&job[data][providerData][objectType]=%7B%7D&job[data][providerData][priority]=%7B%7D&job[data][providerData][replaceMediaContent]=%7B%7D&job[data][providerData][spokenLanguage]=%7B%7D&job[data][providerData][transcriptAssetId]=%7B%7D&job[data][providerData][transcriptId]=%7B%7D&job[data][providerData][voicebaseApiKey]=%7B%7D&job[data][providerData][voicebaseApiPassword]=%7B%7D&job[data][providerType]=%7B%7D&job[data][provisioningParams]=%7B%7D&job[data][publicKey]=%7B%7D&job[data][puserId]=%7B%7D&job[data][recipientEmail]=%7B%7D&job[data][recipientId]=%7B%7D&job[data][recipientName]=%7B%7D&job[data][referenceTime]=%7B%7D&job[data][remoteMediaId]=%7B%7D&job[data][resultsFilePath]=%7B%7D&job[data][returnVal]=%7B%7D&job[data][rtmp]=%7B%7D&job[data][s3Region]=%7B%7D&job[data][scanResult]=%7B%7D&job[data][secondaryBroadcastingUrl]=%7B%7D&job[data][secondaryContact]=%7B%7D&job[data][separator]=%7B%7D&job[data][serverPassPhrase]=%7B%7D&job[data][serverPassword]=%7B%7D&job[data][serverPrivateKey]=%7B%7D&job[data][serverPublicKey]=%7B%7D&job[data][serverUrl]=%7B%7D&job[data][serverUsername]=%7B%7D&job[data][server][dc]=%7B%7D&job[data][server][description]=%7B%7D&job[data][server][host]=%7B%7D&job[data][server][name]=%7B%7D&job[data][server][objectType]=%7B%7D&job[data][server][password]=%7B%7D&job[data][server][port]=%7B%7D&job[data][server][protocol]=%7B%7D&job[data][server][systemName]=%7B%7D&job[data][server][username]=%7B%7D&job[data][serviceToken]=%7B%7D&job[data][signatureType]=%7B%7D&job[data][signSecret]=%7B%7D&job[data][srcAssetId]=%7B%7D&job[data][srcAssetType]=%7B%7D&job[data][srcCategoryId]=%7B%7D&job[data][srcFilePath]=%7B%7D&job[data][srcFileSyncId]=%7B%7D&job[data][srcFileSyncLocalPath]=%7B%7D&job[data][srcFileSyncRemoteUrl]=%7B%7D&job[data][srcFileSyncs]=%7B%7D&job[data][srcFiles]=%7B%7D&job[data][srcFileUrl]=%7B%7D&job[data][srcVersion]=%7B%7D&job[data][srcXslPath]=%7B%7D&job[data][sseKmsKeyId]=%7B%7D&job[data][sseType]=%7B%7D&job[data][sslCertificatePassword]=%7B%7D&job[data][sslCertificateType]=%7B%7D&job[data][sslCertificate]=%7B%7D&job[data][sslEngineDefault]=%7B%7D&job[data][sslEngine]=%7B%7D&job[data][sslKeyPassword]=%7B%7D&job[data][sslKeyType]=%7B%7D&job[data][sslKey]=%7B%7D&job[data][sslVersion]=%7B%7D&job[data][startObjectKey]=%7B%7D&job[data][status]=%7B%7D&job[data][streamID]=%7B%7D&job[data][streamName]=%7B%7D&job[data][streamType]=%7B%7D&job[data][subjectParams]=%7B%7D&job[data][syncMode]=%7B%7D&job[data][systemPassword]=%7B%7D&job[data][systemUserName]=%7B%7D&job[data][templateId]=%7B%7D&job[data][templatePath]=%7B%7D&job[data][thumbAssetId]=%7B%7D&job[data][thumbBitrate]=%7B%7D&job[data][thumbHeight]=%7B%7D&job[data][thumbOffset]=%7B%7D&job[data][thumbParamsOutputId]=%7B%7D&job[data][thumbPath]=%7B%7D&job[data][timeout]=%7B%7D&job[data][timeReference]=%7B%7D&job[data][timeZoneOffset]=%7B%7D&job[data][toPartnerId]=%7B%7D&job[data][totalVodDuration]=%7B%7D&job[data][to][categoryUserFilter][categoryDirectMembers]=%7B%7D&job[data][to][categoryUserFilter][categoryFullIdsEqual]=%7B%7D&job[data][to][categoryUserFilter][categoryFullIdsStartsWith]=%7B%7D&job[data][to][categoryUserFilter][categoryIdEqual]=%7B%7D&job[data][to][categoryUserFilter][categoryIdIn]=%7B%7D&job[data][to][categoryUserFilter][createdAtGreaterThanOrEqual]=%7B%7D&job[data][to][categoryUserFilter][createdAtLessThanOrEqual]=%7B%7D&job[data][to][categoryUserFilter][freeText]=%7B%7D&job[data][to][categoryUserFilter][orderBy]=%7B%7D&job[data][to][categoryUserFilter][permissionLevelEqual]=%7B%7D&job[data][to][categoryUserFilter][permissionLevelIn]=%7B%7D&job[data][to][categoryUserFilter][permissionNamesMatchAnd]=%7B%7D&job[data][to][categoryUserFilter][permissionNamesMatchOr]=%7B%7D&job[data][to][categoryUserFilter][permissionNamesNotContains]=%7B%7D&job[data][to][categoryUserFilter][relatedGroupsByUserId]=%7B%7D&job[data][to][categoryUserFilter][statusEqual]=%7B%7D&job[data][to][categoryUserFilter][statusIn]=%7B%7D&job[data][to][categoryUserFilter][updatedAtGreaterThanOrEqual]=%7B%7D&job[data][to][categoryUserFilter][updatedAtLessThanOrEqual]=%7B%7D&job[data][to][categoryUserFilter][updateMethodEqual]=%7B%7D&job[data][to][categoryUserFilter][updateMethodIn]=%7B%7D&job[data][to][categoryUserFilter][userIdEqual]=%7B%7D&job[data][to][categoryUserFilter][userIdIn]=%7B%7D&job[data][to][emailRecipients]=%7B%7D&job[data][to][filter][createdAtGreaterThanOrEqual]=%7B%7D&job[data][to][filter][createdAtLessThanOrEqual]=%7B%7D&job[data][to][filter][emailLike]=%7B%7D&job[data][to][filter][emailStartsWith]=%7B%7D&job[data][to][filter][firstNameOrLastNameStartsWith]=%7B%7D&job[data][to][filter][firstNameStartsWith]=%7B%7D&job[data][to][filter][idEqual]=%7B%7D&job[data][to][filter][idIn]=%7B%7D&job[data][to][filter][idOrScreenNameStartsWith]=%7B%7D&job[data][to][filter][isAdminEqual]=%7B%7D&job[data][to][filter][lastNameStartsWith]=%7B%7D&job[data][to][filter][loginEnabledEqual]=%7B%7D&job[data][to][filter][objectType]=%7B%7D&job[data][to][filter][orderBy]=%7B%7D&job[data][to][filter][partnerIdEqual]=%7B%7D&job[data][to][filter][permissionNamesMultiLikeAnd]=%7B%7D&job[data][to][filter][permissionNamesMultiLikeOr]=%7B%7D&job[data][to][filter][roleIdEqual]=%7B%7D&job[data][to][filter][roleIdsEqual]=%7B%7D&job[data][to][filter][roleIdsIn]=%7B%7D&job[data][to][filter][screenNameLike]=%7B%7D&job[data][to][filter][screenNameStartsWith]=%7B%7D&job[data][to][filter][statusEqual]=%7B%7D&job[data][to][filter][statusIn]=%7B%7D&job[data][to][filter][tagsMultiLikeAnd]=%7B%7D&job[data][to][filter][tagsMultiLikeOr]=%7B%7D&job[data][to][filter][typeEqual]=%7B%7D&job[data][to][filter][typeIn]=%7B%7D&job[data][to][objectType]=%7B%7D&job[data][typeAsString]=%7B%7D&job[data][type]=%7B%7D&job[data][url]=%7B%7D&job[data][userId]=%7B%7D&job[data][username]=%7B%7D&job[data][userRoles]=%7B%7D&job[data][views]=%7B%7D&job[data][virusFoundAction]=%7B%7D&job[data][vodEntryId]=%7B%7D&job[data][webexHostId]=%7B%7D&job[data][wsdlPassword]=%7B%7D&job[data][wsdlUsername]=%7B%7D&job[data][wvAssetIds]=%7B%7D&job[entryId]=%7B%7D&job[entryName]=%7B%7D&job[jobSubType]=%7B%7D&lockKey[batchIndex]=%7B%7D&lockKey[schedulerId]=%7B%7D&lockKey[workerId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "batch updateExclusiveConvertCollectionJobAction action updates a BatchJob of type CONVERT_PROFILE that was claimed using the getExclusiveConvertJobs"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6a438e3a-53f3-40f1-857e-a51dc5d3c187"
            }
          ]
        },
        {
          "id": "705b864d-3e9f-42c3-9034-7ae95c939d06",
          "name": "batch.updateExclusiveJob",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/batch/action/updateExclusiveJob?id=%7B%7D&job[data][actualSrcFileSyncLocalPath]=%7B%7D&job[data][addedPrivacyContexts]=%7B%7D&job[data][amfArray]=%7B%7D&job[data][assetId]=%7B%7D&job[data][authenticationMethod]=%7B%7D&job[data][backupEncoderIP]=%7B%7D&job[data][backupStreamID]=%7B%7D&job[data][bodyParams]=%7B%7D&job[data][cachedObjectType]=%7B%7D&job[data][calculateComplexity]=%7B%7D&job[data][campaignId]=%7B%7D&job[data][captionAssetId]=%7B%7D&job[data][categoryId]=%7B%7D&job[data][changedCategoryId]=%7B%7D&job[data][columns]=%7B%7D&job[data][commandLinesStr]=%7B%7D&job[data][concatenatedDuration]=%7B%7D&job[data][connectTimeout]=%7B%7D&job[data][contentMatchPolicy]=%7B%7D&job[data][contentMoid]=%7B%7D&job[data][contentParameters]=%7B%7D&job[data][conversionProfileId]=%7B%7D&job[data][cpcode]=%7B%7D&job[data][createLink]=%7B%7D&job[data][createThumb]=%7B%7D&job[data][customData]=%7B%7D&job[data][customHeaders]=%7B%7D&job[data][data]=%7B%7D&job[data][deletedPrivacyContexts]=%7B%7D&job[data][description]=%7B%7D&job[data][destCategoryFullIds]=%7B%7D&job[data][destCategoryId]=%7B%7D&job[data][destDataFilePath]=%7B%7D&job[data][destDirLocalPath]=%7B%7D&job[data][destDirRemoteUrl]=%7B%7D&job[data][destFileLocalPath]=%7B%7D&job[data][destFileName]=%7B%7D&job[data][destFilePath]=%7B%7D&job[data][destFileSyncLocalPath]=%7B%7D&job[data][destFileSyncRemoteUrl]=%7B%7D&job[data][destFileSyncStoredPath]=%7B%7D&job[data][destVersion]=%7B%7D&job[data][destXsdPath]=%7B%7D&job[data][detectGOP]=%7B%7D&job[data][distributionProfileId]=%7B%7D&job[data][distributionProfile][accountId]=%7B%7D&job[data][distributionProfile][adFreeApplicationGuid]=%7B%7D&job[data][distributionProfile][adServerPartnerId]=%7B%7D&job[data][distributionProfile][allowAdsenseForVideo]=%7B%7D&job[data][distributionProfile][allowComments]=%7B%7D&job[data][distributionProfile][allowDownload]=%7B%7D&job[data][distributionProfile][allowEmbedding]=%7B%7D&job[data][distributionProfile][allowInvideo]=%7B%7D&job[data][distributionProfile][allowMidRollAds]=%7B%7D&job[data][distributionProfile][allowPostRollAds]=%7B%7D&job[data][distributionProfile][allowPreRollAds]=%7B%7D&job[data][distributionProfile][allowRatings]=%7B%7D&job[data][distributionProfile][allowResponses]=%7B%7D&job[data][distributionProfile][allowStreaming]=%7B%7D&job[data][distributionProfile][allowSyndication]=%7B%7D&job[data][distributionProfile][apiAuthorizeUrl]=%7B%7D&job[data][distributionProfile][apiHostUrl]=%7B%7D&job[data][distributionProfile][apikey]=%7B%7D&job[data][distributionProfile][asperaHost]=%7B%7D&job[data][distributionProfile][asperaLogin]=%7B%7D&job[data][distributionProfile][asperaPass]=%7B%7D&job[data][distributionProfile][asperaPrivateKey]=%7B%7D&job[