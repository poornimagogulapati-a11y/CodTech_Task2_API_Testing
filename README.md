# CodTech Internship - Task 2  
## API Testing using Postman  

---

## 📌 Objective  
To test RESTful APIs using Postman for Authentication and Data Retrieval.

---

## 🛠 Tool Used  
- Postman  

---

## 🔐 Authentication API Testing  

**Method:** POST  
**Endpoint:** https://fakestoreapi.com/auth/login  

### Request Body:
```json
{
  "username": "mor_2314",
  "password": "83r5^_"
}
```

### ✅ Test Result:
- Status Code: 200 OK  
- JWT Token generated successfully  

### 📸 Screenshot:

![POST API Result](post.png)

---

## 📦 Data Retrieval API Testing  

**Method:** GET  
**Endpoint:** https://fakestoreapi.com/products  

### ✅ Test Result:
- Status Code: 200 OK  
- Products data retrieved successfully in JSON format  

### 📸 Screenshot:

![GET API Result](get.png)

---

## 🧪 Validation Performed  
- Verified HTTP status codes  
- Confirmed successful authentication  
- Validated JSON response format  
- Ensured proper data retrieval  

---

## 📂 Repository Structure  

```
CodTech_Task2_API_Testing
│
├── CodTech_Task2_API_Testing.postman_collection.json
├── Task2_Test_Results.txt
├── README.md
└── Screenshots
      ├── post.png
      └── get.png
```

---

## 🎯 Conclusion  

The RESTful APIs were successfully tested using Postman.  
Both Authentication and Data Retrieval functionalities are working correctly.

---
