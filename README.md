Demo application for AngularJS seminar
=========

Check out the live demo at http://duylam.github.io/angularjs-techcamp2014

This is the source code of demo application for AngularJS seminar at TechCamp Sai Gon 2014. The presentation slide can be [downloaded from here](http://www.slideshare.net/duypl/building-singlepage-web-applications-with-angularjs-techcamp-sai-gon-2014). The demo app uses following libraries:

- [AngularJS](http://angularjs.org/) (of course)
- [Twitter Bootstrap](http://getbootstrap.com/) to make life easier :)
- [Faker.js](https://github.com/marak/Faker.js/) to help generate dummy data
- jQuery (I hope you understand what it is -:) 


How to deploy
-------

Essential, the demo app is a bunch of JavaScript code running in browser and doesn't require any technology in web server. So the deployment should be just simple, if you're lazy (as I am), here is short guideline: map */public* folder in the source code to the website in your favorite web server and access it from browser (e.g http://localhost/index.html). Otherwise, here is the detail version of guideline:

1. Use Git to retrieve the source code to your local (say C:\angularjs). If you don't know what is Git, [click on this](https://github.com/duylam/angularjs-techcamp2014/archive/master.zip) to download the source code .zip file and extract to somewhere (again, like C:\angularjs)
1. Install any web server to your PC (IIS, Apache, etc.)
1. Create a new website in web server (read the web server documentation), then map the newly created website location to the *C:\angularjs*
1. Done, you can access the app in your browser e.g http://localhost/index.html

