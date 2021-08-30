## Server/Back-End for Model Website of Theoretical Space Travel Provider

- The goal is to emulate the functionality of an airline website, adjusted for space travel
    - Database will feature typical customer accounts as well as extensive trip and destination data

### Note on using Postman:

When using Postman to test routes, for req.body either choose 'raw' and select JSON from the dropdown menu, or activate line with 'urlencoded' middleware in app.js if you would like to enter req.body via 'x-www-form-urlencoded' in Postman. The latter approach is also necessary if the data is being entered using a form on the client side.
