# spring-soap-api
SOAP Webservices demo using Spring Boot

## Build and execute the application locally

To build the application, execute:

    mvn clean packages

To run the application, execute:

     java -jar target/countries-webservice.jars

## Test the application locally

There's a file called [request.xml](./request.xml) in the root folder of this project that contains the SOAP request that you can use to test the application.

To test the application, use the following command:

    curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws    