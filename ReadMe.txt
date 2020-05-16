Project Architecture: The following projects are present in the solution:
1.	ASP.NET Web Application Project (AngularJS UI):
The UI project has 4 main modules, namely: Login module, Contact Us module, About Us module and Selling module. All of these modules, except for Login have separate angular modules, controllers, services and routing config files. All these files have been referenced in the index.html and all the modules have been injected in the main angular module (in app.js).
Login module uses the main angular controller and service.

2.	2. ASP.NET Web-Api Project (RESTful Services):
The back-end Web-Api project has three controllers, namely: Contact controller, Login controller and Payment controller. Entity framework is the ORM for this project and the same uses ContactDataModel as the data model. There are four entity classes, namely: User.cs, Payment.cs, Product.cs and Contact.cs.

