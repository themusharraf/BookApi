# BookAPI Deployment Test Server 

![orm](https://github.com/themusharraf/bookapi/assets/122869450/7e30603c-a0f2-466c-a826-892454b756fd) 
 [main.py](main.py)
   
## Example Request for Updating User:
### http

```
PUT /users/1
Content-Type: application/json

{
  "username": "new_username",
  "email": "new_email@example.com",
  "is_active": true,
  "password": "new_password"
}
```
## Example Request for Updating Book:
### http

```
PUT /books/1
Content-Type: application/json

{
  "title": "Updated Title",
  "language": "English",
  "isbn": "978-3-16-148410-0",
  "pages": 250
}
```
