# coronavirus-tracker-website-spring-boot-thymeleaf

Java Spring Boot web application to track reported data of confirmed Coronavirus infections COVID-19 (2019-nCoV) around the world.
Here for the frontend, I use Thyemleaf and Spring Boot as backend.
In my application, I have a model, which represents formal underlying data constructs that the View uses to present the user with the look and feel of the application.
Have a controller to maps user requests and handles them and calls the service if needed.
And the service layer fetches the data from a covid-19 API, and here I use Commons CSV to reads and writes files in variations of the Comma Separated Value (CSV) format from the API.
Technology: Java, Spring Boot, Thymeleaf, Bootstrap
