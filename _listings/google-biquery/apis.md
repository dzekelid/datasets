---
name: Google Biquery
x-slug: google-biquery
description: BigQuery is Googles fully managed, petabyte scale, low cost enterprise
  data warehouse for analytics. BigQuery is serverless. There is no infrastructure
  to manage and you dont need a database administrator, so you can focus on analyzing
  data to find meaningful insights using familiar SQL. BigQuery is a powerful Big
  Data analytics platform used by all types of organizations, from startups to Fortune
  500 companies.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Datasets
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/apis.md
specificationVersion: "0.14"
apis:
- name: BigQuery - Get Datasets
  x-api-slug: projectsprojectiddatasets-get
  description: Lists all datasets in the specified project to which you have been
    granted the READER dataset role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasets-get-openapi.md
- name: BigQuery - Create Dataset
  x-api-slug: projectsprojectiddatasets-post
  description: Creates a new empty dataset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasets-post-openapi.md
- name: BigQuery - Delete Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-delete
  description: Deletes the dataset specified by the datasetId value. Before you can
    delete a dataset, you must delete all its tables, either manually or by specifying
    deleteContents. Immediately after deletion, you can create another dataset with
    the same name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-delete-openapi.md
- name: BigQuery - Get Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-get
  description: Returns the dataset specified by datasetID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-get-openapi.md
- name: BigQuery - Update Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-patch
  description: Updates information in an existing dataset. The update method replaces
    the entire dataset resource, whereas the patch method only replaces fields that
    are provided in the submitted dataset resource. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-patch-openapi.md
- name: BigQuery - Update Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-put
  description: Updates information in an existing dataset. The update method replaces
    the entire dataset resource, whereas the patch method only replaces fields that
    are provided in the submitted dataset resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-put-openapi.md
- name: BigQuery - Get Datasets
  x-api-slug: projectsprojectiddatasets-get
  description: Lists all datasets in the specified project to which you have been
    granted the READER dataset role.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasets-get-openapi.md
- name: BigQuery - Create Dataset
  x-api-slug: projectsprojectiddatasets-post
  description: Creates a new empty dataset.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasets-post-openapi.md
- name: BigQuery - Delete Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-delete
  description: Deletes the dataset specified by the datasetId value. Before you can
    delete a dataset, you must delete all its tables, either manually or by specifying
    deleteContents. Immediately after deletion, you can create another dataset with
    the same name.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-delete-openapi.md
- name: BigQuery - Get Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-get
  description: Returns the dataset specified by datasetID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-get-openapi.md
- name: BigQuery - Update Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-patch
  description: Updates information in an existing dataset. The update method replaces
    the entire dataset resource, whereas the patch method only replaces fields that
    are provided in the submitted dataset resource. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-patch-openapi.md
- name: BigQuery - Update Dataset
  x-api-slug: projectsprojectiddatasetsdatasetid-put
  description: Updates information in an existing dataset. The update method replaces
    the entire dataset resource, whereas the patch method only replaces fields that
    are provided in the submitted dataset resource.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/BigQuery_500px.png
  humanURL: https://cloud.google.com/bigquery/
  baseURL: ://www.googleapis.com//bigquery/v2
  tags: Data, Cloud, Google APIs, Stack Network, API Service Provider, API Provider,
    Databases, Profiles, Relative Data, Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/google-biquery/projectsprojectiddatasetsdatasetid-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.beacons.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.biquery.stack.network
- type: x-code
  url: https://cloud.google.com/bigquery/docs/reference/libraries
- type: x-documentation
  url: https://cloud.google.com/bigquery/docs/
- type: x-getting-started
  url: https://cloud.google.com/bigquery/docs/quickstarts
- type: x-how-to-guides
  url: https://cloud.google.com/bigquery/docs/how-to
- type: x-partners
  url: https://cloud.google.com/bigquery/partners/
- type: x-pricing
  url: https://cloud.google.com/bigquery/pricing
- type: x-quotas
  url: https://cloud.google.com/bigquery/quota-policy
- type: x-service-level-agreement
  url: https://cloud.google.com/bigquery/sla
- type: x-support
  url: https://cloud.google.com/bigquery/support
- type: x-tutorials
  url: https://cloud.google.com/bigquery/docs/tutorials
- type: x-website
  url: https://cloud.google.com/bigquery/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---