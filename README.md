# Employee Dashboard
## Splash screen
- show a splash screen for 2seconds and then navigate to login page.
## Login page
- locally store user name and password and authenticate
- use redux or context api or local storage.
- on login success navigate to Dashboard page.

## Dashboard
- Total number of employees
- Average salary in each age group
- on tap view all page list all employees list
## List page
-   able to view all and add new employee

## Details
- able to view single employee details and delete the employee

### List all employees API
- https://dummy.restapiexample.com/api/v1/employees
- method: GET

### Add new employee API
- https://dummy.restapiexample.com/api/v1/create
- method: POST
- params: {"name":"test","salary":"123","age":"23"}
- should save locally and update the list of employees and the dashboard.

### Remove an employee API
- https://dummy.restapiexample.com/api/v1/delete/2
- method: DELETE
- should update the list and the dashboard.

