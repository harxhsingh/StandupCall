REST (Representational State Transfer) is an architectural style used for designing networked applications, particularly web services. REST APIs (Application Programming Interfaces) are a set of rules and conventions that allow different software applications to communicate with each other using the principles of REST.

Here are some key points about REST APIs:

1. **Stateless**: REST APIs are stateless, meaning that each request from a client to the server contains all the necessary information to process that request. The server does not maintain any session information about the client between requests.

2. **Resources**: REST APIs are based on the concept of resources. A resource can be any entity that the client wants to interact with, such as a user, product, or document. Each resource is identified by a unique URL (Uniform Resource Locator).

3. **HTTP Verbs**: REST APIs use HTTP methods (also known as verbs) to define the operations that can be performed on a resource. The most commonly used HTTP methods are:
   - `GET`: Retrieves a representation of a resource.
   - `POST`: Creates a new resource.
   - `PUT`: Updates an existing resource or creates a new resource.
   - `DELETE`: Deletes a resource.

4. **Uniform Interface**: REST APIs follow a uniform interface, which means they have a consistent and standardized way of interacting with resources. This includes using standard HTTP status codes to indicate the success or failure of a request, such as 200 OK, 201 Created, 400 Bad Request, etc.

5. **Representation**: Resources in REST APIs are represented in a format such as JSON (JavaScript Object Notation) or XML (eXtensible Markup Language). These representations encapsulate the data associated with a resource and are transferred between the client and server.

6. **Hypermedia**: REST APIs can include hypermedia links within the responses, allowing the client to navigate to related resources by following those links. This concept is known as Hypermedia as the Engine of Application State (HATEOAS) and enables a more discoverable and self-descriptive API.

7. **Authentication and Authorization**: REST APIs can use various mechanisms for authentication and authorization, such as API keys, tokens, or OAuth. These mechanisms ensure that only authorized clients can access protected resources.

REST APIs have become widely adopted due to their simplicity, scalability, and compatibility with the HTTP protocol. They are commonly used in web development to expose and consume data or services across different platforms and systems.