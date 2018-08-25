{
  "info": {
    "name": "HPE OneSphere API Get Appliances",
    "_postman_id": "3207c6c1-d415-4e21-aec7-6a27aa02a2ca",
    "description": "Returns appliances.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Appliances",
      "item": [
        {
          "id": "11ed5974-3fea-47be-823b-e246327819ea",
          "name": "GetAppliance",
          "request": {
            "url": "http://deic02-hpe.hpeonesphere.com/rest/appliances?name=%7B%7D&regionUri=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Returns appliances."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "43137a69-5aff-4ba5-934d-b8a15126aec1"
            }
          ]
        }
      ]
    }
  ]
}