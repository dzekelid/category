{
  "info": {
    "name": "Jumpseller Get Products Category Category",
    "_postman_id": "268c646c-fc15-4e7e-a9b7-355cef6c17af",
    "description": "",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Products",
      "item": [
        {
          "id": "dceb552a-55d7-4736-8ff6-e9b9857a7ebc",
          "name": "getProductsCategoryCategory.json",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.jumpseller.com",
              "path": [
                "v1",
                "products/category/:category_id.json"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "category_id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Products Category Category"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "545ab280-984a-421b-9ef9-b71aec0655e1"
            }
          ]
        }
      ]
    }
  ]
}