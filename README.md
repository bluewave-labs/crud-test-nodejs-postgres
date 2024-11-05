# CRUD Test: Nodejs & PostgreSQL

Create a simple CRUD application with Node that implements the below models:

```
User {
    firstName
    lastName
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

## Practices and patterns

- [Unit testing: Link 1](https://en.wikipedia.org/wiki/Unit_testing), [Link 2](https://www.testim.io/blog/node-js-unit-testing-get-started-quickly-with-examples/), [Link 3](https://www.lambdatest.com/learning-hub/nodejs-unit-testing)
- Clean git commits that show your work progress.

---

## Help

- Use postgreSQL as database
- Each User can have multiple tasks
- When a User is deleted, its related tasks must be deleted as well

---

## Validations

- During Create; validate all the fields (You can use Google's **LibPhoneNumber** to validate mobile number).
- Users must be **unique** in the database: By **firstname, lastname, dateOfBirth, and phone**.

---

### Delivery

Follow those steps to deliver your work: 

-  Properly clone this repository in a new GitHub repository in private mode. Make sure you do not erase previous commits (for code review purposes).
-  Share the repository with the users `MuhammadKhalilzadeh` and `gorkem-bwl` in private mode on github.com.

---

#### Useful links

There are a few great links about Git, GitHub collaboration and naming convention. Make sure your read those documents before you start your work. 

- [Basic Git Instructions: Making pull request to the original repository](https://github.com/MuhammadKhalilzadeh/basic-git-instructions?tab=readme-ov-file#making-pull-request-to-the-original-repository)
- [Git Collaborative Workflow Tutorial: Making a Pull Request](https://github.com/ajhollid/bluewave_collaborative_git?tab=readme-ov-file#making-a-pull-request)
- [Link to a brief description on our naming convention](https://github.com/MuhammadKhalilzadeh/basic-git-instructions?tab=readme-ov-file#checking-out-and-creating-a-new-branch)
