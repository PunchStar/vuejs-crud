
<h4 align="center">Vue.js based REST-ful CRUD system.</h4>

* Vue CRUD allows to create both a mechanism for managing a single table, as well as a CMS or extended CRM with a login system and modules
* Application built with Vue CRUD is SPA (Single Page Application) so it works much faster than apps based on Wordpress, Joomla, etc.
* Vue CRUD uses the vue along with its ecosystem (Vuex, Vuetify, etc). Enjoy the benefits of the most popular JS framework in the world.
* The application architecture is adapted to work with REST API
## Functions
Vue CRUD provides a set of utilities, from which you can compose your own application. Features included in the system can communicate with each other thanks to the use of the Vuex library. Vue CRUD includes the following elements:

- **CRUD** | <a href="http://vue-crud-demo.id-a.pl/#/crud" target="_blank">DEMO / SANDBOX</a>:
  - operations on records:
    - Store,
    - Update,
    - Suspend/Restore,
    - Delete,
    - Multiple update,
    - Multiple Suspend/Restore,
    - Multiple Delete
  - filtering:
    - Show active/inactive records,
    - Search phrase in whole table,
    - Search phrase in selected column (exact, like and list mode)
  - items view versions:
    - client side (small tables),
    - server side (big tables)
  - items view types:
    - table,
    - **NEW!** tree
  - other functions and features:
    - datatable mechanism allows selection of the number of records per page, page transition and sorting,
    - management of a child table from the parent table module,
    - export to excel (xlsx),
    - table refreshing,
- **Authentication system** | <a href="http://vue-crud-demo.id-a.pl/#/login" target="_blank">DEMO / SANDBOX</a>:
  - login form (built-in communication with API, validation),
  - optional locale selection,
  - redirecting to the app,


## Demo versions

#### <a href="http://vue-crud-demo.id-a.pl" target="_blank">DEMO / SANDBOX</a>

#### <a href="http://vue-crud-crm.id-a.pl" target="_blank">CRM DEMO</a>
Credentials with limited privileges (readonly):\
Login:  guest@vue-crud.com\
Pass:   ajSGenC0\
To get full user account, contact me on my <a href="http://id-a.pl" target="_blank">company site</a>.

## Quick start

Do you want to test the application quickly, and you do not have an API ready? No problem, you can use the ready-made example in the **examples** folder. The API for this example is available on the internet, so you can connect to it by entering its address in the configuration file.

### Steps

1. Clone Vue CRUD:
``` console
git clone git@github.com:what-crud/vue-crud.git
```
2. Type following commands:
``` console
yarn
:: or
npm install
```
3. Choose one of the following templates:
- `empty`,
- `simple-crud`,
- `sandbox`,
- `crm`,
- `cms`

...and type e.g.:
``` console
yarn load-template simple-crud
:: or
npm run load-template simple-crud
```
4. If you have your own API prepared, modify **src/config/api.js** file.

5. Serve your app:
``` console
npm run serve
```
6. Your app is already running (probably at http://localhost:8080).

## API
The application requires a connection with the appropriate API. API can be created in any technology - the condition is its compliance with the Vue CRUD communication specification. If you need to create your API and do not know how to get started, and you don't mind PHP and Laravel, download or clone the <a href="https://github.com/oh-crud/laravel-crud-api" target="_blank">Laravel CRUD API</a> project.
