---
swagger: "2.0"
info:
  title: DataDog API Get Graph Embed Embed
  version: 1.0.0
  description: Get the HTML fragment for a previously generated embed with embed_id.
basePath: api/v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  graph/embed/:embed_id:
    get:
      summary: Get Graph Embed Embed
      description: |2-

                  Get the HTML fragment for a previously generated embed with embed_id
      operationId: getGraphEmbedEmbed
      responses:
        200:
          description: OK
      tags:
      - monitoring
      - graph
      - embed
      - embed
definitions: []
x-collection-name: DataDog
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