# Developer-Test


## React-Redux Application

* You need to create a basic `CRUD`(_create, receive, update, delete_) Application which can use the APIs from [Learncode Academy Sample API](http://rest.learncode.academy/)
* The needs to have the following sections
  * `List page`, listing all the entities you have in your API 
  * A `detail page`, The user can click on any of the items and see the details of that item
  * The user can delete the items from the `list page` directly
  * The user should also be able to edit any item, from an `Edit` view
* You can design the page however you like
* Structure the Application as per your needs and liking
* The application should also use `Router` to navigate between the pages.
* The `Edit` page should have the basic validations on the form
* use component level state (`this.state`) only when absolutely required, otherwise make use of `Redux` for everything
* The `API` requests should handle state for loading, error, empty response and so on.


## Notes
Use a starter kit of your choice.
Feel free to use npm packages to help you achieve a result.

## Deliverable
Submit a pull request against this repository. Developers will review your code and ask you questions in the pull request.

We will pull your code and execute the following commands:
```
npm install
npm start
```
These commands should start a Node.JS server and serve your app in development mode. We expect the terminal to display a URL to see your code in browser. Recommended url is `http://localhost:3000`
