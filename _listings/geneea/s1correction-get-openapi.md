---
swagger: "2.0"
x-collection-name: Geneea
x-complete: 0
info:
  title: Geneea Natural Language Processing Get Correction
  description: Performs text correction (diacritization) on the given document.
  version: "1.0"
host: api.geneea.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account:
    get:
      summary: Get Account
      description: Information about current user account.
      operationId: getAccount
      x-api-path-slug: account-get
      responses:
        200:
          description: OK
      tags:
      - Account
  /s1/correction:
    get:
      summary: Get Correction
      description: Performs text correction (diacritization) on the given document.
      operationId: getS1Correction
      x-api-path-slug: s1correction-get
      parameters:
      - in: query
        name: extractor
        description: document extractor
      - in: query
        name: language
        description: document language
      - in: query
        name: returnTextInfo
      - in: query
        name: text
        description: raw document text
      - in: query
        name: url
        description: document URL
      responses:
        200:
          description: OK
      tags:
      - Correction
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