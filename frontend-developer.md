# Yottly Frontend Entry Task

The goal of the task is to implement a simple single page application.
This application will react to user input, then load some data from public API and display results.

## Functional requirements
End user should be able to enter a GitHub username and the app will load data about this user and all his repositories. Use public [GitHub API](https://developer.github.com/v3/).
App will show user info and a table containing list of repositories.

User data will include:
- username
- name
- avatar
- location
- date of profile creation
- number of all repositories
- link to the user profile

Repository data for table will include:
- name
- date of the last update
- number of open issues

The table will show maximum of 5 repositories per page. Repositories should be lazy-loaded dynamically while browsing through pages to ensure fresh data. The *name* and *last update* columns should allow sorting the data in both directions. Sorting should reset page to the first one. Sorting and pagination should be done on server side.
Under the table, user should see user's repositories statistics:
- sum of all watchers
- sum of all open issues

After a click on a table row, the application will display repository detail.
Repository detail will include:
- name
- description
- date of the last update
- number of watchers
- number of open issues
- licence type
- primary language
- link to the repository

The application will preserve it's state between page reloads.

## Technical requirements
Build the application on top of the Node.js, using React framework. Any open-source module that doesn't solve the core functionality of the app may be used.
Utilize ES6 (and higher) language features. Keep an eye on the application architecture - the code should be reusable, extendible and easy to maintain. Style your app modestly, rather focus on scalability of your style base. Create a repository on GitHub, share it with us and commit as you progress. As a scaffolding tool we recommend to use [Create React App](https://github.com/facebook/create-react-app).

## Bonus points
Following features are optional but welcomed:
1) Use TypeScript instead of JavaScript. In that case, type all interfaces used. Regarding backend entities - use only relevant properties in interfaces.
2) Use Redux as a tool for state management system.
3) Create at least one test focused on the core functionality.

## Contact
If you struggle, you can contact us anytime and we will provide more information. Also if you stuck at one point, just try to implement the rest of functionality.

Good luck and have fun!

Contact: jsoltes@virtua.ai