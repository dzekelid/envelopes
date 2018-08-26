{
  "info": {
    "name": "Dezrez Get all printable envelopes and their content.",
    "_postman_id": "cc579d16-eaf5-43bd-9736-0fb468fc3a4b",
    "description": "Get all printable envelopes and their content..",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Printable",
      "item": [
        {
          "id": "dce2e529-91ed-483a-a85d-3cb8f47ae364",
          "name": "DocumentGeneration_GetPrintBagContent",
          "request": {
            "url": "http://api.dezrez.com/api/documentgeneration/printbagcontents",
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Get all printable envelopes and their content.."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ff862a42-bd7f-4422-aceb-b9013630cc9c"
            }
          ]
        }
      ]
    }
  ]
}