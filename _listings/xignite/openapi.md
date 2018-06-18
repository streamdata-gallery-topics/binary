---
swagger: "2.0"
x-collection-name: Xignite
x-complete: 1
info:
  title: Xignite Statistics
  description: delivers-and-charts-more-than-1400-economical-timeseries-fom-the-federal-reserve-bank-
  version: 1.0.0
host: www.xignite.com
basePath: xStatistics.json/XigniteStatistics
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  'Topic, Binary, ':
    get:
      summary: Get Topic Binary Chart
      description: Get time-series and a chart in binary format for a topic.
      operationId: postGettopicbinarychart
      x-api-path-slug: topic-binary-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Topic
      - Binary
      - Chart
  Topic, Binary, , Preset:
    get:
      summary: Get Topic Binary Chart Preset
      description: Get time-series and a chart in binary format for a topic.
      operationId: postGettopicbinarychartpreset
      x-api-path-slug: topic-binary--preset-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Topic
      - Binary
      - Chart
      - Preset
  Topic, Binary, , Custom:
    get:
      summary: Get Topic Binary Chart Custom
      description: Get time-series and a custom chart in binary format for a topic.
      operationId: postGettopicbinarychartcustom
      x-api-path-slug: topic-binary--custom-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Topic
      - Binary
      - Chart
      - Custom
  ', Binary':
    get:
      summary: Get Chart Binary
      description: Get chart in binary format for a topic.
      operationId: postGetchartbinary
      x-api-path-slug: binary-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Chart
      - Binary
  ', Binary, Preset':
    get:
      summary: Get Chart Binary Preset
      description: Get chart in binary format for a topic.
      operationId: postGetchartbinarypreset
      x-api-path-slug: binary-preset-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Chart
      - Binary
      - Preset
  ', Binary, Custom':
    get:
      summary: Get Chart Binary Custom
      description: Get chart in binary format for a topic.
      operationId: postGetchartbinarycustom
      x-api-path-slug: binary-custom-get
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Market Data
      - Chart
      - Binary
      - Custom
---