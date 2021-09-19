[Back Home](index.md)
# Define a API
TODO - Needs more documentation. But it's a click click process in admin backend.

## RESTFul API <a name="restful">
Clients RESTFul API's are always hosted on below URL. Note the way client path is appended to host URI.


***https://proxyapi.dennisfleischmann.de/api/*** your/own/route &nbsp;&nbsp;

## WebSocket API <a name="websock">
A test socket client is available at &nbsp;&nbsp;

[https://proxyapi.dennisfleischmann.de/api/myclient](https://proxyapi.dennisfleischmann.de/api/myclient)

**Must** - Provide your ***collection-key*** in the first text box on the page. 


**Optional** - Provide ***SSE-name*** in the second text box on the page. this is optional param. if not provided a random is generated internally , not exposed to user. hence in any of usecases when you want to refer SocketClient in your domain , use named Socket client.

## SSE API <a name="sse">
Not available yet. will come up soon.


