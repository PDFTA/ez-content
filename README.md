# ez-content

EZ Content is an API endpoint product that allows people to understand the meta-data surrounding http header information.

The initial application will be a python flask app served through Google App Engine. Authentication will be handled using Google Firestore.

## Layers
Navigator Object - [w3 Doc](https://www.w3schools.com/jsref/obj_navigator.asp) with [Demo](https://www.w3schools.com/jsref/tryit.asp?filename=tryjsref_nav_all)
HTTP Headers - Device Type, Time of day, Languages
GA Data - City, Country
Logic - Nested logic dependent on higher layers, For example Weather requires location from layer 2
Business Logic - User First Name, User Last name, previous purchases
