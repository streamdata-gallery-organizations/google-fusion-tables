---
swagger: "2.0"
x-collection-name: Google Fusion Tables
x-complete: 0
info:
  title: Google Fusion Tables API Get Table
  description: Retrieves a specific table by its ID.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /fusiontables/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /query:
    get:
      summary: Execute SQL Statement
      description: "Executes a SQL statement which can be any of \n- SELECT\n- SHOW\n-
        DESCRIBE"
      operationId: fusiontables.query.sqlGet
      x-api-path-slug: query-get
      parameters:
      - in: query
        name: hdrs
        description: Whether column names are included (in the first row)
      - in: query
        name: sql
        description: A SQL statement which can be any of - SELECT- SHOW- DESCRIBE
      - in: query
        name: typed
        description: 'Whether typed values are returned in the (JSON) response: numbers
          for numeric values and parsed geometries for KML values'
      responses:
        200:
          description: OK
      tags:
      - Query
    post:
      summary: Execute Fusion Table SQL Statement
      description: "Executes a Fusion Tables SQL statement, which can be any of \n-
        SELECT\n- INSERT\n- UPDATE\n- DELETE\n- SHOW\n- DESCRIBE\n- CREATE statement."
      operationId: fusiontables.query.sql
      x-api-path-slug: query-post
      parameters:
      - in: query
        name: hdrs
        description: Whether column names are included in the first row
      - in: query
        name: sql
        description: A Fusion Tables SQL statement, which can be any of - SELECT-
          INSERT- UPDATE- DELETE- SHOW- DESCRIBE- CREATE
      - in: query
        name: typed
        description: 'Whether typed values are returned in the (JSON) response: numbers
          for numeric values and parsed geometries for KML values'
      responses:
        200:
          description: OK
      tags:
      - Query
  /tables:
    get:
      summary: Get Tables
      description: Retrieves a list of tables a user owns.
      operationId: fusiontables.table.list
      x-api-path-slug: tables-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of tables to return
      - in: query
        name: pageToken
        description: Continuation token specifying which result page to return
      responses:
        200:
          description: OK
      tags:
      - Table
    post:
      summary: Create Table
      description: Creates a new table.
      operationId: fusiontables.table.insert
      x-api-path-slug: tables-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/import:
    post:
      summary: Import Table
      description: Imports a new table.
      operationId: fusiontables.table.importTable
      x-api-path-slug: tablesimport-post
      parameters:
      - in: query
        name: delimiter
        description: The delimiter used to separate cell values
      - in: query
        name: encoding
        description: The encoding of the content
      - in: query
        name: name
        description: The name to be assigned to the new table
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}:
    delete:
      summary: Delete Table
      description: Deletes a table.
      operationId: fusiontables.table.delete
      x-api-path-slug: tablestableid-delete
      parameters:
      - in: path
        name: tableId
        description: ID of the table to be deleted
      responses:
        200:
          description: OK
      tags:
      - Table
    get:
      summary: Get Table
      description: Retrieves a specific table by its ID.
      operationId: fusiontables.table.get
      x-api-path-slug: tablestableid-get
      parameters:
      - in: path
        name: tableId
        description: Identifier for the table being requested
      responses:
        200:
          description: OK
      tags:
      - Table
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