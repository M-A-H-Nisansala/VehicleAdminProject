###### Vehicle Selling Application #########

Here This Vehicle selling application has two types of login panels. One is for admin and other is for client.
For Admin :- Provide facility to search, insert, delete, and update vehicles .
For Client :- Provide facility to search and view details of the available vehicles.

Admin portal:- (https://vehicle-selling-app-de.herokuapp.com/) 
Client Portal:- (https://vehicle-selling-app-de.herokuapp.com/client)
 


## Admin Vehicle
 [Demo](https://vehicle-selling-app-de.herokuapp.com/) 
username : Admin
password: admin 

## Admin Backend
### Run local Mode:
```
Build:
webpack --watch

Run:
nodemon dist/bundle.js

Access:
localhost:3000/vehicle
```

### Run Remote Mode:
```
Build:
webpack

Push to Server:
git push heroku master

Access Api:
https://vehicle-selling-app-de.herokuapp.com/
```

Api Documents:


## Admin FrontEnd:
### Run local Mode:

```
Build and Run:
ng serve

Access:
localhost:4200/
```

### Run Remote Mode:
```
Build:
ng build

Push to Server:
git push heroku master

Access:
https://vehicle-selling-app-de.herokuapp.com/
```

