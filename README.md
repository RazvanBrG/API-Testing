# API-Testing

Here are some examples of API testing using Postman tool.

**API:**
https://qachallenge.ro/api/

**Create (POST):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=insert

Body (form-data) parameters: Key: first_name     Value: RRRRR
                             Key: last_name      Value: BBBBB

**Result:**
User has been added to the list.

![Screenshot of Postman tool ilustrating POST function.](https://imgur.com/a/5fh4x4x)

![Screenshot of API ilustrating POST function.](https://imgur.com/3VR7GHz)


**Read (GET):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=fetch_all

**Result:**
The application will return all existing users.

![Screenshot of Postman tool ilustrating GET function.](https://imgur.com/EQdBsHZ)


**To get a single user:**
Endpoint: http://qachallenge.ro/api/test_api.php?action=fetch_single&id=628

**Result:**
The application will return just the user with the specified ID.

![Screenshot of Postman tool ilustrating GET function.](https://imgur.com/tKZoAqL)


**Update (POST):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=update&id=808

Body (form-data) parameters: Key: first_name     Value: Razvan
                             Key: last_name      Value: Bibirig

**Result:**
The user with ID 808 will take new values from the Body section.

![Screenshot of Postman tool ilustrating POST function.](https://imgur.com/lkVeqvy)
![Screenshot of Postman tool ilustrating POST function.](https://imgur.com/1ceEeta)


**Delete(DELETE):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=delete&id=808

**Result:**
The user with specified ID will be deleted.

![Screenshot of Postman tool ilustrating POST function.](https://imgur.com/Uv9Aace)
