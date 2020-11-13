# JMeter Cognito Testsuite
JMeter Testsuite for Cognito secured API services

Amazon Cognito is very popular identity provider that supports Oauth 2.0, SAML 2.0, OpenID and multi-factor authentication features.
One of most popular features of cognito is hosted login page. You don't need to create your own login service & UI to implement authentication.
Recently Postman become one of most popular UI clients to test API services. But Oauth 2.0 authentication is not very convenient in Postman. In case of Cognito login it requires you to enter login credentials manually every time when you need to login. To automate that process I implemented Jmeter tests suit to automatic users registration & login without providing username/password to Cognito login form.

## Features
* Automatic Cognito user registration
* Automatic Cognito login and aquiring authentication token
* Support of M2M (Machine to Machine authorization)
* Nice execution request/response statistic
* Several predefined development environments DEV,QA,STAGE,PROD

![Jmeter](screenshot.png?raw=true "Jmeter Test Suite")
