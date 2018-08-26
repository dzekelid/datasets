---
name: OpenDataSoft
x-slug: opendatasoft
description: OpenDataSoft is a cloud-based turnkey platform for data publishing and
  API management. Its interface is intuitively designed to empower anyone, regardless
  of technical skills, to upload easy-to-understand Open Data, or to even share data
  within an admi...
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
x-kinRank: "7"
x-alexaRank: "323884"
tags: Datasets
created: "2018-08-26"
modified: "2018-08-26"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/apis.md
specificationVersion: "0.14"
apis:
- name: OpenDataSoft - Get Source Datasets
  x-api-slug: sourcedatasets-get
  description: |-
    List of available datasets, each with their endpoints, paginated.

    Links provided:
    * previous page
    * next page
    * last page
    * first page
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasets-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasets-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset
  x-api-slug: sourcedatasetsdataset-id-get
  description: |-
    List of available endpoints for the specified dataset, with metadata and endpoints.

    Will provide links for:
    * the attachments endpoint
    * the files endpoint
    * the records endpoint
    * the catalog endpoint
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-id-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Aggregates
  x-api-slug: sourcedatasetsdataset-idaggregates-get
  description: Compute aggregations from dataset records and return a list of each
    aggregate indexed by their names.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idaggregates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idaggregates-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Attachments
  x-api-slug: sourcedatasetsdataset-idattachments-get
  description: Get list of all available attachments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachments-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Attachments Attachment
  x-api-slug: sourcedatasetsdataset-idattachmentsattachment-id-get
  description: Download attachment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachmentsattachment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachmentsattachment-id-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Csv
  x-api-slug: sourcedatasetsdataset-idexportscsv-get
  description: Export dataset in CSV format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportscsv-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportscsv-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Geojson
  x-api-slug: sourcedatasetsdataset-idexportsgeojson-get
  description: Export dataset in GEOJSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsgeojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsgeojson-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Ical
  x-api-slug: sourcedatasetsdataset-idexportsical-get
  description: Export dataset in ICAL format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsical-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsical-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Json
  x-api-slug: sourcedatasetsdataset-idexportsjson-get
  description: Export dataset in JSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsjson-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Ov2
  x-api-slug: sourcedatasetsdataset-idexportsov2-get
  description: Export dataset in OV2 format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsov2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsov2-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Shp
  x-api-slug: sourcedatasetsdataset-idexportsshp-get
  description: Export dataset in Esri shapefile (shp) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsshp-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsshp-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Xls
  x-api-slug: sourcedatasetsdataset-idexportsxls-get
  description: Export dataset in XLS (Excel) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsxls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsxls-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset
  x-api-slug: sourcedatasetsdataset-id-get
  description: |-
    List of available endpoints for the specified dataset, with metadata and endpoints.

    Will provide links for:
    * the attachments endpoint
    * the files endpoint
    * the records endpoint
    * the catalog endpoint
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-id-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Aggregates
  x-api-slug: sourcedatasetsdataset-idaggregates-get
  description: Compute aggregations from dataset records and return a list of each
    aggregate indexed by their names.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idaggregates-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idaggregates-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Attachments
  x-api-slug: sourcedatasetsdataset-idattachments-get
  description: Get list of all available attachments
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachments-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachments-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Attachments Attachment
  x-api-slug: sourcedatasetsdataset-idattachmentsattachment-id-get
  description: Download attachment
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachmentsattachment-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idattachmentsattachment-id-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Csv
  x-api-slug: sourcedatasetsdataset-idexportscsv-get
  description: Export dataset in CSV format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportscsv-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportscsv-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Geojson
  x-api-slug: sourcedatasetsdataset-idexportsgeojson-get
  description: Export dataset in GEOJSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsgeojson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsgeojson-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Ical
  x-api-slug: sourcedatasetsdataset-idexportsical-get
  description: Export dataset in ICAL format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsical-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsical-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Json
  x-api-slug: sourcedatasetsdataset-idexportsjson-get
  description: Export dataset in JSON format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsjson-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsjson-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Ov2
  x-api-slug: sourcedatasetsdataset-idexportsov2-get
  description: Export dataset in OV2 format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsov2-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsov2-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Shp
  x-api-slug: sourcedatasetsdataset-idexportsshp-get
  description: Export dataset in Esri shapefile (shp) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsshp-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsshp-get-openapi.md
- name: OpenDataSoft - Get Source Datasets Dataset Exports Xls
  x-api-slug: sourcedatasetsdataset-idexportsxls-get
  description: Export dataset in XLS (Excel) format
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2716-opendatasoft.jpg
  humanURL: http://opendatasoft.com
  baseURL: https://public.opendatasoft.com//api/v2
  tags: Data, Government, Technology, SaaS, Enterprise, Relative Data, General Data,
    Service API, Relative StreamRank, Cities, Streams
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsxls-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/datasets/master/_listings/opendatasoft/sourcedatasetsdataset-idexportsxls-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://opencorporates.api.gallery.streamdata.io
- type: x-api-stack
  url: http://opendatasoft.stack.network
- type: x-blog
  url: http://www.opendatasoft.com/category/news/
- type: x-crunchbase
  url: https://crunchbase.com/organization/opendatasoft
- type: x-crunchbase
  url: http://www.crunchbase.com/company/opendatasoft
- type: x-email
  url: contact@opendatasoft.com
- type: x-email
  url: cil@opendatasoft.com
- type: x-twitter
  url: https://twitter.com/opendatasoft
- type: x-website
  url: http://opendatasoft.com
- type: x-website
  url: https://www.opendatasoft.com
- type: x-website
  url: http://www.opendatasoft.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---