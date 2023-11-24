## Long Quiz in Advanced Systems Integration & Architecture

1. Define Service Oriented Architecture (SOA).
    - Service-Oriented Architecture (SOA) is a stage in the evolution of application development and/or integration. It defines a way to make software components reusable using the interfaces. Formally, SOA is an architectural approach in which applications make use of services available in the network. 
    Reference: https://www.geeksforgeeks.org/service-oriented-architecture/

2. List and discuss the characteristics of SOA.
    - The first characteristic of SOA is that it have loose coupling meaning a client does not need or isn't required to understand the language that the service is using because it is independent and relies on a structured interface so that it can process the communication between the client and service. The second characteristic is it have interoperability meaning it can interact with variety of services since it is a necessity for large- scale distributed networks. The third characteristic is it can be located easily since it is loosely coupled. Lastly, it is self-contained meaning it can operate by itself since it is independent.

3. Define Microservices.
    - Microservices are an architectural and organizational approach to software development where software is composed of small independent services that communicate over well-defined APIs. Reference: https://aws.amazon.com/microservices/

4. List and discuss the benefits of using Microservices.
    - The first benefit of using microservices is that it is scalable meaning it can make necessary changes without the need to disrupt an entire application. The second benefit is since microservices are independent, it can isolate the problem that crashed and the single crash won't disrupt the entire application. Lastly, it is flexible meaning they can be created by any programming language so that developers can find and use the best language for a certain application.

5. List and discuss the similarities and differences of SOA and Microservices.
    - The differences between SOA and microservices is that the software size needed for SOA is larger since it is used by large-scale distributed networks while microservices, based on the word itself "micro", it uses smaller. Microservices are more fault tolerant since it have fault isolation while in SOA when one service slows down, it affects the entire application. The similarities between SOA and microservices is that it both provide support for web services. Their common goal is to have an easier software development.

6. Define Web Services.
    - A web service is a set of open protocols and standards that allow data to be exchanged between different applications or systems. Web services can be used by software programs written in a variety of programming languages and running on a variety of platforms to exchange data via computer networks such as the Internet in a similar way to inter-process communication on a single computer.
    Reference: https://www.geeksforgeeks.org/what-are-web-services/

7. List and discuss the benefits of using Web Services.
    - The first benefit of using web services is that it have interoperability meaning it can interact with variety of services and can communicate with any other application that allows organizations to integrate with these applications. Since it has interoperability, another benefit is that it can re-use codes that are being used by other applications that they are communicating with. Since it both have interoperability and reusability, this can mean to have less cost in creating an application. 

8. List and discuss the characteristics of Web Services.
    - The first characteristic of web services is that it is XML-based that removes any paltform binding, networking, and operating system since it has interoperability. The second characterisitic is that it have loose coupling meaning a client does not need or isn't required to understand the language that the service is using because it is independent and relies on a structured interface so that it can process the communication between the client and service. The third characteristic is that it have interoperability meaning it can interact with variety of services and can communicate with any other application that allows organizations to integrate with these applications.

9. List and discuss the distinct roles in Web Services Architecture.
    - The first distinct role in web services architecture is service provider meaning it is a collection of software, such as the application program or the platform, that provides a web service. The second is service requester meaning it is a collection of software, such as the application program or the platform, that is responsible for the requesting of web service from a service provider. Lastly, service registry meaning it is a central location where the service provider can issue their service description which will then be found by the service requester.

10. List and discuss the Web Services Components.
    - The first web services component is the XML/JSON where it is used to encode data and messages. XML is for the structure of data while JSON is for the interchange of data. The second is SOAP/REST where it is a protocol to exchange data and messages between applications. SOAP uses XML while REST uses HTTP for data exchange. The third is WSDL where it is used to describe the web service's interface. The fourth is UDDI where it is used to publish and discover web services. Lastly, it is a service provider and consumer where the web service is where they communicate with each other through protocols and data formats that are present in a certain web service.
