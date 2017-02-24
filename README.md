# Simple WebApp using AngularJS and Firebase
A simple web application using angularjs and firebase.
It's a simple web application where a user can simply signup and signin and create post and can edit/delete their post.

Configure the app by adding the project's config object:-
var config = {
    apiKey: "apiKey",
    authDomain: "projectId.firebaseapp.com",
    databaseURL: "https://databaseName.firebaseio.com",
    storageBucket: "bucket.appspot.com"
  };
firebase.initializeApp(config);
