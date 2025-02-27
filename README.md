# API Testing Documentation

## Overview
This document outlines the API testing process conducted using Postman. It includes a structured set of test cases to evaluate the API’s functionality, authentication, and response handling.

## Postman Collection
The API testing was conducted using the Postman collection found in `API_Testing.postman_collection.json`. Import this collection into Postman to replicate the tests.

---

### Structure of this Documentation is as shown in the Screenshot
![Image](https://github.com/user-attachments/assets/fede33a5-ade2-4365-a9d2-8aa50e26899f) <br/>

### Variables used are as follows
![Image](https://github.com/user-attachments/assets/b502e821-663a-4b1d-9561-a741738bd9d9) <br/>

---

## 1. Fetch Books
This API request retrieves a list of available books.
![Image](https://github.com/user-attachments/assets/a2b90828-7eb0-4f02-8998-63252b299632) <br/>

---

## 2. Query Parameter: Limit
This test checks how the API handles the `limit` parameter.
![Image](https://github.com/user-attachments/assets/433cb509-80df-4f4b-8017-717951ec70e6) <br/>

---

## 3. Query Parameters (Both Params)
This request tests the API's behavior when multiple query parameters are provided.
![Image](https://github.com/user-attachments/assets/e4879095-79b4-4cfa-bca1-e5ac4a985e4a) <br/>

---

## 4. Fetch Single Book
This API request fetches details of a specific book using its ID.
![Image](https://github.com/user-attachments/assets/a1f09ab0-374f-4f5b-8a33-3bae0dea3271) <br/>

---

## 5. Fetch Credentials
This test fetches stored credentials required for authentication.
![Image](https://github.com/user-attachments/assets/9d6ec0ef-9576-4dd8-8c52-a13e3791c07a) <br/>

---

## 6. Authorization
This test verifies API authentication and authorization mechanisms.
![Image](https://github.com/user-attachments/assets/bce8deb6-49f3-49d9-a90a-b3ff3a43ba7a) <br/>

---

## 7. Orders
This request tests the order placement functionality.
![Image](https://github.com/user-attachments/assets/8a648b4a-9297-4b45-ae46-fd8ec9e49290) <br/>


---

## 8. Orders Out of Stock
This request checks the API's response when ordering an out-of-stock item.
![Image](https://github.com/user-attachments/assets/4c651fed-b6fd-40f1-a31a-14522226473f) <br/>

---

## 9. Random Orders
This test places an order with randomly selected parameters.
![Image](https://github.com/user-attachments/assets/8f98e540-3a19-469f-93c4-541bb8c7e460)

---

## 10. Orders Check
This request verifies existing orders in the system.
![Image](https://github.com/user-attachments/assets/3973c723-3b4a-4adc-94c2-370d02c71b69) <br/>

---

## 11. Order by ID
This request retrieves details of a specific order using its ID.
![Image](https://github.com/user-attachments/assets/dc74b68c-462c-4dee-ba9f-8beeaffd99e2) <br/>

---

## 12. Patch Order ID
This request updates order details using the PATCH method.
![Image](https://github.com/user-attachments/assets/dbdedbda-dc2c-4620-8d4a-567d2b3edb66) <br/>

---

## 13. Delete Order by ID
This request deletes a specific order using its ID.
![Image](https://github.com/user-attachments/assets/2cd925cd-3f83-4d9a-99b1-084d2dc7f687) <br/>

---

## Conclusion
These tests validate API functionality, authentication, and response handling under different conditions. Import the provided Postman collection to replicate these tests.

---

## Credits
The APIs used for this testing were provided by [Introduction to Postman Course](https://github.com/vdespa/introduction-to-postman-course).

