# MinticLogin
 Se realiza la Historia de Usuario Login 
 
----------------------------------------------

Post: http://localhost:8000/user/

JSON: 

{
 "username": "fjgomezpe",
 "password": "contraseña",
 "name": "francisco",
 "email": "fjgomezpe@misionTIC.com",
 "account": {
 "lastChangeDate": "2021-09-23T10:25:43.511Z",
 "balance": 20000,
 "isActive": true
 }
}

---------------------------------------------

Post: localhost:8000/login/

JSON:
{
"username": "fjgomezpe",
"password": "contraseña"

}

--------------------------------------------

localhost:8000/refresh/

JSON:
{
    "refresh": "eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoicmVmcmVzaCIsImV4cCI6MTYzNDc4ODY2NSwianRpIjoiYjg5YjM0MjQ1OTA4NDEwMmE2ZmIwMDZiMWJkZDRmMzYiLCJ1c2VyX2lkIjoxfQ.Ti-Ro9xAKco52f-V2Ctiy6Wgy7N6he1sIYox4b-bYpw",

}

--------------------------------------------

http://localhost:8000/user/1

Autorization> Bearer Token > agrecar el campo del access
eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJ0b2tlbl90eXBlIjoiYWNjZXNzIiwiZXhwIjoxNjM0NzAyNjY0LCJqdGkiOiI4Nzc3NTg1ODAwZDg0MjA3YjBiNzkxZmQ0ZDU2ODcyZCIsInVzZXJfaWQiOjF9.cePRrNIbGtJo16tqtsJ2_UfHVOATGKfiWtF6PRqraT

