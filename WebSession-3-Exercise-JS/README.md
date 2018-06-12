# Web Session 3 Exercise - JS, jQuery

Your task for this exercise is to create your first dynamic website.

You are given three files: `users.js`, `posts.js`, `comments.js`. Use these 3 files to create an interactive interface.

You are **NOT** required to use all three files. This should be more focused on using jQuery and Javascript in a project, so don't worry too much about the interface.

### Ideas for your interface

Combine the ones you prefere. This are just ideas, you can do other things with your data.

- Display all users data
- Display first 10 users and add pagination
- Display just the names of your users and when clicking or hover on a name, display the complete information
- Attach a button to each user to display it's posts
- Display all posts
- Attach a button to each post to toggle it's comments
- Add a user/post/comment
- Edit an existing user/post/comment

### Tips & Tricks

- Try to use Bootstrap without adding extra CSS. You will learn the power of bootstrap
- The js files should be included in the following order (Remember to not import unused files): `jQuery`, `bootstrap`, `users/posts/comments`, `custom scripts`
- As the data files are just global arrays, you can refer to them in your scripts just with it's variables name. Ex.

```
users.map(i => console.log(`${i.name} - ${i.email}`))
```

- If using jQuery, remember to do everything inside `ready` function.
- Try to use ES6 standard.
- jQuery is a very complete framework. If you think you need a function to manipulate in some sort of way your HTML, there will be a jQuery function that does that for you.

### Resources

- http://api.jquery.com/
- https://codeburst.io/es6-tutorial-for-beginners-5f3c4e7960be
- https://www.digitalocean.com/community/tutorials/an-introduction-to-jquery
