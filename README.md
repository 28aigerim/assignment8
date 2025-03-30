# Employee Database
____
#### Employee Database 
Created database employee.sqlite with columns: 
- id (int, primary key, auto-increment)
- name (text)
- position (text)
- salary (real)
- hire_date (text)

#### Employee entity class 
Class Employee with attributes: 
- id (int)
- name (text)
- position (text)
- salary (real) 
- hire_date (text)

Methods: __str__(), getter and setter methods: get_salary(), set_salary().

#### EmployeeDAO class 
EmployeeDAO class handles the CRUD operations on the employee table in the database.
Methods: 
- insert(employee:Employee): Insert a new employee into the employee table.
- get_by_id(id:int): Retrieve an employee’s details from the employee table by ID.
- get_all(): Retrieve all employees from the employee table.
- update(employee:Employee): Update an employee’s details in the employee table.
- delete(id:int): Delete an employee from the employee table using the employee's ID.

#### Testing 
All provided CRUD operations in DAO class tested in the provided 'sample_input_output' file.
