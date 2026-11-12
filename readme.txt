=====================================================
LITTLE LEMON RESTAURANT API - CAPSTONE PROJECT
=====================================================

1. Static Web Application Routes:
----------------------------------
GET  /                   - Serve HTML Index Home Page

2. Authentication Routes (Djoser):
----------------------------------
POST /auth/users/        - Register a new user
POST /auth/token/login/  - Generate Auth Token (Login)
POST /auth/token/logout/ - Invalidate Auth Token (Logout)

3. Menu Items API Routes:
-------------------------
GET  /api/menu-items/    - List all menu items
POST /api/menu-items/    - Create a new menu item
GET  /api/menu-items/<id>- Retrieve single menu item
PUT  /api/menu-items/<id>- Update menu item
DELETE /api/menu-items/<id>- Delete menu item

4. Table Booking API Routes:
----------------------------
GET  /api/booking/tables/ - List all table reservations
POST /api/booking/tables/ - Create a new booking

5. Unit Testing Command:
------------------------
python manage.py test tests/