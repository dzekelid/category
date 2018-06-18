---
swagger: "2.0"
x-collection-name: Mattermost
x-complete: 1
info:
  title: Mattermost API Reference
  description: -api-v4-is-stable-with-the-mattermost-server-4-0-release--api-v3-was-deprecated-on-january-16th-2018-and-scheduled-for-removal-in-mattermost-v5-0--details-heretagapiv3deprecation--looking-for-the-api-v3-reference-it-has-moved-herehttpsapi-mattermost-comv3-
  termsOfService: https://about.mattermost.com/default-terms/
  version: 4.0.0
host: your-mattermost-url.com
basePath: /api/v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /users/{user_id}/preferences/{category}:
    get:
      summary: List a user's preferences by category
      description: |-
        Lists the current user's stored preferences in the given category.
        ##### Permissions
        Must be logged in as the user being updated or have the `edit_other_users` permission.
      operationId: lists-the-current-users-stored-preferences-in-the-given-category-permissionsmust-be-logged-in-as-the
      x-api-path-slug: usersuser-idpreferencescategory-get
      parameters:
      - in: path
        name: category
        description: The category of a group of preferences
      - in: path
        name: user_id
        description: User GUID
      responses:
        200:
          description: OK
      tags:
      - List
      - Users
      - Preferences
      - By
      - Category
---