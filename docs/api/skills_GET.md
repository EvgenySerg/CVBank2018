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

[
    {
        "skill_group_name": "Programming languages",
        "id": "1",
        "skill_group_id": [
            {
                "id": "1.1",
                "name": "Java",
            },
            {
                "id": "1.2",
                "name": "C++",
            }

        ]
    }
]

[
    {
        "skill_group_name": "IDEs",
        "id": "2",
        "skill_group_id": [
            {
                "id": "2.1",
                "name": "Idea",
            },
            {
                "id": "2.2",
                "name": "Eclipse",
            }

        ]
    }
]

```

## Error responce

**Code:** 401 UNAUTHORIZED\
**Content:** ```json { error:"Log in"}```

## Notes

**skills** - ```array of objects```