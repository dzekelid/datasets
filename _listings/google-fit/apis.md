---
name: Google Fit
x-slug: google-fit
description: Google Fit is an open ecosystem that allows developers to upload fitness
  data to a central repository where users can access their data from different devices
  and apps in one location. Fitness apps can store data from any wearable or sensor.
  Fitness apps can access data created by any app. Users fitness data is persisted
  when they upgrade their fitness devices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Datasets
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-fit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitness - Delete All Data Source Datasets
  x-api-slug: useriddatasourcesdatasourceiddatasetsdatasetid-delete
  description: Performs an inclusive delete of all data points whose start and end
    times have any overlap with the time range specified by the dataset ID. For most
    data types, the entire data point will be deleted. For data types where the time
    span represents a consistent value (such as com.google.activity.segment), and
    a data point straddles either end point of the dataset, only the overlapping portion
    of the data point will be deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-fit/useriddatasourcesdatasourceiddatasetsdatasetid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-fit/useriddatasourcesdatasourceiddatasetsdatasetid-delete-openapi.md
- name: Fitness - Get All Data Source Datasets
  x-api-slug: useriddatasourcesdatasourceiddatasetsdatasetid-get
  description: Returns a dataset containing all data points whose start and end times
    overlap with the specified range of the dataset minimum start time and maximum
    end time. Specifically, any data point whose start time is less than or equal
    to the dataset end time and whose end time is greater than or equal to the dataset
    start time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fit.jpg
  humanURL: https://developers.google.com/fit/overview
  baseURL: ://www.googleapis.com//fitness/v1/users
  tags: Fitness, Wearables, Google APIs, Stack Network, API Service Provider, API
    Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-fit/useriddatasourcesdatasourceiddatasetsdatasetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-fit/useriddatasourcesdatasourceiddatasetsdatasetid-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.drive.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.fit.stack.network
- type: x-authentication
  url: https://developers.google.com/fit/android/get-api-key
- type: x-getting-started
  url: https://developers.google.com/fit/rest/v1/get-started
- type: x-website
  url: https://developers.google.com/fit/overview
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---