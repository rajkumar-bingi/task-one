# task-one

3 End Point’s
1.Register
2.Login
3.Product List

Using Django Rest Framework, Postgres (PgAdmin) &amp; JWT/Django authentication

Register:
Crete an API post call to get fields like username, phone, email, password
and role (admin, manager, staff).

Login:
Create an API call for user to login, using his credentials / fields names like
email and password if valid user return response with his details along with JWT
authentication token.

Product List:
Create an API post call for Products list to take input fields like product
name, product price, product description, inventory count along with JWT token.
Use the JWT token to verify whether he has access to CRUD operations or not.

Perform CRUD operations like
1 - API call to create product - (admin)
2 - API call to read all products – (admin, manager)
3 - API call to update inventory – (admin, manager)
4 - API call to Delete a product – (admin)
5 - No CRUD Operation for Staff

Use JWT authentication whether the session user has rights to perform these
operations or not.

Note:
Database should be Postgres and for authentication you must use JWT/Django
these are mandatory along with Django Rest Framework.
