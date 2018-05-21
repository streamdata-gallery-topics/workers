---
swagger: "2.0"
x-collection-name: Data.Gov
x-complete: 0
info:
  title: Data.gov API Get Workers Tasks
  description: Get a tasks status given its ID
  version: "3"
host: catalog.data.gov
basePath: /api/3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /workers/jobs/:
    get:
      summary: Get Workers Jobs
      description: List all scheduled jobs
      operationId: getWorkersJobs
      x-api-path-slug: workersjobs-get
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Jobs
    post:
      summary: Add Workers Jobs
      description: Create a new scheduled job
      operationId: postWorkersJobs
      x-api-path-slug: workersjobs-post
      parameters:
      - in: body
        name: payload
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Jobs
  /workers/jobs/schedulables:
    get:
      summary: Get Workers Jobs Schedulables
      description: List all schedulable jobs
      operationId: getWorkersJobsSchedulables
      x-api-path-slug: workersjobsschedulables-get
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Jobs
      - Schedulables
  /workers/jobs/{id}:
    delete:
      summary: Delete Workers Jobs
      description: Delete a single scheduled job
      operationId: deleteWorkersJobs
      x-api-path-slug: workersjobsid-delete
      parameters:
      - in: path
        name: id
        description: A job ID
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Jobs
    get:
      summary: Get Workers Jobs
      description: Fetch a single scheduled job
      operationId: getWorkersJobs
      x-api-path-slug: workersjobsid-get
      parameters:
      - in: path
        name: id
        description: A job ID
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Jobs
    put:
      summary: Put Workers Jobs
      description: Update a single scheduled job
      operationId: putWorkersJobs
      x-api-path-slug: workersjobsid-put
      parameters:
      - in: path
        name: id
        description: A job ID
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Jobs
  /workers/tasks/{id}:
    get:
      summary: Get Workers Tasks
      description: Get a tasks status given its ID
      operationId: getWorkersTasks
      x-api-path-slug: workerstasksid-get
      parameters:
      - in: path
        name: id
      responses:
        200:
          description: OK
      tags:
      - Workers
      - Tasks
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---