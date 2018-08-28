---
swagger: "2.0"
x-collection-name: Google Fit
x-complete: 0
info:
  title: Google Fit API Add Data Point To Data Source Datasets
  description: Adds data points to a dataset. The dataset need not be previously created.
    All points within the given dataset will be returned with subsquent calls to retrieve
    this dataset. Data points can belong to more than one dataset. This method does
    not use patch semantics.
  contact:
    name: Google
    url: https://google.com
  version: v1
host: www.googleapis.com
basePath: /fitness/v1/users
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{userId}/dataSources/{dataSourceId}/datasets/{datasetId}:
    delete:
      summary: Delete All Data Source Datasets
      description: Performs an inclusive delete of all data points whose start and
        end times have any overlap with the time range specified by the dataset ID.
        For most data types, the entire data point will be deleted. For data types
        where the time span represents a consistent value (such as com.google.activity.segment),
        and a data point straddles either end point of the dataset, only the overlapping
        portion of the data point will be deleted.
      operationId: fitness.users.dataSources.datasets.delete
      x-api-path-slug: useriddatasourcesdatasourceiddatasetsdatasetid-delete
      parameters:
      - in: query
        name: currentTimeMillis
        description: The clients current time in milliseconds since epoch
      - in: path
        name: datasetId
        description: Dataset identifier that is a composite of the minimum data point
          start time and maximum data point end time represented as nanoseconds from
          the epoch
      - in: path
        name: dataSourceId
        description: The data stream ID of the data source that created the dataset
      - in: query
        name: modifiedTimeMillis
        description: When the operation was performed on the client
      - in: path
        name: userId
        description: Delete a dataset for the person identified
      responses:
        200:
          description: OK
      tags:
      - Dataset
    get:
      summary: Get All Data Source Datasets
      description: Returns a dataset containing all data points whose start and end
        times overlap with the specified range of the dataset minimum start time and
        maximum end time. Specifically, any data point whose start time is less than
        or equal to the dataset end time and whose end time is greater than or equal
        to the dataset start time.
      operationId: fitness.users.dataSources.datasets.get
      x-api-path-slug: useriddatasourcesdatasourceiddatasetsdatasetid-get
      parameters:
      - in: path
        name: datasetId
        description: Dataset identifier that is a composite of the minimum data point
          start time and maximum data point end time represented as nanoseconds from
          the epoch
      - in: path
        name: dataSourceId
        description: The data stream ID of the data source that created the dataset
      - in: query
        name: limit
        description: If specified, no more than this many data points will be included
          in the dataset
      - in: query
        name: pageToken
        description: The continuation token, which is used to page through large datasets
      - in: path
        name: userId
        description: Retrieve a dataset for the person identified
      responses:
        200:
          description: OK
      tags:
      - Dataset
    patch:
      summary: Add Data Point To Data Source Datasets
      description: Adds data points to a dataset. The dataset need not be previously
        created. All points within the given dataset will be returned with subsquent
        calls to retrieve this dataset. Data points can belong to more than one dataset.
        This method does not use patch semantics.
      operationId: fitness.users.dataSources.datasets.patch
      x-api-path-slug: useriddatasourcesdatasourceiddatasetsdatasetid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: currentTimeMillis
        description: The clients current time in milliseconds since epoch
      - in: path
        name: datasetId
        description: Dataset identifier that is a composite of the minimum data point
          start time and maximum data point end time represented as nanoseconds from
          the epoch
      - in: path
        name: dataSourceId
        description: The data stream ID of the data source that created the dataset
      - in: path
        name: userId
        description: Patch a dataset for the person identified
      responses:
        200:
          description: OK
      tags:
      - Dataset
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