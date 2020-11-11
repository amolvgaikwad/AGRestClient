# AGRestClient
Xamarin Package to integrate Backend/ Rest Api in your application. 

Follow Below easy steps to integrate AGRestClient.

Step 1 : Add AGRestClient in your app.
Step 2 : Add Namespace(using AGRestClient;) in your sourcode 
Step 3 : Use below apis & thats all.


var ResponseTuple = await RestClientManager.SendAsyncGetRequest<Item1>
("https://jsonplaceholder.typicode.com/posts/1");     

var ResponseTuple = await RestClientManager.SendAsyncDeleteRequest<Item1>
("https://jsonplaceholder.typicode.com/posts/1");     

var ResponseTuple = await RestClientManager.SendAsyncPostRequest<Item1>("https://jsonplaceholder.typicode.com/posts/1","JsonString");

var ResponseTuple = await RestClientManager.SendAsyncPutRequest<Item1>("https://jsonplaceholder.typicode.com/posts/1","JsonString");
