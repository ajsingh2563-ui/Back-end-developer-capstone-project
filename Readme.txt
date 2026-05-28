============================================================
LITTLE LEMON RESTAURANT API - TESTING GUIDE
============================================================

Welcome reviewer! Below are the API paths and credentials required 
to test the functionality of this capstone project using the Insomnia 
REST Client.

------------------------------------------------------------
1. USER REGISTRATION & AUTHENTICATION ENDPOINTS
------------------------------------------------------------
* Register a new user (POST):
  http://127.0.0.1:8000/auth/users/

* Log in / Generate Auth Token (POST):
  http://127.0.0.1:8000/auth/token/login/
  
  (Note: Remember to use the generated token in the 'Auth' tab 
   as a 'Bearer Token' or 'Token <key>' for the protected routes below.)

------------------------------------------------------------
2. MENU API ENDPOINTS
------------------------------------------------------------
* List all menu items (GET) / Create a menu item (POST):
  http://127.0.0.1:8000/api/menu-items/

* View, Update, or Delete a single menu item (GET, PUT, DELETE):
  http://127.0.0.1:8000/api/menu-items/<id>/

------------------------------------------------------------
3. TABLE BOOKING API ENDPOINTS
------------------------------------------------------------
* List all reservations (GET) / Create a new booking (POST):
  http://127.0.0.1:8000/api/bookings/

* View, Update, or Cancel a specific booking (GET, PUT, DELETE):
  http://127.0.0.1:8000/api/bookings/<id>/

------------------------------------------------------------
4. STATIC CONTENT LANDING PAGE
------------------------------------------------------------
* Main restaurant homepage serving static HTML/CSS:
  http://127.0.0.1:8000/

============================================================
Thank you for reviewing my project!
============================================================
