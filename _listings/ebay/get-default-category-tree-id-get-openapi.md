---
swagger: "2.0"
x-collection-name: eBay
x-complete: 0
info:
  title: Ebay Get Get Default Category Tree
  description: A given eBay marketplace might use multiple category trees, but one
    of those trees is considered to be the default for that marketplace. This call
    retrieves a reference to the default category tree associated with the specified
    eBay marketplace ID. The response includes only the tree's unique identifier and
    version, which you can use to retrieve more details about the tree, its structure,
    and its individual category nodes.
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
  /category_tree/{category_tree_id}/get_category_suggestions:
    get:
      summary: Get Category Tree Category Tree  Get Category Suggestions
      description: 'This call returns an array of category tree leaf nodes in the
        specified category tree that are considered by eBay to most closely correspond
        to the query string q. Returned with each suggested node is a localized name
        for that category (based on the Accept-Language header specified for the call),
        and details about each of the category''s ancestor nodes, extending from its
        immediate parent up to the root of the category tree. Note: This call can
        return a large payload, so you are advised to submit the request with the
        following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip With
        this header (in addition to the required headers described under HTTP Request
        Headers), the call returns the response with gzip compression. You identify
        the tree using the category_tree_id parameter, which was returned by the getDefaultCategoryTreeId
        call in the categoryTreeId field. Important: This call is not supported in
        the Sandbox environment. It will return a response payload in which the categoryName
        fields contain random or boilerplate text regardless of the query submitted.'
      operationId: getCategorySuggestions
      x-api-path-slug: category-treecategory-tree-idget-category-suggestions-get
      parameters:
      - in: path
        name: category_tree_id
        description: The unique identifier of the eBay category tree for which suggested
          nodes are being requested
      - in: query
        name: q
        description: A quoted string that describes or characterizes the item being
          offered for sale
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
      - Suggestions
  /category_tree/{category_tree_id}/get_item_aspects_for_category:
    get:
      summary: Get Category Tree Category Tree  Get Item Aspects For Category
      description: 'This call returns a list of aspects that are appropriate or necessary
        for accurately describing items in the specified leaf category. Each aspect
        identifies an item attribute (for example, color) for which the seller will
        be required or encouraged to provide a value (or variation values) when offering
        an item in that category on eBay. For each aspect, getItemAspectsForCategory
        provides complete metadata, including: The aspect''s data type, format, and
        entry mode Whether the aspect is required in listings Whether the aspect can
        be used for item variations Whether the aspect accepts multiple values for
        an item Allowed values for the aspectUse this information to construct an
        interface through which sellers can enter or select the appropriate values
        for their items or item variations. Once you collect those values, include
        them as product aspects when creating inventory items using the Inventory
        API.'
      operationId: getItemAspectsForCategory
      x-api-path-slug: category-treecategory-tree-idget-item-aspects-for-category-get
      parameters:
      - in: query
        name: category_id
        description: The unique identifier of the leaf category for which aspects
          are being requested
      - in: path
        name: category_tree_id
        description: The unique identifier of the eBay category tree from which the
          specified categorys aspects are being requested
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
      - Item
      - Aspects
      - Category
  /get_default_category_tree_id:
    get:
      summary: Get Get Default Category Tree
      description: A given eBay marketplace might use multiple category trees, but
        one of those trees is considered to be the default for that marketplace. This
        call retrieves a reference to the default category tree associated with the
        specified eBay marketplace ID. The response includes only the tree's unique
        identifier and version, which you can use to retrieve more details about the
        tree, its structure, and its individual category nodes.
      operationId: getDefaultCategoryTreeId
      x-api-path-slug: get-default-category-tree-id-get
      parameters:
      - in: query
        name: marketplace_id
        description: The ID of the eBay marketplace for which the category tree ID
          is being requested
      responses:
        200:
          description: OK
      tags:
      - Auctions
      - Default
      - Category
      - Tree
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