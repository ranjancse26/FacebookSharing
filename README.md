# FacebookSharing

A project to showcase Facebook Sharing Mechanism


# How to run?

We are using "http server" the reason being, It's a simple zero-configuration command-line http server. https://www.npmjs.com/package/http-server

But you may run the app using any web server on any port. 

The Facebook Developer App is configured with the below Site Url
http://localhost:8081

Please do run the app on 8081

ex: http-server F:\ReactJSBased -p 8081

You should see something like below

Starting up http-server, serving F:\ReactJSBased
Available on:
  http://192.168.2.6:8081
  http://127.0.0.1:8081
Hit CTRL-C to stop the server

Finally, navigate to browser using http://localhost:8081

# Facebook Developer App Configuration

Feel free to register in https://developers.facebook.com/ and then change the below appId. If you are running on local, please do add a Web platform like below

![Alt text](https://github.com/ranjancse26/FacebookSharing/blob/master/FBDeveloperApp.png)

FB.init({
		appId      : '727076837459028',
		xfbml      : true,
		version    : 'v2.2'
}); 
