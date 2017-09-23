#Knet integration
Integrating Knet payment gateway for Hybrid App(Ionic Framework and AngularJS)

Knet integrating the payment gateway in ionic. 

1- I will add the cordovaInAppBrowser plugin and Inject the dependency.
2- then make all the fields i get that to send to that Gateway with all validations.
3- now I needed some 3 files as success, failure. and paymentfile.html.
4- $cordovaInAppBrowser.open("filename?)
         success and faliure  file are in server and access them through server
5- get the response in the  file than to controller, based on the response traverse the path and its done.
6- finally  serialize the data while sending 