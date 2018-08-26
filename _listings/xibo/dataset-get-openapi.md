---
swagger: "2.0"
x-collection-name: Xibo
x-complete: 0
info:
  title: Xibo API DataSet Search
  description: Search this users DataSets
  termsOfService: http://xibo.org.uk/legal
  version: 1.0.0
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /dataset:
    get:
      summary: DataSet Search
      description: Search this users DataSets
      operationId: dataSetSearch
      x-api-path-slug: dataset-get
      parameters:
      - in: formData
        name: code
        description: Filter by DataSet Code
      - in: formData
        name: dataSet
        description: Filter by DataSet Name
      - in: formData
        name: dataSetId
        description: Filter by DataSet Id
      - in: formData
        name: embed
        description: Embed related data such as columns
      responses:
        200:
          description: OK
      tags:
      - DataSet
      - Search
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