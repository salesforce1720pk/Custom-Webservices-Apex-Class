# 🧩 Custom REST Web Service for Account Object

## 📘 Overview
This Apex class **`accountWebService`** exposes RESTful endpoints for the **Account** object in Salesforce.  
It supports the following HTTP methods:

- **GET** → Retrieve Account by ID  
- **POST** → Create a new Account  
- **PATCH** → Update an existing Account  

**Base URL Format:**
/services/apexrest/Account/AccountServices/


---

## ⚙️ Class Declaration
```apex
@RestResource(urlMapping = '/Account/AccountServices/*')
global with sharing class accountWebService {
    ...
}
