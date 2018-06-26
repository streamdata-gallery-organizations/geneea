{
  "info": {
    "name": "Geneea Natural Language Processing Get Correction",
    "_postman_id": "d9247afd-0f6f-402a-9c0d-7982dd367939",
    "description": "Performs text correction (diacritization) on the given document.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Account",
      "item": [
        {
          "id": "0d464a7b-0533-4bf0-a21a-fa6b74177491",
          "name": "getAccount",
          "request": {
            "url": "http://api.geneea.com/account",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Information about current user account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09b5cb57-4cf8-4ddb-ba95-4ffeac3a7e2a"
            }
          ]
        }
      ]
    },
    {
      "name": "Correction",
      "item": [
        {
          "id": "cb24541b-6514-488a-a664-6fb85c65c217",
          "name": "getS1Correction",
          "request": {
            "url": "http://api.geneea.com/s1/correction?extractor=%7B%7D&language=%7B%7D&returnTextInfo=%7B%7D&text=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Performs text correction (diacritization) on the given document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "682b391a-bf84-4b27-98b5-2567fa19fd98"
            }
          ]
        }
      ]
    }
  ]
}