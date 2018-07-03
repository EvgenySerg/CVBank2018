# Show employer's profile

---

## URL:   /profile

## Method:   GET

## URL Params: none

## Data Params: none

## Success Responce

Example:\
**Code**:200\
**Content**:

```json
{  
   "employerProfile":{  
      "companyDetail":{  
         "companyName":"Superferma",
         "companyWebSite":"www.sait234.net",
         "country":"Israel",
         "city":"Tel Aviv-Yafo",
         "street":"King George",
         "building":"30-5",
         "postcode":"102920",
         "phone":"0536541212"
      },
      "applicantDetail":{  
         "firstName":"Avas",
         "lastName":"Avasov",
         "position":"CEO",
         "cellPhoneNumber":"+972534501456",
         "email":"avas@mail.com"
      }
   }
}
```

## Error responce

**Code:** 401 UNAUTHORIZED\
**Content:** ```json { error:"Unauthorized access"}```