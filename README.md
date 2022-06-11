# Mozio Location Polygon API

## API Documentation

URL/  : Endpoint: /Providers

      : GET, POST
      
      : Description: Create a Provider.
      
      : URL: http://localhost:8000/providers

URL/  : Endpoint: /Providers/1

      : GET, DELETE, PUT
      
      : Description: A Provider's Details. Update, Delete Provider.
      
      : URL: http://localhost:8000/providers/1

URL/  : Endpoint: /Providers/1/Polygons

      : GET, POST
      
      : Description: A Provider's Service Areas. Create new Service Area.
      
      : URL: http://localhost:8000/providers/1/polygons

URL/  : Endpoint: /Providers/1/Polygons/1

      : GET, DELETE, PUT
      
      : Description: A Service Area's Polygon Details. Update, Delete Service Area.
      
      : URL: http://localhost:8000/providers/1/polygons/1

URL/  : Endpoint: /Providers/1/Polygons/1/Polygon

      : GET, POST,
      
      : Description: A Service Area's Polygon 'Lats' and 'Lngs'. Add New Polygon Coordinates.
      
      : URL: http://localhost:8000/providers/1/polygons/1/polygon

URL/  : Endpoint: /Providers/1/Polygons/1/Polygon/1

      : GET, DELETE, PUT
      
      : Description: A Polygon's 'lat' and 'lng' coordinates. Update, Delete a Polygon.
      
      : URL: http://localhost:8000/providers/1/polygons/1/polygon/1

URL/  : Endpoint: /Users/

      : Description: Create a new User.
      
      : URL: http://localhost:8000/users/

URL/  : Endpoint: /Login/

      : Description: Login to platform.
      
      : URL: http://localhost:8000/login/

URL/  : Endpoint: /Services/?lat=&lng=

      : Description: List all 'service areas' within parameters 'lat' and 'lng'.
      
      : URL: http://localhost:8000/services?lat=&lng=



