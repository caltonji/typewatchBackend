# Typewatch Backend

API
---


`POST /message` (Create or update message)
* Input

  * `id`: string
  * `message`: string

* Output (JSON)

  * `error`: whether an error occured (boolean)
  * `body`: description of the error or success
  * SavedOrder": {
      "__v": 0,
      "tip": 50,
      "location": "clough",
      "customer": "56065f187400040b388e0a96",
      "_id": "5606752679240c1d3c951def",
      "reviews": [],
      "notes": "",
      "items": [
        null,
        "5606752679240c1d3c951dee"
      ],
      "dateLastStatusChange": "2015-09-26T10:36:22.965Z",
      "dateCreated": "2015-09-26T10:36:22.965Z",
      "status": "Created"
    }

`DELETE /message` (Delete message)
* Input
  * `id`: string


`GET /message/` View message
* Input
  * `id`: string


`GET /messages/` View all message
* Input

