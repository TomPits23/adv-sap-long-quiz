## Long Quiz in Advanced Systems Integration & Architecture
1. Define Service Oriented Architecture (SOA).

Service Oriented Architecture, or SOA, is a way of designing software applications that use services as the building blocks. Services are reusable and interoperable components that provide specific functions or business capabilities. Services can communicate with each other using standard protocols and formats, regardless of the underlying technologies or platforms. 

2. List and discuss the characteristics of SOA.

Interoperability: Services can work together across different systems and platforms, using common standards and protocols. This enables the integration and collaboration of numerous applications and organizations.

Discovery: Services can be published and registered in a service registry or repository, where they can be discovered and accessed by other services or applications. The service registry provides information about the service, such as its name, description, location, contract, and policies.

Composition: Services can be combined or orchestrated to create complex applications or business processes. To reach a higher degree of functionality or value, services might call upon or be called upon by other services.

Reusability: Services can be reused to create multiple applications or processes, without having to rewrite or duplicate code. This reduces development time and cost, and improves consistency and quality.

Loose coupling: Services are designed as self-contained and independent components, that have minimal dependencies on other services. This enables services to be deployed and updated independently and lessens the effect of changes or failures in one service on another.

Abstraction: Services provide a high-level and abstract view of their functionality and behavior, without exposing the low-level details and implementation. This makes it easier to comprehend and use services, and it permits service modifications without negatively impacting users or other services.


Quality of service: Services can define and enforce policies and agreements that specify the quality of service they provide and expect, such as availability, reliability, performance, security, and compliance. These policies and agreements can be monitored and managed by service governance tools and mechanisms

3. Define Microservices.

Microservices are an architectural style that allows applications to be composed of multiple services that communicate with each other using standard protocols and formats. 



4. List and discuss the benefits of using Microservices.

Improved scalability: Microservices can scale up or down independently, depending on the demand and load of each service. This allows for better resource utilization and performance optimization.  Microservices have many benefits, such as improved scalability, fault isolation, faster time to market, greater flexibility, smaller development teams, higher software testability, and improved maintainability.

Better fault isolation: Microservices can isolate failures and errors within a single service, without affecting the rest of the application. This improves the availability and reliability of the application, and reduces the risk of cascading failures.


Faster time to market: Microservices enable continuous delivery and deployment, which means that developers can release new features and updates more frequently and with less risk. This fosters a culture of innovation and creativity, and allows for faster feedback and validation from customers.


Greater flexibility: Microservices allow developers to use the best tools and technologies for each service, without being constrained by the choices of the whole application. Microservices can be programmed in any language and run on any platform, offering diversity and agility in development.


Smaller development teams: Microservices promote a modular and decentralized approach to software development, where each service can be managed by a small and autonomous team. This increases developer productivity and teamwork while lowering complexity and coordination overhead.

Higher software testability: Microservices can be tested individually and independently, without requiring the whole application to be deployed or integrated. This simplifies the testing process and improves the quality and coverage of the tests.


Improved maintainability: Microservices can be updated or replaced easily, without affecting the other services or the whole application. This enhances the software's maintainability and evolvability while lowering the technical debt and legacy problems.

5. List and discuss the similarities and differences of SOA and Microservices.

SOA and microservices are both architectural styles that use services as the building blocks of software applications. Services are reusable and interoperable components that provide specific functions or business capabilities. However, SOA and microservices differ in the scope, granularity, and governance of the services. SOA has an enterprise scope, meaning that the services are designed to be shared and reused across multiple applications and business domains.Microservices, on the other hand, have an application scope, meaning that the services are designed to be specific and dedicated to a single application or business domain. Microservices are also monolithic and fine-grained, meaning that they have a narrow functionality and contain only one layer of logic and data. In conclusion, while the concepts of services underpin both SOA and microservices, their approaches to defining, implementing, and managing services vary. Microservices are more suited for small-scale, agile cloud-based applications, whereas Service-Oriented Architecture is better suited for large-scale, complex enterprise applications. In contrast, Microservices are more focused on decoupling and scalability.



6. Define Web Services.

They provide a mechanism for various applications to access designated features or obtain data from distant servers without requiring direct integration or comprehension of each other's internal operations.

7. List and discuss the benefits of using Web Services.

Exposing the existing function on the network - Web services enable you to expose the functionality of your existing code over the network. 

Interoperability - Web services use standard protocols such as SOAP and WSDL to describe and invoke the services, ensuring that the applications can understand each other and exchange data correctly.


Cost reduction - By using web services, you can reuse existing components and avoid creating complex point-to-point connections between applications.

8. List and discuss the characteristics of Web Services.

Supports RPC - Web services support remote procedure call (RPC), which is a mechanism that allows a client to invoke a function or a method on a remote server. 

XML-based - Web services use XML to represent and transport data between the service provider and the service consumer.

Coarse-grained - Service reduce the network overhead and improve the performance of the distributed system.

Loosely coupled - loosely coupled, meaning that they are independent of each other and can be invoked without knowing the details of the implementation or the location of the service provider.

9. List and discuss the distinct roles in Web Services Architecture.

Service requester -  The service requester is the consumer of a web service and uses the service registry to gain information about, and access to, a web service. 

Service Provider - The web service is created by the service provider and made available to client applications for use in their particular applications. Along with providing the web service's implementation and interface, the service provider also defines the service using Web Services Description Language (WSDL).. 


Bind - The web service's URL or the WSDL service description that can be found in the service registry can be used by the service requester to bind to the web service. 

Publish - The publish operation is performed by the service provider to make the web service available to the service requester.

Find -  The web service can be located by the service requester using a search engine or directory service, or by looking through the service registry.


10. List and discuss the Web Services Components.

SOAP: SOAP (Simple Object Access Protocol) is a messaging protocol that uses XML to encode data and messages. SOAP is used to invoke web services and exchange information between the service provider and the service consumer. SOAP relies on HTTP, SMTP, or other communication protocols to transport the messages over the network

WSDL: WSDL (Web Services Description Language) is an XML-based language that describes the interface and the functionality of a web service. 

UDDI: UDDI (Universal Description, Discovery, and Integration)  - UDDI allows service providers to register their web services and provide information about their interface, functionality, and location. 
