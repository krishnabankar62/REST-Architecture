#                Representational State Transfer

**Submitted By : Krishna Bankar**\
*(Software trainee at MountBlue Technology)*\
**Under guidance of Santu sir**\
*(Mintor at MountBlue Technology)*

### Abstract :
   > Representational state transfer (REST) is a de-facto standard for a software architecture for interactive applications that typically use multiple
   Web services. When user request somthing and server respond its result, It is not simpe as we see. For every person request client compuer
   send request to his local server if result found then response send back to client compuer else if local server don't have result for request then
   forward this request to web server / cloud server / Internet server if result found respond back to local server and local server respond back to
   the client who made request.\
   In case result not found at web server then alt message like "page not found" send back to the client or any other error message may desplay.

### Keywards :
   *REST, RESTful, REST API, PUT, DELETE, CLIENT-SERVER, HTTP-GET, HTTP-POST.*

### Introduction :
   > Representational State Transfer (REST) is a style of architecture based on a set of principles that describe how networked resources are defined
   and addressed.  REST is a style of software architecture as opposed to a set of standards. As a result, such applications or architectures are
   sometimes referred to as RESTful or REST-style applications or architectures.

![rest_diagram](https://github.com/krishnabankar62/REST-Architecture/blob/main/rest_diagram.png?raw=true)

   * Every resource is uniquely addressable using a uniform and minimal set of commands (Typically using HTTP commands of GET, POST, PUT, or
   DELETE over the Internet).
   * The protocol is client/server, stateless, layered, and supports caching.

### Overall REST Description :
   #### 1. The terms that are used ini REST Architecuture :
   HTTP, HTTP-GET, HTTP-POST, PUT, DELETE, Client-Server, Database, Clients, Server, Web-Server or Cloud-Server or Internet-Server.

   		HTTP : "Hypertext Transfer Protocol".
   		HTTPs : "Hypertext Transfer Protocol Secure".

   		There are two types of HTTP request / methods to talk with server :
   		* HTTP-GET : Used for short data request and when we request requested text shown in the url bar.
   		* HTTP-POST : Used for long data attribute request and there is no data shown in url bar.

   		* HTTP-PUT : Used to update specific resources by id.
   		* HTTP-DELETE : Used to delete specific resources by id.

   		* Client : Client is a device by which a person can request somthing to server.
   		* Server : Server is a another device which respond to request of Client.

   		* Web-Server / Cloud-Server / Internet-Server : Using web browser as client we can request to server that is the master server on Internet.

   		* DataBase : A database is a collection of information that is organized so that it can be easily accessed, managed and updated.
            Computer databases typically contain aggregations of data records or files, containing information about sales transactions or
            interactions with specific customers. And server executs query on database to get result and send back to client for its request.


####    2. REST constraints :
        Set of formal and informal guides to define REST Architecuture :
        i. Client-Server
        ii. Stateless
        iii. Cacheable
        iv. Layered System


##### 2.i. Client-Server :

![client-server](https://github.com/krishnabankar62/REST-Architecture/blob/main/clien-server.png?raw=true)

        Client makes an HTTP request to a URL that is hosted by Server and Server respond back to Client.
        like web browser request for a specific URL and Server respond at HTML page.
        Client-Server works on separation principle where client works independently and server also works independently,
        because of separation we can improve portablity and scalablity of client and server with effecting each other.

##### 2.ii. Stateless :

![statless](https://github.com/krishnabankar62/REST-Architecture/blob/main/statless.png?raw=true)

        In Stateless communication when Client request to Server, Client must contains all necessary information to
        undarstand request. and client can make multiple HTTP requests in any order and will recive same response.
        Stateless communication is web URL spacific rather than commands. It does not maintain previous information save.

##### 2.iii. Cacheable :
        Cacheable constraints used to improve network efficiency. Using cache constraints we can reuse data that is already
        requested implicitly or explicitly by client. The advantage of Cacheable constraints to add or eleminate interactions with cache to
        improving efficiency, scalablity.

##### 2.iv. Layered System ;
        In order to improve REST's behavior we can add Layered System constraints.
        The Layered System allowd REST architecture to composed of hierarchical Layeres by constrainning component behavior so that
        each component can not see its immediate layere. And even client need not know whether its communicating with the actual server,
        proxy server or any other intermediary.

##### 3. REST Response Codes :
        When client make request for each request server executs query in the database and respond accordingly.
        response cotains some status code :
![Table](https://github.com/krishnabankar62/REST-Architecture/blob/main/status_codes.png?raw=true)

        For successful HTTP request server returns status code :
        GET 		: 200 (OK)
        POST  	: 201 (CREATED
        PUT		: 200 (OK)
        DELETE	: 204 (NO CONTENT)

### Acknowledgement :
   > I here by inform that whatever content I writen down this is I study myself by book and internet material and best of my knowladge.
   And not copied from anywhere.

### Conclusion :
   > So, As we have already disscussed so many things about REST that is an Architecuture to communicate with server.
   Client that can be a compuer or web browser which makes request to if its local server found result then send it to client or forward it to
   cloud server / internet server or master server; master server executs query in the database then send result or error with status code.
   To improve scalablity, efficiency and flexiblity we can add Cacheable constraints and Layered System.

### Refrences :
   For further reading :
   1. [medium.com](https://medium.com/@sagar.mane006/understanding-rest-representational-state-transfer-85256b9424aa)
   2. [sitepoint.com](https://www.sitepoint.com/developers-rest-api/)
   3. [codecademy.com](https://www.codecademy.com/articles/what-is-rest)
   4. [geeksforgeeks](https://www.geeksforgeeks.org/rest-api-architectural-constraints/#:~:text=REST%20is%20a%20software%20architectural,and%20predefined%20set%20of%20rules.)
   5. [wikipedia](https://en.wikipedia.org/wiki/Representational_state_transfer)
