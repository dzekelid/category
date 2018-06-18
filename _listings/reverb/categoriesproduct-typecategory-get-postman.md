{
  "info": {
    "name": "reverb Get Categories Product Type Category",
    "_postman_id": "fa654e25-a2d8-4144-84ea-17c561b38914",
    "description": "Get categories product type category.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Categories",
      "item": [
        {
          "id": "eefbbca0-a023-4126-9f4c-0721fc82ce55",
          "name": "getCategories",
          "request": {
            "url": "http://api.reverb.com/api/categories",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List of supported product categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b900cf78-fe28-4813-aa25-651c4eb677a5"
            }
          ]
        },
        {
          "id": "13a7d2a1-21dd-42cc-94ac-cc07c3610cc0",
          "name": "getCategoriesFlat",
          "request": {
            "url": "http://api.reverb.com/api/categories/flat",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get categories flat."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a29d001b-f1df-422a-adb6-da71f2e9b40d"
            }
          ]
        },
        {
          "id": "664fac2f-28b6-4cbf-b276-ca1c6aa6fab7",
          "name": "getCategoriesTaxonomy",
          "request": {
            "url": "http://api.reverb.com/api/categories/taxonomy",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Full taxonomy tree of categories including middle categories"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1f353867-e09e-49d4-901b-6230463e6369"
            }
          ]
        },
        {
          "id": "f79fe489-8c3a-407b-953f-56559be3ef49",
          "name": "getCategoriesProductTypeCategory",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.reverb.com",
              "path": [
                "api",
                "categories/:product_type/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "product_type",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get categories product type category."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "731afa5f-fa59-441b-b125-d777cd812984"
            }
          ]
        }
      ]
    }
  ]
}