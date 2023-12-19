# Asynchronous Request And Response pattern using MassTransit

The definition of the Request Response pattern is: "It is a message exchange pattern in which a requestor sends a request message to a replier system, which receives and processes the request, ultimately returning a message in response." 
In this repo, you would see how to implement asynchronous Request Response messaging with MassTransit and RabbitMQ or other message transporting service like Azure Service Bus. Enjoy!


- Adding the Request Response message contracts
- Sending the Request message with IRequestClient
- Consuming the Request and returning the Response
- Refactoring Request Response messaging to a service
- Returning multiple Response message types
