# Get registry of CVs

---
## URL:     /cv

## Method:   GET

## URL Params:

**Required**:

- **page**=[int]; example: **page**=10
- **cvOnPage**=[int]; example: **cvOnPage**=50

## Data Params: none

##Success Responce
Example:\
**Code**:200\
**Content**:

```json
{
    "firstName":"Avas",
    "lastName":"Avasov",
    "jobTitle": "Java developer",
    "shortSummary": "I have been working as a mobile developer for over 5+ years. My goal is to do the best mobile application for your needs.",
    "cellPhoneNumber":"+9724574455",
    "email":"avas@mail.com",
    "age": 35,
    "area": "Beer-Sheva",
    "skills": [
        { "id": "1", "name": "Java", "skill_group_id": "1", "skill_group_name": "Programming_Languages", },
        { "id": "2", "name": "Spring", "skill_group_id": "1", "skill_group_name": "Technologies_Frameworks", },
        { "id": "3", "name": "Eclipce", "skill_group_id": "1", "skill_group_name": "Environments_IDE", },
        { "id": "4", "name": "MongoDB", "skill_group_id": "1", "skill_group_name": "Databases", },
        { "id": "5", "name": "Linux", "skill_group_id": "1", "skill_group_name": "Systems", }]
    "active":"false",s
    "approved":"false"
}
```

## Error responce

**Code:** 401 UNAUTHORIZED\
**Content:** ```json { error:"Log in"}```

## Notes

**firstName** -```string``` (first name of candidate)\
**lastName** - ```string``` (last name of candidate)\
**jobTitle** - ```string``` (position for which the candidate applies)\
**shortSummary** - ```string```  (descripsion of candidate experience and knowledges)\
**cellPhoneNumber** - ```string``` (phone number of candidate)\
**email** - ```string``` (candidate's e-mail)\
**age** - ```integer``` (age of the candidate)\
**skills** - ```array of objects```