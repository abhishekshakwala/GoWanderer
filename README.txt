PLEASE FOLLOW THE FOLLOWING INSTRUCTION TO RUN GO WANDERER APPLICATION:
---------------------------------------------------------------------------

INSTALLATION REQUIREMENTS:
---------------------------------------------------------------------------

Install Java 1.8

Development Environment: NetBeans IDE 8.2

Install Tomcat Server

Jars Needed to be installed:

JSON Parser Jars: json-simple-1.1.1

Functional requirements
---------------------------------------------------------------------------

On running the application first page (index.html) asks for the user details, second page (querypage.jsp) calls CountriesService to load the countries on page load. On selecting the country second service call is made to AirportInfoService which returns Airport code and using that code user can fetch flight details and finally ZomatoSearchService serves the best rated restaurants in the destination location.

Front-End Page:

index.html
querypage.jsp

Back-End Page:

Servlet: query.java

Service layer:

CountriesService.java
AirportInfoService.java
FlightSearchService.java
ZomatoSearchService.java

Non Functional requirements
---------------------------------------------------------------------------

The program would not be more than 5MB in size.