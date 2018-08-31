{
  "info": {
    "name": "Geneea Natural Language Processing Get Sentiment",
    "_postman_id": "77d164db-b60f-45d9-82bf-64a6277f628d",
    "description": "Performs sentiment analysis on the given document.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Sentiment",
      "item": [
        {
          "id": "c229ba05-981f-4542-bd7a-c9edad49f08f",
          "name": "getS1Sentiment",
          "request": {
            "url": "http://api.geneea.com/s1/sentiment?extractor=%7B%7D&language=%7B%7D&returnTextInfo=%7B%7D&text=%7B%7D&url=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Performs sentiment analysis on the given document."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ccd51c38-891b-467a-b66a-b1b014d522bb"
            }
          ]
        }
      ]
    }
  ]
}