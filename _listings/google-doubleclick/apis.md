---
name: Google Doubleclick
x-slug: google-doubleclick
description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
  to access and update account information and to submit creatives. The API also allows
  an application (whether it does static bidding or real-time bidding) to discover
  direct deals that sellers make available.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
x-kinRank: "9"
x-alexaRank: "0"
tags: Category
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/apis.md
specificationVersion: "0.14"
apis:
- name: Google Doubleclick API Get Content Categories
  x-api-slug: google-doubleclick-api
  description: Retrieves a list of content categories, possibly filtered. This method
    supports paging.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/contentCategories
  tags: Advertising,Content Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-get-openapi.md
- name: Google Doubleclick API Get Content Category
  x-api-slug: google-doubleclick-api
  description: Updates an existing content category. This method supports patch semantics.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/contentCategories
  tags: Advertising,Content Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-patch-openapi.md
- name: Google Doubleclick API Create Content Category
  x-api-slug: google-doubleclick-api
  description: Inserts a new content category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/contentCategories
  tags: Advertising,Content Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-post-openapi.md
- name: Google Doubleclick API Update Content Category
  x-api-slug: google-doubleclick-api
  description: Updates an existing content category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/contentCategories
  tags: Advertising,Content Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/userprofilesprofileidcontentcategories-put-openapi.md
- name: Google Doubleclick API Delete Content Category
  x-api-slug: google-doubleclick-api
  description: Deletes an existing content category.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/contentCategories/{id}
  tags: Advertising,Content Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/userprofilesprofileidcontentcategoriesid-delete-openapi.md
- name: Google Doubleclick API Get Content Category
  x-api-slug: google-doubleclick-api
  description: Gets one content category by ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https://///userprofiles/{profileId}/contentCategories/{id}
  tags: Advertising,Content Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/userprofilesprofileidcontentcategoriesid-get-openapi.md
- name: Google Doubleclick API
  x-api-slug: google-doubleclick-api
  description: The Ad Exchange Buyer REST API allows your Real-Time Bidding application
    to access and update account information and to submit creatives. The API also
    allows an application (whether it does static bidding or real-time bidding) to
    discover direct deals that sellers make available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-double-click.png
  humanURL: https://www.doubleclickbygoogle.com/
  baseURL: https:///
  tags: Category
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/category/master/_listings/google-doubleclick/openapi.md
x-common:
- type: x-authentication
  url: https://developers.google.com/ad-exchange/buyer-rest/auth-guide
- type: x-blog
  url: http://googleadsdeveloper.blogspot.com/search/label/ad_exchange
- type: x-blog-rss
  url: http://googleadsdeveloper.blogspot.com/feeds/posts/default?alt=rss
- type: x-developer
  url: https://developers.google.com/ad-exchange/buyer-rest/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/google-doubleclick-ad-exchange-buyer-api
- type: x-getting-started
  url: https://developers.google.com/ad-exchange/buyer-rest/start
- type: x-support
  url: https://developers.google.com/ad-exchange/buyer-rest/community/
- type: x-website
  url: https://www.doubleclickbygoogle.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---