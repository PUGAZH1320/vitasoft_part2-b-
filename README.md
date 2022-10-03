### After runnning this backend applicaton (i.e) vitasoft_part2-b- , need to start frontend form application (i.e) vitasoft_part1 repository
## `npm start`
 Runs the backend server on port 3001
 which connects with the MongoDB cluster
 Open [http://localhost:3001](http://localhost:3001) to view it in your browser.
 
 
 #Frontend Form
 ### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

 
it will open our form application

On submit it will show the datas entered in that form on next route (i.e) http://localhost:3000/success


#ADD ON
you can also change MongoDB cluster in .env file which is in  vitasoft_part2-b- repository

in my case it contains
###DATABASE_URL=mongodb+srv://admin1:admin@cluster0.imzz1.mongodb.net/test
 
### Im using REST client which is a vs code extension instead of postman here.
route.rest constains all the request

###GET http://localhost:3001/
will get all the data present in DB.

###DELETE http://localhost:3001/form/delete-details/:id
will delete the data respective to ID

######PATCH http://localhost:3001/update/:id
Content-Type: application/json

{
    "firstName":"Mals"
}

will update the value respective to the ID
