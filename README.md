# Tasks

## Level1

- Basic Laravel Auth: ability to log in as administrator
- Use database seeds to create first user with email admin@admin.com and password "password123"
- CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
- Companies DB table consists of these fields: Name (required), email, website
- Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone
- Use database migrations to create those schemas above
- Use basic Laravel resource controllers with default methods – index, create, store etc.
- Use Laravel’s validation function, using Request classes
- Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page
- Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register

## Level2

- Add logo into Companies
- Use database migrations to alter Companies table
- Store companies logos in storage/app/public folder and make them accessible from public