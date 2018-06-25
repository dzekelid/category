---
name: eBay
x-slug: ebay
description: Buy and sell electronics, cars, fashion apparel, collectibles, sporting
  goods, digital cameras, baby items, coupons, and everything else on eBay, the worlds
  online marketplace
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
x-kinRank: "8"
x-alexaRank: "42"
tags: Category
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/apis.md
specificationVersion: "0.14"
apis:
- name: Ebay Get Category Tree Category Tree
  x-api-slug: ebay
  description: 'This call retrieves the complete category tree that is identified
    by the category_tree_id parameter. The value of category_tree_id was returned
    by the getDefaultCategoryTreeId call in the categoryTreeId field. The response
    contains details of all nodes of the specified eBay category tree, as well as
    the eBay marketplaces that use this category tree. Note: This call can return
    a very large payload, so you are strongly advised to submit the request with the
    following HTTP header: &nbsp;&nbsp;Accept-Encoding: application/gzip With this
    header (in addition to the required headers described under HTTP Request Headers),
    the call returns the response with gzip compression.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////category_tree/{category_tree_id}
  tags: Auctions,Category, Tree, Category, Tree
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-id-get-openapi.md
- name: Ebay Get Category Tree Category Tree  Get Category Subtree
  x-api-slug: ebay
  description: 'This call retrieves the details of all nodes of the category tree
    hierarchy (the subtree) below a specified category of a category tree. You identify
    the tree using the category_tree_id parameter, which was returned by the getDefaultCategoryTreeId
    call in the categoryTreeId field. Note: This call can return a very large payload,
    so you are strongly advised to submit the request with the following HTTP header:
    &nbsp;&nbsp;Accept-Encoding: application/gzip With this header (in addition to
    the required headers described under HTTP Request Headers), the call returns the
    response with gzip compression.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////category_tree/{category_tree_id}/get_category_subtree
  tags: Auctions,Category, Tree, Category, Tree, , , Category, Subtree
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-idget-category-subtree-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-idget-category-subtree-get-openapi.md
- name: Ebay Get Category Tree Category Tree  Get Category Suggestions
  x-api-slug: ebay
  description: 'This call returns an array of category tree leaf nodes in the specified
    category tree that are considered by eBay to most closely correspond to the query
    string q. Returned with each suggested node is a localized name for that category
    (based on the Accept-Language header specified for the call), and details about
    each of the category''s ancestor nodes, extending from its immediate parent up
    to the root of the category tree. Note: This call can return a large payload,
    so you are advised to submit the request with the following HTTP header: &nbsp;&nbsp;Accept-Encoding:
    application/gzip With this header (in addition to the required headers described
    under HTTP Request Headers), the call returns the response with gzip compression.
    You identify the tree using the category_tree_id parameter, which was returned
    by the getDefaultCategoryTreeId call in the categoryTreeId field. Important: This
    call is not supported in the Sandbox environment. It will return a response payload
    in which the categoryName fields contain random or boilerplate text regardless
    of the query submitted.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////category_tree/{category_tree_id}/get_category_suggestions
  tags: Auctions,Category, Tree, Category, Tree, , , Category, Suggestions
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-idget-category-suggestions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-idget-category-suggestions-get-openapi.md
- name: Ebay Get Category Tree Category Tree  Get Item Aspects For Category
  x-api-slug: ebay
  description: 'This call returns a list of aspects that are appropriate or necessary
    for accurately describing items in the specified leaf category. Each aspect identifies
    an item attribute (for example, color) for which the seller will be required or
    encouraged to provide a value (or variation values) when offering an item in that
    category on eBay. For each aspect, getItemAspectsForCategory provides complete
    metadata, including: The aspect''s data type, format, and entry mode Whether the
    aspect is required in listings Whether the aspect can be used for item variations
    Whether the aspect accepts multiple values for an item Allowed values for the
    aspectUse this information to construct an interface through which sellers can
    enter or select the appropriate values for their items or item variations. Once
    you collect those values, include them as product aspects when creating inventory
    items using the Inventory API.'
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////category_tree/{category_tree_id}/get_item_aspects_for_category
  tags: Auctions,Category, Tree, Category, Tree, , , Item, Aspects, Category
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/category-treecategory-tree-idget-item-aspects-for-category-get-openapi.md
- name: Ebay Get Get Default Category Tree
  x-api-slug: ebay
  description: A given eBay marketplace might use multiple category trees, but one
    of those trees is considered to be the default for that marketplace. This call
    retrieves a reference to the default category tree associated with the specified
    eBay marketplace ID. The response includes only the tree's unique identifier and
    version, which you can use to retrieve more details about the tree, its structure,
    and its individual category nodes.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com////get_default_category_tree_id
  tags: Auctions,Default, Category, Tree
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/get-default-category-tree-id-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/get-default-category-tree-id-get-openapi.md
- name: Ebay
  x-api-slug: ebay
  description: Buy and sell electronics, cars, fashion apparel, collectibles, sporting
    goods, digital cameras, baby items, coupons, and everything else on eBay, the
    worlds online marketplace
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/138-ebay.jpg
  humanURL: https://ebay.com
  baseURL: https://api.ebay.com//
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/ebay/openapi.md
x-common:
- type: x-blog
  url: https://go.developer.ebay.com/dev-program-blog
- type: x-crunchbase
  url: http://www.crunchbase.com/company/ebay
- type: x-crunchbase
  url: https://crunchbase.com/organization/leah
- type: x-developer
  url: https://go.developer.ebay.com/
- type: x-email
  url: spam@ebay.com
- type: x-email
  url: spoof@ebay.com
- type: x-github
  url: https://github.com/eBayDeveloper
- type: x-twitter
  url: https://twitter.com/eBay
- type: x-twitter
  url: https://twitter.com/ebaydev
- type: x-website
  url: https://ebay.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---