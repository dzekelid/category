---
swagger: "2.0"
x-collection-name: eBay
x-complete: 0
info:
  title: Ebay Get Category Tree Category Tree  Get Category Subtree
  description: 'This call retrieves the details of all nodes of the category tree
    hierarchy (the subtree) below a specified category of a category tree. You identify
    the tree using the category_tree_id parameter, which was returned by the getDefaultCategoryTreeId
    call in the categoryTreeId field. Note: This call can return a very large payload,
    so you are strongly advised to submit the request with the following HTTP header:
    &nbsp;&nbsp;Accept-Encoding: application/gzip With this header (in addition to
    the required headers described under HTTP Request Headers), the call returns the
    response with gzip compression.'
  contact:
    name: eBay Inc.
  version: 1.0.0
host: api.ebay.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /category_tree/{category_tree_id}:
    get:
      summary: Get Category Tree Category Tree
      description: 'This call retrieves the complete category tree that is identified
        by the category_tree_id parameter. The value of category_tree_id was returned
        by the getDefaultCategoryTreeId call in the categoryTreeId field. The response
        contains details of all nodes of the specified eBay category tree, as well
        as the eBay marketplaces that use this category tree. Note: This call can
        return a very large payload, so you are strongly advised to submit the request
        with the following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip
        With this header (in addition to the required headers described under HTTP
        Request Headers), the call returns the response with gzip compression.'
      operationId: getCategoryTree
      x-api-path-slug: category-treecategory-tree-id-get
      parameters:
      - in: path
        name: category_tree_id
        description: The unique identifier of the eBay category tree being requested
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Category
      - Tree
      - Category
      - Tree
  /category_tree/{category_tree_id}/get_category_subtree:
    get:
      summary: Get Category Tree Category Tree  Get Category Subtree
      description: 'This call retrieves the details of all nodes of the category tree
        hierarchy (the subtree) below a specified category of a category tree. You
        identify the tree using the category_tree_id parameter, which was returned
        by the getDefaultCategoryTreeId call in the categoryTreeId field. Note: This
        call can return a very large payload, so you are strongly advised to submit
        the request with the following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip
        With this header (in addition to the required headers described under HTTP
        Request Headers), the call returns the response with gzip compression.'
      operationId: getCategorySubtree
      x-api-path-slug: category-treecategory-tree-idget-category-subtree-get
      parameters:
      - in: query
        name: category_id
        description: The unique identifier of the category at the top of the subtree
          being requested
      - in: path
        name: category_tree_id
        description: The unique identifier of the eBay category tree from which a
          category subtree is being requested
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Category
      - Tree
      - Category
      - Tree
      - ""
      - ""
      - Category
      - Subtree
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