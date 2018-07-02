 
# Show candidate`s profile
---
### **URL:**     **/profile**
 **Method**:   GET
 **URL Params**: none
 **Data Params:**
```json
   {
	"firstName":"Avas",
	"lastName":"Avasov",
	"cellPhoneNumber":"+972534501456",
	"email":"avas@mail.com",
}
```
### Error responce 
**Code:** 401 UNAUTHORIZED 
**Content:** ``` { error : "Log in" }```

**Code:** 422 Unprocessable Entry 
**Content:**``` { error : "Email invalid" }```

**Code:** 422 Unprocessable Entry 
**Content:** ```{ error : "Phone number invalid" }```

**Code:** 422 Unprocessable Entry 
**Content:** ```{ error : "First name invalid" }```

**Code:** 422 Unprocessable Entry 
**Content:** ```{ error : "Second name invalid" }```
