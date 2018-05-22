---
name: Google Fusion Tables
x-slug: google-fusion-tables
description: Fusion Tables is an experimental data visualization web application to
  gather, visualize, and share data tables.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Google Fusion Tables
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/apis.md
specificationVersion: "0.14"
apis:
- name: Google Fusion Tables API Execute SQL Statement
  x-api-slug: google-fusion-tables-api
  description: "Executes a SQL statement which can be any of \n- SELECT\n- SHOW\n-
    DESCRIBE"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//query
  tags: Query
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-get-openapi.md
- name: Google Fusion Tables API Execute Fusion Table SQL Statement
  x-api-slug: google-fusion-tables-api
  description: "Executes a Fusion Tables SQL statement, which can be any of \n- SELECT\n-
    INSERT\n- UPDATE\n- DELETE\n- SHOW\n- DESCRIBE\n- CREATE statement."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//query
  tags: Query
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-post-openapi.md
- name: Google Fusion Tables API Get Tables
  x-api-slug: google-fusion-tables-api
  description: Retrieves a list of tables a user owns.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables
  tags: Table
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tables-get-openapi.md
- name: Google Fusion Tables API Create Table
  x-api-slug: google-fusion-tables-api
  description: Creates a new table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tables-post-openapi.md
- name: Google Fusion Tables API Import Table
  x-api-slug: google-fusion-tables-api
  description: Imports a new table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/import
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablesimport-post-openapi.md
- name: Google Fusion Tables API Delete Table
  x-api-slug: google-fusion-tables-api
  description: Deletes a table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-delete-openapi.md
- name: Google Fusion Tables API Get Table
  x-api-slug: google-fusion-tables-api
  description: Retrieves a specific table by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-get-openapi.md
- name: Google Fusion Tables API Update Table
  x-api-slug: google-fusion-tables-api
  description: Updates an existing table. Unless explicitly requested, only the name,
    description, and attribution will be updated. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-patch-openapi.md
- name: Google Fusion Tables API Update Table
  x-api-slug: google-fusion-tables-api
  description: Updates an existing table. Unless explicitly requested, only the name,
    description, and attribution will be updated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-put-openapi.md
- name: Google Fusion Tables API Get Columns
  x-api-slug: google-fusion-tables-api
  description: Retrieves a list of columns.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/columns
  tags: Column
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumns-get-openapi.md
- name: Google Fusion Tables API Add Column
  x-api-slug: google-fusion-tables-api
  description: Adds a new column to the table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/columns
  tags: Column
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumns-post-openapi.md
- name: Google Fusion Tables API Delete Column
  x-api-slug: google-fusion-tables-api
  description: Deletes the specified column.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/columns/{columnId}
  tags: Column
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-delete-openapi.md
- name: Google Fusion Tables API Get Column
  x-api-slug: google-fusion-tables-api
  description: Retrieves a specific column by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/columns/{columnId}
  tags: Column
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-get-openapi.md
- name: Google Fusion Tables API Update Column
  x-api-slug: google-fusion-tables-api
  description: Updates the name or type of an existing column. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/columns/{columnId}
  tags: Column
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-patch-openapi.md
- name: Google Fusion Tables API Update Column
  x-api-slug: google-fusion-tables-api
  description: Updates the name or type of an existing column.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/columns/{columnId}
  tags: Column
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-put-openapi.md
- name: Google Fusion Tables API Copy Table
  x-api-slug: google-fusion-tables-api
  description: Copies a table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/copy
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcopy-post-openapi.md
- name: Google Fusion Tables API import Rows
  x-api-slug: google-fusion-tables-api
  description: Imports more rows into a table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/import
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidimport-post-openapi.md
- name: Google Fusion Tables API Replace Rows
  x-api-slug: google-fusion-tables-api
  description: Replaces rows of an existing table. Current rows remain visible until
    all replacement rows are ready.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/replace
  tags: Table
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidreplace-post-openapi.md
- name: Google Fusion Tables API Get Styels
  x-api-slug: google-fusion-tables-api
  description: Retrieves a list of styles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/styles
  tags: Table Style
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstyles-get-openapi.md
- name: Google Fusion Tables API Create Style
  x-api-slug: google-fusion-tables-api
  description: Adds a new style for the table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/styles
  tags: Table Style
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstyles-post-openapi.md
- name: Google Fusion Tables API Delete Style
  x-api-slug: google-fusion-tables-api
  description: Deletes a style.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/styles/{styleId}
  tags: Table Style
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-delete-openapi.md
- name: Google Fusion Tables API DelGetete Style
  x-api-slug: google-fusion-tables-api
  description: Gets a specific style.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/styles/{styleId}
  tags: Table Style
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-get-openapi.md
- name: Google Fusion Tables API Update Style
  x-api-slug: google-fusion-tables-api
  description: Updates an existing style. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/styles/{styleId}
  tags: Table Style
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-patch-openapi.md
- name: Google Fusion Tables API Update Style
  x-api-slug: google-fusion-tables-api
  description: Updates an existing style.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/styles/{styleId}
  tags: Table Style
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-put-openapi.md
- name: Google Fusion Tables API Get Tasks
  x-api-slug: google-fusion-tables-api
  description: Retrieves a list of tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/tasks
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtasks-get-openapi.md
- name: Google Fusion Tables API Delete Task
  x-api-slug: google-fusion-tables-api
  description: Deletes a specific task by its ID, unless that task has already started
    running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/tasks/{taskId}
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-delete-openapi.md
- name: Google Fusion Tables API Get Task
  x-api-slug: google-fusion-tables-api
  description: Retrieves a specific task by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/tasks/{taskId}
  tags: Task
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-get-openapi.md
- name: Google Fusion Tables API Get Templates
  x-api-slug: google-fusion-tables-api
  description: Retrieves a list of templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/templates
  tags: Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplates-get-openapi.md
- name: Google Fusion Tables API Create Template
  x-api-slug: google-fusion-tables-api
  description: Creates a new template for the table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/templates
  tags: Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplates-post-openapi.md
- name: Google Fusion Tables API Delete Template
  x-api-slug: google-fusion-tables-api
  description: Deletes a template
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/templates/{templateId}
  tags: Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-delete-openapi.md
- name: Google Fusion Tables API Get Template
  x-api-slug: google-fusion-tables-api
  description: Retrieves a specific template by its id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/templates/{templateId}
  tags: Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-get-openapi.md
- name: Google Fusion Tables API Update Template
  x-api-slug: google-fusion-tables-api
  description: Updates an existing template. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/templates/{templateId}
  tags: Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-patch-openapi.md
- name: Google Fusion Tables API Update Template
  x-api-slug: google-fusion-tables-api
  description: Updates an existing template
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2//tables/{tableId}/templates/{templateId}
  tags: Template
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-put-openapi.md
- name: Google Fusion Tables API
  x-api-slug: google-fusion-tables-api
  description: Fusion Tables is an experimental data visualization web application
    to gather, visualize, and share data tables.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google Fusion Tables
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/openapi.md
x-common:
- type: x-documentation
  url: https://developers.google.com/fusiontables/docs/v2/reference/
- type: x-forums
  url: https://groups.google.com/forum/#!forum/fusion-tables-api-announce
- type: x-website
  url: https://developers.google.com/fusiontables/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---