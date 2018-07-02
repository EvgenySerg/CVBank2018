# Show candidate's profile

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
"firstName":"Avas",
"lastName":"Avasov",
"cellPhoneNumber":"+972534501456",
"email":"avas@mail.com",
}
```

## Error responce

**Code:** 401 UNAUTHORIZED\
**Content:** ```json { error:"Log in"}```

**Code:** 422 Unprocessable Entry\
**Content:**```json {error:"Email invalid"}```

**Code:** 422 Unprocessable Entry\
**Content:** ```json { error : "Phone number invalid" }```

**Code:** 422 Unprocessable Entry\
**Content:** ```jsin { error : "First name invalid" }```

**Code:** 422 Unprocessable Entry\
**Content:** ```json { error : "Second name invalid" }```