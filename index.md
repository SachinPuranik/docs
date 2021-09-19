
# Table of contents
1. [Introduction](#introduction)
2. [Testing environment](#environment)
3. [Features](#features)
3. [Concepts](concepts.md)
4. [Define API (Static/Dynamic)](api.md)
5. [Examples](example.md)
    1. [Fibonacci](fibonacci.md)
    2. [Infiniteloop](infiniteloop.md)
4. [Generic Commands](commands.md)
5. [Eyeota Specific](eyeota.md)

# Introduction <a name="introduction"></a>

ProxyAPI is a classic tool for software developers to Mock their API's in static and dynamic way.
You can also use it for mocking criss-cross usecases in RESTFul API's(RESTFul), Web Sockets(WebSock) and Server Side Events (SSE).

# Testing environment <a name="environment"></a>

You can use any client side tool to test your api's at your end. You can then call these all api's in your application exactly the same way.

1. We recommond you to use tool ***POSTMAN*** for the testing purpose. it supports both rest api and WebSock testing.
2. While testing you need to add the ***collection-key*** header to http-header section of postman. so it can access appropriate processor/collecion/API's



# Features

### Available
1. Create API collection.
2. Add API's and functionality to collection.
3. Define the Processor (Like a Lambda)
4. Define/modify/update your own small DataStore.
5. Processor and Datastore are all related to one collection.

### Planned
1. Request Logging system
2. Intra socket communication (Two/More websockets communicating with each other )
3. Server Side Events support
4. Kuberneties support
5. Open API-2/3 Compliance

# Known issues
1. Some issues in cookies and session. (Just use in incognito mode to avoid few)
2. Redirection issues
3. Limitation - Currently Get and Post of Same API can not be defined seperately. (Implementation in progress)