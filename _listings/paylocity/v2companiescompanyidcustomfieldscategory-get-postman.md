{
  "info": {
    "name": "Paylocity Get All Custom Fields",
    "_postman_id": "b2cd8834-80b2-4126-a62a-e2e95692009a",
    "description": "Get All Custom Fields for the selected company",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "V2",
      "item": [
        {
          "id": "68b2c5fd-fa88-4621-ba2d-d644511a58cc",
          "name": "v2.companies.companyId.customfields.category.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.paylocity.com",
              "path": [
                "api",
                "v2/companies/:companyId/customfields/:category"
              ],
              "variable": [
                {
                  "id": "category",
                  "value": "{}",
                  "type": "string"
                },
                {
                  "id": "companyId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer + JWT",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get All Custom Fields for the selected company"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c4578b60-f7ff-47cd-bab6-244814d4adb2"
            }
          ]
        }
      ]
    }
  ]
}