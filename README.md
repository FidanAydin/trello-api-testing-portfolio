# 🧪 Trello API Testing

API testing is done to validate the endpoints,functions, menthods sending different HTTP requests to the server and comparing its response with the expected data. It is also faster than the UI testing as the testers do not have to go click by click to validate the application functionality. 
In order to verify APIs are working properly testers must assert the status codes, valid/invalid data received in the response. There are many user-friendly API testing tools,such as Postman, Swagger and others, to use while working on APIs.

This is an API testing project built using **Postman** to validate Trello REST APIs including the creation of a board and its componenets.

---

## 🔗 Project Links

* 📬 Postman Collection:
  [Download Collection](https://github.com/FidanAydin/trello-api-testing-portfolio/blob/main/Trello_API_Tests.postman_collection.json)

* 🌍 Postman Environment:
  [Download Environment](https://github.com/FidanAydin/trello-api-testing-portfolio/blob/main/Trello_Environment.postman_environment.json)

* 📮 Trello API Docs:
  https://developer.atlassian.com/cloud/trello/rest/

---

## 🛠️ Tech Stack

* Postman [Download](https://www.postman.com/downloads/)
* JavaScript (Postman Tests)
* GitHub

---

## 📌 Test Coverage

### Boards

* ✅ Create Board (POST)
* ✅ Get Board by ID (GET)
* ✅ Update Board (PUT)
* ✅ Invite Member to Board via email
* ✅ Get the Members of a Board
* ✅ Remove Member from Board
### Lists
* ✅ Create List (POST)
* ✅ Get A List by ID (GET)
### Cards
* ✅ Create A Card (POST)
* ✅ Update a Card (PUT)
* ✅ Get a Card by ID (GET)
### Checklist 
* ✅ Create Checklist on a Card (POST)
* ✅ Update a Checklist (PUT)
* ✅ Get A Checklist by ID (GET)
### Delete
* ✅ Delete Checklist
* ✅ Delete a Card
* ✅ Delete Board 



## ▶️ How to Run Tests

### Run in Postman

1. Import collection
2. Import environment
3. Add API key + token
4. Click **Run**
