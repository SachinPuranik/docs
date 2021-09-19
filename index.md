
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
You can also use it for mocking criscross usecases in RESTFul API's and WebSockets.

# Testing environment <a name="environment"></a>

ProxyAPI is a classic tool for software developers to Mock their API's in static and dynamic way.
You can also use it for mocking criscross usecases in RESTFul API's and WebSockets.

# Features

### Available
1. Define the rest API's
2. Define the Lambda (Like a Lambda)
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