---
name: Google Fusion Tables
x-slug: google-fusion-tables
description: Fusion Tables is an experimental data visualization web application to
  gather, visualize, and share data tables.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
x-kinRank: "9"
x-alexaRank: "0"
tags: Google Fusion Tables
created: "2018-08-30"
modified: "2018-08-30"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/apis.md
specificationVersion: "0.14"
apis:
- name: Fusion Tables - Execute SQL Statement
  x-api-slug: query-get
  description: "Executes a SQL statement which can be any of \n- SELECT\n- SHOW\n-
    DESCRIBE"
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-get-openapi.md
- name: Fusion Tables - Execute Fusion Table SQL Statement
  x-api-slug: query-post
  description: "Executes a Fusion Tables SQL statement, which can be any of \n- SELECT\n-
    INSERT\n- UPDATE\n- DELETE\n- SHOW\n- DESCRIBE\n- CREATE statement."
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/query-post-openapi.md
- name: Fusion Tables - Get Tables
  x-api-slug: tables-get
  description: Retrieves a list of tables a user owns.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tables-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tables-get-openapi.md
- name: Fusion Tables - Create Table
  x-api-slug: tables-post
  description: Creates a new table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tables-post-openapi.md
- name: Fusion Tables - Import Table
  x-api-slug: tablesimport-post
  description: Imports a new table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablesimport-post-openapi.md
- name: Fusion Tables - Delete Table
  x-api-slug: tablestableid-delete
  description: Deletes a table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-delete-openapi.md
- name: Fusion Tables - Get Table
  x-api-slug: tablestableid-get
  description: Retrieves a specific table by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-get-openapi.md
- name: Fusion Tables - Update Table
  x-api-slug: tablestableid-patch
  description: Updates an existing table. Unless explicitly requested, only the name,
    description, and attribution will be updated. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-patch-openapi.md
- name: Fusion Tables - Update Table
  x-api-slug: tablestableid-put
  description: Updates an existing table. Unless explicitly requested, only the name,
    description, and attribution will be updated.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableid-put-openapi.md
- name: Fusion Tables - Get Columns
  x-api-slug: tablestableidcolumns-get
  description: Retrieves a list of columns.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumns-get-openapi.md
- name: Fusion Tables - Add Column
  x-api-slug: tablestableidcolumns-post
  description: Adds a new column to the table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumns-post-openapi.md
- name: Fusion Tables - Delete Column
  x-api-slug: tablestableidcolumnscolumnid-delete
  description: Deletes the specified column.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-delete-openapi.md
- name: Fusion Tables - Get Column
  x-api-slug: tablestableidcolumnscolumnid-get
  description: Retrieves a specific column by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-get-openapi.md
- name: Fusion Tables - Update Column
  x-api-slug: tablestableidcolumnscolumnid-patch
  description: Updates the name or type of an existing column. This method supports
    patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-patch-openapi.md
- name: Fusion Tables - Update Column
  x-api-slug: tablestableidcolumnscolumnid-put
  description: Updates the name or type of an existing column.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcolumnscolumnid-put-openapi.md
- name: Fusion Tables - Copy Table
  x-api-slug: tablestableidcopy-post
  description: Copies a table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidcopy-post-openapi.md
- name: Fusion Tables - import Rows
  x-api-slug: tablestableidimport-post
  description: Imports more rows into a table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidimport-post-openapi.md
- name: Fusion Tables - Replace Rows
  x-api-slug: tablestableidreplace-post
  description: Replaces rows of an existing table. Current rows remain visible until
    all replacement rows are ready.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidreplace-post-openapi.md
- name: Fusion Tables - Get Styels
  x-api-slug: tablestableidstyles-get
  description: Retrieves a list of styles.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstyles-get-openapi.md
- name: Fusion Tables - Create Style
  x-api-slug: tablestableidstyles-post
  description: Adds a new style for the table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstyles-post-openapi.md
- name: Fusion Tables - Delete Style
  x-api-slug: tablestableidstylesstyleid-delete
  description: Deletes a style.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-delete-openapi.md
- name: Fusion Tables - DelGetete Style
  x-api-slug: tablestableidstylesstyleid-get
  description: Gets a specific style.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-get-openapi.md
- name: Fusion Tables - Update Style
  x-api-slug: tablestableidstylesstyleid-patch
  description: Updates an existing style. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-patch-openapi.md
- name: Fusion Tables - Update Style
  x-api-slug: tablestableidstylesstyleid-put
  description: Updates an existing style.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidstylesstyleid-put-openapi.md
- name: Fusion Tables - Get Tasks
  x-api-slug: tablestableidtasks-get
  description: Retrieves a list of tasks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtasks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtasks-get-openapi.md
- name: Fusion Tables - Delete Task
  x-api-slug: tablestableidtaskstaskid-delete
  description: Deletes a specific task by its ID, unless that task has already started
    running.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-delete-openapi.md
- name: Fusion Tables - Get Task
  x-api-slug: tablestableidtaskstaskid-get
  description: Retrieves a specific task by its ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtaskstaskid-get-openapi.md
- name: Fusion Tables - Get Templates
  x-api-slug: tablestableidtemplates-get
  description: Retrieves a list of templates.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplates-get-openapi.md
- name: Fusion Tables - Create Template
  x-api-slug: tablestableidtemplates-post
  description: Creates a new template for the table.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplates-post-openapi.md
- name: Fusion Tables - Delete Template
  x-api-slug: tablestableidtemplatestemplateid-delete
  description: Deletes a template
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-delete-openapi.md
- name: Fusion Tables - Get Template
  x-api-slug: tablestableidtemplatestemplateid-get
  description: Retrieves a specific template by its id
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-get-openapi.md
- name: Fusion Tables - Update Template
  x-api-slug: tablestableidtemplatestemplateid-patch
  description: Updates an existing template. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-patch-openapi.md
- name: Fusion Tables - Update Template
  x-api-slug: tablestableidtemplatestemplateid-put
  description: Updates an existing template
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-fusion-tables.jpg
  humanURL: https://developers.google.com/fusiontables/
  baseURL: ://www.googleapis.com//fusiontables/v2
  tags: Google APIs, Visualizations, Data, Spreadsheets, Embeddable, Stack Network,
    API Service Provider, API Provider, Databases, Profiles, Relative Data, Service
    API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-fusion-tables/master/_listings/google-fusion-tables/tablestableidtemplatestemplateid-put-openapi.md
x-common:
- type: x-api-gallery
  url: http://google.fonts.api.gallery.streamdata.io
- type: x-api-stack
  url: http://google.fusion.tables.stack.network
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