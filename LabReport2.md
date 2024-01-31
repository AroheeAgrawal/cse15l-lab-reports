# Lab Report 2
## Part 1
![Image](Screenshot 2024-01-16 at 4.22.03 PM.png)
* The method in my code that is called is `ChatHandler.handle(HttpExchange exchange)`.
* The most relevent arguement to this method is `HttpExchange exchange` This represents the HTTP exchange between the server and the client It contains the information about the request and allows the user to send a response. Some relevent fields and their values are `URI uri = exchange.getRequestURI();` this retrieves the URI of the incoming request, `chatMessages` this has a list of chat messages in the server class,and `user`(jpolitz) and `message`(Hello) which are obtained and decoded from the URI.
* The `chatMessages` list  is changed as it gets updated with the new message and reformated based on the request `/add-message?s=Hello&user=jpolitz`. The reformatted message is   `jpolitz: Hello`. This allows this newly formatted chat message to be sent back to the client.
 ![Image](Screenshot 2024-01-16 at 4.22.03 PM.png)
* The method in my code that is called is `ChatHandler.handle(HttpExchange exchange)`.
* The most relevent arguement to this method is `HttpExchange exchange` This represents the HTTP exchange between the server and the client It contains the information about the request and allows the user to send a response. Some relevent fields and their values are `URI uri = exchange.getRequestURI();` this retrieves the URI of the incoming request, `chatMessages` this has a list of chat messages in the server class,and `user`(yash) and `message`(How are you) which are obtained and decoded from the URI.
* The `chatMessages` list  is changed as it gets updated with the new message and reformated based on the requestt `/add-message?s=How%20are%20you&user=yash` The reformatted message is   `jpolitz: Hello\nyash: How are you\n`. This allows this newly formatted chat message to be sent back to the client.
## Part 2
### The absolute path to the private key for SSH key for logging into `ieng6`
![Image](Screenshot 2024-01-16 at 4.22.03 PM.png)
### The absolute path to the public key for SSH key for logging into `ieng6`
![Image](Screenshot 2024-01-16 at 4.22.03 PM.png)
### Terminal interaction logging into ieng6 account without being asked for a password.
![Image](Screenshot 2024-01-16 at 4.22.03 PM.png)
## Part 3
Something that I learnt in week 2 that I did not know before was how to log into 
  
