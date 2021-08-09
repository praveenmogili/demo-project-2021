# demo-project-2021
Sample Demo Project
Build an app with Fron end in react and back end in Django and dockerize it so that it can be portable. Upload the code to a repo or send it as a zipfile with instructions in readme. 

## Build a Front End

Create a react app with CRUD (create, read, update and delete) compoments/actions with two objects this will communicate with back end using REST API
1. Main page of the app will be showing two tabs - Customers and Contacts each tab with a listing of corresponding items.
2. Customers - build. list page with a table which has links to individual customer and edit, delete buttons as well. clicking on customer should take one to view page where there are edit and delte buttons as well. On the list page there is a '+' icon which will allow you to create a customer and save it to backend using REST API.
3. Contacts - similar pages to Customer (list, view, edit delete actions).
4. Customers contact list - provide a page/link to see all the contacts given a customer. 
5. Sign-off page

## Build a Back End
Build a backend in Django and provide a REST API to the front end

Fields for Customer : Name, Adderess (geo location so that its mappable in google) should be sortable by city and/or State
Fields for Contacts : Name, Title, email, phone, customer

App should have an option to create a new Contact and assign it to a customer. Customer can have many contacts.

## Dockerize the application
Using google find a way to dockerize this app and provide a docker-compose file for both react and django as a complete package.

## Setup Authentication using keycloak
Once the app is working, please setup keycloak using docker images and integrate the demo app with keycloak for users login

