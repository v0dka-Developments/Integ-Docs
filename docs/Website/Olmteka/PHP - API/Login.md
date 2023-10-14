---
sidebar_position: 1
---

# Login (username,password)

This function is to log the user in and create a session cookie if 
the user login was successfull

the usage of the function is:

```php title="api.php"
 $result = login($username,$password);
 echo $result;
```

the login function creates the following session details

```php title="api.php - login(){}"
 $_SESSION['username'] = users username;
 $_SESSION['password'] = users encrypted password..
 $_SESSION['start_time'] = current server time
```
