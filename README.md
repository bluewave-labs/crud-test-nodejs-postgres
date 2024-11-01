# CRUD Test: Nodejs & PostgreSQL

Create a simple CRUD application with Node that implements the below models:

```
User {
    firstname
    lastname
    emailAddress
    phone
    dateOfBirth
}

Task {
    title
    dueDate
    description
    ownerId
}
```

---

## Practices and patterns (Must):

- [Unit testing: Link 1](https://en.wikipedia.org/wiki/Unit_testing), [Link 2](https://www.testim.io/blog/node-js-unit-testing-get-started-quickly-with-examples/), [Link 3](https://www.lambdatest.com/learning-hub/nodejs-unit-testing)
- Clean git commits that show your work progress.

---

## Help

- Use postgreSQL as database
- Each User can have multiple tasks
- When a User is deleted, its related tasks must be deleted as well

---

## Validations (Must)

- During Create; validate all the fields(You can use Google **LibPhoneNumber** to validate mobile number).
- Users must be **unique** in the database: By **firstname, lastname, dateOfBirth, and phone**.

---
