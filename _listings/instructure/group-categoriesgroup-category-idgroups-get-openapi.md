---
swagger: "2.0"
x-collection-name: Instructure
x-complete: 0
info:
  title: Instructure Canvas Groups API List groups in group category
  description: List groups in group category.
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /group_categories/{group_category_id}:
    delete:
      summary: Delete a Group Category
      description: Delete a group category.
      operationId: delete-a-group-category
      x-api-path-slug: group-categoriesgroup-category-id-delete
      responses:
        200:
          description: OK
      tags:
      - Group
      - Categories
      - Group
      - Category
      - Id
    get:
      summary: Get a single group category
      description: Get a single group category.
      operationId: get-a-single-group-category
      x-api-path-slug: group-categoriesgroup-category-id-get
      responses:
        200:
          description: OK
      tags:
      - Group
      - Categories
      - Group
      - Category
      - Id
    put:
      summary: Update a Group Category
      description: Update a group category.
      operationId: update-a-group-category
      x-api-path-slug: group-categoriesgroup-category-id-put
      parameters:
      - in: query
        name: auto_leader
        description: 'Assigns group leaders automatically when generating and allocating
          studentsnto groups Valid values are:nu201cfirstu201dnnthe first student
          to be allocated to a group is the leadernu201crandomu201dnna random student
          from all members is chosen as the leadernnn        n        n          Allowed
          values: first, random'
      - in: query
        name: create_group_count
        description: Create this number of groups (Course Only)
      - in: query
        name: group_limit
        description: Limit the maximum number of users in each group (Course Only)
      - in: query
        name: name
        description: Name of the group category
      - in: query
        name: self_signup
        description: Allow students to sign up for a group themselves (Course Only)
      - in: query
        name: split_group_count
        description: (Deprecated) Create this number of groups, and evenly distribute
          studentsnamong them
      responses:
        200:
          description: OK
      tags:
      - Group
      - Categories
      - Group
      - Category
      - Id
  /group_categories/{group_category_id}/assign_unassigned_members:
    post:
      summary: Assign unassigned members
      description: Assign unassigned members.
      operationId: assign-unassigned-members
      x-api-path-slug: group-categoriesgroup-category-idassign-unassigned-members-post
      parameters:
      - in: query
        name: sync
        description: The assigning is done asynchronously by default
      responses:
        200:
          description: OK
      tags:
      - Group
      - Categories
      - Group
      - Category
      - Id
      - Assign
      - Unassigned
      - Members
  /group_categories/{group_category_id}/groups:
    get:
      summary: List groups in group category
      description: List groups in group category.
      operationId: list-groups-in-group-category
      x-api-path-slug: group-categoriesgroup-category-idgroups-get
      responses:
        200:
          description: OK
      tags:
      - Group
      - Categories
      - Group
      - Category
      - Id
      - Groups
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