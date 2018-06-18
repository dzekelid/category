---
swagger: "2.0"
x-collection-name: Reverb
x-complete: 1
info:
  title: reverb
  description: reverb
  termsOfService: https://reverb.com/page/terms
  contact:
    name: Reverb API
    url: https://dev.reverb.com
    email: integrations@reverb.com
  version: "3.0"
host: api.reverb.com
basePath: /api
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /categories/{product_type}/{category}:
    get:
      summary: Get Categories Product Type Category
      description: Get categories product type category.
      operationId: getCategoriesProductTypeCategory
      x-api-path-slug: categoriesproduct-typecategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: product_type
      responses:
        200:
          description: OK
      tags:
      - Categories
      - Product
      - Type
      - Category
  /my/follows/categories/{category}/{subcategory}:
    delete:
      summary: Delete My Follows Categories Category Subcategory
      description: Delete my follows categories category subcategory.
      operationId: deleteMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-delete
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
    get:
      summary: Get My Follows Categories Category Subcategory
      description: Get my follows categories category subcategory.
      operationId: getMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-get
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
    post:
      summary: Post My Follows Categories Category Subcategory
      description: Post my follows categories category subcategory.
      operationId: postMyFollowsCategoriesCategorySubcategory
      x-api-path-slug: myfollowscategoriescategorysubcategory-post
      parameters:
      - in: path
        name: category
      - in: path
        name: subcategory
      responses:
        200:
          description: OK
      tags:
      - My
      - Follows
      - Categories
      - Category
      - Subcategory
---