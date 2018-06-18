---
swagger: "2.0"
x-collection-name: NewsWhip
x-complete: 0
info:
  title: News Whip API Region
  description: Search news by region
  termsOfService: http://www.newswhip.com/PrivacyAndLegal
  version: v1
host: api.newswhip.com
basePath: v1/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  region/{region}/{category}/{time_period}:
    get:
      summary: Region
      description: Search news by region
      operationId: getRegionRegionCategoryTimePeriod
      x-api-path-slug: regionregioncategorytime-period-get
      parameters:
      - in: path
        name: category
        description: Filters articles by {category}
      - in: query
        name: key
        description: API key
      - in: path
        name: region
        description: Filters articles published in that {region}
      - in: query
        name: sort_by
        description: 'One of the following: [default, fb_likes, fb_shares, fb_comments,
          fb_total, twitter, linkedin, fb_tw_and_li, nw_score, nw_max_score]'
      - in: path
        name: time_period
        description: Filters articles published within the last X hours
      - in: query
        name: video_only
        description: true or false
      responses:
        200:
          description: OK
      tags:
      - News
      - Region
      - Region
      - Category
      - Time
      - Period
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