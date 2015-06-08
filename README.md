# angular-nobs: The No B.S. Angular Base skelton app for AngularJS apps

This project is an application skeleton for a typical [AngularJS](http://angularjs.org/) web app.
You can use it to quickly bootstrap your angular webapp projects and dev environment for these
projects.

Feel Free to use this skelton app however you like. Any questions or suggestions. Please contact us here:
[Contact Us](http://hyperdrivedesigns.com/contact-us/)

This skelton app contains some of the common AngularJS libraries. There are no test libraries/frameworks or no built in server. No need to learn Bower, Grunt, Node JS, Karma, Jasmine and all of those extra overhead libraries found in a lot of other Angular JS Skelton Apps. You will need a web server on your local machine such as WAMP, MAMP or XAMPP. If you already have a dev staging server then you can also use that. No extra libraries, no built in server, no bunch of dependencies. No EXTRA Overhead. No BS!! All you need is a web server. Just clone the repo (or download the zip/tarball), into your local dev server or just download the files and then upload them up to your staging server and you are ready to develop and test your application.

## How to use angular-nobs

Clone the angular-nobs repository into your local development enviroment such as WAMP, MAMP, or XAMPP. Or if you have SSH access to a web server you can clone the repo into your web server. Or download the ZIP file, extract and then FTP up to your web server. Get CODING!!!

Because the index.html page is coded for manual Angular JS start up, it is ready out of the box.
This Angular JS Skelton App uses two simple Angular examples. One on each view. Also, there is a copy of bootstrap css for styling. Feel free, to delete the bootstrap css file and roll your own. Also, there is a app.css to use for including your own custom css styles made to your Angular app. Throw your images in the img folder. The lib/angular folder holds the extra Angular libraries that are sometimes needed. Feel free to delete the ones that you are not using when pushing to production.

### Running the app in production

Angular apps are really just a bunch of static html, css and js files that just need to be hosted
somewhere, where they can be accessed by browsers.

## Directory Layout

    app/                --> all of the files to be used in production
      css/              --> css files
        app.css         --> default stylesheet
      img/              --> image files
      index.html        --> app layout file (the main html template file of the app)
      js/               --> javascript files
        app.js          --> application
        controllers.js  --> application controllers
        directives.js   --> application directives
        filters.js      --> custom angular filters
        services.js     --> custom angular services
      lib/              --> angular and 3rd party javascript libraries
        angular/
          angular.js        --> the latest angular js
          angular.min.js    --> the latest minified angular js
          angular-*.js      --> angular add-on modules
      partials/             --> angular view partials (partial html templates)
        partial1.html
        partial2.html