### Conceptual Exercise

Answer the following questions below:

- What is PostgreSQL?

    PostgreSQL is an open source object-relational database system that uses the SQL language.

- What is the difference between SQL and PostgreSQL?

    SQL is a databse management system while PostgreSQL is a more advanced version of SQL that supports different functions of SQL.

- In `psql`, how do you connect to a database?

    `\c <database_name>`

- What is the difference between `HAVING` and `WHERE`?

    `WHERE` is used to filter rows before grouping while `HAVING` is used to filter after grouping.

- What is the difference between an `INNER` and `OUTER` join?

    `INNER` join focuses on what's common between two tables (the middle of a venn diagram), while `OUTER` join focuses on what is not common between the two tables (the two outside circles of a venn diagram).

- What is the difference between a `LEFT OUTER` and `RIGHT OUTER` join?

    `LEFT OUTER` returns all the data from Table 1 and the common data with Table 2, while `RIGHT OUTER` returns all the date from Table 2 and the common data with Table 1.

- What is an ORM? What do they do?

    An ORM is an object relational mapper that writes queries using your preferred programming language.

- What are some differences between making HTTP requests using AJAX 
  and from the server side using a library like `requests`?

    HTTP requests using AJAX are:
    - Client side
    - Asynchronous
    - Request logic is triggered when event is launched or function is called

    While server side requests are:
    - RESTful
    - Server side
    - Request logic is triggered when an endpoint is visited with correct method

- What is CSRF? What is the purpose of the CSRF token?

    Cross-site request forgery is a web security vulnerability that causes users to perform actions that they did not mean. CSRF token is a unique value that is generated server-side and transmitted client-side to be included in a HTTP request. When the request is made, if the CSRF token is present, then the request will be denied.

- What is the purpose of `form.hidden_tag()`?

    Render multiple hidden fields in Flask-WTForms without rendering them individually.