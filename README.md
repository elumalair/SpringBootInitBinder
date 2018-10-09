# SpringBootInitBinder
SpringBootInitBinder


On this page, we will learn Spring MVC Validator with @InitBinder and WebDataBinder. Validator is a spring interface using which we create our custom validators. WebDataBinder binds custom validators. To do this, we create a method in controller and annotate it with @InitBinder which plays the role to identify WebDataBinder method in our controller. registerCustomEditor() is a method of WebDataBinder which configures PropertyEditor like CustomDateEditor. CustomDateEditor binds the date web request parameter to attribute in JavaBean. 

Here in our example we are creating a JavaBean with username, password, email and date of birth of a user. For the demo we are creating two custom validator classes. In first one, we will validate username and password. The second validator will validate email of the user. Now find the complete example.
