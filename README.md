commshare
=========

Grails 2.0 working prototype of a social web application.

Features
--------

The purpose of this demo application is to evaluate the web application framework Grails. This results mainly from my personal interests and from my needs to be more effective. The current version is by no means intended as a fully featured social networking site.

For more information about Grails framework you can visit http://www.grails.org

Here are some features of this demo:

- Simple community/social web aplication developed in Grails 2.0.4.
- Responsive layout using Bootstrap, HTML5 and CSS3 enabling user experience on different view devices (try to resize the browser window width!).
- Login, Logout, Registration with email confirmation, Lost password, Reset password by means of Spring Security.
- Distinguished roles of anonymous, regular and administrator users.
- Approximate displaying of time using Pretty Time.
- Administration of users, roles and other security info.
- Possibility to "follow" other users by means of AJAX.
- Modal dialog to edit user profile.
- Uploading user image in AJAX way.
- Recaptcha integration to help avoid spam.
- Scaffolded, but customized administration of underlying entities.

Instructions
------------

- Install **Grails SDK** version 2.0.4

- Download **commshare** source code from github to your local folder:

	git clone https://github.com/renp/commshare.git

- Optionally run unit and integration tests

	grails test-app
	
- Run and test the app locally

	grails run-app

After this command finishes, you can point your browser to http://localhost:8080/commshare
