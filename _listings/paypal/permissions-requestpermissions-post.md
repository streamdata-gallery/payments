---
swagger: "2.0"
info:
  title: Paypal Request Permissions
  description: "Use the RequestPermissions API operation to request permissions to
    execute API operations on a PayPal account holder\u2019s behalf."
  version: 1.0.0
host: svcs.sandbox.paypal.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Permissions/RequestPermissions:
    post:
      summary: Request Permissions
      description: "Use the RequestPermissions API operation to request permissions
        to execute API operations on a PayPal account holder\u2019s behalf"
      operationId: Permissions.RequestPermissions.post
      responses:
        200:
          description: OK
      tags:
      - payments
      - permissions
definitions: []
x-collection-name: PayPal
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