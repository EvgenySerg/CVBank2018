# API URLs

| #   | URL                                                                                                | Method | Description                                                    |
| --- | -------------------------------------------------------------------------------------------------- | ------ | -------------------------------------------------------------- |
| 1   | /                                                                                                  | GET    | Show home page                                                 |
| 2   | /login                                                                                             | POST   | Send authentication information to the server                  |
| 3   | /register                                                                                          | POST   | Add new profile (register new user)                            |
| 4   | [/cv] (https://github.com/EvgenySerg/CVBank2018/blob/master/docs/api/cv_candidate_GET.md)          | GET    | Get the registry of CV and of scpecified page                  |
| 5   | /cv                                                                                                | POST   | Add new CV                                                     |
| 6   | /cv/{id}                                                                                           | GET    | Get CV detail                                                  |
| 7   | /cv/{id}                                                                                           | PATCH  | Deactivate/activate selected CV/ id - id of selected CV        |
| 8   | /cv/{id}                                                                                           | PUT    | Edit selected CV.                                              |
| 9   | /cv/{id}                                                                                           | DELETE | Delete CV with selected id                                     |
| 10  | [/profile]  (https://github.com/EvgenySerg/CVBank2018/blob/master/docs/api/profie_canidate_GET.md) | GET    | candidate - Get current profile information                    |
| 11  | /profile                                                                                           | PUT    | candidate - Edit current profile information                   |
| 12  | /profile                                                                                           | PUT    | employer - Edit current profile information                    |
| 13  | /profile                                                                                           | GET    | employer - Get current profile information                     |
| 14  | /profile                                                                                           | DELETE | Delete current profile                                         |
| 15  | /searchcv?{params}                                                                                 | GET    | Search CVs with given parameters                               |
| 17  | /defaultsearchcv                                                                                   | PUT    | Save search criteria for default usage of the CV registry page |
| 18  | /skills                                                                                            | GET    | Get current candidate skills                                   |