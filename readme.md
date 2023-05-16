# Tugas Akhir Rakamin Evermos Virtual Internship

### This project aims to provide a framework and components that can be used to build efficient and scalable server-side applications.

## Main feature:

1. Routing and Request Management: Backend-Golang provides a robust routing system to route HTTP requests to the appropriate controllers. This allows you to easily handle requests and associate them with relevant functions or methods.

2. Connection to Databases: This project supports connections to various types of databases, including MySQL, PostgreSQL, and MongoDB. This allows you to integrate applications with the necessary databases.

3. Middleware: Backend-Golang provides middleware which can be used to modify or examine requests before they reach the controller. For example, you can use middleware for authentication, authorization, rate-limiting usage, logging, and so on.

4. User Management: This project provides components for user management, including registration, login, profile settings, and permissions management. You can easily integrate this feature into your application to manage users.

5. Security: Backend-Golang places security as a priority. It provides security features such as password hashing, secure token storage, and protection against common attacks such as Cross-Site Scripting (XSS) and SQL injection attacks.

6. Documentation and Community: This project provides clear and detailed documentation on how to use the components and features provided. Apart from that, there is also an active community where developers can share knowledge, ask questions, and collaborate.

### How to config MySQL DSN   
https://levelup.gitconnected.com/build-a-rest-api-using-go-mysql-gorm-and-mux-a02e9a2865ee

### API Daerah
https://www.emsifa.com/api-wilayah-indonesia/

### How to use makefile command
```bash
make {{command}}

# ex:
make run
```

### Check Relation
```sql
select * from INFORMATION_SCHEMA.TABLE_CONSTRAINTS;


SELECT 
  TABLE_NAME,COLUMN_NAME,CONSTRAINT_NAME, REFERENCED_TABLE_NAME,REFERENCED_COLUMN_NAME
FROM
  INFORMATION_SCHEMA.KEY_COLUMN_USAGE
WHERE
  REFERENCED_TABLE_SCHEMA = 'rakamin_intern' 
```
