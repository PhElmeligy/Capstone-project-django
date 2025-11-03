/admin/	GET	Django admin interface
/restaurant/	GET	Render home page
/restaurant/menu/	GET	List all menu items
/restaurant/menu/	POST	Create a new menu item
/restaurant/menu/<int:pk>	GET	Retrieve a menu item by ID
/restaurant/menu/<int:pk>	PUT	Update a menu item
/restaurant/menu/<int:pk>	PATCH	Update a menu item
/restaurant/menu/<int:pk>	DELETE	Delete a menu item
/restaurant/bookings/	GET	List all bookings
/restaurant/bookings/	POST	Create a booking
/restaurant/bookings/<int:pk>	GET	Retrieve a booking
/restaurant/bookings/<int:pk>	PUT	Update a booking
/restaurant/bookings/<int:pk>	PATCH	Update a booking
/restaurant/bookings/<int:pk>	DELETE	Delete a booking
/restaurant/msg	GET	Authenticated test message
/auth/users/	POST	Register a new user
/auth/token/login/	POST	User login and obtain token
/auth/token/logout/	POST	Logout and delete token
/auth/users/	GET	List users (optional)
