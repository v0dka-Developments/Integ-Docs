---
sidebar_position: 2
---

# validate ()

This function will validate a user session it takes no paramaters as it checks for session

the session has to meet the following requirements:
session time < 15minutes (idle = session destroy)
encrypted password value matches encrypted password value in the database otherwise session destroyed


the usage of the function is:

```php title="api.php"
 $result = validate();
 echo $result;
```
