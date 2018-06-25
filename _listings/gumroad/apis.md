---
name: Gumroad
x-slug: gumroad
description: Sell music, comics, software, books, and films directly to your audience.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
x-kinRank: "8"
x-alexaRank: "4658"
tags: Category
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/gumroad/apis.md
specificationVersion: "0.14"
apis:
- name: Gumroad Post Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Create a new variant of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariants-post-openapi.md
- name: Gumroad Delete Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Permanently delete a variant of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants/:id
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariantsid-delete-openapi.md
- name: Gumroad Get Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Retrieve the details of a variant of a product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants/:id
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariantsid-get-openapi.md
- name: Gumroad Put Products Variant Categories Variant Category Variants
  x-api-slug: gumroad
  description: Edit a variant of an existing product.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2//products/:product_id/variant_categories/:variant_category_id/variants/:id
  tags: Products,Variant,Categories,:variant,Category,Variants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/gumroad/productsproduct-idvariant-categoriesvariant-category-idvariantsid-put-openapi.md
- name: Gumroad
  x-api-slug: gumroad
  description: Share and sell exclusive videos directly to your followers. Selling
    stuff has always been a pain. No longer! Get back to creating.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1067-gumroad.jpg
  humanURL: http://gumroad.com
  baseURL: https://api.gumroad.com//v2
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/gumroad/openapi.md
x-common:
- type: x-application-management
  url: https://gumroad.com/settings/developer
- type: x-base
  url: https://api.gumroad.com/
- type: x-blog
  url: http://blog.gumroad.com
- type: x-blog-rss
  url: http://blog.gumroad.com/rss
- type: x-crunchbase
  url: https://crunchbase.com/organization/gumroad
- type: x-developer
  url: https://gumroad.com/developers
- type: x-email
  url: partners@gumroad.com
- type: x-email
  url: support@gumroad.com
- type: x-embeddable
  url: https://gumroad.com/embed
- type: x-github
  url: https://github.com/gumroad
- type: x-pricing
  url: https://gumroad.com/features/pricing
- type: x-privacy
  url: https://gumroad.com/privacy
- type: x-terms-of-service
  url: https://gumroad.com/terms
- type: x-twitter
  url: https://twitter.com/gumroad
- type: x-webhooks
  url: https://gumroad.com/webhooks
- type: x-website
  url: http://gumroad.com
- type: x-website
  url: https://gumroad.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---