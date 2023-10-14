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

![API_Create](https://github.com/RazvanBrG/API-Testing/assets/145659747/020150ab-b3a2-4e93-b686-3ad17db7a04a)

![API_Create(1)](https://github.com/RazvanBrG/API-Testing/assets/145659747/c1e6c7a1-43ef-47ad-8d6e-5fef8e380dc7)



**Read (GET):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=fetch_all

**Result:**
The application will return all existing users.

![API_Read_ALL](https://github.com/RazvanBrG/API-Testing/assets/145659747/6cee2ba1-4132-4c37-9d37-7278eadd8785)


**To get a single user:**
Endpoint: http://qachallenge.ro/api/test_api.php?action=fetch_single&id=628

**Result:**
The application will return just the user with the specified ID.

![API_Read_1](https://github.com/RazvanBrG/API-Testing/assets/145659747/dc56d1b5-ad01-4785-93c5-45adad9c2e28)



**Update (POST):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=update&id=808

Body (form-data) parameters: Key: first_name     Value: Razvan
                             Key: last_name      Value: Bibirig

**Result:**
The user with ID 808 will take new values from the Body section.

![API_Update](https://github.com/RazvanBrG/API-Testing/assets/145659747/56df2095-8772-4fd6-8285-4eed1badc77e)
![API_Update(1)](https://github.com/RazvanBrG/API-Testing/assets/145659747/9f8c59d4-51c7-4951-8e12-0432e47a7ade)



**Delete(DELETE):**
Endpoint: http://qachallenge.ro/api/test_api.php?action=delete&id=808

**Result:**
The user with specified ID will be deleted.

![API_Delete](https://github.com/RazvanBrG/API-Testing/assets/145659747/3a4fbcff-2075-4348-a294-c4ef49f07c99)

