---
swagger: "2.0"
x-collection-name: Google Fusion Tables
x-complete: 0
info:
  title: Google Fusion Tables API Update Column
  description: Updates the name or type of an existing column.
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
    patch:
      summary: Update Table
      description: Updates an existing table. Unless explicitly requested, only the
        name, description, and attribution will be updated. This method supports patch
        semantics.
      operationId: fusiontables.table.patch
      x-api-path-slug: tablestableid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: replaceViewDefinition
        description: Whether the view definition is also updated
      - in: path
        name: tableId
        description: ID of the table that is being updated
      responses:
        200:
          description: OK
      tags:
      - Table
    put:
      summary: Update Table
      description: Updates an existing table. Unless explicitly requested, only the
        name, description, and attribution will be updated.
      operationId: fusiontables.table.update
      x-api-path-slug: tablestableid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: query
        name: replaceViewDefinition
        description: Whether the view definition is also updated
      - in: path
        name: tableId
        description: ID of the table that is being updated
      responses:
        200:
          description: OK
      tags:
      - Table
  /tables/{tableId}/columns:
    get:
      summary: Get Columns
      description: Retrieves a list of columns.
      operationId: fusiontables.column.list
      x-api-path-slug: tablestableidcolumns-get
      parameters:
      - in: query
        name: maxResults
        description: Maximum number of columns to return
      - in: query
        name: pageToken
        description: Continuation token specifying which result page to return
      - in: path
        name: tableId
        description: Table whose columns are being listed
      responses:
        200:
          description: OK
      tags:
      - Column
    post:
      summary: Add Column
      description: Adds a new column to the table.
      operationId: fusiontables.column.insert
      x-api-path-slug: tablestableidcolumns-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: tableId
        description: Table for which a new column is being added
      responses:
        200:
          description: OK
      tags:
      - Column
  /tables/{tableId}/columns/{columnId}:
    delete:
      summary: Delete Column
      description: Deletes the specified column.
      operationId: fusiontables.column.delete
      x-api-path-slug: tablestableidcolumnscolumnid-delete
      parameters:
      - in: path
        name: columnId
        description: Name or identifier for the column being deleted
      - in: path
        name: tableId
        description: Table from which the column is being deleted
      responses:
        200:
          description: OK
      tags:
      - Column
    get:
      summary: Get Column
      description: Retrieves a specific column by its ID.
      operationId: fusiontables.column.get
      x-api-path-slug: tablestableidcolumnscolumnid-get
      parameters:
      - in: path
        name: columnId
        description: Name or identifier for the column that is being requested
      - in: path
        name: tableId
        description: Table to which the column belongs
      responses:
        200:
          description: OK
      tags:
      - Column
    patch:
      summary: Update Column
      description: Updates the name or type of an existing column. This method supports
        patch semantics.
      operationId: fusiontables.column.patch
      x-api-path-slug: tablestableidcolumnscolumnid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: columnId
        description: Name or identifier for the column that is being updated
      - in: path
        name: tableId
        description: Table for which the column is being updated
      responses:
        200:
          description: OK
      tags:
      - Column
    put:
      summary: Update Column
      description: Updates the name or type of an existing column.
      operationId: fusiontables.column.update
      x-api-path-slug: tablestableidcolumnscolumnid-put
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: columnId
        description: Name or identifier for the column that is being updated
      - in: path
        name: tableId
        description: Table for which the column is being updated
      responses:
        200:
          description: OK
      tags:
      - Column
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