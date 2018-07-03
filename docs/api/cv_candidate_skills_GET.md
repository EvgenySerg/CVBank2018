# Get registry of CVs

---
## URL:     /skills

## Method:   GET

## URL Params: none

## Data Params: none

##Success Responce
Example:\
**Code**:200\
**Content**:

```json
{
    "skills": [
        { "id": "1", "name": "Java", "skill_group_id": "1", "skill_group_name": "Programming_Languages", },
        { "id": "2", "name": "Spring", "skill_group_id": "1", "skill_group_name": "Technologies_Frameworks", },
        { "id": "3", "name": "Eclipse", "skill_group_id": "1", "skill_group_name": "Environments_IDE", },
        { "id": "4", "name": "MongoDB", "skill_group_id": "1", "skill_group_name": "Databases", },
        { "id": "5", "name": "Linux", "skill_group_id": "1", "skill_group_name": "Systems", }]
}
```

## Error responce

**Code:** 401 UNAUTHORIZED\
**Content:** ```json { error:"Log in"}```

## Notes

**skills** - ```array of objects```