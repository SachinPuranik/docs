[Home](index.md)
# Concepts

## Workspace <a name="workspace"></a>
***Workspace*** is your complete playgroud for the project. You can invite members to your playground and allow them to use/change it as per their roles.

## Collection <a name="collection"></a>
***Collection*** is grouping the API set to one. it also provides the 
**collection-key** whch can be used while calling the API's from your application. Always add this ***collection-key*** to your http headers while accessing your api's.

***Processor*** and ***Datastore*** are mapped to this collection-key. Means API's in this collection can make use of this processor and datastore when marked as dynamic.For static API's only static API response is returned.

## Processor <a name="processor"></a>
***Processor*** is like AWS-lambda with limited functionality. it can be a javascript code which will be executed while generating the dynamic responces for your API's. it's a small execution unit for your workspace. 

> - Must always return a JSON.
> - Each workspace will always have it's own Processor and DataStore.

## DataStore <a name="datastore"></a>
***DataStore*** is a small JSON which persists on the server and can be refered for generating further dynamic responses.


## Bindings <a name="bindings"></a>
***Bindings*** is a set of javascript objects which are available for use in the ***Processor***. Bindings provide the way to access request-params, request-headers, creating-logs, storing information , etc.


Details list of [bindings](bindings.md) goes here.






